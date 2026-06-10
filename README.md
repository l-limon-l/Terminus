# Terminus 💻

**A sleek, developer-first HTML/CSS landing page template with a terminal-inspired aesthetic.**
Built with vanilla web technologies, it features a built-in language toggler, smooth micro-animations, and a suite of ready-to-use secondary pages. Perfect for tech products, CLI tools, developer utilities, or cybersecurity startups.

<img width="2560" height="1305" alt="image" src="https://github.com/user-attachments/assets/62ba46e7-cfb0-4569-901c-54cea39fcb12" />

## ✨ Key Features

- **👨💻 Developer-First Aesthetic:** Clean, terminal-like UI with monospace fonts (JetBrains Mono) and mint-green "success" accents.
- **⚡ Zero Dependencies:** Built with 100% Vanilla HTML, CSS, and JS. No Webpack, no npm, no complex build steps required. Just open and edit!
- **🌍 Built-in Localization (i18n):** Features a lightweight, vanilla JS language toggler (English & Russian included).
- **📄 Ready-to-use Pages:** Comes with pre-formatted secondary pages (`roadmap.html`, `privacy.html`, `terms.html`, `licenses.html`, `docs.html`, `contact.html`).
- **📱 Fully Responsive:** Carefully optimized to look perfect on desktops, tablets, and smartphones.
- **🎨 Easy to Customize:** CSS variables are centrally located in `styles.css` making it incredibly easy to re-theme the entire site.

## 🛠 Tech Stack

- **Structure:** HTML5
- **Styling:** Vanilla CSS3 (Custom Properties, Flexbox, CSS Grid)
- **Logic:** Vanilla JavaScript (for language toggling and DOM interactions)
- **Typography:** [JetBrains Mono](https://www.jetbrains.com/lp/mono/) & [Inter](https://rsms.me/inter/)

## 🚀 Getting Started

Since Terminus is built without any front-end frameworks, getting started is as simple as it gets:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/terminus.git
   cd terminus
   ```

2. **Open in browser:**
   Double-click `index.html` or open it in your browser of choice.
   *(Alternatively, if you use VS Code, you can use the "Live Server" extension for hot-reloading).*

## ⚙️ Customization

### Changing the Brand Color
Terminus uses a centralized CSS variables system. Open `assets/css/styles.css` and look at the `:root` block at the top. To change the primary "mint" color, simply edit the following variables:
```css
:root {
  --mint:        #00E5A0; /* Change this to your brand color */
  --mint-dim:    #00A878;
  --mint-bright: #4DFFC2;
}
```

### Adding your Logo/Favicons
Place your own `favicon.ico` and `apple-touch-icon.png` inside the `assets/img/` directory.

### Editing Content
All content is hardcoded directly in the HTML files. Look for the `[Square Brackets]` to easily identify placeholders where you should insert your own copy, links, and product features.
