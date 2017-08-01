# BuckleScript Chrome

This repository aims to provide [BuckleScript](https://github.com/BuckleScript/bucklescript) bindings to the [Google Chrome extensions API](https://developer.chrome.com/extensions/api_index) so users can write Chrome apps in OCaml.

Currently, there is a demo application consuming the Chrome types as well. This package will emit Chrome extension compatible JavaScript, but it does not actually bundle it into a Chrome-loadable package.

## Contribute

There is a [GitHub Project](https://github.com/thoughtbot/bucklescript-chrome/projects/1) where you can see which APIs to implement next.

## Build
```sh
npm install
npm run build
```
