# Immagini nel riquadro (Leaflet) + Classifica + Countdown

## Aggiungere le immagini ai pin
- Metti i file dentro **`images/`** (es. `p1.jpg`, `p2.jpg`).
- In `pins.json` aggiungi il campo `"img"` con percorso relativo (es. `"images/p1.jpg"`).
- Cliccando un pin si apre il **riquadro foto** con titolo e descrizione.

## Countdown
- Scadenza impostata a **01/01/2026 00:00 (Europa/Roma)**. Cambia `data-target` in `index.html` se serve.

## Pubblica
- Carica tutto su **GitHub Pages** (root del repo). Se cambi un’immagine, puoi forzare l’aggiornamento aggiungendo `?v=2` al percorso.
