
# Blextra Starter Template

🐣 A minimal starter template to quickly set up your site with the [Blextra](https://github.com/BlackTechX011/Blextra) Hugo theme.

[🌐 Live Demo ↗](https://BlackTechX011.github.io/Blextra-starter-template/)

---

## Quick Start

To quickly get started with Blextra, simply create a new repository based on this template:

1. **Use this repository as a template**  
   Click the "Use this template" button at the top of the repository to create your own copy.

2. **Clone your new repository**  
   After creating your own repo, clone it to your local machine:
   ```bash
   git clone https://github.com/yourusername/your-repository-name.git
   ```

3. **Start building your website**  
   You can now begin customizing the content, themes, and structure of your website with Blextra!

---

## Deployment

### GitHub Pages

This template includes a pre-configured GitHub Actions workflow in `.github/workflows/pages.yaml` to automatically deploy your website to GitHub Pages. Here’s how to set it up:

1. **Set up GitHub Pages deployment**  
   Ensure that GitHub Pages is set as the deployment source:
   - Navigate to your repository's **Settings** tab.
   - Under the **Pages** section, choose **GitHub Actions** as the source.

2. **Run the workflow**  
   If the workflow does not trigger automatically, you can manually run it:
   - [Run the workflow manually](https://docs.github.com/en/actions/using-workflows/manually-running-a-workflow).

For more details on configuring GitHub Pages with a custom GitHub Actions workflow, check out [GitHub Pages with custom workflows](https://github.blog/changelog/2022-07-27-github-pages-custom-github-actions-workflows-beta/).

---

## Local Development

Before starting, ensure that you have the following installed:

- [Hugo](https://gohugo.io/getting-started/installing/)
- [Go](https://golang.org/doc/install)
- [Git](https://git-scm.com)

Once you have everything set up, follow these steps:

1. **Clone the repository**  
   Clone the starter template to your local machine:
   ```bash
   git clone https://github.com/BlackTechX011/Blextra-starter-template.git
   ```

2. **Navigate to the project directory**  
   Move into the project folder:
   ```bash
   cd Blextra-starter-template
   ```

3. **Start the Hugo server**  
   Run the Hugo server to preview your site:
   ```bash
   hugo mod tidy
   hugo server --logLevel debug --disableFastRender -p 1313
   ```
   Your site will be accessible at `http://localhost:1313`.

---

## Updating the Theme

To update the Blextra theme or any other Hugo modules, run the following commands:

1. **Update Hugo modules**  
   ```bash
   hugo mod get -u
   hugo mod tidy
   ```

2. **Check the Hugo documentation**  
   For more information on updating modules, see [Update modules](https://gohugo.io/hugo-modules/use-modules/#update-modules).

---

## License

This repository is licensed under the MIT License. See [LICENSE](LICENSE) for more details.

