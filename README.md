# Vishnu R N — Portfolio Website

A single-page, dark/techy developer portfolio built with plain HTML, CSS and JavaScript
(no frameworks, no build step) — so it publishes straight to **GitHub Pages for free**.

## Files

- `index.html` — page content
- `style.css` — styling (dark theme, responsive)
- `script.js` — mobile nav + scroll-reveal animation
- `resume.pdf` — downloadable résumé (linked from the hero section)

## Preview locally

Just double-click `index.html` to open it in your browser — no server needed.

## Publish for free on GitHub Pages

1. **Create a GitHub account** at https://github.com if you don't have one.
2. **Create a new repository.**
   - Click the **+** icon (top right) → **New repository**.
   - Name it `your-username.github.io` (replace `your-username` with your actual GitHub
     username, e.g. `eranavishnu.github.io`) — this exact naming publishes it at the root
     of your GitHub Pages domain. You can also use any other repo name (e.g. `portfolio`);
     it'll just publish at `your-username.github.io/portfolio` instead.
   - Set it to **Public**, then click **Create repository**.
3. **Upload the files.**
   - On the new repo page, click **uploading an existing file**.
   - Drag in `index.html`, `style.css`, `script.js`, and `resume.pdf`.
   - Scroll down and click **Commit changes**.
4. **Turn on GitHub Pages.**
   - Go to the repo's **Settings** tab → **Pages** (left sidebar).
   - Under **Build and deployment → Source**, choose **Deploy from a branch**.
   - Under **Branch**, select `main` and folder `/ (root)`, then **Save**.
5. **Wait ~1 minute**, then refresh that Pages settings page — it'll show your live URL:
   - `https://your-username.github.io/` (if you used the `.github.io` repo name), or
   - `https://your-username.github.io/your-repo-name/` otherwise.

That's it — the site is live and free, with free HTTPS included. Every time you upload a
changed file and commit, the live site updates automatically within a minute or two.

## Making edits later

- **Small text changes** (bio, skills, links): edit `index.html` directly on GitHub
  (click the pencil icon on the file) or locally in any text editor, then re-upload/commit.
- **Colors/theme**: tweak the CSS variables at the top of `style.css` (`--bg`, `--accent`, etc.).
- **New projects**: copy one `<article class="project-card">...</article>` block in the
  Projects section of `index.html` and edit its content.

## Optional: custom domain

If you buy a domain later, add a `CNAME` file to the repo containing just your domain
name, then set it under **Settings → Pages → Custom domain**. GitHub's docs walk through
the DNS records: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site
