# I-BlackPDF-

**Every page stays on your machine.**

A single-file, client-side PDF toolkit — 30 tools for organizing, converting, editing, securing and inspecting PDFs, all running in the browser. No uploads, no accounts, no backend.

**Live demo:** _add your GitHub Pages link here after deploying (see below)_

## Why

Most PDF sites upload your file to a server, process it, and send it back. BLACKPDF does the same jobs — merge, split, convert, sign, redact and more — entirely client-side using [pdf-lib](https://github.com/Hopding/pdf-lib), [pdf.js](https://github.com/mozilla/pdf.js), [mammoth](https://github.com/mwilliamson/mammoth.js), [SheetJS](https://github.com/SheetJS/sheetjs), [Tesseract.js](https://github.com/naptha/tesseract.js) and [JSZip](https://github.com/Stuk/jszip). Your files never leave your device.

Two exceptions: **Summarize with AI**, **Ask your PDF**, and **Translate PDF** send extracted text to the Claude API to generate a response. This is disclosed in the UI and in the FAQ — every other tool is fully local.

## Features

- **Organize** — merge, split, remove/extract pages, reorder, drag-and-drop page manager
- **Create & convert** — PDF Maker, Word ⇄ PDF, Excel ⇄ PDF, Text ⇄ PDF, PDF ⇄ Markdown, Images ⇄ PDF, Scan to PDF, on-device OCR
- **Edit & stamp** — rotate, crop, add text, page numbers, watermark
- **Security & compare** — sign PDF, redact PDF (genuinely flattens pages, not just an overlay), compare two versions
- **Optimize & inspect** — compress, edit document metadata
- **AI-powered** — summarize, ask questions about a document, translate (clearly labeled as the only tools that leave the browser)

Plus a command palette (`Ctrl`/`⌘ + K`), persistent favorites, live tool search, and a fully keyboard- and screen-reader-accessible workspace.

## Running it

This is a single static HTML file with no build step.

```bash
# just open it
open index.html

# or serve it locally
npx serve .
```

## Deploying

Works on any static host. For GitHub Pages: **Settings → Pages → Deploy from branch → `main` / root**, then it's live at `https://<username>.github.io/<repo>/`.

## Disclaimer

Independent project, not affiliated with iLovePDF or any other PDF service. Built as a demonstration of what's possible fully client-side.

## License

MIT — see [LICENSE](./LICENSE).
