# HiDev DropWind

**HiDev plugin for DropWind vendor configuration**

[![Latest Stable Version](https://poser.pugx.org/dropwind/hidev-dropwind/v/stable)](https://packagist.org/packages/dropwind/hidev-dropwind)
[![Total Downloads](https://poser.pugx.org/dropwind/hidev-dropwind/downloads)](https://packagist.org/packages/dropwind/hidev-dropwind)
[![Build Status](https://img.shields.io/travis/dropwind/hidev-dropwind.svg)](https://travis-ci.org/dropwind/hidev-dropwind)
[![Scrutinizer Code Coverage](https://img.shields.io/scrutinizer/coverage/g/dropwind/hidev-dropwind.svg)](https://scrutinizer-ci.com/g/dropwind/hidev-dropwind/)
[![Scrutinizer Code Quality](https://img.shields.io/scrutinizer/g/dropwind/hidev-dropwind.svg)](https://scrutinizer-ci.com/g/dropwind/hidev-dropwind/)
[![Dependency Status](https://www.versioneye.com/php/dropwind:hidev-dropwind/dev-master/badge.svg)](https://www.versioneye.com/php/dropwind:hidev-dropwind/dev-master)

[HiDev] is the automation tool mixed with code generator for easier continuous development.

This plugin provides [DropWind] vendor configuration for HiDev.
Used for DropWind packages.

Provides DropWind information and settings:

- general data: vendor name and company title
- contact data: email, forum, github page
- authors data: names, roles, emails, github and home pages
- default license: BSD-3-Clause

See [src/config/goals.yml].

[HiDev]:                https://github.com/hiqdev/hidev
[dropwind]:             https://github.com/dropwind
[src/config/goals.yml]: src/config/goals.yml

## Installation

The preferred way to install this yii2-extension is through [composer](http://getcomposer.org/download/).

Either run

```sh
php composer.phar require "dropwind/hidev-dropwind"
```

or add

```json
"dropwind/hidev-dropwind": "*"
```

to the require section of your composer.json.

## License

This project is released under the terms of the proprietary [license](LICENSE).
Read more [here](https://en.wikipedia.org/wiki/Proprietary_software).

Copyright © 2017, DropWind (http://dropwind.com/)
