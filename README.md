# README

## Demo

You can see the slides of this repository at https://hogenttin.github.io/hogent-docsify/ . Play with it to see what it can do!

## Installation

1. Install [nodejs](https://nodejs.org) .
2. Install [docsify-cli](https://github.com/docsifyjs/docsify-cli) :

    ```console
    npm install -g docsify-cli
    ```

## Basic usage

Edit, add or delete put your markdown files in the root directory.

### Creating slides (debugging)

You can start up a live preview:

```console
docsify serve .
```

_Tip: if you hide the sidebar, you can easily create PDF's using your webbrowser's `Print to PDF` function._

## Advanced

**You don't really need this** if you want to keep things simple, but it's here if you want an example.

### Automatic deployment

This repo automatically builds the website and pushes them to https://hogenttin.github.io/hogent-docsify/ whenever a commit is pushed to the `main` branch. This is done using using [GitHub actions](https://docs.github.com/en/actions) . You can find the workflow in the [.github](./.github) folder.

### Formatting

A [prettier](https://prettier.io/docs/en/) config has been added in [.prettierrc.json5](./.prettierrc.json5) .

### Linting

A [markdownlint](https://github.com/DavidAnson/markdownlint) config has been added in [.markdownlint.jsonc](./.markdownlint.jsonc) .

## Configuration

### Theme

If you want another theme, you can change edit the `theme.css` header tag in [index.html](./index.html) to point to another CSS file. You can also use an existing link like https://hogenttin.github.io/hogent-docsify/hogent-docsify.css . Using this specific URL will always keep your theme up to date with the one on this repo.

### [docsify](https://docsify.js.org) options

You can add them to [index.html](./index.html) .

## Bugs

-   https://github.com/docsifyjs/docsify/issues/1929
-   https://github.com/prettier/prettier/issues/5019

## Links

-   Inspired by https://github.com/HoGentTIN/hogent-revealjs/ .
