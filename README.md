# UpContent Theme Preview

## Installation
After cloning run ensure you have yarn installed (`npm install -g yarn`). Then run
```shell
yarn install
```
If you run into any issues with node versions and want to use the same one it was built with this was originally built using node 14.

## Creating your theme
To create your theme simply modify the SCSS variables in theme.scss.

## Previewing
To build the theme and preview run the following command than open one of the links in the output in your browser 
```shell
yarn serve
```

This is a pretty simple build chain so you'll need to re-run the serve command (or build command below) every time you make changes

If you prefer to use a different web server such as your built in IDE web server you can instead simply run `yarn build`
