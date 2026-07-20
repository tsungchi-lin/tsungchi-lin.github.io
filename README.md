# Tsung-Chi Lin — Personal Website

Static one-page academic website prepared for GitHub Pages.

## GitHub repository

Create a **public** repository with this exact name:

```text
tsungchi-lin.github.io
```

Then unzip this package and upload everything inside the folder to the repository root. The repository root should contain `index.html`, `CNAME`, `README.md`, and the `assets` folder directly—not another enclosing website folder.

## Publish with GitHub Pages

1. Open the repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, select **Deploy from a branch**.
4. Select the `main` branch and `/ (root)` folder.
5. Save and wait a few minutes.
6. Test the temporary address:

```text
https://tsungchi-lin.github.io/
```

## Custom domain

The included `CNAME` file is already configured for:

```text
www.lintsungchi.com
```

After the temporary GitHub Pages address works:

1. In **Settings → Pages → Custom domain**, enter `www.lintsungchi.com` and save.
2. At the current domain/DNS provider, point the `www` CNAME record to `tsungchi-lin.github.io`.
3. Configure the root domain `lintsungchi.com` according to GitHub Pages' current apex-domain instructions, or forward it to `www.lintsungchi.com`.
4. Wait for GitHub's DNS check to pass, then enable **Enforce HTTPS**.
5. Keep the Wix site active until both `lintsungchi.com` and `www.lintsungchi.com` open the GitHub-hosted site correctly.

## Editing the website

- Main page content and links: `index.html`
- Visual styling: `assets/css/styles.css`
- Profile image: `assets/images/profile.jpg`
- CV: `assets/files/Lin-CurriculumVitae.pdf`

## Preview locally

From the website folder, run:

```bash
python3 -m http.server 8000
```

Then open `http://localhost:8000` in a browser.
