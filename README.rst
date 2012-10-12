=====================
django_localflavor_cz
=====================

Country-specific Django helpers for the Czech Republic.

What's in the Czech localflavor?
================================

* CZPostalCodeField: A form field that validates input as a Czech postal code.
  Valid formats are XXXXX or XXX XX, where X is a digit.

* CZBirthNumberField: A form field that validates input as a Czech Birth
  Number. A valid number must be in format XXXXXX/XXXX (slash is optional).

* CZICNumberField: A form field that validates input as a Czech IC number
  field.

* CZRegionSelect: A ``Select`` widget that uses a list of Czech regions as its
  choices.

See the source code for full details.

About localflavors
==================

Django's "localflavor" packages offer additional functionality for particular
countries or cultures.

For example, these might include form fields for your country's postal codes,
phone number formats or government ID numbers.

This code used to live in Django proper -- in django.contrib.localflavor -- but
was separated into standalone packages in Django 1.5 to keep the framework's
core clean.

For a full list of available localflavors, see https://github.com/django/
