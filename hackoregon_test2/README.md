|
--------------------------------------------- |
hackoregon_test2 |

[![image](<https://badge.fury.io/py/>2019-test2-backend.svg)](<https://badge.fury.io/py/>2019-test2-backend)

[![image](<https://travis-ci.org/hackoregon/>2019-test2-backend.svg?branch=master)](<https://travis-ci.org/hackoregon/>2019-test2-backend)

testing cookiecutter

# Documentation

The full documentation is at <<http://hackoregon.github.io/>>2019-test2-backend

# Features

> -   TODO (add what your project does)

# Data Sources

# Quickstart to install package in your own Django Project (Non-Hack
Oregon Workflow)

Install hackoregon_test2:

> pip install hackoregon_test2

Add subpackages to your `INSTALLED_APPS`:

`` ` python INSTALLED_APPS = (     ...     'toad',     ... ) ```

Add hackoregon_test2's URL patterns:

`` ` python from hackoregon_test2.toad import urls as toad_urls   urlpatterns = [     ...     url(r'^', include(toad_urls)),     ... ] ```

Setup your database with a matching schema

Run the project

# Running Tests

This repo uses pytest and pytest-django to run tests.

For project development work, tests will be run in docker container
using the bin/test.sh script:

# Credits

Tools used in rendering this package:

> -   [Cookiecutter](<https://github.com/audreyr/cookiecutter>)
> -   [cookiecutter-djangopackage](<https://github.com/pydanny/cookiecutter-djangopackage>)
