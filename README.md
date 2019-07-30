# Custom Contextual Links

The Custom Contextual Links module allows you to add your own links to the 
contextual drop down widgets of blocks, views and nodes.

Contextual links are really great for quick access to settings pages within 
your Backdrop website. They cut down the time required to click through the 
sometimes cumbersome Backdrop administrative navigation. However, the links 
displayed in the contextual widget need to be defined through a module. This 
is where CCL comes in. This module allows you to use a UI to add and manage 
custom links that will be displayed in the contextual widgets.

You can add contextual links to:

- a single node
- all nodes of a content type
- all nodes
- a specific block
- all blocks
- all views
- all displays of a specific view
- all specific display of a view

Node action links support so far:

- make a node sticky/unsticky
- publish/unpublish a node
- Promote/remove a node from the home page

Local action links can be assigned to pages with a similar interface like core 
blocks. The visibility can be controlled by:

- path
- content type
- user role

Additionally you can also use Backdrop core tokens for title and links. This 
allows to create a link like "node/[node:nid]/devel" which will add a link to 
the devel view of a node into the contextual widget.

## Installation

- Install this module using the [official Backdrop CMS instructions](https://backdropcms.org/guide/modules).

## Configuration and Usage

After activating the module and any needed sub-modules, you can add new 
contexual links via the admin UI at **Configuration > User interface >
Custom Contextual Links** (**admin/config/user-interface/ccl**).

More details may be found (or added) in the [Wiki](https://github.com/backdrop-contrib/ccl/issues)

## Issues

Bugs and Feature requests should be reported in the [Issue Queue](https://github.com/backdrop-contrib/ccl/issues)

## Current Maintainers

- [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org) 

## Credits

- Ported to Backdrop by [Laryn Kragt Bakker](https://github.com/laryn), [CEDC.org](https://CEDC.org)
- Maintained for Drupal by [Benjamin Koether](https://www.drupal.org/u/bkoether)
- Sponsored for Drupal by [Mellenger Interactive](https://www.drupal.org/mellenger-interactive)


## License

This project is GPL v2 software. See the LICENSE.txt file in this directory for
complete text.
