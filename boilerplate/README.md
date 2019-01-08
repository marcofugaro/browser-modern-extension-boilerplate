# <%= kebabTitle %> [![Build Status][travis-image]][travis-url]

> <%= description %>

## Install

#### [Chrome extension]()
#### [Firefox add-on]()

## Development

- `yarn start` to compile and watch the files for changes.

  To enable the autoreload on chrome:

  1. Go to `chrome://extensions/`
  1. Make sure **Developer mode** is on
  1. Click **Load unpacked** and choose the **build/** folder

  Instead, if you want to develop on firefox, check out [web-ext](https://github.com/mozilla/web-ext).

- `yarn build` to just compile the files.
- `yarn bundle` to compile the files and put them in a `.zip`, ready to be published.

## License

MIT © [<%= name %>](https://github.com/<%= githubUsername %>)


[travis-image]: https://travis-ci.org/<%= githubUsername %>/<%= kebabTitle %>.svg?branch=master
[travis-url]: https://travis-ci.org/<%= githubUsername %>/<%= kebabTitle %>
