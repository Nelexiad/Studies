# Domande e Risposte - Cybersecurity Study Guide

---

## 1. Professional Code of Conduct & Ethics

### **Domanda 1**
Un professionista ISC2 scopre una grave vulnerabilità nel sistema di una società cliente, ma rivelare questa informazione potrebbe causare un danno economico significativo al cliente. Quale Canon del Codice Etico ISC2 dovrebbe avere la priorità assoluta in questa situazione?

**A)** Canon 3: Provide Diligent Service (Fornire Servizio Diligente)  
**B)** Canon 2: Act Honorably (Agire Onorevolmente)  
**C)** Canon 1: Protect Society (Proteggere la Società)  
**D)** Canon 4: Advance the Profession (Far Progredire la Professione)

**Risposta Corretta: C) Canon 1: Protect Society**

**Spiegazione:**
Il Canon 1 "Protect Society" ha la priorità assoluta perché stabilisce che i professionisti devono "proteggere la società, il bene comune, la fiducia pubblica necessaria e la confidenza, e l'infrastruttura". Una grave vulnerabilità non risolta rappresenta un rischio per la società nel suo complesso, che supera gli interessi economici del singolo cliente. Il professionista deve considerare l'impatto sociale delle decisioni di sicurezza e proteggere il bene comune sopra gli interessi personali o del cliente.

**Concetti Chiave:**
- Gerarchia etica: società > cliente > professionista
- Responsabilità verso il bene pubblico
- Bilanciamento degli interessi conflittuali
- Disclosure responsabile delle vulnerabilità

---

### **Domanda 2**
Quale delle seguenti NON è una conseguenza diretta della violazione del Codice Etico ISC2?

**A)** Revoca della certificazione  
**B)** Danneggiamento della reputazione professionale  
**C)** Arresto immediato da parte delle autorità  
**D)** Perdita della fiducia dei clienti e colleghi

**Risposta Corretta: C) Arresto immediato da parte delle autorità**

**Spiegazione:**
L'arresto immediato non è una conseguenza diretta della violazione del Codice Etico ISC2. Il Codice Etico è un framework professionale, non una legge penale. Le conseguenze dirette includono la revoca della certificazione (conseguenza amministrativa), il danneggiamento della reputazione professionale, e la perdita della fiducia. Le conseguenze legali dipenderebbero dalla natura specifica della violazione e dalle leggi applicabili, ma non sono automatiche.

**Concetti Chiave:**
- Differenza tra sanzioni professionali e penali
- Conseguenze amministrative vs legali
- Impatto sulla carriera professionale
- Natura del Codice Etico come standard professionale

### **Domanda 2-bis**
Quale dei seguenti NON è un canone etico dell'ISC2?

**A)** Protect society, the common good, necessary public trust and confidence, and the infrastructure  
**B)** Advance and protect the profession  
**C)** Provide active and qualified service to principal  
**D)** Act honorably, honestly, justly, responsibly and legally

**Risposta Corretta: C) Provide active and qualified service to principal**

**Spiegazione:**
Il Codice Etico stabilisce di "Fornire un servizio diligente e competente ai mandanti ovvero **Provide diligent and competent service to principals**", non "servizio attivo e qualificato". Tutte le altre opzioni sono canoni validi del Codice Etico. "Fornire servizio attivo e qualificato" non è elencato tra i canoni etici ISC2, che si concentrano su linee guida sociali, professionali ed etiche più ampie.

Le altre opzioni sono corrette perché riflettono i canoni ufficiali:
- "Protect society..." è il primo canone e sottolinea la responsabilità verso la società.
- "Act honorably..." è il secondo canone e richiede integrità personale.
- "Advance and protect the profession" è il quarto canone e incoraggia il progresso della professione.

**Concetti Chiave:**
- Esatta formulazione dei Canoni ISC2 in inglese
- Differenza tra "Diligent/Competent" e "Active/Qualified"

---

## 2. Governance e Strutture Organizzative

### **Domanda 3**
In una gerarchia di governance aziendale, qual è il corretto ordine di influenza dall'alto verso il basso?

**A)** Standards → Regulations → Policies → Procedures  
**B)** Regulations → Standards → Policies → Procedures  
**C)** Policies → Regulations → Standards → Procedures  
**D)** Procedures → Policies → Standards → Regulations

**Risposta Corretta: B) Regulations → Standards → Policies → Procedures**

**Spiegazione:**
Il flusso gerarchico corretto parte dalle **Regulations** (normative legali che stabiliscono i requisiti obbligatori), seguite dagli **Standards** (framework e best practice che forniscono guidance), dalle **Policies** (che definiscono la direzione strategica dell'organizzazione), e infine dalle **Procedures** (istruzioni operative dettagliate). Questo ordine garantisce che ogni livello supporti e implementi quello superiore, mantenendo la compliance legale e l'efficacia operativa.

**Concetti Chiave:**
- Gerarchia decisionale aziendale
- Relazione tra compliance e operazioni
- Cascata dell'autorità normativa
- Implementazione dall'alto verso il basso

---

### **Domanda 4**
Un'azienda multinazionale opera in USA (soggetta a HIPAA), nell'Unione Europea (soggetta a GDPR), e in Giappone. Come dovrebbe approcciare la compliance?

**A)** Applicare solo le normative del paese della sede principale  
**B)** Seguire le normative meno restrittive per ridurre i costi  
**C)** Applicare la normativa più restrittiva tra quelle applicabili  
**D)** Creare policy diverse per ogni paese

**Risposta Corretta: C) Applicare la normativa più restrittiva tra quelle applicabili**

**Spiegazione:**
Le organizzazioni multinazionali devono essere conformi a tutte le normative applicabili nei territori in cui operano. Il principio della "normativa più restrittiva" garantisce compliance universale evitando violazioni in qualsiasi giurisdizione. Questo approccio, chiamato anche "compliance to the highest standard", semplifica la governance riducendo la complessità operativa e minimizzando i rischi legali. Ad esempio, se GDPR è più restrittivo di altre normative sulla privacy, applicando GDPR globalmente l'azienda sarà conforme ovunque.

**Concetti Chiave:**
- Compliance multi-giurisdizionale
- Principio del "denominatore comune più alto"
- Gestione del rischio normativo
- Semplificazione operativa attraverso standardizzazione

---

## 3. CIA Triad (Confidentiality, Integrity, Availability)

### **Domanda 5**
Un ransomware ha crittografato tutti i file di un'azienda ma non li ha esfiltrati o modificati. Quale principio del triangolo CIA è stato principalmente compromesso?

**A)** Confidentiality (Riservatezza)  
**B)** Integrity (Integrità)  
**C)** Availability (Disponibilità)  
**D)** Tutti e tre i principi sono ugualmente compromessi

**Risposta Corretta: C) Availability (Disponibilità)**

**Spiegazione:**
In questo scenario, il ransomware ha reso i file inaccessibili agli utenti legittimi crittografandoli, ma non li ha divulgati (confidentiality intatta) né alterati (integrity preservata). Il principio principalmente compromesso è l'**Availability** perché i sistemi e i dati non sono più accessibili agli utenti autorizzati quando necessario. Questo è l'obiettivo tipico del ransomware: negare l'accesso ai dati per ottenere un riscatto, senza necessariamente compromettere la riservatezza o l'integrità dei dati originali.

**Concetti Chiave:**
- Distinzione tra i tre pilastri della sicurezza
- Natura degli attacchi ransomware
- Impatto specifico sulla disponibilità
- Analisi dell'incidente basata su CIA

---

### **Domanda 6**
Un dipendente modifica accidentalmente i prezzi in un database di e-commerce durante la manutenzione, causando prezzi errati sui prodotti visualizzati ai clienti. Quale principio CIA è stato violato?

**A)** Confidentiality (Riservatezza)  
**B)** Integrity (Integrità)  
**C)** Availability (Disponibilità)  
**D)** Nessun principio è stato violato perché è stato un errore accidentale

**Risposta Corretta: B) Integrity (Integrità)**

**Spiegazione:**
L'**Integrity** è stata compromessa perché le informazioni non sono più accurate, complete, coerenti e affidabili. I prezzi modificati erroneamente non riflettono i valori corretti, rendendo i dati inaffidabili per i clienti e l'azienda. Il fatto che la modifica sia avvenuta accidentalmente non cambia l'impatto sull'integrità dei dati. La confidentiality non è compromessa (i dati non sono stati divulgati impropriamente) e l'availability è mantenuta (i dati sono ancora accessibili).

**Concetti Chiave:**
- Integrità dei dati come accuratezza e affidabilità
- Impatto delle modifiche non autorizzate (intenzionali o accidentali)
- Distinzione tra causa e effetto sulla sicurezza
- Controlli preventivi per mantenere l'integrità

---

## 4. Privacy e Protezione Dati Personali

