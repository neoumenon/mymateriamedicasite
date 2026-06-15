# mymateriamedicasite

Static legal pages for the [My Materia Medica](https://github.com/neoumenon/mymateriamedica) app, published via GitHub Pages.

## Pages

| Path | Document |
|------|----------|
| `/` | Index of all legal documents |
| `/privacy/` | Privacy Policy |
| `/terms/` | Terms of Use |
| `/disclaimer/` | Medical Disclaimer |
| `/ai/` | AI Features |
| `/correlation/` | Correlation Disclaimer |
| `/apple-health/` | Apple Health Data |

## GitHub Pages

1. In this repo: **Settings → Pages**
2. Source: **Deploy from a branch**
3. Branch: `main` / `/ (root)`

Once enabled, the site will be available at:

`https://neoumenon.github.io/mymateriamedicasite/`

## Keeping copy in sync

Legal text is mirrored from `mymateriamedica/mobile/disclaimers/*.md` and `mobile/src/content/disclaimers.ts`. Update both the app and these HTML pages when policies change.
