# Meniskus-Motivator 🦵😉

Eine schicke, humorvolle Fitness-/Physio-Timer-App für den Browser.

Du kannst einstellen:
- Wiederholungen pro Satz
- Aktivphase pro Wiederholung (Sekunden)
- Ruhe zwischen Wiederholungen
- Anzahl Sätze
- Ruhezeit zwischen Sätzen

Dazu gibt's ein animiertes Knie-Visual, freundliche Motivations-Sprüche und einen klaren Timer-Ablauf für regelmässiges Training nach der Meniskus-OP.

## Lokal starten

Da die App komplett statisch ist (nur `index.html`), hast du mehrere einfache Optionen:

### Option A: Direkt Datei öffnen
1. `index.html` doppelklicken
2. Läuft sofort im Browser

### Option B: Mit Python-Server (empfohlen)
```bash
python3 -m http.server 4173
```
Dann öffnen: `http://localhost:4173`

### Option C: Mit Node `serve`
```bash
npx serve .
```

## Superschnell deployen (mind. 3 einfache Varianten)

## 1) GitHub Pages (kostenlos, sehr einfach)
Perfekt für statische Seiten.

1. Repo nach GitHub pushen.
2. In GitHub: **Settings → Pages**.
3. **Deploy from branch** wählen (`main` / aktueller Branch, Ordner `/root`).
4. Nach 1–2 Minuten ist die App online unter einer URL wie:
   - `https://<dein-user>.github.io/<repo-name>/`

Vorteile: kostenlos, stabil, ideal für dieses Projekt.

---

## 2) Netlify (Free Tier, Drag & Drop möglich)

### Ohne Build-Setup (am schnellsten)
1. Auf netlify.com einloggen.
2. Projektordner als ZIP hochladen (oder Repo verbinden).
3. Fertig – Netlify erstellt direkt eine URL wie:
   - `https://glittery-knee-timer.netlify.app`

Vorteile: ultrafix, kostenlose HTTPS-Domain, gute DX.

---

## 3) Vercel (Free Tier)

1. Repo auf GitHub/GitLab/Bitbucket.
2. Auf vercel.com „New Project".
3. Repo auswählen.
4. Framework Preset: **Other** / static.
5. Deploy drücken.

Ergebnis: URL wie
- `https://meniskustimer.vercel.app`

Vorteile: sehr schnell, automatische Deploys bei Git Push.

---

## 4) Cloudflare Pages (zusätzliche Gratis-Option)

1. Repo verbinden.
2. Build command leer lassen (statische Seite).
3. Output-Verzeichnis auf Root (`.`) setzen.
4. Deploy.

URL z. B.:
- `https://meniskustimer.pages.dev`

Vorteile: schnell, gutes CDN, kostenloses TLS.

## Welche Deployment-Variante ist am einfachsten?

Wenn du "jetzt sofort online" willst:
1. **Netlify Drag & Drop** (am wenigsten Setup)
2. **Vercel mit Git-Repo** (sehr smooth)
3. **GitHub Pages** (am klassischsten, gratis)

Für dieses Projekt (statische Einzeldatei) funktionieren alle top.

## Projektstruktur

```text
.
├── index.html
└── README.md
```

## Hinweis

Die App ist ein Trainings-Organizer/Motivations-Tool und ersetzt keine medizinische Beratung.
Bitte bei Schmerzen oder Unsicherheit mit deiner Physio/Fachperson abstimmen.
