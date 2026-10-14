# Vercel setup notes

If you want preview deployments and a global CDN, Vercel is a great free option.

Steps:
1. Sign in to Vercel with your GitHub account.
2. Import the repository `zezomedhat2007-ship-it/ziadmedhat-portfolio`.
3. Framework Preset: Other (Static). Leave Build Command empty. Output Directory: `./`.
4. Click Deploy. Vercel will create a preview deployment for every branch and a production URL for the main branch.
5. If you need a custom domain, add it in Vercel project settings and follow the DNS instructions.

Notes:
- No additional code changes are required — the repo is static and will deploy as-is.
