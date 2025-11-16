# USAC recipes
This repository contains a site for sharing recipes among USAC members.
The recipes are subdivided into Cooking and Baking. Cooking recipes are mainly meant for meals on climbing weekends and baking recipes are mainly meant for the bake a cake task people get assigned during climbing weekends.

## Deployment
The site is deployed using GitHub Pages as preview and to netlify for prod. To deploy the site, simply push to the `main` branch. GitHub Pages will automatically build and deploy the site and every few days the `deploy` branch will be reset to the `main` branch and thus deploying on netlify.

## Contributing recipes
Contributing recipes is done through decap CMS. To contribute a recipe, follow these steps:
go to the [USAC recipes prod site](https://usac-recipes.netlify.app/), click on the "Admin" button in the top right corner, and log in using your credentials. Once logged in, you can add a new recipe by clicking on the "New Entry" button and filling out the form. After submitting the form, your recipe will be added to the `main` branch, which can then be viewed on the [USAC recipes dev site](https://spacekek.github.io/usac_recepten/).

## Contributing to the code
To contribute to the code, fork the repository and create a new branch for your changes. Once you have made your changes, create a pull request to the `main` branch. Your changes will be reviewed and merged if approved.

## Tech stack
The site is built using [Hugo](https://gohugo.io/) and uses [Decap CMS](https://decapcms.org/) for content management. The site is hosted on GitHub Pages for development and netlify for production.
Deployment is automated using GitHub Actions for pages and netlify. (hugo build and deploy action)

The split between github pages and netlify is due to the decap cms, this needs a login (and thus some sort of backend), netlify provides this but only has limited deployments per month.
