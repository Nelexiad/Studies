# Incontro 3 - Threat & Vulnerability Management

Versione riorganizzata degli appunti del terzo incontro.

## Tema della giornata

- Focus: identificazione, analisi e gestione di minacce e vulnerabilita'.

## Traccia iniziale

- Distinzione tra minaccia, vulnerabilita', exploit e rischio.
- Tecniche di identificazione delle vulnerabilita'.
- Prioritizzazione e remediation.
- Vulnerability assessment e strumenti di scansione.
- Collegamento tra esposizione tecnica, impatto e gestione del rischio.

## Ripasso: header di un pacchetto e `RFC 793`

### Header di un pacchetto

- Un pacchetto di rete non contiene solo dati: contiene anche un `header`, cioe' una parte iniziale con informazioni di controllo.
- L'header serve a dire al sistema `da dove arriva`, `dove deve andare` e `come deve essere trattato` il traffico.
- A seconda del protocollo, l'header puo' contenere campi come indirizzi IP, porte, flag, numeri di sequenza, lunghezza e checksum.

### Perche' e' utile capirlo

- Leggere l'header aiuta a capire come comunicano i sistemi.
- E' fondamentale per analisi del traffico, troubleshooting, scansioni di rete e comprensione di alcuni attacchi.

### `RFC 793` e handshake TCP

- La `RFC 793` e' il documento storico di riferimento del protocollo `TCP`.
- Descrive anche il meccanismo classico con cui una connessione TCP viene avviata: il `three-way handshake`.

### SYN, SYN/ACK, ACK

- `SYN`: il client invia un segmento con flag `SYN` per chiedere l'apertura della connessione.
- `SYN/ACK`: il server risponde con `SYN` + `ACK` per confermare la richiesta e proporre a sua volta l'apertura della sessione.
- `ACK`: il client invia l'acknowledgment finale e la connessione TCP viene stabilita.

### Idea chiave

- Il three-way handshake serve a sincronizzare le due parti prima dello scambio dati.
- Per questo i flag `SYN` e `SYN/ACK` sono importanti anche in scansioni, analisi di rete e rilevazione di comportamenti anomali.

## Ripasso: pila `ISO/OSI` e modello `TCP/IP`

### A cosa servono

- Il modello `ISO/OSI` e il modello `TCP/IP` servono a descrivere come avviene la comunicazione di rete.
- Aiutano a capire `dove` si trova un problema, `quale protocollo` e' coinvolto e `quale livello` osserviamo durante analisi, scansioni o troubleshooting.

### Modello `ISO/OSI`

- Il modello `ISO/OSI` e' un modello teorico a `7 livelli`.
- E' molto utile per studiare e ragionare in modo ordinato sul funzionamento delle reti.

### I 7 livelli OSI

1. `Physical`
2. `Data Link`
3. `Network`
4. `Transport`
5. `Session`
6. `Presentation`
7. `Application`

### Modello `TCP/IP`

- Il modello `TCP/IP` e' piu' vicino al funzionamento reale delle reti moderne e di Internet.
- In genere viene descritto con `4 livelli`.

### I 4 livelli TCP/IP

1. `Link` o `Network Access`
2. `Internet`
3. `Transport`
4. `Application`

### Mappatura semplificata

- `OSI 7 + 6 + 5` corrispondono in pratica al livello `Application` del modello `TCP/IP`.
- `OSI 4` corrisponde al livello `Transport`.
- `OSI 3` corrisponde al livello `Internet`.
- `OSI 2 + 1` corrispondono al livello `Link`.

### Esempi utili

- `Application`: HTTP, HTTPS, DNS, SMTP
- `Transport`: TCP, UDP
- `Internet`: IP, ICMP
- `Link`: Ethernet, Wi-Fi, MAC addressing

### Perche' e' utile in cybersecurity

- Aiuta a capire se stiamo osservando un problema di rete, di trasporto o di applicazione.
- E' utile per leggere scansioni porte/servizi, pacchetti, log e risultati di strumenti di assessment.
- Permette di collegare meglio concetti come porte, IP, handshake TCP e protocolli applicativi.

### Idea chiave

- `ISO/OSI` serve soprattutto a ragionare bene.
- `TCP/IP` serve soprattutto a capire come funzionano davvero le reti che usiamo.
