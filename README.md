# About

Export MySQL Workbench Schema model into various models such as Doctrine, Propel, Sequelize, and others.

## Usage

* Install using composer, `composer require --dev mysql-workbench-schema-exporter/exporter`.
* From terminal execute:

```shell
$ vendor/bin/mysql-workbench-schema-export \
    vendor/mysql-workbench-schema-exporter/mysql-workbench-schema-exporter/example/data/sakila.mwb \
    build
```