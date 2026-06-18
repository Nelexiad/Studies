# Incontro 1 - Awareness & Landscape

Versione riorganizzata degli appunti del primo incontro.

## Tema della giornata

- Focus: awareness, panorama della cybersecurity e contesto generale del corso.

## Obiettivi della sicurezza informatica

### Triade CIA

- Gli obiettivi fondamentali della sicurezza informatica sono spesso riassunti nella `Triade CIA`.
- `CIA` significa `Confidentiality`, `Integrity`, `Availability`.
- Questa triade serve a capire cosa bisogna proteggere e quale tipo di impatto produce un incidente di sicurezza.

### Confidentiality - Confidenzialita'

- La confidenzialita' ha l'obiettivo di impedire che le informazioni siano viste o divulgate a soggetti non autorizzati.
- Esempi di misure collegate: controllo degli accessi, autenticazione, cifratura, classificazione dei dati.

### Integrity - Integrita'

- L'integrita' ha l'obiettivo di garantire che dati e informazioni restino corretti, completi e non alterati in modo non autorizzato.
- Esempi di misure collegate: hashing, firme digitali, logging, controllo delle modifiche, versioning.

### Availability - Disponibilita'

- La disponibilita' ha l'obiettivo di assicurare che sistemi, servizi e dati siano accessibili quando servono agli utenti autorizzati.
- Esempi di misure collegate: backup, ridondanza, disaster recovery, protezione da guasti e attacchi DoS.

### Idea chiave

- Ogni incidente di cybersecurity puo' essere letto anche chiedendosi quale elemento della triade CIA e' stato colpito.
- In molti casi l'incidente impatta piu' di un elemento, ma di solito ce n'e' uno prevalente.

## Riferimenti normativi

### Art. 615-ter c.p. - Accesso abusivo a un sistema informatico o telematico

- Il riferimento corretto e' l'art. 615-ter del codice penale, non del codice di procedura penale.
- La norma riguarda l'accesso abusivo a un sistema informatico o telematico protetto da misure di sicurezza.
- Il punto centrale e' l'accesso senza autorizzazione, oppure il mantenimento nel sistema contro la volonta' di chi ha il diritto di escludere l'accesso.

### Da ricordare

- E' un riferimento fondamentale quando si parla di reati informatici in ambito italiano.
- Si collega ai temi di autorizzazione, controllo degli accessi e abuso di credenziali.
- Va distinto da una semplice attivita' tecnica: il profilo giuridico dipende dalla presenza o meno di autorizzazione.

### Introduzione a NIS2, CRA e GDPR

- Nel contesto europeo stiamo introducendo tre riferimenti molto importanti: `NIS2`, `CRA` e `GDPR`.
- Tutti e tre riguardano la sicurezza, ma da prospettive diverse: organizzazione, prodotto e dati personali.

#### NIS2

- La `NIS2` rafforza i requisiti di cybersecurity per organizzazioni considerate essenziali o importanti.
- Introduce obblighi su governance, gestione del rischio, continuita' operativa, sicurezza della supply chain e notifica degli incidenti.
- E' molto rilevante perche' porta la cybersecurity dentro la responsabilita' del management, non solo dell'IT.

#### CRA

- Il `Cyber Resilience Act (CRA)` riguarda la sicurezza dei prodotti con elementi digitali.
- Spinge i produttori a progettare e mantenere prodotti piu' sicuri lungo il loro ciclo di vita.
- Il tema chiave e' la security by design e by default applicata a software, dispositivi e componenti digitali.

#### GDPR

- Il `GDPR` riguarda la protezione dei dati personali e la privacy.
- Impone regole su raccolta, uso, conservazione, protezione e violazione dei dati personali.
- In ambito cybersecurity e' centrale perche' un incidente di sicurezza puo' diventare anche una violazione della privacy con obblighi di notifica e sanzioni.

### Differenza sintetica

- `NIS2`: protegge reti, sistemi e resilienza organizzativa.
- `CRA`: protegge la sicurezza dei prodotti digitali.
- `GDPR`: protegge i dati personali degli interessati.

## Relazione tra IT, OT e Cybersecurity

### Distinzione di base

- Il mondo IT e' orientato soprattutto alla gestione del dato, delle informazioni e dei servizi digitali.
- Il mondo OT e' orientato soprattutto alla gestione e alla messa in sicurezza dei sistemi operativi e industriali che controllano processi fisici.

### Punto di incontro nella cybersecurity

- La cybersecurity deve mettere insieme questi due mondi, che hanno priorita' diverse ma dipendenze sempre piu' strette.
- In ambito IT la protezione riguarda soprattutto dati, account, applicazioni, reti e continuita' dei servizi informativi.
- In ambito OT la protezione riguarda anche disponibilita', continuita' operativa, sicurezza dei processi e stabilita' degli impianti.

### Idea chiave del corso

- Fare cybersecurity significa integrare IT e OT in una visione comune di rischio.

### Modello Purdue

- Il `modello Purdue` e' un modello architetturale usato per descrivere e organizzare i sistemi industriali a livelli.
- Serve a separare in modo logico le funzioni operative, dal campo fino ai livelli gestionali e aziendali.
- E' molto utile per capire segmentazione, flussi di comunicazione e punti di controllo nella sicurezza OT.

### Livelli del modello Purdue

