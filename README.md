# Ryan S. Gladwin — Portfolio

A four-page journalism portfolio (Home, Writing, Video Content, Contact), forked from André Beganski's template and reskinned for Ryan.

## Files
- `index.html` — homepage with bio and beat grid
- `writing.html` — Cultural Profiles, Scoops, Wacky News, Original Reporting, Jargon-Free Explainers
- `video.html` — What's the Meta?, Interviews, Other Content
- `contact.html` — contact form (Formspree)
- `style.css` — shared stylesheet for all pages
- `headshot.jpg` — profile photo

## Publish it with GitHub Pages
1. Create a new GitHub repo. Naming it `ryansgladwin.github.io` gives you a clean root URL; any other name works too, it'll just live at `username.github.io/repo-name`.
2. Upload all the files in this folder to the repo (drag-and-drop on github.com works fine, or `git push`).
3. In the repo, go to **Settings → Pages**.
4. Under "Build and deployment," set Source to **Deploy from a branch**, branch `main`, folder `/ (root)`. Save.
5. Wait a minute or two, then visit the URL GitHub gives you.

## Before it's fully live
- **Writing samples**: `writing.html` has one placeholder card per category (dashed border, "Sample coming soon"). Swap in real headlines, links, and thumbnail images — instructions are in an HTML comment near the top of `<main>`.
- **Video content**: `video.html` has one placeholder per section. Swap the placeholder box for a real YouTube embed — instructions are in an HTML comment near the top of `<main>`.
- **Contact form**: go to [formspree.io](https://formspree.io), make a free account and a form, then replace `YOUR_FORM_ID` in `contact.html` with the ID it gives you. Until then the form won't actually send anywhere.
- **Resume**: not included yet — if you want a "Resume" link in the nav, upload a PDF and I can wire it in.
