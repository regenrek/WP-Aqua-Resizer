# WP Aqua Resizer

This small script will allow you to resize & crop WordPress images uploaded via the media uploader on the fly. It relies on WP's native functions to resize the images, and checks if there is an already resized version of the image so that it won't be wasting your server's resources to regenerate the images.

The original Aqua Resizer was created by Syamil MJ


## Why use this version?

- composer.json for dependency management [Composer](https://getcomposer.org)
- Wordpress Plugin
- Latest Aqua Resizer version

## Install

Create or edit your composer.json file.

``` json
  "repositories": [
    {
      "type": "composer",
      "url": "http://wpackagist.org"
    },
    {
      "type": "git",
      "url": "https://github.com/kkern/WP-Aqua-Resizer.git"
    }
  ],
  "require": {
    "php": ">=5.3.2",
    "composer/installers": "v1.0.12",
    "kkern/WP-Aqua-Resizer": "dev-master"
  }
```

Install files

``` json
	composer update

```



## How-To

There aren't any special shortcodes or template tags implemented.
Just use the original Documentation which you can find here:

[https://github.com/syamilmj/Aqua-Resizer](https://github.com/syamilmj/Aqua-Resizer)













