# Running your portfolio on localhost

You only have one file: `index.html`. No build step, no npm install.

**Option 1 — just double-click it.** It'll open in your browser directly. Everything (animations, fonts) still works.

**Option 2 — real localhost (recommended, avoids any browser file-permission quirks):**

Open a terminal in this folder and run one of these:

```bash
# Python (most machines already have this)
python3 -m http.server 5500

# Node
npx serve .
```

Then visit **http://localhost:5500** in your browser.

## Making it live on the internet (free)
When you're ready to share a real link with recruiters instead of a local one:
- **GitHub Pages** — push this folder to a GitHub repo, enable Pages in repo settings. Free, and the URL doubles as proof you know Git.
- **Netlify / Vercel** — drag-and-drop the folder in their dashboard, get a live URL in ~30 seconds.

## Editing it
Everything is in `index.html` — one CSS block at the top, content in the middle, one JS block at the bottom. Search for a section heading (e.g. `id="projects"`) to find where to edit.
