PageTemplate
============

A Plugin for moziloCMS 2.0

This plugin renders a specific template for only the single page, where this plugin is included.

## Installation
#### With moziloCMS installer
To add (or update) a plugin in moziloCMS, go to the backend tab *Plugins* and click the item *Manage Plugins*. Here you can choose the plugin archive file (note that it has to be a ZIP file with exactly the same name the plugin has) and click *Install*. Now the PageTemplate plugin is listed below and can be activated.

#### Manually
Installing a plugin manually requires FTP Access.
- Upload unpacked plugin folder into moziloCMS plugin directory: ```/<moziloroot>/plugins/```
- Set default permissions (chmod 777 for folders and 666 for files)
- Go to the backend tab *Plugins* and activate the now listed new PageTemplate plugin

## Syntax
```
{PageTemplate|<template>}
```
Is this plugin tag placed on a content page, that single page will be rendered coompletely in the given template.

1. Parameter ```<template>```: The template name of the template which shall be used for the current content page.

## License
This Plugin is distributed under *GNU General Public License, Version 3* (see LICENSE) or - at your choice - any further version.

## Documentation
A detailed documentation and demo can be found here:  
https://github.com/devmount-mozilo/PageTemplate/wiki/Dokumentation
