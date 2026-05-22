# Xavier Saliniere — Resume

> **CI-generated resume files:**
> - **English:** [Xavier-SALINIERE_resume.EN.html](out/Xavier-SALINIERE_resume.EN.html) | [Xavier-SALINIERE_resume.EN.pdf](out/Xavier-SALINIERE_resume.EN.pdf)
> - **French:** [Xavier-SALINIERE_resume.FR.html](out/Xavier-SALINIERE_resume.FR.html) | [Xavier-SALINIERE_resume.FR.pdf](out/Xavier-SALINIERE_resume.FR.pdf)

## Files

- `resume.json` — English JSON Resume (ATS-friendly)
- `resume.fr.json` — French JSON Resume (ATS-friendly)
- `README.md` — This file

## Usage

### Install dependencies

```bash
npm install
```

### Validate JSON Resume

```bash
npm run validate      # English
npm run validate_fr   # French
```

### Render to HTML

```bash
npm run render      # English → index.html
npm run render_fr   # French → index.fr.html
```

### Export to PDF

Requires puppeteer/Chrome installed.

```bash
npm install puppeteer
npm run export      # English → out/Xavier-SALINIERE_resume.EN.pdf
npm run export_fr   # French → out/Xavier-SALINIERE_resume.FR.pdf
```

### Serve locally

Renders to `index.html` (or `index.fr.html` for French) and starts server at http://localhost:3000.

```bash
npm run serve      # English
npm run serve_fr   # French
```
