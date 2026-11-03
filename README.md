# Schema Diamond Painting

Web app a pagina singola che converte una foto in uno schema per diamond painting.

1. **Foto**: carica un'immagine (trascina, clicca o incolla), scegli ingrandimento e inquadratura, regola luminosità, contrasto e saturazione.
2. **Misure**: drill quadrati (2,5 mm) o rotondi (2,8 mm), formati tela standard da 15×20 a 70×90 cm o proporzioni libere.
3. **Colori**: da 6 a 70 colori DMC (palette di 454 colori), sfumature regolabili, pulizia dei drill isolati.
4. **PDF**: copertina, mappa delle sezioni, istruzioni, legenda con quantità (+10% di scorta) e pagine di griglia con simboli, in A4 o US Letter.

Tutto gira nel browser: la foto non viene caricata su nessun server.

## Sviluppo

Nessuna build: è un solo file `index.html`. Per provarlo in locale basta aprirlo nel browser o servire la cartella:

```
npx serve .
```

Dipendenze caricate da CDN: [jsPDF 2.5.1](https://github.com/parallax/jsPDF) (cdnjs) e Google Fonts.

## Deploy su Netlify

Il file `netlify.toml` pubblica la cartella radice così com'è (nessun comando di build).