- `Livello 0`: processo fisico, sensori e attuatori.
- `Livello 1`: controllo di base, per esempio `PLC`, RTU e controllori.
- `Livello 2`: supervisione locale, per esempio `HMI`, stazioni operatore e SCADA locale.
- `Livello 3`: gestione delle operazioni di stabilimento e sistemi di coordinamento di sito.
- `Livello 4`: sistemi business e IT aziendale, come `ERP` e servizi centrali.
- Spesso si cita anche una `DMZ industriale` tra OT e IT per separare meglio i domini.

### Perche' e' importante

- Aiuta a capire che non tutti i sistemi industriali devono comunicare liberamente tra loro.
- Supporta la segmentazione di rete e il principio di separazione tra ambiente OT e ambiente IT.
- E' un riferimento molto usato quando si parla di difesa in profondita' in ambito industriale.

### IEC 62443

- La `IEC 62443` e' una famiglia di standard dedicata alla cybersecurity dei sistemi `ICS/OT` e di automazione industriale.
- E' uno dei riferimenti piu' importanti per progettare, gestire e valutare la sicurezza in ambienti industriali.

### Idea chiave della IEC 62443

- Lo standard promuove un approccio strutturato alla sicurezza industriale, basato su segmentazione, gestione del rischio, hardening, controllo degli accessi e ciclo di vita sicuro.
- Introduce concetti molto importanti come `zone` e `conduit`.

### Zone e conduit

- Le `zone` raggruppano asset o sistemi con requisiti di sicurezza simili.
- I `conduit` sono i canali controllati di comunicazione tra zone diverse.
- L'obiettivo e' non lasciare comunicazioni aperte in modo indiscriminato, ma governare i flussi tra segmenti della rete industriale.

### Collegamento pratico con il corso

- Il `modello Purdue` aiuta a leggere `come e' organizzata` un'architettura industriale.
- La `IEC 62443` aiuta a capire `come proteggerla` in modo strutturato.
- L'obiettivo non e' proteggere solo i dati o solo gli impianti, ma mettere al sicuro l'intero ecosistema tecnologico e le sue interazioni.

### Esempio pratico: Colonial Pipeline

- Un caso spesso citato e' l'attacco ransomware a Colonial Pipeline negli Stati Uniti nel 2021.
- L'attacco ha colpito principalmente i sistemi IT aziendali, non direttamente i controlli industriali OT dell'oleodotto.
- Nonostante questo, l'azienda ha fermato in via precauzionale parte delle operazioni della pipeline, perche' i sistemi IT erano fondamentali per la gestione sicura e operativa del servizio.
- Il risultato e' stato un impatto reale sul mondo fisico: interruzioni operative e problemi nella distribuzione del carburante.

### Perche' questo esempio e' importante

- Dimostra che un incidente nel dominio IT puo' propagare effetti molto concreti nel dominio OT.
- Fa capire che IT e OT non sono mondi separati: sono interdipendenti.
- In cybersecurity industriale non basta proteggere gli impianti; bisogna proteggere anche i sistemi informativi che li supportano.

## Minacce di oggi

### Insider Threat

- La minaccia interna riguarda persone che hanno accesso legittimo all'organizzazione e che, volontariamente o involontariamente, causano danni.
- Può trattarsi di dipendenti, collaboratori, amministratori o fornitori con accesso privilegiato.

### Supply Chain Attack

- L'attacco alla supply chain colpisce un fornitore, un software terzo, un integratore o un componente esterno per raggiungere l'obiettivo finale.
- E' una minaccia critica perche' sfrutta la fiducia gia' esistente tra organizzazioni e partner.

### Ransomware industriale

- Il ransomware industriale colpisce ambienti IT/OT con effetti che possono fermare produzione, servizi essenziali o processi fisici.
- In questi scenari il danno non e' solo informatico, ma anche operativo ed economico.

### Cyber-warfare

- La cyber-warfare indica attivita' offensive nel dominio cyber legate a conflitti tra stati o a operazioni con finalita' geopolitiche.
- Spesso prende di mira infrastrutture critiche, energia, trasporti, telecomunicazioni e sistemi governativi.

### Idea chiave

- Il panorama delle minacce moderne mostra che la cybersecurity non riguarda piu' solo il singolo virus o il singolo hacker.
- Oggi le minacce sono organizzate, interconnesse e capaci di colpire persone, processi, tecnologie e supply chain nello stesso tempo.

## Struttura di un indirizzo di rete

### Esempio base

- `192.168.0.0/24` identifica una rete IPv4.
- `192.168.0.30` e' un possibile host appartenente a quella rete.

### Come si legge `192.168.0.0/24`

- `192.168.0.0` e' l'indirizzo di rete.
- `/24` e' il prefisso CIDR e indica che i primi 24 bit identificano la rete.
- In pratica, con `/24`, i primi tre ottetti rappresentano la parte di rete e l'ultimo ottetto rappresenta la parte host.

### Cosa e' il CIDR

- `CIDR` significa `Classless Inter-Domain Routing`.
- E' il modo moderno di scrivere `quanta parte` di un indirizzo IP appartiene alla rete e quanta parte resta agli host.
- Si scrive con una barra seguita da un numero, per esempio `/24`.

### Come si interpreta

- Il numero dopo la barra indica `quanti bit` dell'indirizzo identificano la rete.
- Per esempio, in `/24`, i primi `24 bit` sono la parte rete e i restanti `8 bit` sono la parte host.
- In questo modo si capisce subito quanto e' grande la subnet.

### Perche' e' importante

- Il `CIDR` ha sostituito il vecchio ragionamento rigido basato solo sulle classi `A`, `B` e `C`.
- Permette di creare reti di dimensione molto piu' flessibile.
- Per questo oggi si usa normalmente `CIDR` insieme alla subnet mask.

