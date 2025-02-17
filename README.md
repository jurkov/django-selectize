![PyPI](https://img.shields.io/pypi/v/django-selectize)
![PyPI - Python Version](https://img.shields.io/pypi/pyversions/django-selectize)
![PyPI - Downloads](https://img.shields.io/pypi/dm/django-selectize)
![GitHub contributors](https://img.shields.io/github/contributors/djangoer/django-selectize)
![GitHub last commit](https://img.shields.io/github/last-commit/djangoer/django-selectize)
   
> **Note**
> Note: This is only in Developing stage Now.

django-selectize  is a Django app based on Selectize.js that help you to create Select and Multiselect widgets in Django forms.


Requirements
------------

* Django


Installing django-selectize
---------------------------

There are several ways to install django-selectize:

* Automatically, via a package manager: `pip install django-selectize`
* Download a release package then unzip and run `python setup.py install` to install it into your python directory.
* If you don't like to install then download a release package, unzip and copy the folder `selectize` to your Django-project directory.


Required settings
-----------------

Begin by adding `selectize` to the `INSTALLED_APPS` setting of your project. For example, you might have something like the following in your Django settings file:

	INSTALLED_APPS = (
	    'django.contrib...',
	    'django.contrib....',
	    'selectize',
	    # ...other installed applications...
	)

**Note:** you must place `selectize` above other installed applications.

Usage
-----

Please run the demo project located at https://github.com/djangoer/django-selectize/tree/master/demo

For testing
-----------
You need to install Selenium:

    pip install selenium

Run the tests:

    ./manage.py test
