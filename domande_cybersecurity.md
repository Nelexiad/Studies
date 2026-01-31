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

---

## 11. Terminologia delle Minacce

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
Quale modello di deployment cloud è adatto per aziende con bisogni e preoccupazioni simili?

**A)** Private cloud  
**B)** Multi-tenant  
**C)** Community cloud  
**D)** Hybrid cloud

**Risposta Corretta: C) Community cloud**

**Spiegazione:**
Il **Community Cloud** è un modello di deployment collaborativo in cui l'infrastruttura è condivisa tra diverse organizzazioni che appartengono a una specifica comunità con **interessi comuni** (es. stessa missione, requisiti di sicurezza, policy di compliance, o settore industriale).

**Caratteristiche distintive:**
- **Condivisione dei costi**: I costi sono divisi tra i membri della comunità, rendendolo più economico del Private Cloud.
- **Sicurezza condivisa**: Offre un livello di sicurezza e privacy più alto del Public Cloud, ma meno isolato del Private Cloud.
- **Compliance settoriale**: Ideale per settori altamente regolamentati come sanità, finanza o governo che devono aderire agli stessi standard.
- **Gestione**: Può essere gestito dalle organizzazioni stesse o da una terza parte.

**Confronto con gli altri modelli:**
- **Private Cloud**: Infrastruttura dedicata a una **singola** organizzazione. Massima sicurezza e controllo, ma costi elevati.
- **Public Cloud (spesso Multi-tenant)**: Infrastruttura aperta al pubblico generale. Risorse condivise (multi-tenancy), costi bassi, ma controllo limitato.
- **Hybrid Cloud**: Combinazione di due o più infrastrutture (es. Private + Public) che rimangono entità uniche ma sono connesse.
- **Multi-tenant**: Non è un modello di deployment, ma una **caratteristica architetturale** (tipica del Public Cloud) dove più clienti condividono le stesse risorse fisiche/logiche.

**Concetti Chiave:**
- 4 modelli di deployment NIST: Public, Private, Community, Hybrid
- Community Cloud = Interessi condivisi + Risorse condivise
- Equilibrio tra costi, sicurezza e controllo
- Adattabilità per settori regolamentati

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

## Note per lo Studio

### **Strategie per le Domande d'Esame:**

1. **Gerarchia Etica**: Ricorda sempre l'ordine di priorità: Società → Professione → Clienti → Individuo

2. **Framework Integration**: Gli standard non sono mutualmente esclusivi; molte organizzazioni usano combinazioni (ISO 27001 + NIST CSF)

3. **Compliance Multi-giurisdizionale**: Applicare sempre la normativa più restrittiva

4. **CIA Analysis**: Analizza sempre quale principio è **principalmente** impattato, anche se altri potrebbero essere coinvolti

5. **Risk-Based Approach**: Le decisioni di sicurezza devono sempre considerare il contesto di rischio specifico

### **Aree di Approfondimento Consigliate:**

- Incident Response Planning e Communication
- Data Classification e Handling Procedures  
- Business Continuity e Disaster Recovery
- Vendor Risk Management e Third-Party Security
- Emerging Technologies Security (Cloud, IoT, AI)

---

*Ricorda: La cybersecurity non riguarda solo la tecnologia, ma soprattutto le persone, i processi, e le decisioni etiche che guidiamo come professionisti.*