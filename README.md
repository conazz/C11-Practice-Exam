# C11 Practice Exam — GitHub Pages setup

This folder has one file you need: **index.html**. It's the whole app — questions, styling, and all the app logic are built into that single file, so there's nothing else to upload.

## How to put it live on GitHub Pages

1. Go to github.com and log in, then click the **+** icon (top right) → **New repository**.
2. Name it something like `C11-Practice-Exam`, set it to **Public**, and click **Create repository**.
3. On the new repo's page, click **Add file → Upload files**.
4. Drag in `index.html` from this folder, then click **Commit changes**.
5. Go to the repo's **Settings** tab → **Pages** (left sidebar).
6. Under "Build and deployment", set **Source** to **Deploy from a branch**, pick branch **main** and folder **/ (root)**, then click **Save**.
7. Wait a minute or two, then refresh that Pages settings page — it will show your live link, something like:
   `https://<your-github-username>.github.io/C11-Practice-Exam/`

That link is what you share with people, bookmark, or use yourself from any device with a browser.

## Notes

- **Favorites** (the ★ you tap while reviewing) are saved in the browser you use to open the page. If you open the link on your phone and on your laptop, each keeps its own separate favorites list — they don't sync between devices.
- Updating the quiz later is the same drag-and-drop: replace `index.html` in the repo (**Add file → Upload files**, same name, it'll ask to overwrite) and GitHub Pages updates automatically within a minute or two.
- No build steps, no dependencies to install — it's a plain HTML file the browser reads directly.
