frontend-sandbox-typescript
====

TypeScriptの練習用テンプレートのセットです。

## Description

2020年現在のFrontend開発によく使われるライブラリなどの基本設定を完了したものになっています。
以下Requirement以下のライブラリの設定ファイル、基本コマンドを設定済みです。

## Requirement

- Eslint
- prettier 
- webpack
- typescript

## Install

```$xslt

git clone 

```

## Usage

```$xslt
npm init -y

# or touch package.json

npm install --save-dev eslint
npm install --save-dev --save-exact prettier
npm install --save-dev prettier-eslint prettier-eslint-cli

npm install --save-dev eslint-plugin-standard eslint-plugin-promise eslint-plugin-import
npm install --save-dev eslint-config-standard eslint-plugin-node
npm install --save-dev eslint-plugin-prettier eslint-config-prettier

# make configuration file
touch .eslintrc.json
touch .prettierrc.json

npm install --save-dev webpack webpack-cli webpack-dev-server
npm install --save-dev typescript ts-loader source-map-loader
npm install --save-dev @typescript-eslint/parser @typescript-eslint/eslint-plugin
npm install --save-dev jest

touch tsconfig.json

mkdir src
mkdir dist

```

## Licence

[MIT](https://github.com/tcnksm/tool/blob/master/LICENCE)

## Author

[ryu-saiwai](https://github.com/tcnksm)