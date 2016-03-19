# [InstantClick](http://instantclick.io/)

Modified version of InstantClick with latest bug fixes + tweaks. Changelog:
- Option to not cache the browser back button.
- Basic preload caching, to save on unnecessary fetches.
- Fix history bug when clicking on the same link multiple times.

####Install

```
npm install instantclick2
```

####How to use

```
var InstantClick = require('instantclick2');

InstantClick.init({
    preloadingMode: 50,
    cacheBrowserBackBtn: true
});
```

---
All the informations you need to use InstantClick are on the link above. This ReadMe’s purpose is about how to use and contribute to a development version of InstantClick.

## Tests

Tests (in the `tests` folder) are PHP-generated HTML pages with which to check how InstantClick behaves on different browsers. That’s what I use before releasing a new version to make sure there are no obvious regressions.

To access the suite of tests, run `php -S 127.0.0.1:8000` from the project’s root directory (**not** from the `tests` folder) and head to [http://127.0.0.1:8000/tests/](http://127.0.0.1:8000/tests/).

## [Contributing](Contributing.md)

See the `Contributing.md` file.
