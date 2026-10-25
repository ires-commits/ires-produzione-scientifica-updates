# IRES Produzione Scientifica — aggiornamenti

Questo repository **pubblico** distribuisce i pacchetti ZIP di aggiornamento del plugin WordPress IRES Produzione Scientifica. Il repository sorgente `ires-commits/ires-produzione-scientifica` rimane **privato**.

## Release

Le versioni vengono pubblicate come [GitHub Releases](../../releases) con tag `vX.Y.Z`, file `ires-produzione-scientifica-X.Y.Z.zip` e `SHA256SUMS`.

Gli ZIP includono codice PHP e risorse del plugin: sono pubblicamente scaricabili. **Non includere mai credenziali, dati riservati o segreti nei pacchetti.**

## Stato

La distribuzione non è ancora attiva: il codice del plugin deve essere importato nel repository sorgente privato e la GitHub Action richiede il segreto `DISTRIBUTION_TOKEN` per pubblicare qui. Non sono ancora state create release.

## Aggiornamenti WordPress

Il plugin deve leggere le release pubbliche da `ires-commits/ires-produzione-scientifica-updates`, verificare numero di versione e integrità e richiedere conferma prima di installare. Nessun token GitHub è necessario su WordPress.
