# Markdown TOC

Generate and update magically a table of contents based on the headlines of a
parsed [markdown](http://en.wikipedia.org/wiki/Markdown) file in Atom.

This project is based on [Darius Morawiec](https://github.com/nok)'s
[markdown-toc](https://github.com/nok/markdown-toc) and the
[jokinkuang](https://github.com/jokinkuang)'s
[fork](https://github.com/jokinkuang/markdown-toc).

<!-- TOC titleSize:2 tabSpaces:2 depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 skip:1 title:1 charForUnorderedList:* -->
## Table of Contents
* [Usage](#usage)
* [Commands](#commands)
* [Installation](#installation)
* [Features](#features)
* [Configuration](#configuration)
* [Contributors](#contributors)
* [Similar project](#similar-project)
* [Questions?](#questions)
* [License](#license)
<!-- /TOC -->


# Usage

Open Atom's [command
palette](https://flight-manual.atom.io/getting-started/sections/atom-basics/#command-palette)
with <kbd>Ctrl+Shift+P</kbd> and search for TOC. As alternative, you can use the
`Packages > Markdown TOC` menu, which is also available in the right click
contextual menu (`Toggle Markdown TOC`).

![Demo](https://raw.githubusercontent.com/ponsfrilus/md-toc/master/RECORD.gif)


# Commands

  * `md-toc:create`: create the TOC (shortcut is <kbd>Ctrl+Alt+c</kbd>)
  * `md-toc:update`: update the TOC (shortcut is <kbd>Ctrl+Alt+u</kbd>)
  * `md-toc:delete`: delete the TOC (shortcut is <kbd>Ctrl+Alt+r</kbd>)
  * `md-toc:toggle`: toggle the TOC 


# Installation

```bash
apm install md-toc
```

or

```bash
cd ~/.atom/packages
/usr/bin/git clone git@github.com:ponsfrilus/md-toc.git
```


# Features

  * Auto linking via anchor tags, e.g.  `# A 1` → `#a-1`
  * Depth control [1-6] with `depthFrom:1` and `depthTo:6`
  * Enable or disable links with `withLinks:1`
  * Refresh list on save with `updateOnSave:1`
  * Use ordered list (1. ..., 2. ...) with `orderedList:0`
  * Auto indent when Title not start from `#`
  * Optional TOC title `## Table of Contents` with `title:[0,1]`
  * Soft/Hard tab support with `tabSpaces:4`. 0 for hard others for soft.  
    Default is `@Editor.tabLength` or 2 if not set.
  * Option to skip 0 to n titles with `skip:[0|n]`
  * Choose between `-` or `*` for unordered list in TOC


# Configuration

To change the configuration, `change` the value in text (this is the default)：

`<!-- TOC titleSize:2 tabSpaces:2 depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 skip:0 title:1 charForUnorderedList:* -->`

and then `update` the TOC (shortcut is <kbd>Ctrl+Alt+u</kbd>).


# Contributors

Thanks to all contributors for any fix or improvement, whether small or large.

  * [Darius Morawiec](https://github.com/nok) (initial author)
  * [Giacomo Bresciani](https://github.com/brescia123)
  * [Kévin Lanceplaine](https://github.com/lanceplaine)
  * [Ilya Zelenin](https://github.com/wyster)
  * [spjoe](https://github.com/spjoe)
  * [Tom Byrer](https://github.com/tomByrer)
  * [betrue12](https://github.com/betrue12)
  * [jokinkuang](https://github.com/jokinkuang) (main fork)
  * [ponsfrilus](https://github.com/ponsfrilus) (this repo)


# Similar project

  * [markdown-toc](https://atom.io/packages/markdown-toc)
  * [markdown-toc-auto](https://atom.io/packages/markdown-toc)
  * [atom-mdtoc](https://atom.io/packages/atom-mdtoc)


# Questions?

Don't be shy and feel free to contact me on [Twitter](https://twitter.com/ponsfrilus).


# License

The package is Open Source Software released under the [MIT](LICENSE.md) license.
