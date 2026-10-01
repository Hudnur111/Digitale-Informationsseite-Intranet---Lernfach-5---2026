# Digitale Informationsseite (Intranet)

Eine moderne, performante und benutzerfreundliche **Intranet-Webanwendung** zur zentralen Bereitstellung von Informationen, News und Ressourcen innerhalb des Unternehmensnetzwerks.

## 🚀 Features

*   **Zentrale Informationsdrehscheibe:** Schneller Zugriff auf Unternehmensnews, Dokumente und wichtige Links.
*   **Optimiert für Vercel:** Vorkonfiguriert für ein schnelles, serverloses Deployment.
*   **Clean URLs:** Benutzerfreundliche Navigation ohne störende Dateiendungen (z. B. `/dashboard` statt `/dashboard.html`).
*   **Responsive Design:** Optimale Darstellung auf Desktop-Monitoren, Tablets und Smartphones.

## 🛠️ Technologien

*   **Frontend:** HTML5, CSS3, JavaScript (Vanilla JS)
*   **Hosting & Deployment:** [Vercel](https://vercel.com)

## 📁 Projektstruktur

```text
├── public/                 # Statische Assets (Bilder, Icons)
├── css/                    # Stylesheets
├── js/                     # Clientseitige Skripte
├── index.html              # Startseite (Dashboard)
├── vercel.json             # Vercel-Konfigurationsdatei
└── README.md               # Projektdokumentation
```

## ⚙️ Konfiguration (Vercel)

Die Anwendung nutzt eine optimierte `vercel.json` im Hauptverzeichnis, um saubere URLs zu garantieren und das Routing für das Intranet abzusichern:

```json
{
  "version": 2,
  "cleanUrls": true,
  "trailingSlash": false
}
```

## 📦 Lokale Entwicklung & Deployment

### Lokale Vorschau

Da es sich um eine Standard-HTML-Anwendung handelt, können Sie das Projekt lokal über einen einfachen Webserver (z. CLI-Tools wie `serve` oder die VS Code Extension *Live Server*) starten:

```bash
# Mit npm einen lokalen Server starten
npx serve .
```

### Deployment auf Vercel

Um die Intranet-Anwendung live zu schalten, nutzen Sie entweder die Vercel-Git-Integration oder deployen Sie direkt über das Terminal:

```bash
# 1. Vercel CLI installieren (falls noch nicht geschehen)
npm install -g vercel

# 2. Deployment starten
vercel
```
