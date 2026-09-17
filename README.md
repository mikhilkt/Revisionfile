# Revisionfile

A local-first revision workspace for BI notes.

## Use it

1. Open `index.html` in a modern browser (or deploy the repository with GitHub Pages).
2. Choose your `BI notes` folder. Subfolders automatically become sections and PDFs become notes inside them.
3. Select any PDF to read it. Click **Start challenge** to generate a fresh 10-question multiple-choice quiz from the PDF's extractable text.

The folder and PDFs stay in the browser. No upload or server is required. PDF text extraction uses PDF.js from a CDN; a browser must be online the first time it loads the library.

## Folder shape

```text
BI notes/
├── Finance/
│   ├── balance-sheets.pdf
│   └── ratios.pdf
└── Strategy/
    └── competitive-analysis.pdf
```

Each folder is rendered as a section automatically. Quizzes are regenerated whenever a PDF is opened and again when a new challenge is started. Scanned/image-only PDFs need OCR text before they can produce questions.
