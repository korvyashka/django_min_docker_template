Custom Django docker minimal template
==============================

Minimal django template, based on http://cookiecutter-django.readthedocs.org/en/latest/settings.html
Have only basic apps and settings needed for minimal setup of django on docker-compose:

 - Nginx
 - Whitenoise for handling static
 - Postgres
 - Several contrib django apps like auth, admin, etc.


Basic Commands
--------------

Setting Up Your Users
^^^^^^^^^^^^^^^^^^^^^

    $ python manage.py createsuperuser

#TODO
 - Setup basic test env.
 - Live reloading and saas


Deployment
----------


Docker
^^^^^^

See detailed `cookiecutter-django Docker documentation`_.

.. _`cookiecutter-django Docker documentation`: http://cookiecutter-django.readthedocs.org/en/latest/deployment-with-docker.html
