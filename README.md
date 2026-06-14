# Gian Kappeler · Persönliche Website

Online-Portfolio und Lebenslauf von **Gian Kappeler** – angehender Informatiker EFZ
und Quereinsteiger aus der Logistik, auf der Suche nach einem IT-Praktikum.

🔗 **Live:** [gian-kappeler.ch](https://gian-kappeler.ch)

## Über die Seite

Eine einseitige, statische Website (One-Pager), die Werdegang, Projekte und
Fähigkeiten übersichtlich präsentiert. Aufgebaut in den Abschnitten:

- **Hero** – kurze Vorstellung mit Kontaktmöglichkeiten
- **Projekte** – Arbeiten aus Ausbildung und Eigenregie (Full-Stack, Desktop, Web)
- **Berufserfahrung** – Stationen als Timeline
- **Technik** – Programmiersprachen, Frameworks, Sprachen und Stärken
- **Ausbildung** – schulischer und beruflicher Werdegang
- **Kontakt** – E-Mail, GitHub und LinkedIn

## Technik

Bewusst schlank und ohne Build-Schritt gehalten:

- **HTML** – semantisches Markup, eine Datei pro Seite
- **CSS** – eigenes Stylesheet, Custom Properties für Farben und Abstände,
  responsives Layout (CSS Grid / Flexbox)
- **JavaScript** – minimal, ohne Framework: Scroll-Reveal-Animationen,
  Scrollspy in der Navigation und Sticky-Header
- **Schriften** – [Fraunces](https://fonts.google.com/specimen/Fraunces) und
  [Schibsted Grotesk](https://fonts.google.com/specimen/Schibsted+Grotesk),
  **lokal gehostet** (kein Google-Fonts-CDN, daher datenschutzfreundlich)

Keine Abhängigkeiten, kein Tracking, keine Cookies.

## Projektstruktur

```
.
├── index.html          # Startseite (One-Pager)
├── rechtliches.html    # Impressum & Datenschutzerklärung
├── style.css           # Gesamtes Styling
├── gian-kappeler.jpg   # Porträt
├── fonts/              # Lokal gehostete Schriften (woff2) + fonts.css
└── README.md
```

## Lokal ansehen

Da es eine rein statische Seite ist, genügt ein Doppelklick auf `index.html`.
Für saubere Pfade (z. B. korrektes Laden der Schriften) empfiehlt sich ein
einfacher lokaler Server:

```bash
# Python 3
python -m http.server 8000
# danach im Browser: http://localhost:8000
```

## Deployment

Die Seite wird über **[Vercel](https://vercel.com)** ausgeliefert. Jeder Push auf
den `main`-Branch löst automatisch ein neues Deployment aus – es ist kein
Build-Schritt nötig, die Dateien werden direkt statisch gehostet.

## Datenschutz

Die Website ist datensparsam: keine Formulare, kein Analytics, keine Cookies und
keine externen Schrift-Anbieter. Details unter
[Impressum & Datenschutz](rechtliches.html).

---

© Gian Kappeler
