Markdown TOC
============

Generate and update magically a table of contents based on the headlines of a parsed [markdown](http://en.wikipedia.org/wiki/Markdown) file.


## Table of Contents

- [Usage](#usage)
- [Installation](#installation)
- [Features](#features)
- [Contributors](#contributors)
- [Questions?](#questions)
- [License](#license)


## Usage

The PopupWindow in following gif is `Command Shift P`.

![Magic](https://raw.githubusercontent.com/nok/markdown-toc/master/RECORD.gif)

<!--
## API Attributes

- `titleSize:2`
- `tabSpaces:4`
- `depthFrom:1`
- `depthTo:6`
- `withLinks:1`
- `updateOnSave:1`
- `orderedList:0`
-->

## Installation

```bash
apm install markdown-toc
```

or

```bash
cd ~/.atom/packages
git clone .../markdown-toc.git
```


## Features

- Auto linking via  anchor tags, e.g.  `# A 1` → `#a-1`
- Depth control [1-6] with `depthFrom:1` and `depthTo:6`
- Enable or disable links with `withLinks:1`
- Refresh list on save with `updateOnSave:1`
- Use ordered list (1. ..., 2. ...) with `orderedList:0`
- Auto indent when Title not start from `#`
- Toc Title `## 目录(TOC)`
- Soft/Hard tab support with `tabSpaces:4`. 0 for hard others for soft. Default is `@Editor.tabLength`.

```
<!-- TOC titleSize:2 tabSpaces:4 depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->

## 目录(TOC)
- [title2](#title2)
- [title2](#title2)
	- [title3](#title3)

<!-- /TOC -->
```

## Configurations

To change the configurations,`Change` the value in text：

 `<!-- TOC titleSize:2 tabSpaces:4 depthFrom:1 depthTo:6 withLinks:1 updateOnSave:1 orderedList:0 -->`

 and then `Update` the toc。

## Contributors

Thanks to all contributors for any fix or improvement, whether small or large.

- [Giacomo Bresciani](https://github.com/brescia123)
- [Kévin Lanceplaine](https://github.com/lanceplaine)
- [Ilya Zelenin](https://github.com/wyster)
- [spjoe](https://github.com/spjoe)
- [Tom Byrer](https://github.com/tomByrer)
- [betrue12](https://github.com/betrue12)


## Questions?

Don't be shy and feel free to contact me on [Twitter](https://twitter.com/darius_morawiec).


## License

The package is Open Source Software released under the [MIT](LICENSE.md) license.
