## Hi there 👋

# Personal GitHub Homepage for BaoHeiLiao

This repository contains a simple, responsive personal GitHub homepage ready to be published with GitHub Pages. It includes a small HTML/CSS site you can customize quickly.

Contents
- index.html — the homepage
- assets/styles.css — styling for the site
- README.md — this file with publishing instructions

Quick preview
- Hero showing your GitHub avatar, name, short bio
- Projects section with links to your repositories (placeholders)
- Contact section with mailto and social links

How to publish (two easy ways)
1) Publish from the repository root (recommended)
- Commit the files to the default branch (usually `main` or `master`) at the repo root.
- In GitHub, go to Settings → Pages → Branch → select `main` (or your default), folder `/ (root)` and click Save.
- Your site will be available at `https://<your-username>.github.io/` (may take a minute).

2) Publish on a separate `gh-pages` branch
- Create and push a `gh-pages` branch containing the site files.
- In GitHub Settings → Pages → choose `gh-pages` branch, folder `/ (root)`.
- This is useful if you want the default branch for code and a separate branch for the site.

Customize
- Update the text in `index.html` (name, bio, projects, links).
- Replace the avatar by changing the <img> src to a hosted image (or keep `https://github.com/BaoHeiLiao.png`).
- Add or remove project cards in the Projects section; point href to specific repo URLs.

Optional extras
- Add a `CNAME` file if you have a custom domain (place your domain name inside it).
- Add GA/Matomo or privacy-friendly analytics scripts in index.html.
- Add more pages (blog, resume) and a navigation menu.

Deploy using git (example)
```bash
git clone https://github.com/BaoHeiLiao/BaoHeiLiao.git
cd BaoHeiLiao
# copy or edit files locally
git add .
git commit -m "Add GitHub Pages personal homepage"
git push origin main
```

Need help customizing colors, layout, or wiring up a blog? Tell me which direction you'd like (minimal, portfolio, blog, technical CV) and I'll update the templates.

<!--
**BaoHeiLiao/BaoHeiLiao** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

Here are some ideas to get you started:

- 🔭 I’m currently working on ...
- 🌱 I’m currently learning ...
- 👯 I’m looking to collaborate on ...
- 🤔 I’m looking for help with ...
- 💬 Ask me about ...
- 📫 How to reach me: ...
- 😄 Pronouns: ...
- ⚡ Fun fact: ...
-->
