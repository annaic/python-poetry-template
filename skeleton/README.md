# ${{ values.serviceName }}

This is a template repository for Python projects that use Poetry for their dependency management.

- **Github repository**: <https://github.com/${{ values.destination.owner + "/" + values.destination.repo }}/>

## Getting started with your project

First, create a repository on GitHub with the same name as this project, and then run the following commands:

``` bash
git init -b main
git add .
git commit -m "init commit"
git remote add origin git@github.com:annaic/${{ values.serviceName }}.git
git push -u origin main
```

Finally, install the environment and the pre-commit hooks with

```bash
make install
```

You are now ready to start development on your project! The CI/CD
pipeline will be triggered when you open a pull request, merge to main,
or when you create a new release.
