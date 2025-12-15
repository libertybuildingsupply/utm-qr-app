# UTM & QR Code Generator

A lightweight, browser-based tool for creating **UTM-tracked URLs** and **QR codes** with consistent naming rules.

Built for **Liberty Building Supply** to standardize campaign tracking across print, digital, email, social, and QR-based marketing.

---

## ✨ Features

- Build clean, standardized UTM URLs
- Generate high-quality QR codes from UTM links
- Enforces lowercase, hyphenated UTM values
- Supports print, email, social, search, and website campaigns
- Optional UTM fields (ID, term, content)
- Copy-ready campaign URLs
- Downloadable QR codes (PNG)
- No backend required — runs entirely in the browser

---

## 🧠 UTM Structure (Design Philosophy)

This tool follows a simple and consistent UTM model:

- **Campaign Source**  
  Where the link is placed or published  
  *(e.g., newspaper, catalog, website, email, QR sign)*

- **Campaign Medium**  
  The type of marketing channel  
  *(e.g., print, social, email, search, googleads, website)*

- **Campaign Name**  
  The promotion, campaign, catalog edition, or season  
  *(e.g., spring-catalog-2025, monthly-march-2025)*

This structure keeps analytics clean and reporting reliable over time.

---

## 🖥️ How to Use

1. Open `index.html` in any modern web browser
2. Enter your website URL
3. (Optional) Add a landing page path
4. Fill in:
   - Campaign Source
   - Campaign Medium
   - Campaign Name
5. Review the generated campaign URL
6. Click **Generate QR Code**
7. Copy the URL or download the QR code image

---

## 🧩 Optional UTM Fields

The tool also supports:

- `utm_id` — internal tracking or job number
- `utm_term` — paid search keywords
- `utm_content` — link position or variation

These fields are optional and hidden by default.

---

## 📦 Tech Stack

- HTML
- CSS
- Vanilla JavaScript
- [QRCode.js](https://github.com/davidshimjs/qrcodejs)

No frameworks. No build step. No dependencies beyond the QR library.

---

## 🚀 Deployment

This app can be:
- Opened locally in a browser
- Hosted on GitHub Pages
- Served via Docker / Nginx
- Embedded into an internal tools site

---

## 📄 License

Internal use for Liberty Building Supply.  
Public repository for transparency and reuse.

---

## 🛠️ Future Ideas (Optional)

- Dropdown presets for Source / Medium
- CSV export of generated campaigns
- Bulk QR generation
- Campaign history log
- Dark mode toggle

---

Built with clarity and consistency in mind.
