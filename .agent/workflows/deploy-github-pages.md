---
description: Deploy Trading Resources ke GitHub Pages
---

# Deploy ke GitHub Pages

## Prerequisites
- Akun GitHub (gratis)
- Git installed di komputer

## Steps

### 1. Initialize Git Repository
```bash
cd c:/Users/irfan/.gemini/antigravity/playground/pulsing-spicule
git init
```

### 2. Create .gitignore
```bash
echo "node_modules/" > .gitignore
echo ".DS_Store" >> .gitignore
```

### 3. Commit Files
```bash
git add .
git commit -m "Initial commit: Trading resources"
```

### 4. Create GitHub Repository
1. Buka https://github.com/new
2. Repository name: `trading-resources` (atau nama lain)
3. Public (agar bisa di-deploy)
4. Jangan centang "Initialize with README" (sudah ada)
5. Click "Create repository"

### 5. Push ke GitHub
```bash
git remote add origin https://github.com/USERNAME/trading-resources.git
git branch -M main
git push -u origin main
```
*Ganti USERNAME dengan username GitHub Anda*

### 6. Enable GitHub Pages
1. Buka repository di GitHub
2. Settings → Pages
3. Source: Deploy from a branch
4. Branch: `main` → folder: `/ (root)`
5. Save

### 7. Wait & Access
- GitHub akan build (tunggu 1-2 menit)
- URL: `https://USERNAME.github.io/trading-resources/`
- README.md otomatis jadi homepage

## Hasil
✅ File MD otomatis jadi website
✅ Gratis hosting
✅ Custom domain (optional)
✅ Auto-update setiap push

## Update Content
Setiap kali edit file:
```bash
git add .
git commit -m "Update content"
git push
```
Website auto-update dalam 1-2 menit!

## Tips
- GitHub Pages support Markdown natively
- Bisa pakai Jekyll theme untuk tampilan lebih bagus
- Bisa custom domain (example.com)