### **Domanda 7**
Un'azienda americana che non ha uffici in Europa raccoglie dati di marketing da visitatori del proprio sito web, inclusi cittadini europei. Il GDPR si applica a questa situazione?

**A)** No, perché l'azienda non ha presenza fisica in Europa  
**B)** No, perché è un'azienda americana soggetta solo alle leggi USA  
**C)** Sì, perché il GDPR ha portata internazionale e si applica al trattamento di dati di cittadini UE  
**D)** Sì, ma solo se l'azienda vende prodotti in Europa

**Risposta Corretta: C) Sì, perché il GDPR ha portata internazionale e si applica al trattamento di dati di cittadini UE**

**Spiegazione:**
Il GDPR ha **portata extraterritoriale** e si applica a qualsiasi organizzazione che tratti dati personali di cittadini UE, indipendentemente dalla presenza fisica nell'UE. L'articolo 3 del GDPR stabilisce che il regolamento si applica quando: 1) il trattamento avviene nel contesto di uno stabilimento UE, oppure 2) riguarda soggetti UE e l'offerta di beni/servizi o il monitoraggio del comportamento. Raccogliere dati di marketing da cittadini europei rientra chiaramente in questa seconda categoria.

**Concetti Chiave:**
- Portata extraterritoriale del GDPR
- Principio di territorialità dei dati vs nazionalità del data controller
- Applicabilità basata sui soggetti dei dati, non sulla sede dell'azienda
- Implicazioni globali delle normative privacy moderne

---

### **Domanda 8**
Quale delle seguenti NON è considerata una PII diretta?

**A)** Codice fiscale  
**B)** Indirizzo IP  
**C)** Numero di passaporto  
**D)** Indirizzo email personale

**Risposta Corretta: B) Indirizzo IP**

**Spiegazione:**
L'**indirizzo IP** è considerato una **PII indiretta** (o quasi-identificatore) perché da solo non identifica direttamente una persona specifica, ma può essere utilizzato in combinazione con altre informazioni per l'identificazione. Le PII dirette (codice fiscale, numero di passaporto, email personale) possono identificare univocamente una persona senza bisogno di informazioni aggiuntive. L'indirizzo IP può cambiare, essere condiviso tra più utenti, o richiedere informazioni aggiuntive dal provider per collegarlo a una persona specifica.

**Concetti Chiave:**
- Distinzione tra PII dirette e indirette
- Capacità identificativa autonoma vs combinata
- Variabilità e condivisione degli identificatori di rete
- Necessità di informazioni aggiuntive per l'identificazione definitiva

---

## 5. Standard e Framework

### **Domanda 9**
Quale delle seguenti è la corretta sequenza delle 5 funzioni del NIST Cybersecurity Framework?

**A)** Protect → Identify → Detect → Respond → Recover  
**B)** Identify → Protect → Detect → Respond → Recover  
**C)** Detect → Identify → Protect → Respond → Recover  
**D)** Identify → Detect → Protect → Respond → Recover

**Risposta Corretta: B) Identify → Protect → Detect → Respond → Recover**

**Spiegazione:**
La sequenza corretta del NIST CSF segue un approccio logico e progressivo:
1. **IDENTIFY**: Prima devi sapere cosa hai (asset, sistemi, dati, rischi)
2. **PROTECT**: Implementa safeguard basati su ciò che hai identificato
3. **DETECT**: Monitora per identificare eventi di sicurezza
4. **RESPOND**: Reagisci agli incidenti rilevati
5. **RECOVER**: Ripristina le operazioni normali

Questo ordine riflette il ciclo naturale della gestione della sicurezza: conoscenza → prevenzione → rilevamento → reazione → ripristino.

**Concetti Chiave:**
- Approccio sistematico alla cybersecurity
- Sequenza logica delle attività di sicurezza
- Ciclo continuo di miglioramento
- Framework basato su funzioni complementari

---

### **Domanda 10**
Un'organizzazione vuole ottenere una certificazione riconosciuta internazionalmente per il proprio sistema di gestione della sicurezza informatica. Quale standard dovrebbe implementare?

**A)** NIST Cybersecurity Framework  
**B)** ISO 27001  
**C)** OWASP Top 10  
**D)** COBIT

**Risposta Corretta: B) ISO 27001**

**Spiegazione:**
**ISO 27001** è l'unico standard tra quelli elencati che offre una **certificazione formale** riconosciuta internazionalmente per i sistemi di gestione della sicurezza informatica (ISMS). È basato sul ciclo PDCA e richiede audit di terze parti per la certificazione. Gli altri standard sono importanti ma non offrono certificazione formale: NIST CSF è un framework di guidance, OWASP Top 10 è specifico per applicazioni web, e COBIT si focalizza sulla governance IT generale.

**Concetti Chiave:**
- Differenza tra standard certificabili e framework di guidance
- Valore della certificazione di terze parti
- Riconoscimento internazionale degli standard ISO
- Sistema di gestione formale vs implementazione informale

---

## 6. Gestione dei Rischi e Controlli

### **Domanda 11**
Un'azienda sta implementando controlli di sicurezza. Secondo il principio di "data minimization", quale approccio dovrebbe adottare per la raccolta dei dati clienti?

**A)** Raccogliere tutti i dati possibili per future necessità non ancora identificate  
**B)** Raccogliere solo i dati essenziali per gli scopi dichiarati e limitarne la conservazione  
**C)** Raccogliere solo dati pubblicamente disponibili  
**D)** Raccogliere dati solo tramite fonti esterne verificate

**Risposta Corretta: B) Raccogliere solo i dati essenziali per gli scopi dichiarati e limitarne la conservazione**

**Spiegazione:**
Il principio di **data minimization** è fondamentale in cybersecurity e privacy (specialmente nel GDPR). Stabilisce che le organizzazioni dovrebbero:
- Raccogliere solo i dati **strettamente necessari** per gli scopi specifici dichiarati
- **Limitare la conservazione** ai tempi necessari (data retention policies)
- **Non raccogliere dati "per il futuro"** senza scopo specifico attuale
- **Classificare i dati** per importanza e applicare protezioni appropriate

Questo principio riduce la superficie di attacco, limita l'esposizione in caso di breach, semplifica la compliance, e rispetta la privacy degli interessati.

**Concetti Chiave:**
- Principio di necessità e proporzionalità
- Data retention policies
- Riduzione della superficie di attacco
- Compliance privacy by design

---

### **Domanda 12**
In un approccio di gestione del rischio basato su ISO 27001, quale metodologia viene utilizzata per il miglioramento continuo?

**A)** Metodologia Agile  
**B)** Ciclo PDCA (Plan-Do-Check-Act)  
**C)** Metodologia Waterfall  
**D)** Six Sigma

**Risposta Corretta: B) Ciclo PDCA (Plan-Do-Check-Act)**

**Spiegazione:**
**ISO 27001** è esplicitamente basato sul **ciclo PDCA** per il miglioramento continuo del sistema di gestione della sicurezza informatica:

- **PLAN**: Stabilire obiettivi, politiche, processi e procedure ISMS
- **DO**: Implementare e operare le politiche, controlli, processi e procedure ISMS  
- **CHECK**: Valutare e misurare le prestazioni dei processi rispetto alla politica ISMS
- **ACT**: Intraprendere azioni correttive e preventive basate sui risultati dell'audit interno ISMS

Questo approccio garantisce che l'ISMS sia continuamente monitorato, valutato e migliorato.

**Concetti Chiave:**
- Miglioramento continuo in cybersecurity
- Approccio sistematico alla gestione
- Ciclo di valutazione e correzione
- Framework di management system

---

## 7. Incident Response e Business Continuity

### **Domanda 13**
Durante un incidente di sicurezza, un'azienda deve bilanciare la trasparenza con i clienti e la necessità di non compromettere le indagini. Quale principio del Codice Etico ISC2 fornisce guidance per questa situazione?

**A)** Canon 1: Protect Society - la trasparenza deve essere massima  
**B)** Canon 2: Act Honorably - bilanciare onestà e responsabilità  
**C)** Canon 3: Provide Diligent Service - proteggere solo gli interessi del cliente  
**D)** Canon 4: Advance the Profession - condividere tutto per scopi educativi

**Risposta Corretta: B) Canon 2: Act Honorably - bilanciare onestà e responsabilità**

**Spiegazione:**
**Canon 2 "Act Honorably"** richiede di agire in modo onorevole, onesto, giusto, responsabile e legale. In una situazione di incident response, questo significa:
- **Onestà**: essere veritieri nelle comunicazioni senza nascondere l'incidente
- **Responsabilità**: considerare l'impatto delle comunicazioni sulle indagini e sulla security posture
- **Giustizia**: bilanciare i diritti dei clienti di essere informati con la necessità di proteggere l'integrità delle indagini

