LegGoogleChartsBundle
=====================

> **Note**:
> The GoogleChartsImage API is now obsolete and I am writing a new version of the bundle, based on Google Charts
> tools (in Javascript), the official and LTS API. Therefore, you can use this bundle, but its development is stopped. 

What is LegGoogleChartsBundle ?
-------------------------------

LegGoogleChartsBundle is a bundle for the PHP 5.3 framework Symfony2.
It allows developers to use easily the Google Charts API with PHP classes.
It is fully tested with the PHPUnit framework.

Features include:

- Charts Gallery to create charts very easily
- Charts models support : create charts is simplified by the externalisation of the code
- Drivers system to add your own charts files formats
- CacheEngine to very easily use cache on your charts
- Unit tested

**Note:** This bundle does *not* create images alone : it use GoogleChartsImage tool.
Therefore you can not display charts without an active internet connection.

[![Build Status](https://secure.travis-ci.org/tgalopin/LegGoogleChartsBundle.png?branch=master)](http://travis-ci.org/tgalopin/LegGoogleChartsBundle)

Documentation
-------------

The bulk of the documentation is stored in the `Resources/doc/index.md` file in this bundle:

[Read the Documentation](https://github.com/tgalopin/LegGoogleChartsBundle/blob/master/Resources/doc/01 - Getting Started.md)

Installation
------------

All the installation instructions are located in [documentation](https://github.com/tgalopin/LegGoogleChartsBundle/blob/master/Resources/doc/01 - Getting Started.md).

License
-------

This bundle is under the Creative Commons BY-NC 3.0 license. See the complete license in the bundle: [Resources/meta/LICENSE.md](https://github.com/tgalopin/LegGoogleChartsBundle/blob/master/Resources/meta/LICENSE.md)

About
-----

The LegGoogleChartsBundle is developped mainly by Titouan Galopin.

Reporting an issue or a feature request
---------------------------------------

Issues and feature requests are tracked in the [Github issue tracker](https://github.com/tgalopin/LegGoogleChartsBundle/issues).

When reporting a bug, it may be a good idea to reproduce it in a basic project
built using the [Symfony Standard Edition](https://github.com/symfony/symfony-standard)
to allow developers of the bundle to reproduce the issue by simply cloning it
and following some steps.