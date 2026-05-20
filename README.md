# WordCamp US 2025

This repo contains the remote CSS used for [WordCamp US 2025](https://us.wordcamp.org/2025/). It also serves as an issue tracker.

## Development

Any changes to the root `style.css` will automatically sync to the WordCamp site using Remote CSS.

Changes should be made in `css/style.css`, using [a branch workflow](https://docs.github.com/en/get-started/using-github/github-flow). Once merged, an automation will trigger to build the `/style.css` file (runs a linter, postcss, & autoprefixer).

You can run these locally with the following commands:

```
npm install
npm run lint
npm run build
```
