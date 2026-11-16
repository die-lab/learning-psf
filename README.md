# Suggeritore

App web per imparare le battute di un personaggio. Copione incluso: *Ritorno all'Olimpo*.

Si apre dal browser, senza installare nulla. Ogni attore sceglie il proprio personaggio, sente o legge la battuta prima, dice la sua, e vede subito la battuta giusta e quella dopo. Scrivendo o dettando la battuta, l'app segnala le parole saltate.

## Cambiare spettacolo

1. Sostituisci `copione.txt` con il nuovo copione.
2. In `index.html` cambia il titolo nella riga `var CONFIG={title:"...",file:"copione.txt"};`.

Ogni attore può anche caricare un copione solo per sé (file .docx o .txt) da «Cambia copione» dentro l'app.

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
