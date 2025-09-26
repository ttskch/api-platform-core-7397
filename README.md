# api-platform-core-7397

## What's this?

This is an example repository for [api-platform/core#7397](https://github.com/api-platform/core/pull/7397).

## Installation

```shell
$ git clone git@github.com:ttskch/api-platform-core-7397.git
$ cd api-platform-core-7397
$ composer install
$ bin/console doctrine:database:create
$ bin/console doctrine:migrations:migrate -n
```

## Usage

```shell
$ symfony server:start --no-tls -d
$ open http://localhost:8000/api
```

```shell
$ symfony server:stop
```
