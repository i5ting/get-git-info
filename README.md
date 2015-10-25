# get-git-info

获取当前git的remote地址里的user和project

[![npm version](https://badge.fury.io/js/get-git-info.svg)](http://badge.fury.io/js/get-git-info)

## Install 

```
npm install --save get-git-info
```

## Usages

```
var cfg = require('get-git-info')(__dirname);
console.log(cfg)
```

以当前项目为例

打印出

```
{ user: 'i5ting', project: 'get-git-info' }
```
