# 👻 Capitolo 3 — L'ultima sorpresa

Terzo mini-gioco della serie, da aprire **dopo** il quiz (`/Quiz/`). È uno
scherzo affettuoso: un build-up dolce e lento abbassa la guardia, poi parte un
**jumpscare**, e si chiude con una risata.

Single-page `index.html` autonomo: CSS e JS inline, **nessuna dipendenza
esterna**. La faccia spaventosa è disegnata in SVG e l'urlo è generato a runtime
con la Web Audio API — nessun file immagine o audio da caricare.

## ▶️ Come funziona

- **Locale:** apri `index.html` in un browser moderno.
- **Online:** `https://guidoputignano.github.io/step3/`

Sequenza emotiva pensata di proposito: **tenerezza → spavento → risata**.
Lo jumpscare parte solo dopo il tap su "Aprilo" (serve un gesto per far partire
audio + vibrazione sul telefono).

## 🛠️ Personalizzarlo

Apri `index.html`:
- Testi del build-up: le righe `#l1…#l4` nella sezione `#build`.
- Durata/ritmo: `runBuildup()` (delay delle righe e della barra).
- Messaggio finale: sezione `#gotcha`.
- Volume dell'urlo: `master.gain.value` nell'oggetto audio `A`.
