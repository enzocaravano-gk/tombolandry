# TombolAndry

La tombola sul telefono, in due modi:

**A distanza** — il banco è automatico e sta su un piccolo server (Cloudflare, dati in Europa, cartella `server` del progetto di sviluppo). Chi crea la partita invita gli altri con un link; ognuno sceglie fino a 4 cartelle. Bisogna tappare i numeri e dichiarare il premio prima del numero successivo: chi si distrae perde il premio. Nessun account; la partita si cancella da sola.

**Nella stessa stanza** — un dispositivo fa da **banco** e chiama i numeri a voce, ognuno gioca con la sua **cartella** sul proprio telefono, senza internet tra i telefoni.

- Il banco crea la partita e ottiene un codice di 7 lettere da dare ai giocatori
- Tutti i telefoni con lo stesso codice estraggono gli stessi numeri nello stesso momento: non serve nessun server e non passa niente da internet tra i telefoni (tenete l'ora del telefono in automatico)
- 90 cartelle fisse e numerate, uguali su tutti i telefoni, in 15 serie da 6: in ogni serie i numeri da 1 a 90 compaiono una volta sola. Regole vere (3 righe, 9 colonne, 5 numeri per riga); due cartelle di serie diverse hanno al massimo 8 numeri in comune su 15
- Il giocatore sceglie il numero della sua cartella e lo dice al banco
- I numeri usciti si segnano toccandoli
- Il banco segna quali cartelle sono in gioco e di chi: a ogni numero le controlla da solo e annuncia a voce ambo, terno, quaterna, cinquina e tombola
- Anche il banco può giocare con una sua cartella
- Voce del banco con la smorfia napoletana (si può spegnere)

Per giocare in locale basta aprire `index.html` nel browser.

Nessuna risorsa esterna: niente font, script o librerie caricati da altri server. La sola connessione è quella al server delle partite a distanza.