### Interpretazione pratica dell'esempio

- Rete: `192.168.0.0`
- Subnet mask equivalente: `255.255.255.0`
- Intervallo host tipico: da `192.168.0.1` a `192.168.0.254`
- Broadcast della rete: `192.168.0.255`

### Numero massimo di host in una LAN `/24`

- Una rete `IPv4 /24` lascia `8 bit` per la parte host.
- Con `8 bit` si ottengono `2^8 = 256` indirizzi totali.
- Di questi, normalmente `1` indirizzo e' riservato alla `rete` e `1` al `broadcast`.
- Quindi il numero massimo tipico di host utilizzabili e' `254`.

### E il gateway?

- Il `gateway` non e' un indirizzo extra fuori dal conteggio: usa uno dei `254` indirizzi host disponibili.
- Quindi il massimo teorico degli host assegnabili nella subnet resta `254`.
- Se uno di questi indirizzi viene assegnato al gateway, allora gli indirizzi `ancora liberi` per altri dispositivi diventano `253`.

### Distinzione corretta

- `254` = host utilizzabili nella subnet
- `253` = host ancora disponibili se uno e' gia' occupato dal gateway

### Cosa significa subnet

- Una `subnet` e' una suddivisione logica di una rete IP in porzioni piu' piccole.
- Serve a organizzare meglio gli host, separare segmenti di rete e controllare piu' facilmente traffico e indirizzamento.
- La `subnet mask`, o il prefisso `CIDR` come `/24`, indica quali bit appartengono alla rete e quali agli host.

### Esempio pratico di subnet

- In `192.168.0.0/24`, la parte rete e' `192.168.0` e l'ultima parte identifica gli host.
- Se restringo la rete, per esempio con una subnet piu' piccola, diminuisco il numero di host disponibili ma aumento la separazione logica.
- Le subnet sono molto usate per segmentazione, sicurezza e ordine amministrativo.

### Classi IPv4

- Storicamente gli indirizzi `IPv4` erano spiegati con il sistema delle `classi`.
- Oggi questo approccio e' soprattutto didattico, mentre nella pratica si usa molto di piu' `CIDR`.

### Classi principali

- `Classe A`: primo ottetto da `1` a `126`, pensata per reti molto grandi.
- `Classe B`: primo ottetto da `128` a `191`, pensata per reti medie.
- `Classe C`: primo ottetto da `192` a `223`, pensata per reti piu' piccole.
- `Classe D`: primo ottetto da `224` a `239`, usata per il `multicast`.
- `Classe E`: primo ottetto da `240` a `255`, riservata a usi sperimentali o speciali.
- `127.x.x.x` e' riservato al `loopback`.

### Idea chiave

- Le classi `A`, `B` e `C` aiutano a capire l'evoluzione storica dell'indirizzamento IPv4.
- Nelle reti moderne, pero', si ragiona quasi sempre con `subnet mask` e `CIDR`, perche' sono piu' flessibili.

### Quali IP si usano per una rete privata

- Per una rete privata `IPv4` non si usa un indirizzo qualsiasi di Internet, ma uno dei `range riservati` definiti per uso interno.
- I tre principali range privati sono quelli di `RFC 1918`.

### Range privati IPv4

- `10.0.0.0/8`
- `172.16.0.0/12`
- `192.168.0.0/16`

### Esempi pratici

- In una piccola LAN domestica o d'ufficio si usa spesso qualcosa come `192.168.1.0/24`.
- In reti aziendali piu' grandi si puo' usare anche `10.0.0.0/8`, suddividendola poi in molte subnet.
- Anche il blocco `172.16.0.0/12` e' privato, ma si vede un po' meno spesso nelle reti piccole.

### Idea chiave pratica

- Quindi, se chiedi `che IP uso per una rete privata?`, la risposta corretta e': un indirizzo appartenente a uno di questi tre blocchi privati.
- Un esempio semplice e molto comune e' `192.168.1.10` dentro una rete `192.168.1.0/24`.

### Nota sul secondo esempio

- La forma corretta del secondo esempio e' `192.168.0.30`.

### IP e MAC nella LAN

- In una `LAN` non si usa solo l'indirizzo IP e non si usa solo il MAC address: servono entrambi, ma a livelli diversi.
- L'`indirizzo IP` serve per identificare logicamente la macchina e capire a quale rete appartiene la destinazione.
- Il `MAC address` serve invece per consegnare concretamente il frame Ethernet sul collegamento locale, quindi al livello 2.

### Come dialogano davvero due macchine nella stessa LAN

- L'applicazione ragiona usando l'IP della destinazione.
- Se la destinazione e' nella stessa rete locale, il sistema deve scoprire quale MAC address corrisponde a quell'IP.
- Per farlo usa `ARP` (Address Resolution Protocol), che risolve un indirizzo IP locale nel relativo MAC address.
- Una volta ottenuto il MAC, il frame Ethernet viene inviato sulla LAN verso quel dispositivo.

### Risposta breve alla domanda

- Si dialoga logicamente con l'`IP`.
- Si consegna localmente con il `MAC`.
- Quindi, sulla LAN, IP e MAC lavorano insieme.

### Comandi PowerShell utili per l'analisi di rete

- In fase di analisi o troubleshooting di base, alcuni comandi molto usati in Windows/PowerShell sono `ping`, `tracert` e `ipconfig`.
- Servono a verificare raggiungibilita', percorso dei pacchetti e configurazione locale della macchina.

### Ping

