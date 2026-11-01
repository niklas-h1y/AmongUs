# Among Us — Space Imposter

A browser-based multiplayer social deduction game.

## Play

Once GitHub Pages is enabled and the deployment workflow has completed:

**https://niklas-h1y.github.io/AmongUs/**

## Publishing

This repository includes `.github/workflows/deploy-pages.yml`, which deploys the repository root to GitHub Pages whenever code is pushed to `main`.

In the repository settings, open **Settings → Pages → Build and deployment** and set **Source** to **GitHub Actions**. The first deployment will then run automatically after a push to `main`. You can also start it manually from the **Actions** tab using **Deploy Among Us to GitHub Pages**.

The game entry point is `index.html`. Static files in the repository root are uploaded as the Pages site.

## Development

Open `index.html` in a modern browser for local testing. The online lobby currently uses PeerJS for peer-to-peer connections.
