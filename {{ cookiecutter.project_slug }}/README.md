# {{ cookiecutter.project_name }}

Start of a Django project that implements a number of initial design decisions, security settings and 
project structure.

* Uses argon2 for more secure password hashing.
* Implements a custom user model in an `accounts` app.
* Uses an initial folder structure that places settings and base URL configuration in a `common` package instead of 
  naming it after the project.
* Includes a number of settings needed for secure deployment.
* Includes the Django Debug Toolbar when running with `DEBUG=True`

## Design Decisions

* [Use argon2 for password hashing](https://docs.djangoproject.com/en/5.0/topics/auth/passwords/#using-argon2-with-django)

It's more secure than the defaults but requires an extra package.

* [Implement a custom user model](https://docs.djangoproject.com/en/5.0/topics/auth/customizing/#using-a-custom-user-model-when-starting-a-project)

Start off with the flexibility to use a custom user model from the start.

* Project Structure

```
something
```

* Assumes the use of a PostgreSQL database

author: {{ cookiecutter.author }}
