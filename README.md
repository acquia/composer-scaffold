Acquia Scaffold
====

This is a Composer package containing the necessary [Composer Scaffold](https://www.drupal.org/docs/develop/using-composer/using-drupals-composer-scaffold) definitions to run a project on Acquia hosting.

## Installation and usage

To use these settings, you must already have configured a [Composer-based Drupal project](https://www.drupal.org/docs/develop/using-composer/using-drupals-composer-scaffold). Especially, ensure that your root composer.json includes the Drupal packagist repository and Drupal-specific installer paths. Then require this package via Composer:

`composer require acquia/scaffold`

This will ensure that scaffolded files are placed in the docroot, and that a compatible version of Composer Scaffold is included.

For easier project setup, consider using [Acquia BLT](https://github.com/acquia/blt), which includes this package by default, or reference [BLT’s project template](https://github.com/acquia/blt-project).

# License

Copyright (C) 2019 Acquia, Inc.

This program is free software: you can redistribute it and/or modify it under the terms of the GNU General Public License version 2 as published by the Free Software Foundation.

This program is distributed in the hope that it will be useful, but WITHOUT ANY WARRANTY; without even the implied warranty of MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.  See the GNU General Public License for more details.
