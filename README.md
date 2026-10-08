# CE Portfolio

A computer-engineering themed resume and project site (circuit board + datasheet). Plain HTML, CSS and JavaScript, so there is no build step.

## Edit your content
Open `index.html` and change the `DATA` block near the bottom. Everything on the site comes from it.
Put your resume PDF next to `index.html` and name it `resume.pdf`.

## Preview locally
Open `index.html` in a browser, or run `npx serve` in this folder.

## Deploy to GitHub Pages
1. Create a new GitHub repo and push these files to the `main` branch.
2. In the repo, go to Settings > Pages.
3. Under "Build and deployment", choose "Deploy from a branch", select `main` and `/ (root)`, then Save.
4. Your site appears at `https://<username>.github.io/<repo>/` after a minute or two.

## Import into Vercel
1. Sign in at vercel.com with GitHub and click Add New > Project.
2. Import the same repo.
3. Framework Preset: Other. Leave Build Command and Output Directory empty.
4. Click Deploy. Every push to `main` redeploys automatically.
5. Optional: add a custom domain under Project > Settings > Domains.
