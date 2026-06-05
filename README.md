

---

```markdown
<!-- Banner / Header -->
<p align="center">
  <img src="https://img.shields.io/badge/Chrome%20Extension-Accounting%20Tools-blue?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Chrome Extension Badge">
  <img src="https://img.shields.io/badge/License-MIT-green?style=for-the-badge" alt="License Badge">
  <img src="https://img.shields.io/badge/Version-1.0.0-orange?style=for-the-badge" alt="Version Badge">
</p>

<h1 align="center">📊 Accounting Tools Chrome Extension</h1>

<p align="center">
  <b>A powerful browser extension built for accountants, by an accountant.</b><br>
  Streamline your workflow, automate calculations, and manage financial data directly in your browser.
</p>

<p align="center">
  <a href="#features">Features</a> •
  <a href="#installation">Installation</a> •
  <a href="#usage">Usage</a> •
  <a href="#screenshots">Screenshots</a> •
  <a href="#contributing">Contributing</a> •
  <a href="#license">License</a>
</p>

---

## ✨ Features

| Feature | Description | Status |
|---------|-------------|--------|
| 🔢 **Quick Calculator** | Inline calculator for rapid computations | ✅ Active |
| 📑 **Invoice Parser** | Extract data from invoices and receipts | ✅ Active |
| 💱 **Currency Converter** | Real-time currency conversion with 160+ currencies | ✅ Active |
| 📈 **Tax Calculator** | Automated tax computation engine | 🚧 In Progress |
| 📤 **Export to Excel** | One-click export to `.xlsx` format | 🚧 In Progress |
| 🔒 **Secure Mode** | Client-side encryption for sensitive data | 📋 Planned |

---

## 🚀 Installation

### From Chrome Web Store
> *Coming soon — pending review*

### Manual Installation (Developer Mode)
1. Clone this repository:
   ```bash
   git clone https://github.com/[your-username]/[your-repo-name].git
   ```
2. Open Chrome and navigate to `chrome://extensions/`
3. Enable **Developer mode** (toggle in top-right corner)
4. Click **Load unpacked**
5. Select the cloned project folder
6. The extension icon will appear in your toolbar 🎉

---

## 🛠️ Tech Stack

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Chrome%20API-4285F4?style=flat-square&logo=google-chrome&logoColor=white" alt="Chrome API">
  <img src="https://img.shields.io/badge/Manifest%20V3-20232A?style=flat-square&logo=chrome&logoColor=61DAFB" alt="Manifest V3">
</p>

---

## 📸 Screenshots

<p align="center">
  <img src="docs/screenshots/dashboard.png" alt="Dashboard Preview" width="600">
  <br>
  <em>Main dashboard with quick-access accounting tools</em>
</p>

---

## 🧮 Usage Examples

### Quick Calculator
```javascript
// Press Alt + A to open the calculator overlay
// Or click the extension icon and select "Calculator"
```

### Invoice Parser
1. Right-click on any invoice image or PDF
2. Select **"Parse Invoice"** from the context menu
3. Data is extracted and formatted automatically

### Currency Conversion
```javascript
// Automatically converts prices on e-commerce pages
// Supports: USD, EUR, GBP, KES, and 160+ others
```

---

## 📁 Project Structure

```
accounting-tools-extension/
├── 📂 assets/           # Icons, images, and static files
├── 📂 src/
│   ├── 📂 background/   # Service worker scripts
│   ├── 📂 content/      # Content scripts for page injection
│   ├── 📂 popup/        # Extension popup UI
│   └── 📂 utils/        # Helper functions and utilities
├── 📄 manifest.json     # Extension configuration (Manifest V3)
├── 📄 popup.html        # Main popup interface
├── 📄 popup.js          # Popup logic
├── 📄 styles.css        # Global styles
└── 📄 README.md         # This file
```

---

## 🤝 Contributing

Contributions are welcome! Whether you're fixing a bug, adding a feature, or improving documentation:

1. **Fork** the repository
2. **Create** a feature branch: `git checkout -b feature/amazing-feature`
3. **Commit** your changes: `git commit -m 'Add amazing feature'`
4. **Push** to the branch: `git push origin feature/amazing-feature`
5. **Open** a Pull Request

---

## 📜 License

This project is licensed under the **MIT License** — see the [LICENSE](LICENSE) file for details.

---

## 👤 Author

<p align="left">
  <b>Richard Muhoro</b> — Accountant & Developer
  <br>
  <a href="https://github.com/[your-username]">
    <img src="https://img.shields.io/badge/GitHub-100000?style=flat-square&logo=github&logoColor=white" alt="GitHub">
  </a>
  <a href="mailto:[your-email@example.com]">
    <img src="https://img.shields.io/badge/Email-D14836?style=flat-square&logo=gmail&logoColor=white" alt="Email">
  </a>
</p>

---

<p align="center">
  <img src="https://img.shields.io/badge/Made%20with%20❤️%20by%20Richard%20Muhoro-2026-blue?style=flat-square" alt="Made by Richard Muhoro">
  <br>
  <em>Built to make accounting work simpler, faster, and smarter.</em>
</p>
```

---

## How to Update Your GitHub Main Branch

1. **Copy** the markdown above
2. **Navigate** to your GitHub repository
3. **Click** `README.md` → **Edit** (the pencil icon)
4. **Paste** the content and replace placeholders like `[your-username]`, `[your-repo-name]`, and `[your-email@example.com]`
5. **Commit** directly to the `main` branch with message: `docs: update README with graphical format`
6. **Add screenshots** by uploading them to a `docs/screenshots/` folder in your repo