- `ping` invia richieste `ICMP Echo Request` a un host per vedere se risponde.
- Serve per controllare se una destinazione e' raggiungibile e per avere un'indicazione di latenza.
- Se non risponde, non significa sempre che l'host sia spento: potrebbe esserci un firewall che blocca ICMP.

### TTL

- `TTL` significa `Time To Live`.
- E' un valore presente nel pacchetto IP che indica per quanti `hop` massimi il pacchetto puo' ancora transitare.
- Ogni router che inoltra il pacchetto decrementa il `TTL` di `1`.
- Quando il `TTL` arriva a `0`, il pacchetto viene scartato per evitare che circoli all'infinito in rete.

### Collegamento con ping e tracert

- In `ping`, il valore `TTL` della risposta puo' dare un'indicazione tecnica sul percorso o sul sistema remoto, ma non va interpretato in modo assoluto.
- In `tracert`, il meccanismo si basa proprio sull'aumento progressivo del `TTL` per far rispondere i router intermedi e mostrare gli hop del percorso.

### Tracert

- `tracert` mostra i passaggi intermedi, cioe' gli `hop`, che un pacchetto attraversa per arrivare a destinazione.
- E' utile per capire dove si interrompe o rallenta il percorso di rete.
- Aiuta a distinguere un problema locale, di gateway, di provider o di rete remota.

### Ipconfig

- `ipconfig` mostra la configurazione IP della macchina.
- Permette di vedere indirizzo `IP`, subnet mask, gateway predefinito e altre informazioni di base.
- E' utile per verificare se la macchina ha una configurazione coerente con la rete in cui si trova.

### Idea pratica

- `ping` risponde alla domanda: `la destinazione risponde?`
- `tracert` risponde alla domanda: `da dove passa il traffico?`
- `ipconfig` risponde alla domanda: `come e' configurata la mia macchina?`

### Lab: DNS Footprinting con `nslookup` e `dig`

- In questo esercizio abbiamo analizzato una piccola topologia con `pfSense`, una macchina `Kali` e una macchina `OpenSUSE`.
- L'obiettivo era capire come interrogare un server `DNS`, leggere diversi tipi di record e verificare se fosse possibile ottenere un `zone transfer`.

### Cosa ho imparato

- `nslookup` puo' essere usato in modalita' interattiva per cambiare server DNS e tipo di record da interrogare.
- Il comando `server 192.168.0.254` permette di scegliere esplicitamente il DNS server da interrogare nel lab.
- Il comando `set type=...` cambia il tipo di record richiesto, per esempio `A`, `NS`, `MX` o `AXFR`.
- `dig` svolge un lavoro simile a `nslookup`, ma mostra il risultato in modo piu' ricco e lineare gia' da riga di comando.

### Cosa ho scoperto nel lab

- Il dominio analizzato era `mylab.com`.
- Il record `NS` del dominio indicava che il nameserver di riferimento era `192.168.0.254`.
- Il record `A` di `opensuse.mylab.com` risolveva all'indirizzo `192.168.0.30`.
- Una richiesta `MX` non restituiva risposta visibile da `Kali`, anche se il record esisteva.
- Il tipo `ANY` non restituiva davvero tutto il contenuto della zona.

### Scoperta piu' importante

- Per vedere davvero tutti i record della zona bisogna tentare un `AXFR`, cioe' un `DNS zone transfer`.
- Da `Kali` il trasferimento di zona veniva `REFUSED`, quindi il server DNS non permetteva quella operazione a quel client.
- Da `OpenSUSE`, invece, il trasferimento era consentito e mostrava tutti i record della zona, inclusi `A`, `SOA`, `CNAME`, `TXT`, `MX` e `NS`.

### Perche' e' importante in cybersecurity

- Questo lab mostra che il `DNS footprinting` puo' rivelare molte informazioni utili su host, servizi e struttura di un dominio.
- Mostra anche che un `zone transfer` configurato male puo' esporre informazioni sensibili a un attaccante.
- Limitare `AXFR` solo a sistemi autorizzati e' quindi una misura di hardening importante del DNS.

### Confronto rapido tra strumenti

- `nslookup` e' utile per fare prove interattive e cambiare rapidamente tipo di query.
- `dig` e' spesso preferito in ambito tecnico perche' da una sintassi chiara e un output piu' dettagliato.
- Esempio equivalente visto nel lab: `dig @192.168.0.254 mylab.com ns`.
- Esempio equivalente con `nslookup`: `nslookup -type=ns -debug mylab.com 192.168.0.254`.

### Lab: ricognizione con `nmap`, `masscan` e `zenmap`

- In questo esercizio abbiamo usato strumenti di scansione di rete per capire quali host e quali servizi risultano esposti.
- L'idea di base e' che una scansione delle porte aiuta a costruire una prima mappa della superficie di attacco.

### Cosa ho imparato

- `nmap` e' uno strumento molto usato per identificare host attivi, porte aperte e servizi in ascolto.
- `masscan` e' pensato per eseguire scansioni molto veloci su grandi insiemi di IP o porte.
- `zenmap` e' l'interfaccia grafica di `nmap` e rende piu' semplice lanciare e leggere le scansioni.

### Differenza pratica tra i tre strumenti

- `nmap` punta su flessibilita', accuratezza e analisi dei servizi.
- `masscan` punta soprattutto sulla velocita' ed e' molto utile nella fase iniziale di scoperta rapida.
- `zenmap` non e' un motore diverso: usa `nmap`, ma con una GUI che aiuta a visualizzare risultati e profili di scansione.

### Cosa si cerca con questi strumenti

