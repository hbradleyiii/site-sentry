site_sentry
#########
A flask based centralized website access control system that helps to prevent unwanted bot activity.
==================================================

*This is a work in progress. Use at your own risk.*

``site_sentry`` is a `flask <http://flask.pocoo.org/>`_ based centralized
website access control system that can be used across multiple websites and web
applications that acts primarily as a gatekeeper. It can also be used to
prevent unwanted bot activity, such as, brute force and denial of service
attacks. This system is a "first line of defense" and assumes that your website
is already built with security in mind. Your website can use ``site_sentry``'s
`REST API <https://github.com/hbradleyiii/site_sentry#using-the-rest-api>`_ as a
full access control system, or ``site_sentry`` can compliment a website's
already existing access control system.




``site_sentry`` allows you to
`create rules <https://github.com/hbradleyiii/site_sentry#setting-up-rules>`_
based on your visitor's ip address, user agent, and/or access method. Rules can
be site-wide or page specific. They can do things like limit the number of
attempts on a login form and can temporarily (or permanently) ban IP addresses
that attempt to go over the limit. IP addresses can be manually whitelisted and
blacklisted.  Rules can be chained to create custom solutions for a balance of
security and user convenience. Because it is centralized, multiple websites can
use the same system which allows the system to more quickly and effectively
recognize and block malicious IP addresses.


Installing and Including in projects
====================================

Installing site_sentry
----------------------

.. code:: bash

    $ pip install site_sentry  # TODO: Does not work yet...

Setting up a dev environment.
-----------------------------

.. code:: bash

    $   # TODO:


Running Tests
-------------

.. code:: bash

    $ cd <site_sentry directory>
    $ py.test   # TODO: Does not work yet...

.. _rules:

Setting up Rules
================

TODO


.. _rest-api:

Using the REST API
==================

TODO


----

*Soli Deo gloria.*
