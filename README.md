[![Build Status](https://travis-ci.org/apowers313/XXXXX.svg?branch=master)](https://travis-ci.org/apowers313/XXXXX)

[![Sauce Test Status](https://saucelabs.com/browser-matrix/apowers313.svg)](https://saucelabs.com/u/apowers313)

Setup:

1. Edit **package.json**, set `name`, `description`, `publish`, `repository.url`, `bugs.url`, `keywords`, and `license`
2. Edit **.jsdoc-conf.json**, set `systemName`
3. Edit **test/test.html**, set `title` and `main.js`
4. Rename **main.js**
5. Change git remote: `git remote rm origin` then `git remote add origin new-repo`
6. [Create](https://github.com/settings/tokens) `GH_TOKEN` and add to Travis CI build
7. [Get SauceLabs token](https://saucelabs.com/beta/user-settings) and set `SAUCE_ACCESS_KEY` and `SAUCE_USERNAME` in Travis CI
8. Update badge URLs in **README.md**, and delete these instructions
