# Pulak Ranjan — Portfolio

A minimal, terminal-inspired portfolio website for a Systems & AI Engineer.

🔗 **Live:** [pulak-ranjan.github.io/me/](https://pulak-ranjan.github.io/me/)

📂 **Repo:** [github.com/pulak-ranjan/me](https://github.com/pulak-ranjan/me)

---

## Features

- **Interactive Terminal** — Functional command-line interface with custom commands (`help`, `whoami`, `skills`, `projects`, `contact`, etc.)
- **Fullscreen Terminal Mode** — Expand terminal to fullscreen on desktop
- **Chatbot** — Floating chatbot (bottom-right) with quick info commands
- **Theme Switcher** — 6 accent colors (green, orange, yellow, cyan, pink, purple)
- **Fully Responsive** — Optimized layouts for desktop, tablet, and mobile
- **Custom Cursor** — Animated cursor with glow effect (desktop only)
- **Smooth Animations** — Scroll reveal, slide-up transitions, typing effects

---

## Tech Stack

- **HTML5** — Semantic markup
- **CSS3** — Custom properties, Grid, Flexbox, animations
- **Vanilla JavaScript** — No frameworks, no dependencies
- **Google Fonts** — IBM Plex Mono, Syne, Space Grotesk

---

## Terminal Commands

| Command | Description |
|---------|-------------|
| `help` | List available commands |
| `whoami` | About me |
| `skills` | Technical skills |
| `projects` | View projects |
| `contact` | Contact information |
| `experience` | Work history |
| `philosophy` | How I work |
| `stack` | Tech stack |
| `social` | Social links |
| `hire` | Why hire me |
| `clear` | Clear terminal |

---

## Sections

1. **Hero** — Introduction with interactive terminal
2. **About** — Background and journey
3. **Skills** — Technical skills (highlighted marketable skills)
4. **Experience** — Work history
5. **Expertise** — Core competencies
6. **Philosophy** — Work principles
7. **Projects** — Selected work
8. **Contact** — Get in touch

---

## Local Development

No build tools required. Just open `index.html` in a browser.

```bash
# Clone the repository
git clone https://github.com/pulak-ranjan/me.git

# Open in browser
open index.html
```

---

## Deployment

Push to `main` branch — GitHub Pages auto-deploys.

---

## Customization

### Change Accent Color
Modify CSS variables in `:root`:
```css
:root {
  --accent: #00ff41;
  --accent-dim: rgba(0,255,65,0.1);
  --accent-glow: rgba(0,255,65,0.4);
}
```

### Add Terminal Commands
Add to `heroCommands` object in JavaScript:
```javascript
const heroCommands = {
  newcommand: [
    {t: 'Output text', c: 'ht-success'},
  ],
};
```

---

## Author

**Pulak Ranjan**  
Systems & AI Engineer

- 📧 cloudnesh@gmail.com
- 🔗 [GitHub](https://github.com/pulak-ranjan)
- 🔗 [LinkedIn](https://linkedin.com/in/pulak-ranjan)

---

## License

MIT License — feel free to use and modify.
