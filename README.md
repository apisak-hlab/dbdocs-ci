# dbdocs-ci

## Introduction

This tool is made for demonstrating the integration between **Dbdocs** CLI and **Github Action** for automation purposes.
What these tools do is scan all file that ends with `.dbml` and automatically host on Dbdocs.

## Prerequisites
To use these tools, you need to go to settings in your repository and add a new repository secret with the following variables.

- `DBDOCS_TOKEN` Required for hosting dbml on Dbdocs site, you can get it by running this command `dbdocs token -g`
- `DBDOCS_PASSWORD` Required for protecting your dbml file with password.

If nothing went wrong, once you've pushed your dbml file. It should log something like this.

```✔ Done. Visit: https://dbdocs.io/xxx/project-name```
