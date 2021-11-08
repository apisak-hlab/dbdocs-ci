# dbdocs-ci

## Introduction

This tool is made for demonstatrating the integration between **dbdocs** cli and **github action** for automation purpose.
What this tools do is scan all file that ends with `.dbml` and automatically host on dbdocs.

## Prerequisites
In order to use this tools, you need to go to settings in your repository and add new repository secret with these following variables.

- `DBDOCS_TOKEN` Required for hosting dbml on dbdocs site, you can get it by running this command `dbdocs token -g`
- `DBDOCS_PASSWORD` Required for protecting your dbml file with password.

If nothing went wrong, once you've pushed your dbml file. It should log something like this.

```✔ Done. Visit: https://dbdocs.io/xxx/project-name```
