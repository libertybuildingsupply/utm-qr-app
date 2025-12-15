````md
# UTM & QR Code Generator

A lightweight, browser-based tool for creating **UTM tracking links** and **QR codes**.

This tool is used by Liberty Building Supply to standardize how marketing links are created and tracked across print materials, email campaigns, social media, websites, and QR codes.

---

## What This Tool Does

- Builds URLs with UTM parameters for campaign tracking
- Generates QR codes from those UTM links
- Keeps UTM values consistent using lowercase and hyphens
- Allows optional UTM fields for advanced tracking
- Runs entirely client-side with no backend or database

---

## UTM Field Meanings

- **Campaign Source**  
  Where the link is placed or published (newspaper, catalog, website, email, sign, etc.)

- **Campaign Medium**  
  The type of marketing channel (print, social, email, search, googleads, website, blog)

- **Campaign Name**  
  The promotion, catalog edition, email campaign, or season

Optional fields include campaign ID, term, and content.

---

## Running the App

### Run Locally

Open `index.html` in any modern web browser.

No build process or server required.

---

### Run with Docker

This app can be served using Nginx in Docker.

```bash
docker compose up -d
````

Then open:

```
http://localhost:8080
```

---

## Project Files

```
utm-qr-app/
├─ index.html
├─ docker-compose.yml
└─ README.md
```

---

## Notes

* This is a static application
* Safe to deploy behind a reverse proxy or tunnel
* Designed for internal use, but easy to reuse or extend

```
