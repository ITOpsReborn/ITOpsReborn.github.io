# ITOpsReborn

Tim Knapp's personal landing page while the next chapter of ITOpsReborn takes shape.

A responsive, dependency-free static site built with HTML, CSS, and inline SVG. The light, Microsoft-inspired palette uses green as its primary accent. No build step, analytics, cookies, or third-party assets. Animation respects the visitor's reduced-motion preference.

## Preview

From the repository directory, run:

```sh
python3 -m http.server 8000
```

Open `http://localhost:8000`.

## Publish

To publish at <https://itopsreborn.github.io/>, open **Settings > Pages**, select **Deploy from a branch**, choose `copilot/itopsreborn-landing-page`, and select `/ (root)`.

The landing page is on this branch because repository rules restrict creation of `main`. GitHub Pages still needs to be enabled by an account with Pages administration access; the app used to create the site could push the branch but could not enable Pages.

## Update

- Edit `index.html` for copy and the LinkedIn and WordPress destinations.
- Edit `styles.css` for colors, layout, and motion.
- Edit `favicon.svg` for the browser icon.

The orbital illustration is decorative. All navigation uses ordinary links and works without JavaScript.
