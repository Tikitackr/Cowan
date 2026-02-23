# 🦞 Cowan – Die Buch-Instanz

**KI-Wissensassistent zum Buch "Agentic Authorship: Mit n8n, Claude und OpenClaw zur automatisierten Buchfabrik"**

Cowan kennt das Buch in- und auswendig und beantwortet deine Fragen zu OpenClaw, Claude, n8n und mehr.

## 🚀 Live Demo

**[https://tikitackr.github.io/Cowan/](https://tikitackr.github.io/Cowan/)**

## ✨ Features

- **KI-Chat mit Quellenangabe** – Antworten basieren auf der Knowledge Base des Buches
- **BYOK (Bring Your Own Key)** – Nutze deinen eigenen Claude API-Key
- **Modellauswahl** – Haiku 4.5 (schnell & günstig) oder Sonnet 4.5 (detaillierter)
- **📚 Wissensbasis-Browser** – Alle 8 Wissensbausteine durchblättern, ohne eine Frage zu stellen
- **Chat-Export** – Konversation als JSON oder Text herunterladen
- **Kostentracking** – Echtzeit-Anzeige von Token-Verbrauch und Kosten
- **Dark/Light Mode** – Manuell umschaltbar
- **Keyboard Shortcuts** – Enter = Senden, Escape = Panels schließen
- **Vorgeschlagene Fragen** – Einstiegsfragen zum schnellen Loslegen
- **Social Media Integration** – Fragen direkt auf X posten (WhatsApp & Telegram demnächst)
- **Onboarding Tutorial** – Interaktiver 5-Schritte-Walkthrough für neue Nutzer
- **Markdown-Rendering** – Code-Blöcke, Fett, Kursiv, Links
- **Easter Eggs** – 🦞 Lobster Wiggle & Konfetti-Animation
- **100% clientseitig** – Läuft komplett im Browser, kein Backend

## 🛠 Technologie

- **React 18** via CDN (kein Build-Tool nötig)
- **Claude API** (Anthropic) für die KI-Antworten
- **Standalone HTML** – Eine einzige Datei, sofort einsatzbereit
- **GitHub Pages** für Hosting

## 📖 Über das Buch

"Agentic Authorship" zeigt, wie man mit n8n-Workflows, Claude als KI-Co-Autor und OpenClaw als Agent-Framework eine automatisierte Buchfabrik aufbaut. Cowan ist der interaktive Begleiter zum Buch.

## 🔑 Nutzung

1. Öffne [https://tikitackr.github.io/Cowan/](https://tikitackr.github.io/Cowan/)
2. Gib deinen Claude API-Key ein (von [console.anthropic.com](https://console.anthropic.com/settings/keys))
3. Stelle deine Frage zum Buch
4. Cowan antwortet mit Wissen aus der Knowledge Base

> 🔒 Dein API-Key wird nur lokal im Browser verwendet und niemals gespeichert.

## 📁 Projektstruktur

```
Cowan/
├── index.html              # Deployed App (React.createElement)
├── cowan-app.jsx           # JSX-Quellcode (lesbar)
├── README.md               # Diese Datei
├── _archive/               # Ältere Versionen
│   ├── cowan-app-v1-stable.jsx
│   ├── cowan-app-v2-gimmicks.jsx
│   ├── cowan-app-v3-social-tutorial.jsx
│   └── cowan-app-test.jsx
└── docs/
    ├── SESSION-LOG.md
    ├── cowan-naechste-schritte.md
    ├── cowan-briefing.md
    └── cowan-schritt-fuer-schritt.md
```

## 🗺 Roadmap

- [ ] Mobile Responsive Optimierung
- [ ] Social Media Kanäle erweitern (WhatsApp, Telegram, Discord)
- [ ] PWA-Fähigkeit
- [ ] Echte Buchinhalte (wenn Buch mit OpenClaw fertig ist)

## Lizenz

MIT

---

Erstellt mit [Claude](https://claude.ai) von [Anthropic](https://anthropic.com)