Il professionista deve trovare un equilibrio comunicando l'essenziale ai clienti senza compromettere le indagini o esporre ulteriori vulnerabilità.

**Concetti Chiave:**
- Bilanciamento di interessi conflittuali
- Comunicazione responsabile durante gli incidenti
- Integrità delle indagini di sicurezza
- Trasparenza calibrata vs disclosure completa

### **Domanda 13-bis**
Which are the components of an incident response plan?

**A)** Preparation → Detection and Analysis → Recovery → Containment → Eradication → Post-Incident Activity  
**B)** Preparation → Detection and Analysis → Eradication → Recovery → Containment → Post-Incident Activity  
**C)** Preparation → Detection and Analysis → Containment, Eradication and Recovery → Post-Incident Activity  
**D)** Preparation → Detection and Analysis → Containment → Eradication → Post-Incident Activity → Recovery

**Risposta Corretta: C) Preparation → Detection and Analysis → Containment, Eradication and Recovery → Post-Incident Activity**

**Spiegazione:**
Il ciclo di vita della risposta agli incidenti (secondo NIST e ISC2) segue questo ordine logico:

1.  **Preparation**: Stabilire policy, procedure e strumenti *prima* che avvenga un incidente.
2.  **Detection and Analysis**: Identificare e analizzare l'incidente per capirne la natura e l'impatto.
3.  **Containment, Eradication and Recovery**:
    *   **Containment**: Limitare la diffusione del danno (es. isolare un sistema).
    *   **Eradication**: Rimuovere la causa radice (es. eliminare il malware).
    *   **Recovery**: Ripristinare i sistemi alla normale operatività.
    *(Queste fasi sono spesso raggruppate perché cicliche e interconnesse).*
4.  **Post-Incident Activity**: Review delle lezioni apprese (Lessons Learned) per migliorare il processo.

**Perché gli altri ordini sono errati:**
- Non si può fare **Recovery** (ripristino) prima di **Eradication** (rimozione della minaccia), altrimenti si ripristinerebbe un sistema ancora infetto.
- **Post-Incident Activity** è sempre l'ultima fase.
- **Containment** deve avvenire subito dopo l'analisi per fermare l'emorragia.

**Concetti Chiave:**
- Ciclo di vita NIST SP 800-61
- Logical flow: Prepare -> Detect -> Stop (Contain) -> Fix (Eradicate) -> Restore (Recovery) -> Learn.

---

## 8. Crittografia e Controlli Tecnici

### **Domanda 14**
Un'organizzazione implementa crittografia end-to-end per proteggere i dati sensibili. Quali stati dei dati dovrebbero essere protetti per una implementazione completa?

**A)** Solo i dati in transito (in transit)  
**B)** Solo i dati in archivio (at rest)  
**C)** Solo i dati in elaborazione (in processing)  
**D)** Tutti e tre: at rest, in transit, e in processing

**Risposta Corretta: D) Tutti e tre: at rest, in transit, e in processing**

**Spiegazione:**
Una **implementazione completa** di protezione crittografica deve coprire tutti i possibili stati dei dati:

- **At Rest**: Dati memorizzati su database, file system, backup (crittografia del storage)
- **In Transit**: Dati che viaggiano sulla rete (TLS/SSL, VPN, encrypted channels)  
- **In Processing**: Dati in memoria durante l'elaborazione (homomorphic encryption, secure enclaves, trusted execution environments)

Proteggere solo uno o due stati lascia gap di sicurezza che possono essere sfruttati da attaccanti. L'approccio "defense in depth" richiede protezione completa attraverso tutti gli stati.

**Concetti Chiave:**
- Stati dei dati in cybersecurity
- Defense in depth strategy
- Protezione end-to-end completa
- Gaps di sicurezza e surface di attacco

---

## 9. Change Management

### **Domanda 15**
Quale dei seguenti NON è un componente del change management?

**A)** Approval  
**B)** Rollback  
**C)** RFG  
**D)** Stakeholder

**Risposta Corretta: C) RFG**

**Spiegazione:**
**RFG** non è un componente riconosciuto del change management. Probabilmente c'è stata una confusione con **RFC (Request for Change)**, che invece è un componente fondamentale. I componenti corretti del change management includono:

- **Approval**: Il processo di approvazione delle modifiche da parte delle autorità competenti (Change Advisory Board, management)
- **Rollback**: La capacità di tornare alla configurazione precedente in caso di problemi con la modifica implementata
- **Stakeholder**: Le parti interessate che devono essere coinvolte, informate e consultate durante il processo di change management

**Altri componenti chiave del Change Management:**
- **RFC (Request for Change)**: Richiesta formale di modifica
- **Impact Assessment**: Valutazione dell'impatto della modifica
- **Change Advisory Board (CAB)**: Gruppo che valuta e approva le modifiche
- **Change Schedule**: Pianificazione temporale delle modifiche
- **Documentation**: Documentazione completa delle modifiche
- **Testing**: Verifica della modifica in ambiente di test
- **Communication Plan**: Piano di comunicazione agli stakeholder

**Concetti Chiave:**
- Change management come processo strutturato
- Importanza dell'approvazione formale
- Necessità di piani di rollback
- Coinvolgimento degli stakeholder
- Differenza tra acronimi corretti (RFC) e inesistenti (RFG)

---

## 10. Access Control Models (Modelli di Controllo degli Accessi)

### **Domanda 16**
Quale modello di controllo degli accessi può garantire l'accesso a un determinato oggetto basandosi su regole complesse?

**A)** ABAC  
**B)** RBAC  
**C)** DAC  
**D)** MAC

**Risposta Corretta: A) ABAC (Attribute-Based Access Control)**

**Spiegazione:**
**ABAC (Attribute-Based Access Control)** è il modello più potente e flessibile per gestire regole di accesso complesse. Nel ABAC:

- Le decisioni di accesso sono basate su **attributi multipli** che possono essere combinati in regole complesse:
  - **Attributi dell'utente**: ruolo, dipartimento, clearance, posizione geografica
  - **Attributi della risorsa**: tipo di dato, classificazione, proprietario
  - **Attributi del contesto**: ora del giorno, metodo di connessione, livello di rischio
  - **Attributi ambientali**: livello di minaccia corrente, stato del sistema

> **Nota:** Molti **SDN (Software Defined Networks)** utilizzano modelli ABAC per gestire l'accesso alla rete in modo dinamico.

- Permette la creazione di **policy complesse e granulari** come:
  - "Consenti l'accesso solo se l'utente è un manager del dipartimento HR, durante orario lavorativo, da una rete aziendale, e il documento è classificato come 'Interno'"
  - "Nega l'accesso se il livello di rischio è alto o la connessione proviene da un paese ad alto rischio"

- È il modello più **moderno e scalabile** per ambienti complessi, cloud e dinamici
- Supporta **fine-grained access control** (controllo degli accessi a grana fine)

**Confronto con gli altri modelli:**

**MAC (Mandatory Access Control):**
- Basato su **classificazioni di sicurezza formali** (Top Secret, Secret, ecc.)
- Regole rigide e predefinite (Bell-LaPadula, Biba)
- Meno flessibile per regole complesse e dinamiche
- Tipicamente utilizzato in ambienti governativi/militari

**RBAC (Role-Based Access Control):**
- Gli accessi sono basati solo sui **ruoli** assegnati agli utenti
- Più semplice ma meno flessibile per regole complesse
- Non considera contesto, ambiente, o altri attributi dinamici

**DAC (Discretionary Access Control):**
- I **proprietari delle risorse** decidono chi può accedere
- Il modello più semplice e meno adatto per regole complesse
- Nessun controllo centralizzato delle policy

**Concetti Chiave:**
- MAC come modello per sicurezza ad alto livello
- Differenze tra enforcement obbligatorio vs discrezionale
- Classificazioni di sicurezza e clearance
- Modelli formali di sicurezza (Bell-LaPadula, Biba)
- Contesti di utilizzo appropriati per ciascun modello

### **Domanda 16-bis**
The Bell and LaPadula access control model is a form of: (★)

**A)** RBAC  
**B)** DAC  
**C)** MAC  
**D)** ABAC

**Risposta Corretta: C) MAC (Mandatory Access Control)**

**Spiegazione:**
Il modello **Bell-LaPadula** è la forma più classica di **Mandatory Access Control (MAC)**.
- **Funzionamento**: Dispone soggetti (utenti) e oggetti (dati) in livelli di sicurezza (es. Top Secret, Secret, Unclassified) e definisce specifiche di accesso rigide.
- **Regole principali (Focus sulla Confidentiality):**
  1.  **Simple Security Property (No Read Up)**: Un utente a livello "Secret" non può leggere dati "Top Secret".
  2.  ***-Property (Star Property) (No Write Down)**: Un utente a livello "Top Secret" non può scrivere dati in un file "Secret" (per prevenire la fuoriuscita di dati sensibili).
