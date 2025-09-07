## Production
```bash
git add .
git commit -m ""
NUXT_APP_BASE_URL=/ npx nuxt build --preset github_pages
npx serve .output/public
npx gh-pages --dotfiles -d .output/public
```