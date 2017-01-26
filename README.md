<<<<<<< HEAD
# Moon Jekyll Theme [![Donate](https://img.shields.io/badge/paypal-donate-blue.svg)](https://www.paypal.me/taylantatli/0usd)

=======
# Moon Jekyll Theme [![Donate](https://img.shields.io/badge/paypal-donate-blue.svg)](https://www.paypal.me/taylantatli/0usd)  

## `Sorry guys but there will be no update until I buy a new laptop.`

>>>>>>> TaylanTatli/master
######(If you like this theme or using it, please give a :star: for motivation.)

**[Moon](http://taylantatli.github.io/Moon)** is a minimal, one column jekyll theme.

## Features
* Minimal, you can focus on your content
* Responsive
* Disqus integration
* Syntax highlighting
* Optional post image
* Social icons
* Page for sharing projects
* Optional background image
* Simple navigation menu
* MathJax support

## Preview

![screenshot of Moon](https://cloud.githubusercontent.com/assets/754514/14509720/61c61058-01d6-11e6-93ab-0918515ecd56.png)    
![screenshot of Moon](https://cloud.githubusercontent.com/assets/754514/14509716/61ac6c8e-01d6-11e6-879f-8308883de790.png)

See a [live version of Moon](http://taylantatli.github.io/Moon) hosted on GitHub.

## Getting Started

To learn how to install and use this theme check out the [Setup Guide](http://taylantatli.me/Moon/moon-theme/) for more information.

## Develop
**Note** F it's recommended to use [`rbenv`](https://github.com/rbenv/rbenv/) when developing with Ruby on Mac OS X.

Using ruby -v `2.3.1`

Install `bundler`

```ruby
gem install bundler
```

If using `rbenv` do `rbenv rehash` so that the `bundle` command can be executed.

Then do `bundle install`

To run the site locally do `bundle exec jekyll serve --config _config.yml,_config_dev.yml` and view in a web browser on `locahost:4000`

## Photo Gallery
Right now images are scaled to be 725px wide.

To add images to the image gallery:  

1. Add the processed image to the `/assets/img/` directory
2. In `photo_gallery/index.md`'s front matter, add the image path and title under `images`

For example:

```yml
images:
- image_path: /assets/img/egg-plate-eggplant.jpg
  title: Egg Plate
```