- Poiché i soggetti (utenti) **non possono modificare** queste specifiche di accesso (sono imposte dal sistema/policy centrale), si tratta di un controllo **Mandatorio (MAC)**.

**Confronto:**
- **DAC (Discretionary)**: Lascia la discrezione al proprietario dell'oggetto.
- **RBAC (Role Based)**: Basa l'accesso sui ruoli lavorativi.
- **ABAC (Attribute Based)**: Basa l'accesso su attributi di soggetto, oggetto e ambiente.

**Concetti Chiave:**
- **Bell-LaPadula** = Confidentiality (No Read Up, No Write Down).
- **Biba** = Integrity (No Read Down, No Write Up).
- **MAC** = Sistema impone le regole, utente non ha discrezione.

### **Domanda 17**
Un'entità che agisce per sfruttare le vulnerabilità del sistema di un'organizzazione target è definita come:

**A)** Risk  
**B)** Threat Vector  
**C)** Attacker  
**D)** Threat Actor

**Risposta Corretta: D) Threat Actor**

**Spiegazione:**
Un **Threat Actor** (o Threat Agent) è il termine formale che definisce l'entità (individuo, gruppo o organizzazione) che avvia un'azione minacciosa per sfruttare una vulnerabilità.

**Perché le altre opzioni sono errate:**
- **Risk (Rischio)**: È la probabilità che una minaccia sposi una vulnerabilità causando un danno. È un concetto probabilistico, non un'entità.
- **Threat Vector (Vettore di Minaccia)**: È il *metodo* o il *percorso* utilizzato dall'attaccante per raggiungere il target (es. phishing email, USB drive, port 80 non patchata). Risponde alla domanda "come", non "chi".
- **Attacker (Attaccante)**: Sebbene sia spesso usato come sinonimo, "Threat Actor" è il termine tecnico più preciso e inclusivo utilizzato nei framework di cybersecurity per categorizzare le sorgenti delle minacce (es. Nation-State, Hacktivist, Insider, Script Kiddie).

**Concetti Chiave:**
- Distinzione tra Actor (Chi), Vector (Come), Vulnerability (Debolezza) e Risk (Probabilità)
- Terminologia standard ISC2
- Categorizzazione dei Threat Actors

---

## 12. Cloud Deployment Models

### **Domanda 18**
Which cloud deployment model is suited to companies with similar needs and concerns?

**A)** Private cloud  
**B)** Multi-tenant  
**C)** Community cloud  
**D)** Hybrid cloud

**Risposta Corretta: C) Community cloud**

**Spiegazione:**
**Community cloud** deployment models are where several organizations with similar needs and concerns (technological or regulatory) share the infrastructure and resources of a cloud environment. This model is attractive because it is cost-effective while addressing the specific requirements of the participating organizations.

**Analisi delle altre opzioni:**
- **Private cloud**: A cloud computing model where the cloud infrastructure is dedicated to a **single** organization (and never shared with others).
- **Hybrid cloud**: A model that combines (i.e., orchestrates) on-premises infrastructure, private cloud services, and a public cloud to handle storage and service.
- **Multi-tenant**: Refers to a cloud **architecture** where multiple cloud tenants (organizations or users) share the same computing resources. Yet, while resources are shared, each tenant's data is isolated and remains invisible to other tenants. It is not a distinct deployment model like Private/Public/Community.

**Concetti Chiave:**
- Community Cloud = Shared interests (mission, policy, compliance)
- Cost-effective vs Private Cloud
- More secure vs Public Cloud

### **Domanda 18-bis**
In which cloud model does the cloud customer have LESS responsibility over the infrastructure? (★)

**A)** PaaS  
**B)** IaaS  
**C)** SaaS  
**D)** FaaS

**Risposta Corretta: C) SaaS**

**Spiegazione:**
Il **Software as a Service (SaaS)** è il modello di servizio cloud in cui il cliente ha la **minima responsabilità** sull'infrastruttura. In questo modello, il cloud provider gestisce tutto: dai server, storage e networking fino alle funzioni applicative, aggiornamenti e sicurezza. Il cliente deve solo utilizzare l'applicazione.

**Confronto delle responsabilità:**
- **SaaS (Software as a Service)**: Il provider gestisce tutto (es. Gmail, Salesforce). Il cliente usa solo il software.
- **PaaS (Platform as a Service)**: Il provider gestisce hardware e runtime. Il cliente gestisce le applicazioni e i dati sviluppati (es. Google App Engine).
- **IaaS (Infrastructure as a Service)**: Il provider gestisce hardware, storage e network. Il cliente gestisce OS, applicazioni e dati (es. AWS EC2).
- **On-Premises**: Il cliente gestisce tutto, dal data center alle applicazioni.

Il **FaaS (Function as a Service)** è simile al PaaS ma più granulare, focalizzato sull'esecuzione di singole funzioni. Anche qui la responsabilità è bassa, ma il SaaS rappresenta il livello in cui l'intera applicazione è gestita esternamente.

**Concetti Chiave:**
- Modello di responsabilità condivisa nel cloud
- Differenza tra gestione dell'infrastruttura vs utilizzo del software
- Progressione IaaS -> PaaS -> SaaS

---

## 13. Crittografia e Hashing

### **Domanda 19**
Quale delle seguenti NON è una caratteristica di una funzione hash crittografica?

**A)** Deterministic (Deterministica)  
**B)** Useful (Utile)  
**C)** Unique (Unica/Collision Resistant)  
**D)** Reversible (Reversibile)

**Risposta Corretta: D) Reversible (Reversibile)**

**Spiegazione:**
Una funzione hash crittografica è progettata per essere una **funzione unidirezionale (one-way function)**. Questo significa che deve essere **computazionalmente impossibile** risalire al messaggio originale partendo dal suo hash. Pertanto, la "reversibilità" è l'esatto opposto di ciò che un hash deve essere.

**Caratteristiche essenziali di un hash crittografico:**
- **Deterministic (Deterministico)**: Lo stesso input deve produrre sempre lo stesso output (hash).
- **Collision Resistant (Resistente alle collisioni)**: Deve essere estremamente difficile trovare due input diversi che producano lo stesso hash (nota: "Unique" nell'opzione si riferisce idealmente a questo, anche se matematicamente le collisioni sono possibili ma improbabili).
- **Avalanche Effect**: Un piccolo cambiamento nell'input (anche un solo bit) deve cambiare drasticamente l'output.
- **Veloce da calcolare**: Deve essere rapido generare l'hash per qualsiasi input.

**Concetti Chiave:**
- Differenza tra Hashing (one-way) e Encryption (two-way, reversibile con chiave)
- Integrità dei dati
- Funzioni one-way

---

## 14. Digital Signatures

### **Domanda 20**
Quale delle seguenti proprietà NON è garantita dalle Firme Digitali (Digital Signatures)?

**A)** Integrity (Integrità)  
**B)** Confidentiality (Riservatezza)  
**C)** Non-repudiation (Non ripudio)  
**D)** Authentication (Autenticazione)

**Risposta Corretta: B) Confidentiality (Riservatezza)**

**Spiegazione:**
Una **Firma Digitale** garantisce l'autenticità del mittente, l'integrità del messaggio (che non è stato modificato) e il non ripudio (il mittente non può negare di averlo inviato). Tuttavia, **NON garantisce la riservatezza**. Una firma digitale è spesso applicata a un messaggio in chiaro o a un hash del messaggio; chiunque intercetti il messaggio firmato può leggerne il contenuto, a meno che non venga utilizzata separatamente la cifratura (encryption) per garantire la confidenzialità.

**Cosa garantisce la Firma Digitale:**
1.  **Authentication**: Conferma l'identità del firmatario.
2.  **Integrity**: L'hash del messaggio assicura che il contenuto non sia stato alterato.
3.  **Non-repudiation**: Solo il possessore della chiave privata poteva generare la firma.

**Cosa NON garantisce:**
- **Confidentiality**: Il messaggio rimane leggibile se non viene cifrato (es. con PGP o S/MIME in combinazione con la firma).

**Concetti Chiave:**
- Scopo primario delle firme digitali (Autenticazione + Integrità + Non ripudio)
- Differenza tra firmare (signing) e cifrare (encrypting)
- Uso dell'hashing e della crittografia asimmetrica nelle firme

---

## 15. Social Engineering

### **Domanda 21**
Quale delle seguenti NON è una tecnica di social engineering?

**A)** Quid pro quo  
**B)** Segregation (Segregazione)  
**C)** Baiting  
**D)** Pretexting

**Risposta Corretta: B) Segregation (Segregazione)**

**Spiegazione:**
**Segregation** (spesso riferito come *Segregation of Duties* o SoD) è un principio di sicurezza e un controllo amministrativo progettato per prevenire frodi ed errori, NON una tecnica di attacco. Richiede che compiti critici siano divisi tra più persone.

