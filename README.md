# hackoregon_test2

![PyPI version](https://badge.fury.io/py/2019-test2-backend.svg) | [![Build Status](https://travis-ci.org/hackoregon/2019-test2-backend.svg?branch=master)](https://travis-ci.org/hackoregon/2019-test2-backend)

testing cookiecutter

# Documentation

The full documentation is at http://hackoregon.github.io/2019-test2-backend


# Features

> -   TODO (add what your project does)

# Data Sources

This API package in this repo is based on the Data Science work in the following projects:

* [Name of repo where data science work is contained](cnn.com)

# Quickstart to install package in your own Django Project (Non-Hack Oregon Workflow)

* Install hackoregon_test2:  
  `pip install hackoregon_test2`

* Add subpackages to your `INSTALLED_APPS`:

  ```python
  INSTALLED_APPS = [     
                      ...     
                      'toad',     
                      ...
                    ]
  ```

* Add hackoregon_test2's URL patterns:

  ```python
  from hackoregon_test2.toad
  import urls as toad_urls   

  urlpatterns = [     
                  ...     
                  url(r'^', include(toad_urls)),     
                  ...
                ]
  ```

* Setup your database with a matching schema

* Run the project

# Running Tests

This repo uses pytest and pytest-django to run tests.

For project development work, tests will be run in docker container
using the bin/test.sh script:

# Credits

Tools used in rendering this package:

 * [Cookiecutter](https://github.com/audreyr/cookiecutter)
 * [cookiecutter-djangopackage](https://github.com/pydanny/cookiecutter-djangopackage)
