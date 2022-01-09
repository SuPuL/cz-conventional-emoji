# @supul/cz-conventional-emoji

一个遵循 conventional-changelog 的带有 emoji 的 commitizen 适配器。

[![Commitizen friendly](https://img.shields.io/badge/commitizen-friendly-brightgreen.svg)](http://commitizen.github.io/cz-cli/)

[![NPM](https://nodei.co/npm/cz-conventional-emoji.png?downloads=true&downloadRank=true&stars=true)](https://nodei.co/npm/cz-conventional-emoji/)

[English](./README.md) | 简体中文

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

## 安装

我们默认你已经安装过 [Commitizen](https://github.com/commitizen/cz-cli)。

### 全局

```
yarn global add @supul/cz-conventional-emoji
# OR
# npm install --global @supul/cz-conventional-emoji

# 设置全局默认适配器
echo '{ "path": "@supul/cz-conventional-emoji" }' > ~/.czrc
```

### 本地

```
yarn add @supul/cz-conventional-emoji
# OR
# npm install --save-dev @supul/cz-conventional-emoji

# 为你的项目设置默认适配器
"config": {
    "commitizen": {
      "path": "./node_modules/@supul/cz-conventional-emoji"
    },
  }
```

## 使用

当需要提交时，只需使用“git cz”代替“git commit”即可。查看[Commitizen](https://github.com/commitizen/cz-cli)官方文档了解更多信息。

## 作者

gaoancun <gaoac.snow@outlook.com>

## 许可证

[MIT](LICENSE)
