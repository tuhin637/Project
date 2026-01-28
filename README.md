# Running Locally 🚀

## 📦 What's This?

Single-file static website built with:
- **HTML5 + CSS3 + Vanilla JavaScript**
- Chart.js (CDN) for graphs
- Font Awesome (CDN) for icons

**No frameworks. No build process. No npm install.**

## 🎯 Quick Start

### Easiest Way
1. Download `index.html`
2. Double-click it
3. Done! ✓

### For Development (VS Code)
1. Install "Live Server" extension
2. Right-click `index.html` → "Open with Live Server"
3. Auto-refreshes on save

### Python Server
```bash
python -m http.server 8000
# Visit: http://localhost:8000
```

### Node Server
```bash
npx http-server
# Visit: http://localhost:8080
```

## 📱 Test on Mobile

1. Same WiFi on both devices
2. Start server on computer
3. Get computer IP: `ipconfig` (Windows) or `ifconfig` (Mac/Linux)
4. Open on phone: `http://YOUR_IP:8000`

## 📂 Structure

```
index.html  (Everything in one file!)
├── <style>   - All CSS
└── <script>  - All JavaScript
```

## 🔧 Troubleshooting

- **Won't open?** Right-click → Open with → Browser
- **No styles?** Make sure you opened the HTML file
- **Port busy?** Use different port: `python -m http.server 8080`

---

**Live Demo:** [https://project-eight-kappa-14.vercel.app/](https://project-eight-kappa-14.vercel.app/)
