# Xavier Saliniere — Resume

## Files

- `resume.json` — Machine-parseable JSON Resume (ATS-friendly)
- `README.md` — This file

## Usage

### Install dependencies

```bash
npm install
```

### Validate JSON Resume

```bash
npm run validate
```

### Render to HTML

```bash
npm run render
```

Creates `resume.html`.

### Export to PDF

Requires puppeteer/Chrome installed.

```bash
npm install puppeteer
npm run export
```

### Serve locally

Renders to `index.html` and starts server at http://localhost:3000 (opens in browser).

```bash
npm run serve
```
