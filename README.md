# My first project 🌱

A personal portfolio / link page — built as a first GitHub project. It's a single `index.html` file, no build tools or installs needed, and it's ready to edit and publish.

## What's in here

- `index.html` — the whole site: structure, styling, and a tiny bit of script, all in one file so it's easy to understand and edit.

## 1. Customize it

Open `index.html` in any text editor (Notepad, VS Code, even GitHub's own editor in the browser). Look for text in square brackets like `[Your Name]` and replace each one with your own details:

- Your name and a short tagline in the hero section
- A couple of sentences about yourself in the "About me" section
- Your real projects (or delete/duplicate the project cards as needed)
- Your actual email, GitHub, and LinkedIn links in the "Find me elsewhere" section

That's it — no coding knowledge required to personalize it, though feel free to tweak colors or wording if you want to experiment.

## 2. Preview it locally

Just double-click `index.html` and it'll open in your browser. Edit, save, refresh — repeat until you're happy with it.

## 3. Push it to GitHub

**Option A — no command line, all in the browser:**

1. Go to [github.com](https://github.com) and log in.
2. Click the **+** icon (top right) → **New repository**.
3. Name it something like `my-portfolio`, choose Public, and click **Create repository**.
4. Click **Add file → Upload files**, drag in `index.html`, write a short commit message like "First commit — my portfolio", and click **Commit changes**.

**Option B — using git from your computer:**

```bash
cd path/to/first-github-project
git init
git add .
git commit -m "First commit — my portfolio"
git branch -M main
git remote add origin https://github.com/yourusername/my-portfolio.git
git push -u origin main
```

(Replace `yourusername` and `my-portfolio` with your actual GitHub username and repo name.)

## 4. Publish it as a live website (optional but fun)

GitHub can host this for free:

1. In your repo, go to **Settings → Pages**.
2. Under "Build and deployment", set **Source** to `Deploy from a branch`, branch `main`, folder `/ (root)`.
3. Save. After a minute or two, your site will be live at `https://yourusername.github.io/my-portfolio/`.

## Notes

- Everything is self-contained — no dependencies to install, no build step.
- Fonts (Fraunces, Space Grotesk, IBM Plex Mono) load from Google Fonts automatically.
- The little sprout animation in the hero respects users' reduced-motion settings.
