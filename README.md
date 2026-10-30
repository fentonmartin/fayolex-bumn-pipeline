# Fayolex BUMN Pipeline

> Sales Intelligence — Peluang LMS di BUMN Indonesia

[![Deploy MkDocs](https://github.com/fentonmartin/fayolex-bumn-pipeline/actions/workflows/deploy.yml/badge.svg)](https://github.com/fentonmartin/fayolex-bumn-pipeline/actions/workflows/deploy.yml)

## 🌐 Live Site

**[https://fentonmartin.github.io/fayolex-bumn-pipeline](https://fentonmartin.github.io/fayolex-bumn-pipeline)**

## Tentang Repository Ini

Pipeline ini berisi research briefs untuk **48 BUMN Indonesia** sebagai target potensial Fayolex Learning Experience — platform LMS dengan metodologi 70:20:10.

### Struktur
- `docs/tier1/` — BUMN Tier 1 (6 BUMN prioritas utama)
- `docs/tier2/` — BUMN Tier 2 (42 BUMN follow-up)
- `docs/dashboard.md` — Tabel ringkasan semua BUMN
- `docs/guide.md` — Panduan tim sales

## Cara Update

1. Edit file `.md` di folder `docs/`
2. Push ke branch `main`
3. GitHub Actions otomatis deploy ke GitHub Pages

```bash
git add -A
git commit -m "update: [nama BUMN] — [apa yang diubah]"
git push origin main
```

> **Internal Use Only** — © 2026 Fayolex Learning Experience