Le altre opzioni sono tutte tecniche di **Social Engineering**:
- **Quid pro quo**: L'attaccante promette un beneficio in cambio di informazioni (es. "Ti darò una penna se compili questo sondaggio con la tua password").
- **Baiting**: L'attaccante lascia un dispositivo fisico infetto (es. chiavetta USB) in un luogo dove la vittima possa trovarlo (esca), sperando che lo inserisca nel computer.
- **Pretexting**: L'attaccante crea uno scenario inventato (pretesto) per persuadere la vittima a rilasciare informazioni o eseguire un'azione (es. finto supporto tecnico).

**Concetti Chiave:**
- Riconoscimento delle tecniche di social engineering
- Differenza tra controlli di sicurezza (difesa) e vettori di attacco
- Segregation of Duties come controllo difensivo

---

## 16. Security Principles (Principi di Sicurezza)

### **Domanda 22**
Quale dei seguenti principi mira principalmente al rilevamento delle frodi (fraud detection)?

**A)** Privileged Accounts  
**B)** Least Privilege  
**C)** Defense in Depth  
**D)** Separation of Duties

**Risposta Corretta: D) Separation of Duties (Separazione dei Compiti)**

**Spiegazione:**
La **Separation of Duties (SoD)** è un principio fondamentale di controllo interno progettato per prevenire frodi ed errori. Richiedendo che più di una persona sia coinvolta nel completamento di un compito critico, si riduce drasticamente la possibilità che un singolo individuo possa commettere una frode e nasconderla senza collusione con qualcun altro.

**Analisi delle altre opzioni:**
- **Least Privilege (Minimo Privilegio)**: Mira a limitare i danni accidentali o intenzionali riducendo i permessi, ma non è focalizzato specificamente sul rilevamento delle frodi.
- **Defense in Depth**: Mira a proteggere gli asset attraverso strati multipli di sicurezza, focalizzandosi sulla resilienza contro gli attacchi esterni/interni.
- **Privileged Accounts**: Sono target di attacco da proteggere, non un principio di sicurezza in sé (la loro gestione sicura lo è).

**Concetti Chiave:**
- SoD come strumento anti-frode principale
- Necessità di collusione per aggirare la SoD
- Differenza tra prevenzione (SoD) e limitazione danni (Least Privilege)

---

## 17. Domanda Scenario Complesso

### **Domanda 23**
Un'azienda sanitaria multinazionale (USA ed Europa) subisce un data breach che espone 50.000 cartelle cliniche. L'incidente viene scoperto dal team IT interno, che identifica anche una vulnerabilità zero-day nel sistema. Il CEO vuole nascondere l'incidente per evitare danni reputazionali, ma il CISO sa che alcune normative richiedono notification entro 72 ore. Come professionista ISC2, qual è la priorità d'azione più appropriata?

**A)** Seguire le istruzioni del CEO per proteggere l'azienda (Canon 3: Provide Diligent Service)  
**B)** Notificare immediatamente alle autorità per proteggere la società (Canon 1: Protect Society)  
**C)** Condividere pubblicamente tutti i dettagli tecnici per far progredire la professione (Canon 4)  
**D)** Dimettersi per evitare conflitti etici

**Risposta Corretta: B) Notificare immediatamente alle autorità per proteggere la società (Canon 1: Protect Society)**

**Spiegazione:**
Questa situazione complessa richiede l'applicazione della **gerarchia etica ISC2**. Nonostante i conflitti con il management:

**Canon 1 (Protect Society)** ha la priorità assoluta perché:
- 50.000 pazienti sono a rischio (furto identità, discriminazione sanitaria)
- La vulnerabilità zero-day rappresenta un rischio sistemico per altre organizzazioni sanitarie
- Le normative (HIPAA, GDPR) richiedono notification per proteggere gli interessati
- Il bene pubblico supera gli interessi aziendali

**Azioni specifiche:**
- Notification alle autorità competenti (HHS per HIPAA, Data Protection Authorities per GDPR)
- Comunicazione ai pazienti interessati
- Disclosure responsabile della vulnerabilità zero-day
- Documentazione delle decisioni etiche prese

Il professionista ISC2 deve anteporre la protezione della società agli interessi del datore di lavoro, anche a costo di conflitti interni.

**Concetti Chiave:**
- Gerarchia etica: società > cliente > professionista
- Breach notification requirements
- Responsible disclosure di vulnerabilità
- Coraggio professionale nelle decisioni etiche
- Bilanciamento di interessi multipli e conflittuali

---

## 18. Network Security Architecture

### **Domanda 24**
A web server that accepts requests from external clients should be placed in which network?

**A)** VPN  
**B)** Intranet  
**C)** Internal Network  
**D)** DMZ

**Risposta Corretta: D) DMZ**

**Spiegazione:**
In Cybersecurity, una **DMZ (Demilitarized Zone)** è un livello aggiuntivo di sicurezza per la rete locale (LAN); è una sottorete isolata che separa la rete interna dall'Internet esterno. Questa area contiene servizi rivolti verso l'esterno, come un Web server, e funge da zona cuscinetto. Impedisce agli utenti esterni di avere accesso diretto ai server interni e ai dati dell'organizzazione.

Ad esempio, un'organizzazione crea una DMZ per ospitare server accessibili pubblicamente (email, web) limitando l'accesso alla rete interna. Il traffico è filtrato da firewall: uno tra Internet e DMZ, e uno tra DMZ e rete interna.

Le altre opzioni non sono appropriate:
- **Internal Network**: protetta da accessi esterni, non adatta a servizi pubblici.
- **Intranet**: rete interna per uso organizzativo, non per utenti esterni.
- **VPN**: tunnel per connessioni sicure remote, non un luogo dove ospitare servizi pubblici.

**Concetti Chiave:**
- Architettura di rete sicura
- Isolamento dei servizi pubblici
- Funzione della DMZ
- Protezione della rete interna

---

## 19. Common Attack Types (Tipi Comuni di Attacco)

### **Domanda 25**
What is the consequence of a Denial of Service attack?

**A)** Exhaustion of device resources  
**B)** Remote control of a device  
**C)** Malware Infection  
**D)** Increase in the availability of resources

**Risposta Corretta: A) Exhaustion of device resources**

**Spiegazione:**
Un attacco **Denial of Service (DoS)** consiste in un sovraccarico malevolo di richieste che porta all'**esaurimento delle risorse** (CPU, memoria, banda), rendendo il servizio indisponibile. L'attacco mira a rendere un sistema o un servizio inutilizzabile per gli utenti legittimi.

Differenze rispetto alle altre opzioni:
- **Remote control**: È tipicamente associato a malware come i Trojan (RAT) che permettono il controllo remoto non autorizzato, non al DoS.
- **Malware Infection**: Gli attacchi DoS di solito non implicano l'installazione di malware sulla vittima; il loro scopo principale è l'interruzione (disruption), non l'infezione.
- **Increase availability**: Un DoS *consuma* risorse, riducendone la disponibilità, non aumentandola.

**Concetti Chiave:**
- Obiettivo del DoS: Resource Exhaustion
- Impatto sulla Availability (Triangolo CIA)
- Distinzione tra disruption e infection/control

### **Domanda 26**
Which are the three packets used on the TCP connection handshake? (★)

**A)** Discover → Offer → Request  
**B)** SYN → SYN/ACK → ACK  
**C)** Offer → Request → ACK  
**D)** SYN → ACK → FIN

**Risposta Corretta: B) SYN → SYN/ACK → ACK**

**Spiegazione:**
Il **TCP Three-Way Handshake** (stretta di mano a tre vie) è il processo utilizzato dal protocollo TCP per stabilire una connessione affidabile.
La sequenza corretta dei flag è:
1.  **SYN** (Synchronize): Il client inizia la connessione.
2.  **SYN/ACK** (Synchronize/Acknowledge): Il server risponde confermando.
3.  **ACK** (Acknowledge): Il client conferma la ricezione e la connessione è stabilita.

Analisi delle opzioni errate:
- **SYN → ACK → FIN**: Il flag FIN è usato per la *terminazione* della connessione, non per l'handshake iniziale.
- **Discover → Offer → Request**: Questa sequenza appartiene al protocollo **DHCP** (processo DORA), non al TCP.
- **Offer → Request → ACK**: Anche questa è una parte parziale del processo DHCP.

**Concetti Chiave:**
- Connection-oriented protocol (TCP)
- Sequenza di stabilimento della connessione
- Differenza con i flag di terminazione (FIN)
- Differenza con protocolli come DHCP (DORA)

### **Domanda 27**
Which type of attack has the PRIMARY objective controlling the system from outside?

**A)** Backdoors  
**B)** Rootkits  
**C)** Cross-Site Scripting  
**D)** Trojans

