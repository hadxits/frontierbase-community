# frontierbase-community

Sample document repository for [Frontierbase](https://www.frontierbase.io).
Reference and use sample data (Excel, CSV, etc.) from related projects.

## Static hosting (GitHub Pages)

1. Go to **Settings** → **Pages**
2. **Source**: Deploy from a branch
3. **Branch**: `main` (or default branch) / **Folder**: `/ (root)`
4. After saving, the site will be available at `https://{org}.github.io/{repo}/`

## Directory structure

```
samples/
├── en/     # English
├── ko/     # Korean
├── ja/     # Japanese
├── zh/     # Chinese
├── es/     # Spanish
├── it/     # Italian
├── de/     # German
└── fr/     # French
```

## Usage

| Method | URL example |
|--------|-------------|
| **GitHub Pages** | `https://{org}.github.io/{repo}/samples/en/sample_pen_en.json` |
| **Raw** | `https://raw.githubusercontent.com/{org}/{repo}/main/samples/en/sample_pen_en.json` |
| **jsDelivr CDN** | `https://cdn.jsdelivr.net/gh/{org}/{repo}@main/samples/en/sample_pen_en.json` |
| **manifest** | Query supported languages and metadata from `manifest.json` |

## Frontierbase

RAG-based AI chatbot service for structured data using Excel, CSV, and Google Sheets.
