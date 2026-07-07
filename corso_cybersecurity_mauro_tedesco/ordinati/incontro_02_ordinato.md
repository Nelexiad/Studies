# Incontro 2 - Security by Design

Versione riorganizzata degli appunti del secondo incontro.

## Tema della giornata

- Focus: progettare sistemi e processi con la sicurezza integrata fin dall'inizio.

## Traccia iniziale

- Principi di security by design.
- Riduzione della superficie di attacco.
- Hardening e configurazioni sicure.
- Segmentazione, controlli di accesso e minimizzazione dell'esposizione.
- Collegamento tra requisiti di sicurezza, architettura e ciclo di vita.

## Ripasso iniziale: reti, DNS e footprinting


### Collegamento con il corso

- Le reti spiegano come comunicano sistemi e servizi.
- Il `DNS` mostra come nomi e host vengono pubblicati e risolti.
- Il `footprinting` mostra quante informazioni possono essere raccolte osservando l'infrastruttura dall'esterno o da una posizione di test controllata.

### Idea chiave

- Prima di progettare una difesa efficace bisogna capire bene cosa e' visibile, come comunica e quali informazioni espone un sistema.

## Hardening

### Cos'e'

- L'`hardening` e' il processo con cui si rende un sistema, un'applicazione, un dispositivo o un'infrastruttura `piu' sicura`.
- L'idea di base e' ridurre tutto cio' che e' inutile, debole o troppo esposto.

### Obiettivo

- Ridurre la `superficie di attacco`.
- Limitare le possibilita' di abuso, errore o compromissione.
- Portare il sistema a una configurazione piu' controllata e coerente con il principio del `least privilege`.

### Esempi pratici di hardening

- Disabilitare servizi, porte, account o funzionalita' non necessarie.
- Cambiare credenziali di default e rimuovere configurazioni insicure predefinite.
- Applicare patch e aggiornamenti di sicurezza.
- Limitare i privilegi degli utenti e dei processi.
- Configurare in modo sicuro protocolli, cifrature, firewall e controlli di accesso.
- Ridurre le informazioni esposte, come banner, versioni software o messaggi di errore troppo dettagliati.

### Hardening non significa solo aggiornare

- Aggiornare e patchare e' importante, ma da solo non basta.
- L'hardening comprende anche configurazione sicura, disattivazione del superfluo, segmentazione, logging e riduzione dell'esposizione.

### Idea chiave

- Fare hardening significa passare da un sistema `installato e funzionante` a un sistema `installato, funzionante e piu' difficile da attaccare`.

## documentazione pubblica su `netref.dev`

-  `netref.dev`, creata per pubblicare varia documentazione.

## Vulnerabilita' logiche e architetturali

- Non tutte le vulnerabilita' derivano da un bug di basso livello: alcune nascono da errori di logica, di progettazione o di architettura.
- Le vulnerabilita' `logiche` dipendono da un comportamento applicativo scorretto o da regole di business mal progettate.
- Le vulnerabilita' `architetturali` dipendono invece da scelte strutturali deboli, come fiducia eccessiva tra componenti, isolamento insufficiente o scambio insicuro di dati.

### Esempi citati

- `Buffer overflow`: scrittura oltre i limiti previsti di un buffer, con possibile corruzione della memoria ed esecuzione di codice indesiderato.
- `Insecure IPC`: comunicazione insicura tra processi o componenti, per esempio senza validazione, autenticazione o controllo degli accessi adeguato.

### Perche' sono importanti

- Questi problemi mostrano che la sicurezza non dipende solo da patch o firewall.
- Se la logica o l'architettura sono deboli, il sistema puo' restare vulnerabile anche se e' aggiornato.

## Contromisure di prevenzione

### Funzioni sicure

- Usare funzioni e librerie piu' sicure aiuta a ridurre errori classici di gestione della memoria e degli input.
- L'obiettivo e' limitare copie non controllate, overflow e uso improprio dei buffer.

### ASLR

- `ASLR` significa `Address Space Layout Randomization`.
- Randomizza la disposizione delle aree di memoria, rendendo piu' difficile prevedere indirizzi utili a un exploit.

