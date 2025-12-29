# JSON Resume

This project uses the [JSON Resume](https://jsonresume.org/) standard to create and maintain your resume in a structured, portable format.

## 📁 Files

- `resume.json` - Your resume data in JSON Resume format

## 🚀 Getting Started

### 1. Install the CLI Tool

```bash
npm install -g resume-cli
```

> **Alternative:** If you have issues with the official CLI, try:
> ```bash
> npm install -g @rbardini/resumed
> ```

### 2. Fill in Your Resume

Edit `resume.json` with your actual information. Replace all placeholder text with your details from your existing resume.

### 3. Export Your Resume

Generate PDF:
```bash
resume export resume.pdf
```

Generate HTML:
```bash
resume export resume.html
```

### 4. Preview Your Resume

```bash
resume serve
```

This will open a browser preview of your resume.

## 🎨 Themes

You can change the theme in the `meta.theme` field of your `resume.json`. Popular themes include:

- `elegant` (default)
- `kendall`
- `flat`
- `modern`
- `macchiato`
- `stackoverflow`

Browse all themes at: https://jsonresume.org/themes

## ☁️ Hosting (Free)

JSON Resume offers free hosting:

1. Create a GitHub Gist named `resume.json` with your resume content
2. Access your resume at: `https://registry.jsonresume.org/YOUR_GITHUB_USERNAME`

## 📄 Export to LaTeX

For a LaTeX version using RenderCV:

```bash
npx @jsonresume/jsonresume-to-rendercv resume.json
rendercv render resume.yaml
```

## 📚 Resources

- [JSON Resume Schema](https://jsonresume.org/schema)
- [Themes Gallery](https://jsonresume.org/themes)
- [Getting Started Guide](https://jsonresume.org/getting-started)
- [Import from LinkedIn](https://jsonresume.org/getting-started) (Chrome Extension)

## 🔗 Quick Links

| Format | URL |
|--------|-----|
| JSON | `registry.jsonresume.org/USERNAME.json` |
| YAML | `registry.jsonresume.org/USERNAME.yaml` |
| TEXT | `registry.jsonresume.org/USERNAME.txt` |
| QR Code | `registry.jsonresume.org/USERNAME.qr` |

