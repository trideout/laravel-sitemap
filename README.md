# [laravel-sitemap](https://gitlab.com/Laravelium/Sitemap) package

A not so simple sitemap generator for Laravel.


## Notes

- **This repo is moved to [GitLab](https://gitlab.com/Laravelium/Sitemap).**
- **This repo is renamed to [laravelium/sitemap](https://gitlab.com/Laravelium/Sitemap)**

## Installation

Run the following command and provide the latest stable version (e.g v3.0.1) :

```bash
composer require laravelium/sitemap
```

or add the following to your `composer.json` file :

#### For Laravel 5.7
```json
"laravelium/sitemap": "3.0.*"
```

#### For Laravel 5.6
```json
"laravelium/sitemap": "2.8.*"
```

#### For Laravel 5.5
```json
"laravelium/sitemap": "2.7.*"
```

Publish needed assets (styles, views, config files) :

```bash
php artisan vendor:publish --provider="Laravelium\Sitemap\SitemapServiceProvider"
```
*Note:* Composer won't update them after `composer update`, you'll need to do it manually!

