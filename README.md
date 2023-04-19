# Seluxias-Template
[![](https://img.shields.io/badge/Language-PHP,%20HTML%20&%20CSS-darkblue)](#)
[![](https://img.shields.io/badge/CSS-Bootstrap%205.2-purple)](#)

Seluxias is a simple template for a landing page.
Just change the colors in the configuration part of the `index.php` file.

In this template are the following parts:
* Information box (title box / welcome)
* Social media buttons
* About me / That's me
* Content part (for texts or what ever) with images
* My projects
* Footer



## Table Of Contents

* [Demo](#demo)
* [Preview](#website-preview)
* [Configuration](#configuration)


> NOTE: This template was developed for a personalized website and has been modified for public download.



## Demo
Try the demo [here](https://dxve.de/projects/seluxias/).



## Website Preview
![Preview](https://cdn.upload-host.de/1/1d3d26-c8c9d1.png)



## Configuration

In the first lines of the `index.php` file you will see php variables.
These you can edit according to your wishes.

The default config is red-dark styled.

```php
// Set your time zone
// https://www.php.net/manual/en/timezones.php
date_default_timezone_set('Europe/Berlin');

// General configuration
$sitename = 'Seluxias Template';
$domain = 'https://dxve.de/projects/mamba-dxve';
$logo = 'https://cdn.upload-host.de/1/9e1281-b783a9.png';

// Social media links
$socialMedia = array(
    array(
        'icon' => '<i class="fab fa-discord"></i>',
        'url' => 'https://discord.com/users/681877886172659877'
    ),
    array(
        'icon' => '<i class="fab fa-instagram"></i>',
        'url' => 'https://www.instagram.com/dxve.b'
    ),
    array(
        'icon' => '<i class="fab fa-tiktok"></i>',
        'url' => 'https://www.tiktok.com/@dxve.tiktok'
    ),
    array(
        'icon' => '<i class="fab fa-youtube"></i>',
        'url' => 'https://www.youtube.com/c/DxveDE'
    ),
    array(
        'icon' => '<i class="fab fa-twitter"></i>',
        'url' => 'https://twitter.com/@dxve_b'
    ),
    array(
        'icon' => '<i class="fab fa-facebook"></i>',
        'url' => 'https://www.facebook.com/dxve.bomke/'
    ),
    array(
        'icon' => '<i class="fab fa-github"></i>',
        'url' => 'https://github.com/DxveDE'
    ),
    array(
        'icon' => '<i class="fab fa-whatsapp"></i>',
        'url' => 'https://wa.me/+4915251838855'
    ),
    array(
        'icon' => '<i class="fas fa-envelope"></i>',
        'url' => 'mailto:kontakt@dxve.de'
    )
);

// Color settings
$titleColor = '#FF7F7F'; // Color of the titles
$titleHoverColor = '#7F3F3F'; // Color of the title on hovering
$textColor = '#C0C0C0'; // Color of texts
$secondaryColor = '#FF0000'; // Secondary color for forwarding and other
$secondaryHoverColor = '#880000'; // Secondary color for forwarding and other on hovering

$backgroundColor = '#13161B'; // Page background color
$backgroundContentColor = '#242936'; // Background color of text rows
$backgroundIconColor = '#242936'; // Icon background color
$backgroundFooterColor = '#242936'; // Footer background color
$boxShadow = '#000000';
```
