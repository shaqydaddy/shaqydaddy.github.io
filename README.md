# Shaquille Ngadimin — Portfolio

Personal / Quille Designs portfolio site. Pure HTML, CSS, and JavaScript — no build step, no dependencies.

## Structure

```
css/       main.css (shared) + about.css, work.css, contact.css (page-specific)
img/       profile photo, favicon, project thumbnails
js/        main.js (nav, language toggle, form, filters), translations.js (NL/EN copy)
videos/    compressed project videos
index.html, about.html, work.html, contact.html
```

All links between pages use relative paths, so the site works from any host or directly from the file system.

## Running locally

Just open `index.html` in a browser, or serve the folder with any static server, e.g.:

```
npx serve .
```

## Deploying for free (GitHub Pages)

1. Create a new GitHub repository and push this folder's contents to it.
2. In the repo, go to **Settings → Pages**.
3. Under **Build and deployment**, set **Source** to `Deploy from a branch`, pick the `main` branch and `/ (root)` folder, then save.
4. GitHub gives you a public URL like `https://<username>.github.io/<repo-name>/` within a minute or two.

Alternative free hosts that work the same way with zero config: **Netlify** (drag-and-drop the folder onto app.netlify.com/drop) or **Vercel**.

## Notes

- The language toggle (NL/EN) switches all text in place — no page reload, no cookies.
- The contact form has no backend; submitting it opens the visitor's email client with the message pre-filled, addressed to quilledesigns.sv@gmail.com.
- Videos were compressed from the original phone exports (100–175MB each) down to 5–7MB each so the repo stays lightweight and pages load quickly.
