# Incontro 2 - Appunti grezzi

Scrivi qui gli appunti grezzi del secondo incontro.

- Avvio del secondo incontro: Security by Design.
- Ripasso iniziale su reti, DNS e footprinting.
- Hardening: rendere un sistema piu' sicuro riducendo servizi, funzioni, accessi e configurazioni inutilmente esposte.
- Esempio: un collega ha pubblicato una web page raggiungibile su netref.dev con varia documentazione.
- La documentazione pubblica e' utile, ma puo' aumentare le informazioni disponibili per footprinting se espone dettagli tecnici sensibili.
- Vulnerabilita' logiche e architetturali.
- Esempi: buffer overflow e insecure IPC.
- Contromisure di prevenzione: funzioni sicure, ASLR, DEP o NX bit, stack canaries.
- John the Ripper: strumento per testare la robustezza delle password e provare a recuperarle a partire dagli hash.
- Funziona confrontando candidate password con hash noti; usa wordlist, regole, brute force e altre tecniche.
- OpenVAS: strumento di vulnerability assessment per cercare vulnerabilita' note su host, servizi e configurazioni.
- Esegue scansioni e confronta cio' che trova con feed di test e vulnerabilita' conosciute.
