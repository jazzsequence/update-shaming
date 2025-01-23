# Update Shaming

Contributors: Chris Reynolds  
Donate link: https://paypal.me/jazzsequence  
Tags: pages, content, updates, old, reaction gifs  
Requires at least: 3.5  
Tested up to: 5.9  
Stable tag: 0.3.4  
License: GPL3  
License URI: http://www.gnu.org/licenses/gpl-3.0.html

The only WordPress plugin not afraid to give you dirty looks.

## Description

The purpose of this plugin is to shame content editors into updating page content that has not been touched in a long time, while simultaneously providing an overview of the oldest pages on a site. Also: gifs.

The plugin adds an **Out of Date Pages** subpage under the Pages menu, which breaks all the pages on the site down by last modified date, grouped by years since it's been modified. Each page listed has a link to edit the page. All images on the Out of Date Pages subpage are sourced from [reactiongifs.com](http://reactiongifs.com).

## Installation

### Via Composer

Update Shaming can be installed on Composer-based WordPress sites by using the following command:

```bash
composer require jazzsequence/update-shaming
```

### Via Git Updater

Update Shaming supports [Andy Fragen's Git Updater](https://git-updater.com) method of managing plugins. 

1. Download and install [Git Updater](https://git-updater.com/git-updater/) on your WordPress site.
1. From the Git Updater admin pages, navigate to **Install Plugin** and use the following values:

**Plugin URI:** `jazzsequence/update-shaming`  
**Repository Branch:** `main`  
**Remote Repository Host:** `GitHub`  
**GitHub Access Token:** (optional, leave blank)

### Via WordPress Plugin Repository
The plugin can be installed via the WordPress plugin repository, however, the version in the repository may not be the most current version. Use the standard methods of searching for and installing the plugin from the Plugins page in your WordPress dashboard.

### Manual
1. Extract the zip file and upload to the `/wp-content/plugins/` directory
2. Activate the plugin through the Plugins menu in the WordPress dashboard.
3. Profit!

## Frequently Asked Questions

**I'm a translator. I don't understand some of these captions.**

I'm well aware that there are some jokes/captions that may get lost in translation. Translators should feel free to make the captions their own in a way that makes the most sense in their language. There should not be any requirement (or assumption of a requirement) that the captions are "set in stone" and can't be different than their source. All other translatable strings should be handled normally.

**Can I submit reactions/captions?**

Sure. Submit a ticket [here](https://github.com/jazzsequence/Update-Shaming/issues/new).


## Screenshots

See https://wordpress.org/plugins/update-shaming/

## Changelog

### 0.3.2
* version bump

### 0.3.1
* version bump, no major changes
* added plugin icon

### 0.3
* Removed all non-reactiongif.com images and replaced with reactiongif alternatives
* Updated readme files and [hacking.md](https://github.com/jazzsequence/Update-Shaming/blob/master/hacking.md)

### 0.2
* Added a view page link
* Cleaned up some alignment issues in the tables

### 0.1

Initial release. See [hacking.md](https://github.com/jazzsequence/Update-Shaming/blob/master/hacking.md) for details about the code.
