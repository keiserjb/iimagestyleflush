
# Image style flush
==================

This module will allow Drupal to flush all image styles at once or flush each
individual image style right from the administrative interface.


## Features
--------

  - Flush all image styles
  - Flush each individual image style
  - Integrates with the admin_menu module


## INSTALLATION

- Install this module using the official Backdrop CMS instructions at
  [](https://docs.backdropcms.org/documentation/extend-with-modules).

## Usage
-----

You can flush image styles under Administration -> Configuration -> Media
-> Image styles

Note that this module only flushes images. It does not rebuild them.


## Known problems
--------------

Private file image styles can't be flushed with this module.

## Differences from Drupal 7

Capabilities should be the same.

## Issues

Bugs and feature requests should be reported in [the Issue Queue](https://github.com/backdrop-contrib/imagestyleflush/issues).

## Current Maintainers

<!-- - [Justin Keiser](https://github.com/keiserjb). -->

## Credits
------
Ported to Backdrop CMS by [Justin Keiser](https://github.com/keiserjb).
The Drupal version was written by [Stepan Kuzmin](https://www.drupal.org/u/tostepankuzmingmailcom) and is maintained by [Hargobind Khalsa](https://www.drupal.org/u/hargobind).

License
-------

This project is GPL v2 software.
See the LICENSE.txt file in this directory for complete text.
