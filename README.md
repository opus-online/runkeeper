# Runkeeper API wrapper

PHP wrapper for Runkeeper Health Graph API

**Version:** 0.3.3

**Author:** Pierre RASO - eX Nihili <pierre@exnihili.com>

## Dependencies

* sfYaml (https://github.com/fabpot/yaml) - Installed via Composer
* PHP cURL support (http://www.php.net/manual/en/book.curl.php)
* PHP json support (http://fr2.php.net/manual/en/book.json.php)

## Usage

See /usage/rk-api.sample.php

## ChangeLog :

### v0.3.3 (2013-03-05)

* Updated README
* Install sfYaml via Composer

### v0.3.2 (2013-03-05)

* Adds support for Records

### v0.3.1 (2012-04-13)

* fixed bug (missing "}")

### v0.3 (2012-04-02)

* fixed bug with cURL on some server which had "error :SSL certificate problem, verify that the CA cert is OK"

### v0.2 (2012-03-19)

* added support for "Delete" requests in "doRunkeeperRequest" method
* added Interfaces in API config

### v.01 (2012-03-03)

* Initial version