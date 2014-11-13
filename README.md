cryptic-theme
=============

Esoteric, occult example theme for Mozu.

build tooling requirements
--------------------------

This theme comes with a great set of build tools. To use them, here's what you need.

* NodeJS > 0.10.0 (for JS compression and the whole build process)

getting started
---------------

Clone or unzip this repo into a directory named after your theme (e.g. `cryptic-theme/`). This repository is set up as a teaching tool. Each existing tagged commit is a "step", meant to demonstrate a tool or technique in Mozu theme development. After you've cloned this repo, run the following command to get yourself to the first step in the tutorial:

```bash
git reset --hard initial
```

You can use the same command to proceed through the other steps. Run "git tag" to view the steps in order:

```bash
$ git tag
initial
v0.1.1-banner
v0.1.2-banner-ui
v0.2.0-widget
v0.3.0-dropzone
v0.4.0-style-changes
v0.5.0-pagetype
v0.6.0-softcart
v0.6.1-softcart-integration
```

This theme is based on the [Mozu Base Blank Theme](http://github.com/mozu/base-blank-theme), so you can begin working on it in the same way:

```bash
node configure.js
```

Local dependencies should all install. You can now use Grunt to lint, compile, and zip your theme!

### simple build
```bash
$ grunt
```

### build and update all resources to a new version number
```bash
$ grunt release --to <version>
```