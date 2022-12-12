# Wordpress CMS

This repository uses Git submodules. After cloning this like a regular repository, run the following command to get all the submodules.

```shell
git submodule update --init --recursive
```

WordPress plugins frequently use [Composer](https://getcomposer.org) for managing PHP dependencies. Run `composer install` in every directory in `wp-content/plugins/*/` and `wp-content/themes/*/` that has a `composer.json`.
