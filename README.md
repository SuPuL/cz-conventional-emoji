# @supul/cz-conventional-emoji

A commitizen adapter following the conventional-changelog format with emoji after type and scope.

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

[![NPM](https://nodei.co/npm/cz-conventional-emoji.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/cz-conventional-emoji/)

English | [简体中文](./README.zh-CN.md)

```
 Select the type of change that you're committing: (Use arrow keys)
❯ Feat:              ✨ Introducing new features.
  Bug:               🐛  Fixing a bug.
  Docs:              📝 Writing docs.
  Style:             🎨 Improving structure / format of the code.
  UI:                💄 Updating the UI and style files.
  Quickfix:          🚑 Critical hotfix.
  Pref:              ⚡️  Improving performance.
(Move up and down to reveal more choices)
```

## Installation

We think you've already installed the [Commitizen](https://github.com/commitizen/cz-cli).

### Globally

```
yarn global add @supul/cz-conventional-emoji
# OR
# npm install --global @supul/cz-conventional-emoji

# set as default adapter globally
echo '{ "path": "@supul/cz-conventional-emoji" }' > ~/.czrc
```

### Locally

```
yarn add @supul/cz-conventional-emoji
# OR
# npm install --save-dev @supul/cz-conventional-emoji

# set as default adapter for your projects
"config": {
    "commitizen": {
      "path": "./node_modules/@supul/cz-conventional-emoji"
    },
  },
```

## Usage

Simply use `git cz` instead of `git commit` when committing. See the doc of [Commitizen](https://github.com/commitizen/cz-cli) for more info.

## Author

Origin:
gaoancun <gaoac.snow@outlook.com>

Fork by:
supul

## License

[MIT](LICENSE)
