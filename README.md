# Summary

Cookiecutter for the start of a Django project.  Implements a number of initial design decisions, security settings and 
project structure.

* Uses argon2 for more secure password hashing.
* Implements a custom user model in an `accounts` app.
* Uses an initial folder structure that places settings and base URL configuration in a `common` package instead of 
  naming it after the project.
* Includes a number of settings needed for secure deployment.

## Usage

```shell
cookiecutter https://github.com/Utegrad/cookiecutter-django-revised.git
```

