# express-mw-lang

[![Build Status](https://travis-ci.org/VoleboNet/express-mw-lang.svg?branch=master)](https://travis-ci.org/VoleboNet/express-mw-lang)
[![codecov](https://codecov.io/gh/VoleboNet/express-mw-lang/branch/master/graph/badge.svg)](https://codecov.io/gh/VoleboNet/express-mw-lang)
[![bitHound Overall Score](https://www.bithound.io/github/VoleboNet/express-mw-lang/badges/score.svg)](https://www.bithound.io/github/VoleboNet/express-mw-lang)
[![bitHound Dependencies](https://www.bithound.io/github/VoleboNet/express-mw-lang/badges/dependencies.svg)](https://www.bithound.io/github/VoleboNet/express-mw-lang/master/dependencies/npm)
[![npm version](https://img.shields.io/npm/v/express-mw-lang.svg)](https://www.npmjs.com/package/express-mw-lang)
[![npm downloads](https://img.shields.io/npm/dm/express-mw-lang.svg)](https://www.npmjs.com/package/express-mw-lang)

Language-helper middleware for Express web server.

This middleware helps to determine language, and handle url of incoming requests.

**PULL REQUEST WITH DOCUMENTATION REQUIRED: [ISSUE](https://github.com/VoleboNet/express-mw-lang/issues/1)**

## Options

```javascript
var langGen = require('express-mw-lang');
let langmw = langGen({
	defaultLanguage: 'en',
	availableLanguages: ['en'],
	onLangCodeReady: function(lang_code, req, res) {
	}
});
```
## Contributing

You could take part in the development process, just follow this [guideline](CONTRIBUTING.md).

## License

Please, read the [`LICENSE`](LICENSE) file in the root of the repository (or downloaded package).
