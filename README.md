# Pactus Wallet Deploy Repository

This repository contains production builds for [Pactus Wallet](https://github.com/pactus/pactus-wallet), automatically deployed from versioned releases.

## Purpose

- Hosts the production version at [wallet.pactus.org](https://wallet.pactus.org)
- Updated automatically when new tags are pushed to the main repository
- Serves as the GitHub Pages deployment target

## How It Works

1. When a new tag (vX.Y.Z) is created in the [main repository](https://github.com/pactus/pactus-wallet)
2. GitHub Actions builds the production artifacts
3. The built files are deployed to this repository's `gh-pages` branch

## Maintenance

- Do not manually edit files in this repository
- All changes should be made in the main repository
- Deployment is managed by GitHub Actions