### DEP / NX bit

- `DEP` (`Data Execution Prevention`) e `NX bit` impediscono l'esecuzione di codice in aree di memoria che dovrebbero contenere solo dati.
- Questo rende piu' difficile sfruttare alcuni attacchi basati su iniezione di codice in memoria.

### Stack canaries

- Gli `stack canaries` sono valori di controllo inseriti nello stack prima dell'indirizzo di ritorno.
- Se un overflow li modifica, il programma rileva l'anomalia e puo' interrompersi prima che l'attacco prosegua.

### Idea chiave

- La prevenzione efficace combina codice piu' sicuro, scelte architetturali corrette e meccanismi di protezione a runtime.

## John the Ripper

### Cos'e'

- `John the Ripper` e' uno strumento molto noto usato per verificare la robustezza delle password.
- Lavora tipicamente su `hash` di password, cercando di trovare quale password in chiaro li genera.
- In ambito difensivo viene usato per audit, assessment e verifica delle policy password.

### Come funziona in generale

- Lo strumento prende in input uno o piu' hash.
- Genera o prova password candidate.
- Calcola l'hash corrispondente con lo stesso algoritmo.
- Confronta il risultato con l'hash bersaglio.
- Se c'e' corrispondenza, la password e' stata trovata.

### Tecniche usate

- `Wordlist attack`: prova password prese da liste di parole comuni o leak noti.
- `Rules`: modifica le parole delle liste, per esempio aggiungendo numeri, simboli o variazioni comuni.
- `Brute force` o `incremental`: prova combinazioni sistematiche di caratteri.
- In alcuni contesti puo' usare anche informazioni contestuali per rendere i tentativi piu' efficaci.

### Perche' e' importante

- Mostra in modo pratico quanto una password debole possa essere recuperata rapidamente.
- Aiuta a capire la differenza tra password semplici, prevedibili e password robuste.
- E' utile per validare policy su lunghezza, complessita' e resistenza agli attacchi offline sugli hash.

### Collegamento con la sicurezza delle password

- Se un attaccante ottiene un database di hash, puo' tentare di recuperarne le password offline.
- In questo scenario la qualita' della password e la forza dell'algoritmo di hashing fanno una grande differenza.
- Per questo sono importanti password forti, salting, algoritmi lenti e policy corrette.

### Idea chiave

- `John the Ripper` non serve solo a "rompere password": serve soprattutto a misurare quanto siano deboli o forti le credenziali in un assessment di sicurezza.

## OpenVAS

### Cos'e'

- `OpenVAS` e' uno strumento di `vulnerability assessment` usato per identificare vulnerabilita' note in sistemi, servizi e configurazioni esposte.
- Serve a eseguire scansioni di sicurezza su host o reti e a segnalare problemi conosciuti che meritano analisi o remediation.

### Come funziona in generale

- Lo strumento esegue una scansione del target.
- Raccoglie informazioni su host, porte, servizi e configurazioni rilevate.
- Confronta cio' che trova con un insieme di test e vulnerabilita' note.
- Produce un report con risultati, severita' e indicazioni di remediation.

### Cosa puo' rilevare

- Servizi esposti e versioni vulnerabili.
- Configurazioni deboli o obsolete.
- Vulnerabilita' note associate a software, sistemi operativi o servizi di rete.
- Alcuni problemi di hardening o esposizione non corretta.

### Perche' e' importante

- Aiuta a trasformare la ricognizione tecnica in una verifica strutturata delle debolezze note.
- E' utile per prioritizzare le correzioni e per capire dove intervenire prima.
- Supporta attivita' di assessment periodico e miglioramento continuo della postura di sicurezza.

### Da ricordare

- `OpenVAS` non sostituisce l'analisi manuale: aiuta a trovare vulnerabilita' note, ma i risultati vanno interpretati.
- Uno scanner puo' generare anche `falsi positivi` o non cogliere problemi logici e architetturali.

### Idea chiave

- `OpenVAS` e' utile per cercare in modo sistematico vulnerabilita' conosciute; la sicurezza reale richiede poi validazione, prioritizzazione e remediation.

