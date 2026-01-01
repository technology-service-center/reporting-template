# Report Template

A template for creating report made with Quarto.

Public link to the report: https://technology-service-center.github.io/reporting-template/

## Getting Started

1. Install [Quarto CLI](https://quarto.org/docs/get-started/)
2. To edit the pages, modified the `.qmd` files. Edit `_quarto.yml` to change the layout of the website.

## Running Website Locally

Use the following command to run the website on your local device:

```
quarto preview
```

## Publicly Deploying the Website

1. Run the `quarto render` to render your website in the `/docs` folder.
2. Go to your repository setting > Pages. Under the "Build and deployment" section, select `Deploy from a branch` and set the branch to `/docs` folder.

## Resources

- [Quarto: Creating a Website](https://quarto.org/docs/websites/)
- [Github Docs: Markdown Syntax](https://docs.github.com/en/get-started/writing-on-github/getting-started-with-writing-and-formatting-on-github/basic-writing-and-formatting-syntax)
- [Quarto: Github Pages](https://quarto.org/docs/publishing/github-pages.html)
