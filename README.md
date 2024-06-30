# JSCAD-Text

> Functions to create and extrude text in TTF fonts

## Overview

**NOTE:** This is based on the community [jscad-text library](https://github.com/jscad-community/jscad-text) but updated for Typescript and expanded with functions to extrude text

The JSCAD project does not provide the ability to use TTF fonts when creating outlines of text (It only supports SIMPLEX fonts.) Therefore, a special set of functionality has been created to suppliment JSCAD.

This library depends on the 'opentype.js' library. It's a really cool library which does some slick stuff; uncompresses the font, reads the contents, and produces SVG like structures.

But even before that, a TTF font file must be available. All operating systems come with one or more fonts, and those can be used, if you can find them. Fonts can also be downloaded from websites.

## Getting started

1. Install the package
```bash
npm install @r-bt/jscad-text
```
