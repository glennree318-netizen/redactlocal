# RedactNook

Redact PII from PDFs and images, plus merge and split PDF — entirely in your browser.
**100% client-side. No uploads. No accounts. Open source.**

## Tools

| Tool | What it does |
|---|---|
| Redact PII | Auto-detect SSN, email, phone, credit cards + keyword & manual draw redaction. Permanently removes data (not just covering it) |
| Merge PDF | Combine multiple PDFs into one, with reordering. Preserves text and vectors |
| Split PDF | Extract page ranges (`1-3, 5, 8-10`) or one file per page, delivered as a ZIP |

## Privacy

Files are processed with `pdf.js` / `jsPDF` / `pdf-lib` in your browser. Nothing is uploaded, no server sees your documents.

## Deploy

Static site — any host works (Vercel, Netlify, GitHub Pages, Cloudflare Pages).
Push to `main` and GitHub Pages auto-publishes.