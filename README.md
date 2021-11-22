# renovate-config-angular [![NPM version](https://img.shields.io/npm/v/renovate-config-angular.svg)](https://www.npmjs.com/package/renovate-config-angular)

Angular [shareable config](https://docs.renovatebot.com/config-presets/) for [Renovate](http://renovatebot.com/)

## Installation

Install `renovate-config-angular`:

```bash
npm install --save-dev renovate-config-angular
```

## Usage
Angular Renovate rules come bundled in `renovate-config-angular`.
To enable these rules, add a `renovate` property in your `package.json`. See the [Renovate configuration docs](https://docs.renovatebot.com/configuration-options/) for more details.

```json
"renovate": {
  "extends": ["config:base", "angular"]
}
```

