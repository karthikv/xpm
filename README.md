# xpm

xpm is an x-tags package manager inspired by npm that allows you to easily
install and uninstall x-tags that you'd like to use.

## Installation

A quick way to install xpm is still in the works, but for now, you'll need to
clone this repository, install the dependencies from requirements.txt, and run
the xpm executable.

## Usage

### Installing tags

Installing tags is simple. Just use the `xpm install [tagName]` command, like
so:

```bash
$ xpm install dropdown
# => Successfully added <x-dropdown> CSS and JS to custom-tags.css and custom-tags.js, respectively.
```

The tag's JavaScript and CSS will be added to `custom-tags.js` and
`custom-tags.css` in the current directory.

### Uninstalling tags

Uninstalling tags is just as easy with the `xpm uninstall [tagName]` command:

```bash
$ xpm uninstall dropdown
# => Successfully removed <x-dropdown> CSS and JS to custom-tags.css and custom-tags.js, respectively.
```

The tag's JavaScript and CSS will be removed from `custom-tags.js` and
`custom-tags.css` in the current directory.
