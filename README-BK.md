# Bulent's Notes

## Deployment

See https://docusaurus.io/docs/deployment for deploying to GitHub Pages (and other hosting providers).

Building with **yarn** caused problems in GitHub Actions, so I switched to use of **npm** instead. Also removed all yarn artefacts from git.

Yarn is still useful for building the website and pushing to the `gh-pages` branch.

```
corepack enable
yarn install
$ GIT_USER=<GitHub username> yarn deploy
```
