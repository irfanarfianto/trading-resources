---
description: Deploy dengan Docsify (Documentation Site)
---

# Deploy dengan Docsify

Docsify = Tool untuk convert Markdown jadi beautiful documentation website

## Prerequisites
- Node.js installed
- Git & GitHub account

## Steps

### 1. Install Docsify CLI
```bash
npm i docsify-cli -g
```

### 2. Initialize Docsify
```bash
cd c:/Users/irfan/.gemini/antigravity/playground/pulsing-spicule
docsify init ./docs
```

### 3. Move MD Files
```bash
# Copy semua file ke folder docs
cp -r trading-education docs/
cp -r trading-prompts docs/
cp -r trading-routines docs/
cp README.md docs/
cp TRADING-RULES.md docs/
cp QUICK-REFERENCE.md docs/
```

### 4. Configure Docsify
Edit `docs/index.html`:
```html
<script>
  window.$docsify = {
    name: 'Trading Resources',
    repo: 'https://github.com/USERNAME/trading-resources',
    loadSidebar: true,
    subMaxLevel: 3,
    search: 'auto',
    coverpage: true
  }
</script>
```

### 5. Create Sidebar
Create `docs/_sidebar.md`:
```markdown
- [Home](/)
- [Trading Rules](TRADING-RULES.md)
- [Quick Reference](QUICK-REFERENCE.md)

- Trading Prompts
  - [Overview](trading-prompts/README.md)
  - [Day Trading](trading-prompts/day-trading-expert-prompt.md)
  - [Scalping](trading-prompts/scalping-expert-prompt.md)

- Trading Routines
  - [Overview](trading-routines/README.md)
  - [Malam](trading-routines/trading-routine-malam.md)
  - [Pagi](trading-routines/trading-routine-pagi.md)

- Trading Education
  - [Overview](trading-education/README.md)
  - [Dasar Trading](trading-education/01-dasar-trading.md)
  - [Candlestick](trading-education/02-chart-candlestick.md)
  - [Support & Resistance](trading-education/03-support-resistance.md)
  - [Indikator](trading-education/04-indikator-teknikal.md)
```

### 6. Test Locally
```bash
docsify serve docs
```
Buka: http://localhost:3000

### 7. Deploy ke GitHub Pages
```bash
git add .
git commit -m "Add Docsify documentation"
git push
```

Enable GitHub Pages (Settings → Pages → Source: main/docs)

## Hasil
✅ Beautiful documentation site
✅ Search functionality
✅ Sidebar navigation
✅ Mobile responsive
✅ Dark mode support

## URL
`https://USERNAME.github.io/trading-resources/`
