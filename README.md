# README

Build a documentation website using markdown.

You can see the documentation website of this repository at https://hogenttin.github.io/hogent-docsify/ . Play with it to see what it can do!

## Basic usage

### How do I use this?

Edit, add or delete your markdown files in the [docs](./docs/) directory, and open [index.html](./docs/index.html) in your webbrowser. **That's all to get started!** :rocket:

If you want to edit the sidebar, then just edit [\_sidebar.md](./docs/_sidebar.md) .

### Live preview

Docsify allows you to start up a live preview, so you can instantly see how your slides look like whilst editing the markdown files.

1. Install [nodejs](https://nodejs.org) .
2. Install [docsify-cli](https://github.com/docsifyjs/docsify-cli) :

    ```console
    npm install --global docsify-cli
    ```

3. Start up the live preview:

    ```console
    docsify serve docs
    ```

### Generate PDF

If you hide the sidebar, you can easily create PDF's using your webbrowser's `Print to PDF` function.

## Configuration

:bulb: **You don't have to change these files or settings** if you want to keep things simple. In that case, just ignore this section.

### Theme

If you want another theme, you can change edit the `theme.css` header tag in [index.html](./docs/index.html) to point to another CSS file. You can also use an existing links like https://hogenttin.github.io/hogent-docsify/theme.css .

If you copy or fork this repo, but always want to keep the theme of your documentation website at any time automatically in sync with this repo, you can ... .

1. Set the `theme` link tag in [index.html](./docs/index.html) to the URL https://hogenttin.github.io/hogent-revealmd/_assets/theme.css .
2. Delete the [local CSS file](./docs/theme.css).

### [docsify](https://docsify.js.org) options

You can add them to [index.html](./docs/index.html) .

### Docsify plugins

You can add additional functionality using [Docsify plugins](https://docsify.js.org/#/plugins). These can be enabled by editing [index.html](./docs/index.html) . E.g., the [Mermaid](https://github.com/Leward/mermaid-docsify) plugin for drawing graphs is added in this repo as an example on how to do it.

## Additional tools

:bulb: **You don't need this** if you want to keep things simple. In that case, just ignore this section. Otherwise, it's here if you want an example.

### Automatic deployment

This repo automatically builds the website and pushes them to https://hogenttin.github.io/hogent-docsify/ whenever a commit is pushed to the `main` branch. This is done using using [GitHub actions](https://docs.github.com/en/actions) . You can find the workflow in the [.github](./.github) folder.

### Formatting

An [editorconfig](https://editorconfig.org/) config has been added in [.editorconfig](./.editorconfig) .

A [prettier](https://prettier.io/docs/en/) config has been added in [.prettierrc.json5](./.prettierrc.json5) .

### Linting

A [markdownlint](https://github.com/DavidAnson/markdownlint) config has been added in [.markdownlint.jsonc](./.markdownlint.jsonc) .

## Bugs

-   https://github.com/docsifyjs/docsify/issues/1929
-   https://github.com/prettier/prettier/issues/5019