- Quali host sono raggiungibili o attivi.
- Quali porte risultano aperte.
- Quali servizi sembrano rispondere su quelle porte.
- Quali sistemi espongono piu' superficie di attacco o configurazioni interessanti da approfondire.

### Perche' e' importante in cybersecurity

- La scansione e' una fase classica di `reconnaissance` o ricognizione tecnica.
- Permette di vedere la rete dal punto di vista di un attaccante o di un difensore che vuole verificare cosa e' esposto.
- Sapere quali porte e servizi sono visibili aiuta a fare hardening, chiudere il superfluo e ridurre il rischio.

### Idea chiave

- `nmap` ti aiuta a capire bene `cosa c'e'`.
- `masscan` ti aiuta a capire molto rapidamente `dove guardare`.
- `zenmap` ti aiuta a usare `nmap` in modo piu' visuale e didattico.

### IP e porta

- Un `indirizzo IP` identifica la macchina o interfaccia di rete.
- Una `porta` identifica invece il servizio o il processo che deve ricevere la comunicazione su quella macchina.
- Insieme, `IP + porta` identificano un endpoint di comunicazione di rete.

### Cosa e' una porta

- La porta e' un numero logico usato dai protocolli di trasporto come `TCP` e `UDP`.
- Serve a distinguere piu' servizi sulla stessa macchina.
- Per esempio, una macchina puo' avere un solo IP ma piu' servizi in ascolto su porte diverse.

### Esempio intuitivo

- L'`IP` e' come l'indirizzo di un edificio.
- La `porta` e' come il numero dell'interno o dell'ufficio da raggiungere dentro quell'edificio.
- Quindi non basta sapere dove si trova la macchina: bisogna anche sapere quale servizio si vuole contattare.

### Esempi comuni

- `192.168.0.30:80` -> servizio web HTTP
- `192.168.0.30:443` -> servizio web HTTPS
- `192.168.0.30:502` -> Modbus TCP

### Porte comunemente scansionate

- Alcune porte vengono scansionate molto spesso perche' corrispondono a servizi molto diffusi o storicamente interessanti per gli attaccanti.

- `20/21` -> `FTP`- trasferimento file
- `22` -> `SSH` - amministrazione sicura
- `25` -> `SMTP` - posta
- `53` -> `DNS` - risoluzione nomi
- `80` -> `HTTP` - web in chiaro
- `443` -> `HTTPS` - web cifrato

### Porte da 1 a 1023

- Nel mondo `TCP/IP`, le porte da `1` a `1023` sono chiamate `well-known ports` o anche `privileged ports`.
- Sono porte storicamente riservate ai servizi di sistema o ai servizi piu' noti.
- Non significa che siano tutte "porte amministrative" in senso stretto, ma che sono porte standard associate a servizi fondamentali o molto comuni.

### Idea pratica

- Molti servizi classici usano proprio queste porte basse.
- Per questo vengono osservate, monitorate e scansionate molto spesso.
- Esempi: `22` per SSH, `25` per SMTP, `53` per DNS, `80` per HTTP, `443` per HTTPS.

### Perche' vengono scansionate spesso

- Per identificare quali servizi sono esposti su una macchina.
- Per cercare configurazioni deboli, versioni vulnerabili o accessi non protetti.
- Per ottenere una mappa iniziale della superficie di attacco del target.

### Come evitare accessi diretti su 80 o 443

- Se una macchina deve pubblicare un servizio web, non si evita il rischio semplicemente cambiando il numero di porta.
- La difesa corretta e' controllare `chi` puo' raggiungere quelle porte e `quale servizio` risponde dietro di esse.

### Misure pratiche

- Esporre solo cio' che serve davvero, evitando servizi inutili in ascolto.
- Mettere un `firewall` o ACL davanti al servizio per limitare gli IP o le reti autorizzate, quando possibile.
- Usare un `reverse proxy`, un `WAF` o un bilanciatore come punto di ingresso, invece di esporre direttamente l'applicazione interna.
- Tenere aggiornati il server web e l'applicazione per ridurre vulnerabilita' sfruttabili.
- Abilitare autenticazione forte, `HTTPS`, logging e monitoraggio.

### Come non dare informazioni sul servizio

- Un attaccante prova spesso a capire subito `che servizio e'`, `che software usa` e `quale versione` e' esposta.
- Queste informazioni possono comparire nei `banner`, negli `header HTTP`, nelle pagine di errore, nei certificati o in risposte troppo verbose.

### Misure di riduzione delle informazioni esposte

- Evitare di mostrare versione e prodotto del server quando non necessario.
- Ridurre o personalizzare i `banner` del servizio.
- Limitare gli `header` che rivelano tecnologia, framework o release.
- Configurare pagine di errore generiche, senza dettagli tecnici interni.
- Non esporre stack trace, path interni, nomi host, moduli caricati o messaggi di debug.

### Hardening

- Disabilitare moduli, plugin, directory listing e funzionalita' non necessarie.
- Rimuovere credenziali di default e account inutili.
- Applicare patch e aggiornamenti regolarmente.
- Impostare configurazioni sicure di `TLS`, cifrature e protocolli consentiti.
- Separare il servizio esposto dai sistemi interni tramite segmentazione o proxy.

### Idea pratica

- Nascondere la versione non sostituisce il hardening, ma aiuta a ridurre le informazioni utili a un attaccante.
- La regola corretta e' doppia: meno dettagli esposti e configurazione piu' sicura del servizio.

### Idea chiave

- Le porte `80` e `443` sono normali porte web e spesso devono restare raggiungibili.
- Quello che si protegge non e' la porta in se', ma l'accesso al servizio e la superficie esposta dietro quella porta.

