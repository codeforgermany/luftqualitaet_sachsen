************
Installation
************

Development Setup
=================

Install the packages for development::

    $ make install-dev

And install the frontend dependencies using `Bower <http://bower.io/>`_::

    $ bower install

Then create the new PostgreSQL user and database::

    $ make create-db

Now create the database tables::

    $ make migrate

And start the development webserver::

    $ make runserver

To see the other targets available in the ``Makefile`` simply run::

    $ make
