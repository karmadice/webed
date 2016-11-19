# Welcome to WebEd
####A CMS based on Laravel

A few months ago, I published a CMS called [LaraWebEd](https://github.com/duyphan2502/LaraWebEd).
Today, I would like to share you version 2 of that CMS. It's called **WebEd**.

####WebEd is always free!

###There are some features of this CMS:
- Modular packages.
- Manage files with Elfinder.
- ACL
- Menu management with drag & drop
- **Database caching** (repository pattern)
- Themes & plugins management.
- Hook

By default, WebEd comes with these plugins: **Pages**, **Blog**, **Custom Fields**.

##System Requirement
On this projects, I use the latest Laravel version (currently 5.3). 
Please go to [laravel documentation page](https://laravel.com/docs/5.3/installation) to check your system requirements.

##WebEd installation guide

####Checkout project
> git clone https://github.com/sgsoft-studio/webed
> composer install

or 

> composer create-project --prefer-dist sgsoft-studio/webed webed

####Install WebEd
> php artisan cms:install

Enjoy!

##Table of contents
- [WebEd module comands](./documentation/console/module.md)
- [WebEd theme commands](./documentation/console/theme.md)
- [How to use custom fields](./documentation/console/plugins/custom-fields.md)