# Installation

```console
composer require phariscope/event-rabbitmq-publisher
```

# Usage

1. First, make sure to have the DATABASE_URL environment variable correctly initialized.
2. [TO DO]


# To Contribut to pharsicope/EventStoreDoctrine

## Requirements

* docker
* git

## Install

* git clone git@github.com:phariscope/EventStoreDoctrine.git

## Unit test

```console
bin/phpunit
```

Using Test-Driven Development (TDD) principles (thanks to Kent Beck and others), following good practices (thanks to Uncle Bob and others) and the great book 'DDD in PHP' by C. Buenosvinos, C. Soronellas, K. Akbary

## Quality

* phpcs PSR12
* phpstan level 9
* coverage 100%
* infection MSI 100%

Quick check with:
```console
./codecheck
```

Check coverage with:
```console
bin/phpunit --coverage-html var
```
and view 'var/index.html' with your browser

Check infection with:

```console
bin/infection
```
and view 'var/infection.html' with your browser