**Risposta Corretta: A) Backdoors**

**Spiegazione:**
Una **Backdoor** è una funzionalità malevola che ascolta su una porta specifica e permette a un attaccante esterno di inviare comandi ed eseguirli sul sistema, ottenendo così il **controllo diretto**. Sebbene Trojan e Rootkit siano spesso usati per *installare* o *nascondere* le backdoor, è la backdoor stessa (il meccanismo di accesso) che fornisce il controllo esterno.

**Analisi delle opzioni:**
- **Trojans**: Sono spesso il veicolo (delivery mechanism) che inganna l'utente per l'installazione, ma non costituiscono necessariamente il meccanismo di controllo (spesso "droppano" una backdoor).
- **Rootkits**: Servono principalmente a *nascondere* la presenza dell'attaccante e mantenere i privilegi, operando a livello profondo del SO.
- **Cross-Site Scripting (XSS)**: Esegue script nel browser della vittima, compromettendo dati tra client e sito web, ma non mira tipicamente al controllo remoto del sistema operativo del server.

**Concetti Chiave:**
- Obiettivo primario: Controllo esterno
- Differenza tra Delivery (Trojan), Hiding (Rootkit) e Access (Backdoor)

---

## 20. Security Governance Documentation

### **Domanda 28**
Which of the following documents contains elements that are NOT mandatory?

**A)** Procedures  
**B)** Regulations  
**C)** Guidelines  
**D)** Policies

**Risposta Corretta: C) Guidelines**

**Spiegazione:**
Le **Guidelines (Linee Guida)** sono raccomandazioni o suggerimenti che **non sono obbligatori** (non-mandatory/discretionary). Sono progettate per guidare azioni, strategie o comportamenti offrendo best practice, ma non hanno la forza vincolante delle regole formali.

Confronto con le altre opzioni (tutte obbligatorie):
- **Regulations (Normative)**: Leggi imposte da governi/agenzie con sanzioni legali (Must follow).
- **Policies (Politiche)**: Requisiti formali stabiliti dall'organizzazione (Must follow, pena sanzioni aziendali).
- **Procedures (Procedure)**: Istruzioni passo-passo dettagliate per eseguire compiti specifici (Must follow per garantire consistenza e sicurezza).

**Concetti Chiave:**
- Natura discrezionale delle Guidelines
- Natura mandatoria di Regulations, Policies e Procedures
- Gerarchia dei documenti di governance

---

## 21. Data Lifecycle Management

### **Domanda 29**
Which of the following is a data handling policy procedure?

**A)** Destroy  
**B)** Collect  
**C)** Transform  
**D)** Encode

**Risposta Corretta: A) Destroy**

**Spiegazione:**
**Destroy (o "disposal")** è una fase del ciclo di vita della gestione dei dati (Data Handling Lifecycle) che prevede l'eliminazione sicura e definitiva dei dati non più necessari, garantendo che non possano essere recuperati o utilizzati impropriamente. Lo smaltimento è un passaggio critico per proteggere le informazioni sensibili da accessi non autorizzati o violazioni (vedi ISC2 Study Guide, Domain 5).

Esempi di procedure di distruzione:
- Distruzione fisica (shredding) di documenti cartacei.
- Cancellazione sicura (wiping/overwriting) di dati digitali tramite software specializzato.

**Perché le altre opzioni non sono core phase del Data Handling:**
- **Collect (Raccolta)**: Simile alla fase "Create", ma nel contesto delle policy di handling, le fasi standard sono Create, Store, Use, Share, Archive, Destroy. "Collect" è più legato al data management iniziale.
- **Transform (Trasformazione)**: Attività di elaborazione dati (cambio formato/struttura), non una fase del ciclo di vita di sicurezza.
- **Encode (Codifica)**: Metodo di protezione o conversione format (es. Base64), non una fase del ciclo di vita.

---

## 22. Network Protocols (Protocolli di Rete)
### **Domanda 30**
If there is no time constraint, which protocol should be employed to establish a reliable connection between two devices?

**A)** DHCP  
**B)** SNMP  
**C)** UDP  
**D)** TCP

**Risposta Corretta: D) TCP**

**Spiegazione:**
Il **TCP (Transmission Control Protocol)** è progettato per fornire una consegna di pacchetti **affidabile**, ordinata e controllata (error-tested) tra applicazioni.
- **Affidabilità**: TCP garantisce che tutti i dati vengano consegnati. Se un pacchetto viene perso, viene ritrasmesso.
- **Ordine**: Garantisce che i pacchetti arrivino nell'ordine corretto.
- **Utilizzo**: Ideale quando l'**integrità dei dati** è più importante della velocità (es. Email, Web browsing, File transfer), ovvero quando "there is no time constraint" che imponga sacrifici sull'affidabilità.

**Analisi delle altre opzioni:**
- **UDP (User Datagram Protocol)**: È un protocollo "connectionless" e semplice che **non garantisce** consegna o ordine. È più veloce del TCP e preferito per applicazioni "real-time" (es. streaming video, VoIP) dove un leggero ritardo (per ritrasmissione) sarebbe peggiore della perdita di qualche pacchetto.
- **DHCP (Dynamic Host Configuration Protocol)**: Protocollo per assegnare automaticamente indirizzi IP ai dispositivi di rete.
- **SNMP (Simple Network Management Protocol)**: Protocollo per la gestione e il monitoraggio dei dispositivi di rete.

**Concetti Chiave:**
- **TCP**: Connection-oriented, Reliable, Slower (Overhead).
- **UDP**: Connectionless, Unreliable, Faster (Low Overhead).
- Trade-off tra affidabilità (TCP) e velocità/latenza (UDP).

### **Domanda 31**
Which of the following is NOT a protocol of the OSI Level 3?

**A)** SNMP  
**B)** IP  
**C)** ICMP  
**D)** IGMP

**Risposta Corretta: A) SNMP**

**Spiegazione:**
Il **Simple Network Management Protocol (SNMP)** è un protocollo di livello **Applicazione (Layer 7)** utilizzato per configurare e monitorare i dispositivi collegati alla rete. Pertanto, **non** appartiene al Livello 3 (Network).

**Analisi dei protocolli di Livello 3 (Network Layer):**
Il livello 3 OSI è responsabile dell'instradamento (routing) e dell'indirizzamento logico. I protocolli chiave includono:
- **IP (Internet Protocol)**: Il protocollo principale per l'indirizzamento e il routing dei pacchetti.
- **ICMP (Internet Control Message Protocol)**: Usato per diagnostica (es. Ping) e messaggi di errore (es. Destination Unreachable).
- **IGMP (Internet Group Management Protocol)**: Usato per gestire l'appartenenza ai gruppi multicast IP.
- **IPsec**: Suite di protocolli per proteggere le comunicazioni IP.

**Mappatura TCP/IP vs OSI:**
- **Application (L7)**: SNMP, HTTP, FTP, DNS.
- **Transport (L4)**: TCP, UDP.
- **Network (L3)**: IP, ICMP, IGMP.
- **Data Link (L2)**: Ethernet, ARP.

## 23. Data Classification & Sensitivity
### **Domanda 32**
Sensitivity is a measure of the...

**A)** ...urgency and protection assigned to information by its owner  
**B)** ...protection and timeliness assigned to information by its owner, or the purpose of representing its need for urgency  
**C)** ...pertinence assigned to information by its owner, or the purpose of representing its need for urgency  
**D)** ...importance assigned to information by its owner, or the purpose of representing its need for protection

**Risposta Corretta: D) ...importance assigned to information by its owner, or the purpose of representing its need for protection**

**Spiegazione:**
La **Sensitivity (Sensibilità)** è la misura dell'**importanza** assegnata alle informazioni dal loro **proprietario (Owner)**, e rappresenta la necessità di proteggere tali informazioni. 
- **Esempio**: Un documento governativo classificato "Top Secret" è altamente sensibile perché la sua divulgazione non autorizzata causerebbe gravi danni alla sicurezza nazionale.
- Il **Data Owner** è il responsabile ultimo della classificazione dei dati e della determinazione del loro valore (importanza).

**Analisi delle opzioni errate:**
- Le opzioni che menzionano "urgency" (urgenza), "timeliness" (tempestività) o "pertinence" (pertinenza) confondono la sensibilità (che riguarda la protezione/riservatezza) con concetti di disponibilità o qualità del dato. La sensibilità è principalmente legata al danno derivante dalla divulgazione (Confidentiality).

## 24. Security Tools (Strumenti di Sicurezza)
### **Domanda 33**
Which tool is commonly used to sniff network traffic? (★)

**A)** John the Ripper  
**B)** Wireshark  
**C)** Burp Suite  
**D)** Nslookup

**Risposta Corretta: B) Wireshark**