### Risposta breve alla domanda

- Quello che unisce un indirizzo IP a una porta e' il concetto di `socket endpoint` o endpoint di comunicazione.
- L'IP dice `dove` si trova la macchina.
- La porta dice `quale servizio` dentro quella macchina deve ricevere il traffico.

### IP Spoofing

- L'`IP spoofing` e' una tecnica in cui un pacchetto viene costruito con un `indirizzo IP sorgente falso`.
- In pratica, l'attaccante fa apparire il traffico come se arrivasse da un altro host.

### A cosa serve

- Nascondere o confondere la vera origine del traffico.
- Fingersi un sistema considerato affidabile.
- Supportare alcuni attacchi di `flooding`, riflessione o aggiramento di controlli deboli basati solo sull'IP.

### Limite pratico importante

- Lo spoofing dell'IP e' piu' semplice nei protocolli o negli scenari in cui non serve completare correttamente una comunicazione bidirezionale.
- Per esempio, con `UDP` e' piu' facile usarlo rispetto a molte sessioni `TCP`, dove bisogna gestire anche le risposte e il three-way handshake.

### Idea chiave

- L'IP spoofing non cambia il contenuto del servizio, ma falsifica `chi sembra inviare` il traffico.
- Per questo non bisogna fidarsi dell'indirizzo IP come unico elemento di autenticazione o fiducia.

### CAM Table

- La `CAM table` e' la tabella interna di uno switch Ethernet che associa i `MAC address` alle sue porte fisiche.
- `CAM` significa `Content Addressable Memory`.
- Serve allo switch per capire su quale porta inoltrare un frame destinato a un certo MAC address.

### Come funziona

- Quando uno switch riceve un frame, legge il `MAC sorgente` e memorizza l'associazione tra quel MAC e la porta da cui il frame e' arrivato.
- Se poi deve inoltrare un frame verso un `MAC destinazione` gia' presente nella CAM table, lo invia solo sulla porta corretta.
- Se il MAC destinazione non e' ancora conosciuto, lo switch esegue `flooding`, cioe' inoltra il frame su piu' porte della LAN, tranne quella di ingresso.

### Perche' e' importante

- La CAM table rende la comunicazione piu' efficiente rispetto a un hub, perche' evita di inviare ogni frame a tutti.
- E' uno dei meccanismi fondamentali del funzionamento degli switch di livello 2.

### Logiche di Port Security

- La `port security` e' una funzione degli switch che controlla quali dispositivi possono usare una determinata porta.
- L'idea di base e' limitare i `MAC address` ammessi su una porta fisica dello switch.

### Obiettivi principali

- Ridurre il rischio che un dispositivo non autorizzato venga collegato alla rete.
- Limitare attacchi o comportamenti anomali a livello 2.
- Impedire che una singola porta venga usata liberamente da troppi dispositivi o da apparati non previsti.

### Come funziona

- Lo switch puo' essere configurato per accettare solo uno o un numero limitato di `MAC address` per porta.
- I MAC consentiti possono essere inseriti manualmente oppure appresi automaticamente dallo switch.
- Se sulla porta compare un MAC non autorizzato o si supera il numero massimo previsto, lo switch considera l'evento una violazione.

### Azioni tipiche in caso di violazione

- `Protect`: il traffico del MAC non autorizzato viene scartato.
- `Restrict`: il traffico viene bloccato e puo' essere generato un log o contatore di violazione.
- `Shutdown`: la porta viene messa in stato di errore o disattivata fino a intervento amministrativo o recovery automatico.

### Esempio pratico

- Se una porta e' destinata a un solo PC aziendale, si puo' consentire un solo MAC address.
- Se qualcuno scollega il PC e collega un dispositivo non autorizzato, la port security puo' bloccare la comunicazione o disabilitare la porta.

### Nota utile per la cybersecurity

- La port security non sostituisce autenticazione, NAC o segmentazione di rete, ma e' un controllo locale molto utile.
- E' particolarmente efficace per aumentare il controllo fisico e logico sugli accessi alla LAN.

### Pila ISO/OSI vs TCP/IP

Il modello `ISO/OSI` e il modello `TCP/IP` servono entrambi a descrivere come comunicano i sistemi in rete, ma hanno scopi e livelli diversi.

#### Modello ISO/OSI

- Il modello `ISO/OSI` e' un modello teorico a `7 livelli`.
- Serve soprattutto a capire e spiegare in modo ordinato le funzioni della comunicazione di rete.

**I 7 livelli OSI sono:**

1. `Physical`
2. `Data Link`
3. `Network`
4. `Transport`
5. `Session`
6. `Presentation`
7. `Application`

#### Modello TCP/IP

- Il modello `TCP/IP` e' piu' pratico e piu' vicino a come funzionano realmente Internet e le reti IP.
- In genere viene descritto con `4 livelli` principali.

**I 4 livelli TCP/IP sono:**

1. `Link` o `Network Access`
2. `Internet`
3. `Transport`
4. `Application`

#### Mappatura semplificata

- `OSI 7 + 6 + 5 (Application, Presentation, Session)` -> `TCP/IP Application`
- `OSI 4 (Transport)` -> `TCP/IP Transport`
- `OSI 3 (Network)` -> `TCP/IP Internet`
- `OSI 2 + 1 (Data Link, Physical)` -> `TCP/IP Link / Network Access`

#### Differenza chiave

- `ISO/OSI` e' soprattutto un modello di riferimento concettuale.
- `TCP/IP` e' il modello usato operativamente nelle reti moderne.

