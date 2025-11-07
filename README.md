# USAC recipes
This repository contains a site for sharing recipes among USAC members.
The recipes are subdivided into Cooking and Baking. Cooking recipes are mainly meant for meals on climbing weekends and baking recipes are mainly meant for the bake a cake task people get assigned during climbing weekends.

## Deployment
The site is deployed using GitHub Pages. To deploy the site, simply push to the `main` branch. GitHub Pages will automatically build and deploy the site.

## Contributing recipes
Contributing recipes is done through decap CMS. To contribute a recipe, follow these steps:
go to the [USAC recipes site](https://usac-recipes.github.io/), click on the "Admin" button in the bottom right corner, and log in using your credentials. Once logged in, you can add a new recipe by clicking on the "New Entry" button and filling out the form. After submitting the form, your recipe will be added to the site.

## Contributing to the code
To contribute to the code, fork the repository and create a new branch for your changes. Once you have made your changes, create a pull request to the `main` branch. Your changes will be reviewed and merged if approved.

## Tech stack
The site is built using [Hugo](https://gohugo.io/) and uses [Decap CMS](https://decapcms.org/) for content management. The site is hosted on GitHub Pages.
Deployment is automated using GitHub Actions. (hugo build and deploy action)
