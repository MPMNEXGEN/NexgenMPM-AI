# NexgenMPM AI

> **AI CEO-managed project management platform** — End-to-end operations from order registration to revenue conversion, fully managed by AI.

![NexgenMPM AI](https://img.shields.io/badge/AI%20CEO-Active-success?style=flat-square)
![Status](https://img.shields.io/badge/Status-Production-blue?style=flat-square)
![License](https://img.shields.io/badge/License-MIT-yellow?style=flat-square)

---

## 🚀 Live Demo

**GitHub Pages:** [https://yourusername.github.io/nexgenmpm-ai](https://yourusername.github.io/nexgenmpm-ai)

---

## 📱 Features

| Feature | Description |
|---------|-------------|
| 🤖 AI CEO | Autonomous order management from registration to revenue |
| 📋 Order Registration | Capture and validate incoming orders |
| 📁 Project Directories | Order-number-wise directories with CEO/Director-only access |
| 📊 MIS Reporting | Automated reports to Human Director |
| 💰 Revenue Tracking | End-to-end revenue conversion monitoring |
| 🔐 Access Control | Role-based CEO/Director permissions |

---

## 🛠️ Tech Stack

- **Frontend:** Pure HTML5, CSS3, JavaScript (Vanilla)
- **Design:** Glassmorphism UI, CSS Grid, Flexbox
- **PWA:** Progressive Web App with offline support
- **Hosting:** GitHub Pages (free HTTPS)

---

## 📦 Installation

### 1. Fork & Clone

```bash
git clone https://github.com/yourusername/nexgenmpm-ai.git
cd nexgenmpm-ai
```

### 2. Deploy to GitHub Pages

1. Go to **Settings** → **Pages** in your forked repo
2. Set **Source** to `Deploy from a branch`
3. Select **main** branch and `/ (root)` folder
4. Click **Save**
5. Your site will be live at `https://yourusername.github.io/nexgenmpm-ai`

### 3. Custom Domain (Optional)

Add a `CNAME` file with your domain:
```
app.nexgenmpm.ai
```

Then configure DNS:
- **A Records:** `185.199.108.153`, `185.199.109.153`, `185.199.110.153`, `185.199.111.153`
- **CNAME:** `www` → `yourusername.github.io`

---

## 📂 Project Structure

```
nexgenmpm-ai/
├── index.html          # Main app (single file)
├── manifest.json       # PWA manifest
├── icon-192.png        # App icon (192x192)
├── icon-512.png        # App icon (512x512)
├── README.md           # This file
└── .github/
    └── workflows/
        └── deploy.yml  # Auto-deploy workflow
```

---

## 🎨 Design System

| Token | Value | Usage |
|-------|-------|-------|
| `--primary` | `#6366f1` | Primary brand color |
| `--secondary` | `#0ea5e9` | Accent / links |
| `--accent` | `#f59e0b` | Warnings / pending |
| `--success` | `#10b981` | Success states |
| `--danger` | `#ef4444` | Errors |
| `--dark` | `#0f172a` | Background |

---

## 🔐 Security

- CEO/Director-only access on project directories
- Order-number-wise isolation
- Role-based permissions
- HTTPS enforced by GitHub Pages

---

## 📄 License

MIT License — see [LICENSE](LICENSE) for details.

---

**Built with ❤️ by NexgenMPM AI**