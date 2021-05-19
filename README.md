# @wrmlopes/newman-reporter-allure
A newman reporter to generate a clean and good report using the Allure-js framework adapted for use in a specific framework.
Generated from the original at
https://www.npmjs.com/package/newman-reporter-allure

## Installation
```console
$ npm install -g @wrmlopes/newman-reporter-allure
```

## Usage
To generate Allure results, specify `allure` in Newman's `-r` or `--reporters` option.

```console
$ newman run <Collection> -e <Environment> -r allure
$ newman run <Collection> -e <Environment> -r allure --reporter-allure-export <allure-results-out-dir>
```
