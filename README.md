# Markleft

A Sublime Text 3 package for nice Markdown editing.

![](https://scrn.es/37ImhN34IBgpHNxrz32LF5.gif)

## Installation

Open a Terminal window and paste the following to install:

```shell
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/ && \
  git clone git@github.com:mkdynamic/markleft.git Markleft
```

To use Markleft, choose "Markleft" as the syntax when editing a file.

## Updating

Open a Terminal window and paste the following to update:

```shell
cd ~/Library/Application\ Support/Sublime\ Text\ 3/Packages/Markleft && \
  git pull
```

## Typeface

Be sure you have [Fira Mono installed](https://mozilla.github.io/Fira/) unless you wish to use a different typeface.

## Default Package

You may wish to disable the built-in Markdown package, by editing your preferences and including:

```json
{ "ignored_packages": ["Markdown"] }
```