**Spiegazione:**
**Wireshark** è l'analizzatore di protocolli di rete più utilizzato al mondo. In termini informali, è un "microscopio" per il traffico di rete che permette di catturare (sniffare) e analizzare pacchetti in tempo reale.

**Analisi delle altre opzioni:**
- **John the Ripper**: Un famoso tool open source per l'auditing e il **password cracking** (recovery).
- **Nslookup**: Uno strumento da riga di comando per l'amministrazione di rete, usato per interrogare il **DNS** (Domain Name System) e mappare nomi di dominio a indirizzi IP.
- **Burp Suite**: Una suite completa di strumenti per il **vulnerability scanning** e il **penetration testing** di applicazioni web.

**Concetti Chiave:**
- **Sniffing**: Intercettazione tecnica dei dati.
- **Network Protocol Analyzer**: Categoria di software (come Wireshark).
- Differenza tra tool admin (Nslookup), audit (John), e web sec (Burp).

---
### **Domanda 34**
Which of these would be the best option if a network administrator needs to **control access** to a network?

**A)** SIEM
**B)** NAC
**C)** IDS
**D)** HIDS

**Risposta Corretta: B) NAC**

**Spiegazione:**
Il **Network Access Control (NAC)** si riferisce a meccanismi che **negano o consentono l'accesso** alla rete basandosi sull'identità del dispositivo o dell'utente e sul suo stato di conformità (health check).
*Esempio:* Un laptop non aggiornato (privo di patch di sicurezza) verrà bloccato o messo in quarantena dal NAC finché non sarà conforme alla policy aziendale.

**Analisi delle opzioni errate:**
- **SIEM (Security Information and Event Management):** Fornisce analisi in tempo reale degli allarmi di sicurezza generati da app e hardware di rete. Serve per il **logging e la gestione incidenti**, non per il controllo accesso diretto.
- **IDS (Intrusion Detection System):** Monitora il traffico di rete per attività sospette. **Rileva** ma non blocca l'accesso (a differenza dell'IPS o del NAC).
- **HIDS (Host Intrusion Detection System):** Come l'IDS, ma installato su un singolo dispositivo (host). Monitora l'host, non l'accesso alla rete.

**Concetti Chiave:**
- **Controllo vs Monitoraggio:** NAC controlla (blocca/ammette); IDS/SIEM monitorano/analizzano.
- **Health Check:** Funzione chiave del NAC (controllo antivirus, patch, OS).

---
### **Domanda 35**
Which of the following areas is the most distinctive property of PHI (Protected Health Information)?

**A)** Non-repudiation
**B)** Integrity
**C)** Confidentiality
**D)** Authentication

**Risposta Corretta: C) Confidentiality**

**Spiegazione:**
La **Confidentiality (Riservatezza)** è considerata la proprietà più distintiva e critica per le **PHI (Protected Health Information)**.
Sebbene l'Integrità e la Disponibilità siano essenziali per *usare* i dati medici (es. dosaggi corretti, accesso in emergenza), la natura stessa delle leggi (come HIPAA) e l'aspettativa del paziente ruotano primariamente attorno alla **privacy** e al fatto che solo il personale medico autorizzato "Need-to-Know" possa vedere tali dati.

**Analisi delle opzioni errate:**
- **Integrity:** Cruciale per la sicurezza del paziente (dati accurati), ma si applica a *tutti* i dati critici, non è la caratteristica *più* distintiva delle PHI rispetto ad altri dati sensibili.
- **Non-repudiation (Non ripudio):** Garantisce che un autore non possa negare un'azione (es. firma digitale su una prescrizione). È importante per l'accountability, ma meno centrale della riservatezza per la definizione di PHI.
- **Authentication:** È un controllo di accesso (verificare l'identità), non una proprietà intrinseca del dato PHI stesso.

**Concetti Chiave:**
- **PHI & Confidentiality:** Il legame principale è la privacy del paziente.
- **Need-to-Know:** Principio fondamentale per l'accesso ai dati sanitari.

---
### **Domanda 36**
The cloud deployment model where a company has resources on-premises and in the cloud is known as:

**A)** Community cloud
**B)** Private cloud
**C)** Hybrid cloud
**D)** Multi-tenant

**Risposta Corretta: C) Hybrid cloud**

**Spiegazione:**
Il **Hybrid Cloud** è un modello che combina (orchestra) infrastruttura **on-premises**, servizi di **private cloud** e **public cloud** per gestire storage e servizi.
Le entità rimangono distinte ma lavorano insieme, permettendo flessibilità (es. tenere dati sensibili on-premise ma usare la potenza di calcolo del cloud pubblico).

**Analisi delle opzioni errate:**
- **Community cloud:** Infrastruttura condivisa da diverse organizzazioni con necessità comuni (es. regolamentazioni simili). Non implica necessariamente un mix on-prem/cloud, ma piuttosto una condivisione tra partner.
- **Private cloud:** Infrastruttura dedicata a una **singola** organizzazione. Può essere on-premise o ospitata, ma è isolata.
- **Multi-tenant:** Non è un modello di *deployment*, ma una caratteristica architetturale (tipica del Public Cloud) dove più clienti condividono le stesse risorse fisiche logiche.

**Concetti Chiave:**
- **Hybrid** = Mix di On-prem/Private + Public.
- **Orchestration** = La chiave per far funzionare un cloud ibrido.

4. **CIA Analysis**: Analizza sempre quale principio è **principalmente** impattato, anche se altri potrebbero essere coinvolti

---
### **Domanda 37**
Which security principle states that a user should only have the necessary permission to execute a task?

**A)** Privileged Accounts
**B)** Defense in Depth
**C)** Least Privilege
**D)** Separation of Duties

**Risposta Corretta: C) Least Privilege**

**Spiegazione:**
Il **Principle of Least Privilege (PoLP)** stabilisce che ai soggetti (utenti o processi) debbano essere concessi solo i privilegi strettamente necessari per completare le loro mansioni specifiche, e nulla di più.
Questo limita la superficie di attacco: se un account viene compromesso, l'attaccante può fare solo ciò che quell'utente poteva fare.

**Analisi delle opzioni errate:**
- **Privileged Accounts:** Si riferisce agli **account** stessi (es. amministratori) che hanno permessi elevati, non al principio di limitazione. Anzi, la gestione sicura dei Privileged Accounts si basa sul principio di Least Privilege (usarli solo quando serve).
- **Defense in Depth:** Si riferisce all'uso di **più livelli** di sicurezza (fisici, tecnici, amministrativi) per proteggere un asset, in modo che se uno fallisce, gli altri intervengano.
- **Separation of Duties (SoD):** Stabilisce che nessun singolo utente deve avere privilegi sufficienti per abusare del sistema da solo (richiede che compiti critici siano divisi tra più persone). SoD previene le frodi; Least Privilege limita i danni.

**Concetti Chiave:**
- **Least Privilege** = "Only what is needed" (Limitazione Danni).
- **SoD** = "Multiple people for one task" (Prevenzione Frodi).
- **Defense in Depth** = "Multiple layers" (Resilienza).

5. **Risk-Based Approach**: Le decisioni di sicurezza devono sempre considerare il contesto di rischio specifico

---
### **Domanda 38**
Which of the following is NOT an element of System Security Configuration Management?

**A)** Updates
**B)** Baselines
**C)** Audit logs
**D)** Inventory

**Risposta Corretta: C) Audit logs**

**Spiegazione:**
La gestione della configurazione (Configuration Management) comprende elementi formali specifici per mantenere lo stato del sistema: **Inventory** (inventario), **Baselines** (configurazioni standard), **Updates** e **Patches**.
Gli **Audit Logs** sono essenziali per la sicurezza, ma sono il **prodotto** della verifica e del monitoraggio (fase di Audit), non un elemento costitutivo della configurazione stessa. L'audit verifica se la configurazione è corretta; non *è* la configurazione.

**Analisi delle opzioni errate:**
- **Inventory (Inventario):** È un elemento fondamentale. "Non puoi proteggere ciò che non conosci".
- **Baselines:** Sono specifiche di configurazione (es. server hardening) usate come riferimento.
- **Updates:** Sono modifiche controllate per mantenere il sistema sicuro (funzionalità e fix).

**Concetti Chiave:**
- **Elementi CM**: Inventory, Baselines, Updates, Patches.
- **Audit Logs** = Strumento di verifica (Output), non di configurazione (Input).

6. **Configuration Integrity**: Mantenere lo stato del sistema noto e fidato.

---
### **Domanda 39**
Risk Management is:

**A)** The assessment of the potential impact of a threat
**B)** The impact and likelihood of a threat
**C)** The identification, evaluation and prioritization of risks
**D)** The creation of an incident response team

**Risposta Corretta: C) The identification, evaluation and prioritization of risks**

