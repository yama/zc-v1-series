# [Zen Cart&reg; - The Art of E-Commerce](https://www.zen-cart.com/) 
[![Build Status](https://travis-ci.org/zencart/zc-v1-series.svg)](https://travis-ci.org/zencart/zc-v1-series) 
[![Download Zen Cart&reg;](https://img.shields.io/sourceforge/dm/zencart.svg)](http://sourceforge.net/projects/zencart/files/latest/download)

===============

Zen Cart&reg; was the first Open Source e-Commerce web application to be fully PA-DSS Certified (starting with v1.5.0). The latest stable version is currently v1.5.4 and also carries PA-DSS certification.

Zen Cart&reg; v1.6.0 brings improved templating and responsive design, in addition to increased flexibility for customizing to each storeowner's own preferences.

It's free software, with free support available 24/7 on the Zen Cart&reg; Support Site forums at <https://www.zen-cart.com/forum.php> provided by our enthusiastic community of actual Zen Cart&reg; users, integrators, and the developers themselves.

--------------------


Zen Cart&reg; v1.6.0
--------------------

[![Download Latest Official Zen Cart&reg; Release](https://a.fsdn.com/con/app/sf-download-button)<br>Download Latest Official Zen Cart&reg; Release](http://sourceforge.net/projects/zencart/files/latest/download)

or
[Download latest in-development version from github](https://github.com/zencart/zc-v1-series/archive/v160.zip)

Requirements
------------
Zen Cart&reg; requires you to provide your own webserver (shared or dedicated/VPS), with a standard LAMP stack (Linux/Apache/MySQL/PHP)

- Compatible with PHP 5.4.2 to 7.0.x
- Compatible with MySQL 5.1 to 5.7, via the PHP mysqli client
- CURL (via PHP) is used to communication with payment/shipping services
- Compatible with with Apache 2.2, (or Apache 2.4 with the backward-compatibility mode enabled for v2.2 .htaccess rules support.)
- Recommended Apache modules include: expires, headers, env, alias, deflate, ssl, mime, rewrite (in addition to other common modules)

Zen Cart&reg; "can" run on IIS, but with some limitations, namely the need to manually secure various folders with IIS equivalents to .htaccess rules.

Zen Cart&reg; can also run on Nginx, but does not supply a configuration file for enforcing any permission/access rules or optimization for serving page assets.


Installation
------------

Installation is simple:

1. [Download Zen Cart&reg;](http://sourceforge.net/projects/zencart/files)
2. Ensure you check that the md5/sha1 hash of the Zip matches those publicly posted.
  * The md5/sha1 values for verifying the zip files hosted at Sourceforge are displayed on the [Zen Cart&reg; website](https://www.zen-cart.com/) along with [instructions on how to verify the file using the hash values](https://www.zen-cart.com/content.php?305).
3. Unzip the downloaded zip file 
4. Everything inside the folder you unzipped needs to be uploaded to your webserver … for example, into your public_html or www or html folder (the folder will already exist on your webserver)
5. In your browser, enter the address to your site, such as: `www.your_site.com` (or if you uploaded it into another foldername use `www.your_site.com/foldername` )
6. Rename the `/includes/dist-configure.php` and `/admin/includes/dist-configure.php` files to `configure.php` and make the files writable (so the install process can write your configuration information into them after you answer a few questions in the following steps).
7. Also make the `/cache` and `/logs` folders writable. (You will be prompted about making other folders writable during installation)
8. Follow the instructions that appear in your browser for installation. 

That's the abbreviated version of installation instructions!

For a MUCH more detailed set of installation instructions, see the [/docs/1.readme_installation.html](https://www.zen-cart.com/docs/1.readme_installation.html) file in your Zen Cart files.

PCI/PA-DSS Compliance
---------------------
__The [Implementation Guide](https://www.zen-cart.com/docs/implementation-guide-v155.pdf) should be followed for PCI Compliant implementation.__

Documentation
-------------
Use your browser to open the [/docs/index.html](https://www.zen-cart.com/docs/index.html) page for links to documentation and the [Implementation Guide](https://www.zen-cart.com/docs/implementation-guide-v154.pdf).


Support
-------
For free support, visit our support site: [https://www.zen-cart.com/forum.php](https://www.zen-cart.com/forum.php)

Follow Us
---------
For news and updates about Zen Cart&reg;, follow us on [Twitter](http://twitter.com/zencart) and [Facebook](http://facebook.com/zencart)

Sign up for our free [Newsletter](http://eepurl.com/bafnNj)

Subscribe to [Critical News Updates And Release Announcements](https://www.zen-cart.com/subscription.php?do=addsubscription&f=2)


&nbsp;  
  
*&copy;Copyright 2003-2016, Zen Cart&reg;. All rights reserved.*

