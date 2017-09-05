# Compass X.509 Plugin [![][travis_img]][travis_url]

Compass X.509 Plugin

## Usage

This plugin registers the main component as a `Connect.AuthenticationMethod` role for the
Compass connect plugin to use. The extensions add functionality to the connect plugin's
main store.

### Scripts

`link-plugin`: Links the Compass plugin and Compass for development along with React to ensure the
  plugin and Compass are using the same React instance.

```shell
COMPASS_HOME=/path/to/my/compass npm run link-plugin
```

`unlink-plugin`: Restores Compass and the plugin to their original unlinked state.

```shell
COMPASS_HOME=/path/to/my/compass npm run unlink-plugin
```

## License

Apache 2.0

[travis_img]: https://travis-ci.com/10gen/compass-auth-x509.svg?token=ezEB2TnpPiu7XLo6ByZp&branch=master
[travis_url]: https://travis-ci.com/10gen/compass-auth-x509
[npm_img]: https://img.shields.io/npm/v/@mongodb-js/compass-auth-x509.svg?style=flat-square
[npm_url]: https://www.npmjs.org/package/@mongodb-js/compass-auth-x509
