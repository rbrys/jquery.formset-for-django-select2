The django-select2(https://github.com/applegrew/django-select2) is a great django(https://www.djangoproject.com/) application that integrates django with select2(http://ivaynberg.github.io/select2/).

But it not work with formsets(checked in July, 2014).
https://github.com/applegrew/django-select2/issues/109

I changed the jquery.formset.js file to deal with that situation.

The result is the jquery.formset-for-django-select2.min.js.
This file has to be used in substitution of the default jquery.formset.js file in templates that uses formsets with a django-select2 field.
