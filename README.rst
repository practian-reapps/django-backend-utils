########################################
Django backend_utils
########################################

.. class:: no-web

    Django backend_utils es una manera fácil de extender la clase ``AbstractUser`` de `Django`_ y define un modelo de *autenticación/autorización* para **aplicaciones SaaS** para los proyectos de `Django`_.




.. contents::

.. section-numbering::

.. raw:: pdf

   PageBreak oneColumn


============
Installation
============


-------------------
Development version
-------------------

The **latest development version** can be installed directly from github_:

.. code-block:: bash
    
    # Universal
    $ pip install --upgrade https://github.com/practian-reapps/django-backend-utils/raw/master/dist/django-backend-utils-0.1.zip

or clone from github_:

.. code-block:: bash

    $ git clone https://github.com/practian-reapps/django-backend-utils.git

(If ``pip`` installation fails for some reason, you can try ``easy_install`` as a fallback.)


--------------
Python version
--------------

Python 3.4.4 is recommended to install Django backend_utils


=====
Usage
=====


Quick start
-----------

1. Add "backend_utils" to your INSTALLED_APPS setting like this::

    INSTALLED_APPS = [
        ...

        'backend_utils',
    ]



.. _Django OAuth Toolkit: https://django-oauth-toolkit.readthedocs.io
.. _Django: https://www.djangoproject.com
.. _github: https://github.com/practian-reapps/django-backend-utils
