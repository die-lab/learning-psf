# Suggeritore

App web per imparare le battute di un personaggio. I copioni stanno nella cartella `copioni/`.

Si apre dal browser, senza installare nulla. Ogni attore sceglie il proprio personaggio, sente o legge la battuta prima, dice la sua, e vede subito la battuta giusta e quella dopo. Scrivendo o dettando la battuta, l'app segnala le parole saltate.

## Aggiungere un copione

Carica il file nella cartella `copioni/` della repository: Word (`.docx`) o testo (`.txt`). Compare da solo nell'elenco «Copione» dell'app, e ognuno può scegliere lì il copione e poi il proprio personaggio.

- Il nome del file diventa il titolo: `Ritorno all'Olimpo.docx` appare come «Ritorno all'Olimpo».
- Per togliere un copione basta cancellare il file.
- Dopo il caricamento può servire un minuto prima che sia visibile.
- L'elenco viene letto da GitHub e funziona quando la repository è pubblica. `copioni/elenco.json` è solo una riserva, usata se GitHub non risponde.

Ogni attore può anche caricare un copione solo per sé da «Gestisci copioni» dentro l'app.

## Formato del copione

```
SCENA 1
Entra Zeus con la cuffia da notte.
ZEUS: Chi è là?
ERA: (sbadigliando) Sono io.
```

- Ogni battuta sta su una riga e inizia con il nome in MAIUSCOLO seguito dai due punti.
- Le righe senza nome sono didascalie.
- Il testo tra parentesi è un'azione e non viene controllato.
- Tutto ciò che precede la prima riga `SCENA` viene ignorato.

## Note

- Progressi e copioni aggiunti restano salvati solo sul dispositivo di chi li usa.
- Microfono e lettura ad alta voce usano le funzioni del browser: la resa cambia da un browser all'altro.
