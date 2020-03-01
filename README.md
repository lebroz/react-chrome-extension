# React Chrome Extension
Chrome extension boilerplate with ReactJS

## Getting Started

Follow the steps below so you can start to implement your Chrome Extension using ReactJS in few minutes.

### Installing

```
$ git clone git@github.com:lebroz/react-chrome-extension.git`
```
```
$ yarn install
```
```
$ yarn build
```

A new directory `build` will appear at the root.

Launch Chrome browser and search chrome://extensions in the address bar.

Once you are here activate the developer setting using the switch at the top right of your screen.

Then new buttons will appear, click on `Load unpacked` button and select `build` directory.

An icon will appear on the toolbar, click on it: A popup will appear with "Hello World"

You are good to go to develop a ReactJS chrome extension.

### Development

```
$ yarn dev
```
This will lauch webpack with watch mode. For customization, check webpack.config.js -> watchOptions.

Once new changes has been rebuild by webpack just go to chrome://extensions
and reload the extension so changes can take effect.

## License

MIT
