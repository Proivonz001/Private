# CLAUDE.md

Questo file fornisce indicazioni a Claude Code (claude.ai/code) quando lavora su questa repository.

## Stato del progetto

La repository è appena stata inizializzata: non contiene ancora codice e lo stack tecnologico non è stato scelto, quindi non esistono comandi di build, test o lint.

Quando viene aggiunto il primo codice:

- aggiorna questo file con i comandi di build, test e lint e con una panoramica dell'architettura;
- aggiungi al `.gitignore` le voci specifiche dello stack scelto (dipendenze, artefatti di build, cache).

## Convenzioni

- La documentazione della repository (README e questo file) è in italiano.
- Tutti i file di testo usano fine riga LF, imposti da `.gitattributes`; codifica, indentazione e spazi finali seguono `.editorconfig`.
- Non committare mai segreti (chiavi API, token, password): vanno in file `.env`, esclusi da git. Per documentare le variabili necessarie usa un `.env.example` senza valori reali.
