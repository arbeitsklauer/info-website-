
# 🌌 Vanguard Studio Portfolio (Open Source)

A premium, high-end studio portfolio website built with a modern tech stack and a unique "Studio-Tech" aesthetic. Optimized for performance and stability across all devices.

## 🚀 Quick Start

1. **Install Dependencies**:
   ```bash
   npm install
   ```

2. **Start the Server**:
   ```bash
   node server.js
   ```

3. **View the Site**:
   Open [http://localhost:3000](http://localhost:3000) in your browser.

## 🛠 Tech Stack

- **Frontend**: HTML5, Vanilla CSS (Grid & Flexbox), GSAP (Animations), ScrollTrigger, Lenis (Smooth Scroll).
- **Backend**: Node.js, Express.
- **Database**: SQLite (better-sqlite3) for persistent data storage.

## 📂 Configuration & Customization

### Backend (`server.js`)
You can find the `CONFIG` object at the top of the file:
- `PORT`: Server port (default: 3000).
- `DB_FILE`: Name of the SQLite database file.
- `API_PREFIX`: Base URL for all API routes.

### Styles (`style.css`)
Modify the CSS Variables in `:root` to change the entire theme:
- `--accent-color`: Main brand color (Purple).
- `--accent-secondary`: Secondary technical color (Cyan).
- `--bg-color`: Background color (Deep Black).
- `--font-main`: Primary typography (Outfit).

### Content
- **Projekte**: The server seeds initial projects if the database is empty. To add more, modify the `seedData` function in `server.js` or interact with the `projects` table in `portfolio.db`.
- **Team**: Update the team section directly in `index.html`.

## 📱 Responsiveness
The site is "Mobile-First" optimized and uses dynamic `clamp()` scaling for typography. The asymmetrical layout automatically switches to a clean stack on mobile devices.

## 📄 License
This project is open-source. Feel free to use, modify, and fork it for your own needs!

---
*Created with Passion by Vanguard Studios.*
