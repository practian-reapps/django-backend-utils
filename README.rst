########################################
backend_utils
########################################

.. class:: no-web

    backend_utils provee componentes para aplicaciones `Django`_ y `Django REST Framework`_ como paginación personalizada, permisos y logs.




    .. image:: https://github.com/practian-reapps/django-oauth2-backend/blob/master/docs/media/a1-ejemplo_de_arquitectura_de_micoserviciosx.png
        :alt: backend_utils
        :width: 100%
        :align: center



.. contents::

.. section-numbering::

.. raw:: pdf

   PageBreak oneColumn


============
Installation
============

--------------
Requirements
--------------

* Python 3.4, 3.5
* Django 1.9, 1.10
* DRF 3.4, 3.5


-------------------
Development version
-------------------


The **latest development version** can be installed directly from github_:

.. code-block:: bash
    
    # De preferencia, trabaje dentro de un virtualenv
    # Universal
    $ pip install --upgrade https://github.com/practian-reapps/django-backend-utils/raw/master/dist/django-backend-utils-0.1.zip

or clone from github_:

.. code-block:: bash

    $ git clone https://github.com/practian-reapps/django-backend-utils.git

(If ``pip`` installation fails for some reason, you can try ``easy_install`` as a fallback.)



Add "backend_utils" to your INSTALLED_APPS setting like this:

.. code-block:: bash

    INSTALLED_APPS = [
        ...

        'backend_utils',
    ]



====
Meta
====

----------
Change log
----------

See `CHANGELOG <https://github.com/practian-reapps/django-backend-utils/blob/master/CHANGELOG.rst>`_.


-------
Licence
-------

BSD-3-Clause: `LICENSE <https://github.com/practian-reapps/django-backend-utils/blob/master/LICENSE>`_.



-------
Authors
-------

- Angel Sullon Macalupu (asullom@gmail.com)



-------
Contributors
-------

See https://github.com/practian-reapps/django-backend-utils/graphs/contributors

.. _github: https://github.com/practian-reapps/django-backend-utils
.. _Django: https://www.djangoproject.com
.. _Django REST Framework: http://www.django-rest-framework.org
.. _Django OAuth Toolkit: https://django-oauth-toolkit.readthedocs.io
.. _oauth2_backend: https://github.com/practian-reapps/django-oauth2-backend
.. _Authorization server: https://github.com/practian-ioteca-project/oauth2_backend_service







