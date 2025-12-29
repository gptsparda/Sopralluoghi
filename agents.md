# Regole progetto - App sopralluoghi

## Obiettivo
Webapp per sopralluoghi: foto + metadati + ZIP + report. Modifiche piccole e testabili.

## Regole di lavoro
- Fare UNA modifica per volta (micro-step), niente refactor gratuiti.
- Non cambiare testi/label se non richiesto.
- Non cambiare id o struttura DOM se non necessario.
- Ogni modifica deve mantenere compatibilita con mobile (Chrome Android).

## Vincoli tecnici
- Evitare funzioni che richiedono permessi speciali su content://
- Preferire https/PWA per share/email/onedrive.
- Se aggiungi feature: prevedere fallback (download ZIP).

## Deliverable
- Aggiornare solo i file necessari.
- Descrivere cosa e stato cambiato in 3 righe nel commit/PR.
