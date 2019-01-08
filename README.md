# browser-modern-extension-boilerplate

> Boilerplate for creating a browser extension with up-to-date tools and autoreload of the extension

## Features

This project is born because of the lack of browser extension starter kits which aren't from 2013 and don't use bower.

[Gulp 4](https://github.com/gulpjs/gulp) is used to manage all the tasks and wire the tools together, it was chosen because it's easily hackable and configurable, you can make it fit and scale with your wildest browser extension!

It uses [webpack](https://webpack.js.org/) to bundle javascript and [SCSS](http://sass-lang.com/) as a preprocessor. [Babel](http://babeljs.io/) transpiles all the future js stuff that hasn't landed in chrome yet, and there are customizable [eslint](https://eslint.org/) and [stylelint](https://stylelint.io/) config files.

The development mode has **autoreload** of the chrome extension, meaning that when you change a file, the extension is loaded again in chrome! 🔥

It comes with the [webextension-polyfill](https://github.com/mozilla/webextension-polyfill), which basically lets you write **async/await code** instead of the callback hell of the chrome extension apis. 💣

<img src="screenshots/start.png" width="700">

It also bundles your extension when you're done, ready to be pusblished to the extension store!

<img src="screenshots/bundle.png" width="700">

## Getting started

The easiest way is to use the [Yeoman generator](https://github.com/marcofugaro/generator-browser-modern-extension), you get to configure more stuff that way, here is a demo:

<img src="screenshots/demo.gif" width="600">

Alternatively, run:

```
curl -fsSL https://github.com/marcofugaro/browser-modern-extension-boilerplate/archive/master.tar.gz | tar -xz --strip-components=2 browser-modern-extension-boilerplate-master/boilerplate
```

Otherwise you can `git clone` or [download](https://github.com/marcofugaro/browser-modern-extension-boilerplate/archive/master.zip) this repo and get the contents of the `boilerplate` folder.

After you downloaded the files, create the .env file by running `cp .env.example .env`. Then replace all the occurrences of `<%= title %>`, `<%= kebabTitle %>` and so on.

## License

MIT © [Marco Fugaro](https://github.com/marcofugaro)