**Spiegazione:**
Il **Risk Management** è un processo olistico che comprende l'**identificazione** dei rischi, la loro **valutazione** (severity = likelihood × impact), e la **prioritizzazione** delle azioni di mitigazione.
*Esempio:* Identificare un rischio di furto dati, valutarne il danno potenziale, e dare priorità all'implementazione della crittografia rispetto ad altri rischi minori.

**Analisi delle opzioni errate:**
- **The assessment of the potential impact of a threat:** È solo una parte (Evaluaton/Impact Analysis), non l'intero processo.
- **The impact and likelihood of a threat:** Queste sono le *componenti* del calcolo del rischio, non la definizione del processo di gestione.
- **The creation of an incident response team:** Questa è una strategia di *risposta* (Response/Mitigation), non il processo di gestione del rischio in sé.

**Concetti Chiave:**
- **Risk Management Cycle**: Identify -> Evaluate -> Prioritize -> Treat -> Monitor.
- **Risk vs Incident Response**: Gestire il rischio è proattivo; rispondere agli incidenti è reattivo.


7. **Risk Assessment**: La base per decisioni informate.

---
### **Domanda 40**
Malicious emails that aim to attack company executives are an example of:

**A)** Rootkits
**B)** Phishing
**C)** Whaling
**D)** Trojans

**Risposta Corretta: C) Whaling**

**Spiegazione:**
Il **Whaling** è una forma specifica di attacco di phishing (ingegneria sociale digitale) che prende di mira **membri di alto rango** di un'organizzazione, come dirigenti (CEO, CFO, C-Level executives). Il termine deriva dal "pescare pesci grossi" (balene).

**Analisi delle opzioni errate:**
- **Phishing:** È la categoria generale di attacchi via email. Sebbene il Whaling *sia* un tipo di phishing, "Whaling" è la risposta *più precisa* e corretta per attacchi specifici agli executives.
- **Rootkits:** Software malevolo usato per mantenere l'accesso privilegiato (root) a un sistema nascondendo la propria presenza.
- **Trojans:** Malware che appare come software legittimo ma esegue funzioni dannose nascoste. Non è un metodo di attacco basato sull'email sociale (anche se può essere *consegnato* via email).

**Concetti Chiave:**
- **Targeting**: Phishing (Massa) vs Spear Phishing (Gruppo specifico) vs Whaling (Executive).
- **Social Engineering**: Manipolazione psicologica vs Exploit tecnico (Rootkit/Trojan).

8. **Exec Protection**: I dirigenti sono target di alto valore.

---
### **Domanda 41**
In order to find out whether personal tablet devices are allowed in the office, which of the following policies would be helpful to read?

**A)** AUP
**B)** BYOD
**C)** Privacy Policy
**D)** Change Management Policy

**Risposta Corretta: B) BYOD**

**Spiegazione:**
La policy **BYOD (Bring Your Own Device)** stabilisce esplicitamente le regole, i permessi e le restrizioni per l'utilizzo di dispositivi personali (come tablet e smartphone) per attività lavorative o all'interno della rete aziendale.
Essa chiarisce *se* tali dispositivi sono permessi e, in tal caso, *a quali condizioni* (es. installazione di MDM, crittografia, ecc.).

**Analisi delle opzioni errate:**
- **AUP (Acceptable Use Policy):** Definisce l'uso accettabile delle risorse *aziendali* (reti, PC forniti dall'azienda). Sebbene possa menzionare dispositivi esterni, il BYOD è il documento specifico per i device personali.
- **Privacy Policy:** Delinea come l'azienda protegge i dati personali dei clienti o dipendenti. Non regola l'hardware permesso.
- **Change Management Policy:** Stabilisce le procedure per *modificare* i sistemi IT in modo controllato. Non c'entra con l'uso dei dispositivi personali.

**Concetti Chiave:**
- **BYOD Policy**: Regola "Device Personale -> Lavoro".
- **AUP**: Regola "Comportamento Utente -> Risorse Aziendali".

9. **Mobile Security**: Gestione del perimetro esteso.

---
### **Domanda 42**
Which type of key can be used to both encrypt and decrypt the same message?

**A)** A public key
**B)** An asymmetric key
**C)** A private key
**D)** A symmetric key

**Risposta Corretta: D) A symmetric key**

**Spiegazione:**
La **Crittografia Simmetrica (Symmetric Key Algorithm)** utilizza una **singola chiave** (Single Shared Key) sia per cifrare (encrypt) che per decifrare (decrypt) i dati.
Perché la comunicazione sia sicura, sia il mittente che il destinatario devono possedere la stessa chiave identica e mantenerla segreta.

**Analisi delle opzioni errate:**
- **A public key:** Utilizzata nella crittografia asimmetrica per cifrare messaggi (destinati al possessore della chiave privata) o verificare firme. Non può decifrare ciò che ha cifrato.
- **An asymmetric key:** Si riferisce alla coppia di chiavi (pubblica/privata). Non esiste "una chiave asimmetrica" che fa tutto da sola; funzionano in coppia.
- **A private key:** Utilizzata nella crittografia asimmetrica per decifrare messaggi (ricevuti) o firmare documenti.

**Concetti Chiave:**
- **Symmetric** = Same Key (Speed/Efficiency). Esempio: AES.
- **Asymmetric** = Key Pair (Public/Private). Esempio: RSA.

10. **Cryptography Basics**: Capire la differenza chiave singola vs coppia.

---
### **Domanda 43**
Which of the following is NOT a possible model for an Incident Response Team (IRT)?

**A)** Dedicated
**B)** Hybrid
**C)** Pre-existing
**D)** Leveraged

**Risposta Corretta: C) Pre-existing**

**Spiegazione:**
I modelli standard riconosciuti per strutturare un Incident Response Team (IRT) sono **Dedicated**, **Hybrid**, e **Leveraged**.
"Pre-existing" non è un termine formale per un modello di IRT. Sebbene un team possa essere composto da staff "preesistente", il modello corretto per descrivere ciò è **Leveraged** (o talvolta "Functional").

**Analisi delle opzioni (Modelli Validi):**
- **Dedicated:** Lo staff lavora al 100% sulla risposta agli incidenti. Massima reattività, costo elevato.
- **Leveraged (a Leva):** Si utilizzano membri dello staff esistente (es. Network Admin, SysAdmin) che hanno altri compiti primari ma vengono attivati per l'incidente. Basso costo, potenziale conflitto di priorità.
- **Hybrid:** Un nucleo dedicato integrato da esperti di dominio (es. Legale, PR, DB Admin) attivati al bisogno. Bilancia costi e competenza.

**Concetti Chiave:**
- **IRT Models:** Dedicated, Hybrid, Leveraged.
- **Pre-existing:** Termine ingannevole (distractor).

11. **IRT Structure**: Scegliere il modello in base a grandezza e rischio.

---
### **Domanda 44**
When a company hires an insurance company to mitigate risk, which risk management technique is being applied?

**A)** Risk tolerance
**B)** Risk mitigation
**C)** Risk transfer
**D)** Risk avoidance

**Risposta Corretta: C) Risk transfer**

**Spiegazione:**
Il **Risk Transfer (Trasferimento del Rischio)** è la tecnica in cui un'organizzazione sposta l'impatto finanziario di un rischio su una terza parte, tipicamente attraverso una **polizza assicurativa** (Insurance).
Questo non elimina il rischio tecnico dell'evento (es. l'attacco hacker può ancora avvenire), ma trasferisce la responsabilità dei costi associati (legali, remediation, notifiche) all'assicuratore.

**Analisi delle opzioni errate:**
- **Risk Mitigation (Mitigazione):** Implica l'implementazione di **controlli** (es. firewall, patching) per ridurre la probabilità o l'impatto tecnico del rischio.
- **Risk Avoidance (Evitamento):** Implica l'eliminazione completa dell'attività che causa il rischio (es. "non raccogliere dati delle carte di credito").
- **Risk Tolerance (Tolleranza/Accettazione):** È il livello di rischio che si sceglie di accettare senza azioni aggiuntive. Assumere un'assicurazione è un'azione attiva, non passiva accettazione.

**Concetti Chiave:**
- **Transfer** = Insurance / Outsourcing (Spostare i soldi/responsabilità).
- **Mitigation** = Controls (Ridurre impatto/probabilità).
- **Avoidance** = Stop Activity (Eliminare causa).

12. **Financial Impact**: L'assicurazione protegge il portafoglio, non i server.

### **Aree di Approfondimento Consigliate:**

- Incident Response Planning e Communication
- Data Classification e Handling Procedures  
- Business Continuity e Disaster Recovery
- Vendor Risk Management e Third-Party Security
- Emerging Technologies Security (Cloud, IoT, AI)

---

*Ricorda: La cybersecurity non riguarda solo la tecnologia, ma soprattutto le persone, i processi, e le decisioni etiche che guidiamo come professionisti.*