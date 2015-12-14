# Installing PHP
The following outlines the recommended PHP setup for the Code Louisville PHP track. Although Treehouse offers Workspaces, we recommend setting up PHP locally as well as installing phpMyAdmin and Composer.

## A common PHP setup

The most common set up for PHP is the *LAMP stack*. LAMP stands for Linux, Apache, MySQL, and PHP. Here’s a quick, introductory overview of these technologies:

- **Linux** is the platform (think operating system) which the server runs on. The platform can also be Windows (WAMP stack) or Apple (MAMP stack).
- **Apache** is the web server. It handles processing web requests and sending the response.
- **MySQL** is the database server. It stores the data for your web application.
- **PHP** is a general-purpose scripting language that is commonly used for web development. Think of it as the glue between the other technologies. 

## Setting up PHP locally
Setting up PHP on your local machine allows you to develop more rapidly. In addition, you become more familiar with the technologies surrounding PHP.

You will want to install the *AMP* technologies outline above for your platform. Follow the instructions below for your platform to get your local *AMP* sever setup.

### Windows
Windows has several applications that include all the *AMP* technologies. We recommend installing [WampServer](http://www.wampserver.com/en/).

### Mac OS X
Mac OS X includes Apache and PHP. So you only need to download MySQL. Follow this guide for [Installing Apache, PHP, and MySQL on Mac OS X](http://jason.pureconcepts.net/2015/10/install-apache-php-mysql-mac-os-x-el-capitan/).

### Linux Platforms
If you are running a Linux platform you are probably familiar with installing packages via the package manager. There will be packages for Apache, PHP, and MySQL. Since the LAMP stack is the most common setup for running PHP, you can find several tutorials by a web search for your distribution of Linux.

## phpMyAdmin
phpMyAdmin is a free tool, written in PHP, which allows web-based administration of MySQL. We recommend using phpMyAdmin as it is commonly used in PHP community.

### Windows
WampServer comes with phpMyAdmin. So there is nothing more you need to do.

### Mac OS X
Follow the *Additional Configuration* outlined in the original guide to [install phpMyAdmin on Mac OS X](http://jason.pureconcepts.net/2012/10/install-apache-php-mysql-mac-os-x/).

### Linux Platforms
phpMyAdmin is included in most Linux distributions. Follow the [phpMyAdmin Installation](http://docs.phpmyadmin.net/en/latest/setup.html#linux-distributions) steps for your Linux distribution.

## Composer
Composer is a tool for dependency management in PHP. It allows you to include other PHP libraries in your projects. We recommend installing Composer globally so you can use it on all your projects.

### Windows
Follow the [Using the Installer](https://getcomposer.org/doc/00-intro.md#using-the-installer) steps to install Composer on Windows.

### Mac OS X and Linux Platforms
Follow the [global installation](https://getcomposer.org/doc/00-intro.md#globally) steps to install Composer on Mac OS X and Linux platforms.

## Virtual Hosts (optional)
By default, Apache serves one web site - `http://localhost`. This is fine for your first web site. However, over time, you will need Apache to serve multiple web sites. By configuring virtual hosts, Apache can serve multiple web sites. To configure virtual hosts, follow the guides below based on your platform.

### Windows
Follow [this guide](https://john-dugan.com/wamp-vhost-setup/) to setup virtual hosts using WampServer.

### Mac OS X and Linux Platforms
Mac OS X and Linux platforms have a similar Apache setup. As such, you can follow this tutorial for [Configuring Apache Virtual Hosts on Mac OS X](http://jason.pureconcepts.net/2014/11/configure-apache-virtualhost-mac-os-x/).

**Note:** the location of the Apache configuration files may vary based on your platform. If you are having trouble, a quick web search for your platform should help determine their location.