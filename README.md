# Ciclofficina Sociale — Sito statico

Sito single-file pronto per **GitHub Pages**.

## Struttura
```
index.html
assets/
  hero.jpg
  repair.jpg
  sale.jpg
  rent.jpg
```

## Tecnologie
- HTML5 + Vanilla JS
- Tailwind CSS via CDN
- AOS (Animate On Scroll) via CDN
- Google Fonts: Bebas Neue + Inter

## Deploy su GitHub Pages
1. Crea un nuovo repository (es. `ciclofficina`).
2. Carica `index.html` e la cartella `assets/` nella **root**.
3. Vai in **Settings → Pages** → Branch `main` / cartella `/ (root)` → Save.
4. Il sito sarà live a `https://<utente>.github.io/ciclofficina/`.

Tutti i percorsi sono **relativi** (`./assets/...`) — funziona sia su sottodominio che su dominio personalizzato.

## Personalizzazione veloce
- Colore accento: cerca `accent: '#f4c430'` in `index.html` (config Tailwind inline).
- Contenuti: tutto è dentro `index.html`, sezione per sezione (Servizi, Officina, Noleggio, Orari, Contatti).
- Immagini: sostituisci i file in `assets/` mantenendo gli stessi nomi.

## Esecuzione locale
Basta aprire `index.html` nel browser, oppure:
```
python3 -m http.server 8000
```