#### Esempio rapido di protocolli

- `Application`: HTTP, HTTPS, DNS, SMTP
- `Transport`: TCP, UDP
- `Internet/Network`: IP, ICMP
- `Link/Data Link`: Ethernet, Wi-Fi, MAC addressing

#### Da ricordare

- Quando si studia teoria di rete, si usa spesso l'OSI per ragionare meglio sui problemi.
- Quando si parla di funzionamento reale delle reti IP, si ragiona piu' spesso in termini di TCP/IP.

## Modbus

### Cos'e'

- Modbus e' un protocollo di comunicazione molto diffuso in ambito industriale e OT.
- Viene usato per far comunicare dispositivi come PLC, sensori, attuatori, sistemi SCADA e altri apparati di automazione.
- Il suo scopo e' scambiare dati di controllo e stato tra dispositivi industriali.

### Varianti principali

- Modbus RTU/ASCII: usato tipicamente su collegamenti seriali.
- Modbus TCP: usato su reti IP/Ethernet.

### Porta di rete

- La porta standard di Modbus TCP e' `502/TCP`.
- Quando si parla di porta di Modbus, di solito ci si riferisce proprio alla porta `502`.

### Nota utile per la cybersecurity

- Modbus e' molto diffuso negli ambienti OT, ma storicamente non e' nato con forti meccanismi di sicurezza integrati.
- Per questo, in ambito cybersecurity industriale, va protetto con segmentazione di rete, controllo degli accessi, monitoraggio e isolamento dei sistemi critici.

## Summary del NIST CSF 2.0

### Cos'e'

- Il NIST Cybersecurity Framework 2.0 e' un framework pensato per aiutare le organizzazioni a gestire il rischio cyber in modo strutturato.
- Non e' una legge e non e' una certificazione: e' una guida pratica per organizzare governance, controlli, processi e miglioramento continuo.
- E' pensato per organizzazioni di qualsiasi dimensione, non solo per infrastrutture critiche.

### Le 6 funzioni del CSF 2.0

- `Govern`: definisce strategia, policy, ruoli, responsabilita', risk management e supervisione.
- `Identify`: identifica asset, sistemi, dati, dipendenze e rischi.
- `Protect`: implementa salvaguardie per limitare o contenere l'impatto degli eventi cyber.
- `Detect`: rileva eventi anomali e possibili incidenti.
- `Respond`: gestisce la risposta all'incidente, il contenimento e la comunicazione.
- `Recover`: ripristina servizi, operazioni e resilienza dopo un incidente.

### Novita' principali rispetto al framework precedente

- La novita' piu' importante e' l'introduzione esplicita della funzione `Govern`.
- La governance non e' piu' implicita: diventa una parte centrale del framework.
- C'e' piu' attenzione al collegamento tra cybersecurity, obiettivi di business, leadership e gestione della supply chain.
- Il framework e' stato reso piu' adatto a organizzazioni diverse, comprese quelle non appartenenti alle infrastrutture critiche.

### Componenti principali del framework

- `Core`: insieme di funzioni, categorie e sottocategorie che descrivono cosa fare.
- `Profiles`: aiutano a descrivere lo stato attuale e lo stato obiettivo della cybersecurity di un'organizzazione.
- `Implementation Tiers`: aiutano a capire quanto il risk management cyber e' maturo e integrato nei processi decisionali.

### Perche' e' utile

- Aiuta a parlare di cybersecurity in modo comprensibile sia per il management sia per i team tecnici.
- Permette di prioritizzare gli investimenti in base al rischio.
- Supporta gap analysis, roadmap di miglioramento e allineamento con altri standard e controlli.

### Idea chiave da ricordare

- Il CSF 2.0 non dice solo quali controlli adottare, ma aiuta a collegare rischio, governance, operativita' e resilienza.
- In pratica, serve a trasformare la cybersecurity da tema tecnico isolato a disciplina integrata nella gestione dell'organizzazione.

## Introduzione a OWASP

### Cos'e'

- `OWASP` significa `Open Worldwide Application Security Project`.
- E' una comunita' e un riferimento molto importante per la sicurezza delle applicazioni, soprattutto web.
- Fornisce guide, progetti, strumenti e liste di rischi comuni utili a sviluppatori, tester e security team.

### Perche' e' importante

- OWASP aiuta a capire quali sono le vulnerabilita' applicative piu' frequenti e pericolose.
- E' molto usato come riferimento pratico per secure coding, test di sicurezza e formazione.

### OWASP Top 10

- Il riferimento piu' noto e' la `OWASP Top 10`, cioe' la lista delle principali categorie di vulnerabilita' nelle applicazioni web.
- Non e' una lista completa di tutti i problemi possibili, ma un riferimento utile per priorita', awareness e progettazione sicura.

### Collegamento con il corso

- OWASP si collega bene ai temi di `security by design`, gestione delle vulnerabilita' e hardening applicativo.
- E' utile per passare dalla teoria generale della cybersecurity ai problemi concreti del software e delle applicazioni esposte in rete.

## Differenza tra CVE, CWE, Vulnerability e Weakness

### Weakness

- Una `weakness` e' una debolezza generale di progettazione, implementazione, configurazione o processo.
- Non indica per forza un problema gia' sfruttabile in un prodotto specifico.
- E' il concetto piu' generale tra i quattro.

### Vulnerability

- Una `vulnerability` e' una vulnerabilita' specifica che puo' essere sfruttata per compromettere confidenzialita', integrita' o disponibilita'.
- In pratica, una weakness diventa una vulnerability quando esiste in un sistema o prodotto reale in modo sfruttabile.

