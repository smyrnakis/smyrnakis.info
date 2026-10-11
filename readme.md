# smyrnakis.info

Source code for [smyrnakis.info](https://smyrnakis.info), my personal website and project portfolio.

The site is a customized version of the [Spectral](https://html5up.net/spectral) template by [HTML5 UP](https://html5up.net/). It is a static website built with HTML, CSS, Sass, and JavaScript.

## Repository structure

- `index.html` contains the website content and page structure.
- `assets/` contains the stylesheets, Sass sources, JavaScript, fonts, and theme assets.
- `images/` contains the photographs, project images, logos, book covers, and favicon files.
- `legacy/` contains old HTML5 UP example pages retained for reference. Excluded from Cloudflare deployment through `.assetsignore`.

## Local development

No package installation or build step is required.

For normal content and styling changes, open `index.html` directly in a browser, edit the files, save, and refresh the page.

Optionally, use a local static server when you want behavior closer to the deployed website:

```powershell
python -m http.server 8000
```

## Deployment

The `master` branch is connected to Cloudflare Workers Static Assets. A push to `master` triggers an automatic deployment to the production website.

- Production domain: [smyrnakis.info](https://smyrnakis.info)
- `www.smyrnakis.info` redirects to the root domain.
- Files matched by `.assetsignore` remain in Git but are not published.

## Historical branches

Older template and layout work remains available in the `oldTemplate`, `newTemplate`, and other historical branches. The active website is maintained on `master`.

## Credits and license

- Design: [Spectral by HTML5 UP](https://html5up.net/spectral)
- Icons: [Font Awesome](https://fontawesome.com/)
- JavaScript libraries: [jQuery](https://jquery.com/) and [Scrollex](https://github.com/ajlkn/jquery.scrollex)

The original HTML5 UP template is distributed under the [Creative Commons Attribution 3.0 Unported license](LICENSE.txt).
