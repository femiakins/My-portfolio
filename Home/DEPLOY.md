# Deploy to GitHub Pages

1. Replace the `homepage` field in `package.json` with your GitHub Pages URL, e.g. `https://your-username.github.io/your-repo`.
2. Commit and push this repository to GitHub.
3. Install the deploy dependency locally:

```powershell
npm install --save-dev gh-pages
```

4. Run the deploy script:

```powershell
npm run deploy
```

This will publish the contents of the `docs/` folder to the `gh-pages` branch and make the site available at your `homepage` URL.