### CWE

- `CWE` significa Common Weakness Enumeration.
- E' una classificazione di tipi di debolezze comuni.
- Descrive la categoria del problema, non il singolo caso concreto.
- Esempio: una validazione insufficiente dell'input o un buffer overflow come classe di errore.

### CVE

- `CVE` significa Common Vulnerabilities and Exposures.
- Identifica una vulnerabilita' specifica e pubblicamente nota in un prodotto, software o sistema reale.
- Ogni CVE ha un identificativo univoco, ad esempio `CVE-2024-12345`.

### Differenza pratica tra CWE e CVE

- `CWE` = tipo di errore o debolezza.
- `CVE` = istanza concreta di vulnerabilita' osservata in un prodotto reale.
- Una stessa CVE puo' essere collegata a una o piu' CWE, perche' una vulnerabilita' concreta deriva spesso da una categoria nota di debolezza.

### Differenza pratica tra Weakness e Vulnerability

- `Weakness` = difetto o debolezza generale.
- `Vulnerability` = debolezza concreta e sfruttabile in un contesto reale.

### Esempio intuitivo

- `CWE`: categoria "input validation error".
- `Weakness`: il software e' progettato male e non controlla correttamente alcuni input.
- `Vulnerability`: in una specifica applicazione questo difetto permette SQL injection.
- `CVE`: viene assegnato un identificativo pubblico alla specifica SQL injection scoperta in quel prodotto.

## CIA e CVSS

### Cos'e' il CVSS

- `CVSS` significa `Common Vulnerability Scoring System`.
- E' uno standard usato per assegnare un punteggio di gravita' a una vulnerabilita'.
- Il punteggio finale va da `0.0` a `10.0` e serve a capire quanto una vulnerabilita' sia severa e prioritaria.

### Perche' e' legato alla CIA

- Il CVSS considera anche l'impatto che una vulnerabilita' puo' avere su `Confidentiality`, `Integrity` e `Availability`.
- Quindi la triade CIA entra direttamente nella valutazione della severita' della vulnerabilita'.
- Se una vulnerabilita' compromette fortemente uno o piu' elementi della CIA, il punteggio tende a salire.

### Come si calcola in pratica

- Il CVSS non si calcola "a mano" in modo intuitivo, ma attraverso metriche standardizzate combinate in una formula.
- La parte piu' usata e' il `Base Score`, che rappresenta la gravita' intrinseca della vulnerabilita'.

### Metriche principali del Base Score

- `Attack Vector (AV)`: da dove puo' essere sfruttata la vulnerabilita', ad esempio rete o accesso locale.
- `Attack Complexity (AC)`: quanto e' difficile sfruttarla.
- `Privileges Required (PR)`: se servono o meno privilegi iniziali.
- `User Interaction (UI)`: se serve l'azione di un utente.
- `Scope (S)`: se l'impatto resta nello stesso ambito di sicurezza o si estende oltre.
- `Confidentiality (C)`: quanto impatta la riservatezza.
- `Integrity (I)`: quanto impatta l'integrita'.
- `Availability (A)`: quanto impatta la disponibilita'.

### Logica del punteggio

- Il punteggio nasce dalla combinazione di due grandi aree:
- `Exploitability`: quanto e' facile sfruttare la vulnerabilita'.
- `Impact`: quanto e' grave l'effetto della vulnerabilita', anche rispetto alla CIA.
- In sintesi: piu' e' facile sfruttarla e piu' alto e' l'impatto su C, I e A, piu' il CVSS sara' alto.

### Classi indicative di severita'

- `0.0`: None
- `0.1 - 3.9`: Low
- `4.0 - 6.9`: Medium
- `7.0 - 8.9`: High
- `9.0 - 10.0`: Critical

### Da ricordare

- Il CVSS misura la severita' tecnica di una vulnerabilita', non il rischio completo per una specifica organizzazione.
- Per valutare il rischio reale bisogna aggiungere il contesto: asset coinvolti, esposizione, contromisure esistenti e valore di business.

## Tipologie di attacco

Una classificazione classica degli attacchi distingue quattro categorie principali.

### Interruzione

- L'attacco di `interruzione` mira a rendere un sistema, un servizio o un dato non disponibile.
- E' collegato soprattutto alla `Availability` della triade CIA.
- Esempio: blocco di un servizio, sabotaggio, attacco DoS o ransomware che impedisce l'accesso ai dati.

### Intercettazione

- L'attacco di `intercettazione` mira a osservare, leggere o catturare informazioni senza autorizzazione.
- E' collegato soprattutto alla `Confidentiality`.
- Esempio: sniffing del traffico, eavesdropping, furto di credenziali o accesso non autorizzato ai dati.

### Modifica

- L'attacco di `modifica` mira ad alterare dati, messaggi, configurazioni o contenuti.
- E' collegato soprattutto alla `Integrity`.
- Esempio: modifica non autorizzata di un database, manomissione di file o alterazione di parametri di sistema.

### Contraffazione

- L'attacco di `contraffazione` mira a creare elementi falsi che sembrano legittimi.
- Può colpire sia la `Integrity` sia la `Confidentiality`, a seconda del contesto.
- Esempio: spoofing, falsificazione di identita', email contraffatte, messaggi o transazioni apparentemente autentiche.

### Collegamento rapido con la CIA

- `Interruzione` -> `Availability`
- `Intercettazione` -> `Confidentiality`
- `Modifica` -> `Integrity`
- `Contraffazione` -> soprattutto `Integrity`, ma spesso anche `Confidentiality`
