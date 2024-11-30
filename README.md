# Blextra Starter Template

[![Deploy Hugo site to Pages](https://github.com/BlackTechX011/Blextra-starter-template/actions/workflows/pages.yaml/badge.svg)](https://github.com/BlackTechX011/Blextra-starter-template/actions/workflows/pages.yaml)
[![Netlify Status](https://api.netlify.com/api/v1/badges/6e83fd88-5ffe-4808-9689-c0f3b100bfe3/deploy-status)](https://app.netlify.com/sites/Blextra-starter-template/deploys)
![Vercel Deployment Status](https://img.shields.io/github/deployments/BlackTechX011/Blextra-starter-template/production?logo=vercel&logoColor=white&label=vercel&labelColor=black&link=https%3A%2F%2FBlextra-starter-template.vercel.app%2F)


🐣 Minimal template for getting started with [Blextra](https://github.com/BlackTechX011/Blextra)


[🌐 Demo ↗](https://imfing.github.io/Blextra-starter-template/)

## Quick Start

Use this template to create your own repository:


## Deployment

### GitHub Pages

A GitHub Actions workflow is provided in [`.github/workflows/pages.yaml`](./.github/workflows/pages.yaml) to [publish to GitHub Pages](https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/) for free. 

For details, see [Publishing with a custom GitHub Actions workflow](https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site#publishing-with-a-custom-github-actions-workflow).

Note: in the settings, make sure to set the Pages deployment source to **GitHub Actions**:



[Run the workflow manually](https://docs.github.com/en/actions/using-workflows/manually-running-a-workflow) if it's not triggered automatically.


## Local Development

Pre-requisites: [Hugo](https://gohugo.io/getting-started/installing/), [Go](https://golang.org/doc/install) and [Git](https://git-scm.com)

```shell
# Clone the repo
git clone https://github.com/BlackTechX011/Blextra-starter-template.git

# Change directory
cd Blextra-starter-template

# Start the server
hugo mod tidy
hugo server --logLevel debug --disableFastRender -p 1313
```

### Update theme

```shell
hugo mod get -u
hugo mod tidy
```

See [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules) for more details.

