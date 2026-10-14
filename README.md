# ziadmedhat-portfolio

Personal portfolio for Ziad Medhat (Zaid) — Electronics & Communications Engineer. This repo is presentation-ready and tailored for industrial/Siemens audiences.

Contents
- `index.html` — landing page (hero, projects, contact)
- `styles.css` — styling
- `cv.html` — one-page CV (print to PDF if needed)
- `cv.pdf` — one-page CV (downloadable)
- `cover_email.txt` — suggested cover email for Siemens

Quick links
- Live preview (after enabling Pages): `https://<your-username>.github.io/ziadmedhat-portfolio/`
- CV raw: `https://raw.githubusercontent.com/zezomedhat2007-ship-it/ziadmedhat-portfolio/main/cv.pdf`

Publish (GitHub Pages)
1. Go to the repo on GitHub: https://github.com/zezomedhat2007-ship-it/ziadmedhat-portfolio
2. Settings → Pages → Source → Branch: `main`, Folder: `/ (root)` → Save
3. Wait ~1–2 minutes, the Pages URL appears in the Pages settings.

Deploy with Vercel (optional, gives previews + CDN)
1. Sign in to https://vercel.com with GitHub.
2. Import Project → select `zezomedhat2007-ship-it/ziadmedhat-portfolio`.
3. Framework: Other (Static). Build command: leave blank. Output directory: `./`.
4. Deploy. Vercel gives a preview URL immediately.

Local preview
```bash
python3 -m http.server 8000
# open http://localhost:8000
```

How to add a demo video (recommended)
1. Add a short, muted MP4 (30–60s) named `assets/demo.mp4`.
2. Edit `index.html` project card and replace the placeholder link with:
```html
<video controls muted playsinline width="560">
  <source src="assets/demo.mp4" type="video/mp4">
  Your browser does not support the video tag.
</video>
```
3. Commit and push. It will be served from Pages/Vercel.

Adding a custom domain (CNAME)
1. If you own a domain, add a `CNAME` file at the repo root containing your domain (e.g. `ziad.example.com`).
2. In your DNS provider, add either an ALIAS/ANAME or CNAME record as GitHub Pages docs recommend. See: https://docs.github.com/en/pages/configuring-a-custom-domain-for-your-github-pages-site

Need me to do additional commits
- I can embed your demo video if you upload it here, or give me a public URL and I'll add an embedded player.
- If you provide a custom domain, I can add the `CNAME` file and verify records.
