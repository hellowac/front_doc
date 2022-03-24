# 查看模块信息

我们可以查看 **全局** 或 **项目** 下已安装的各模块之间的依赖关系图，下面是语法和结果：

```shell
npm list/ls/la/ll [-g]
```

结果:

```shell
...
├─┬ ssf@0.11.2
  │ │ Format data using ECMA-376 spreadsheet Format Codes
  │ │ git://github.com/SheetJS/ssf.git
  │ │ http://sheetjs.com/
  │ └── frac@1.1.2
  │     Rational approximation with bounded denominator
  │     git://github.com/SheetJS/frac.git
  │     http://sheetjs.com/opensource
  ├── wmf@1.0.2
  │   Windows MetaFile (WMF) parser
  │   git://github.com/SheetJS/js-wmf.git
  │   https://sheetjs.com/
  └── word@0.3.0
      Word Processing Document library
      git://github.com/SheetJS/js-word.git
      https://wordjs.com/
```

## 模块安装路径

我们可以查看 **全局** 或 **项目** 中模块安装的路径：

```shell
npm root [-g]
```

结果:

```shell
~/0ft/rz-data-pool-front: npm root
/Users/wangchao/0ft/rz-data-pool-front/node_modules
```

## 模块信息（名称、版本号、依赖关系、Repo）

我们可以查看模块的注册信息，例如包名称（name）、版本号（version）、描述（description）、作者（author）、版权（license）等等信息。

```shell
npm view <name> [package.json属性名称]
```

结果：

```shell
element-ui@2.15.6 | MIT | deps: 6 | versions: 157
A Component Library for Vue.js.
http://element.eleme.io

keywords: eleme, vue, components

dist
.tarball: https://registry.npmjs.org/element-ui/-/element-ui-2.15.6.tgz
.shasum: c9609add35af5a686a4b7685dc1d757c75e01df3
.integrity: sha512-rcYXEKd/j2G0AgficAOk1Zd1AsnHRkhmrK4yLHmNOiimU2JfsywgfKUjMoFuT6pQx0luhovj8lFjpE4Fnt58Iw==
.unpackedSize: 7.8 MB

dependencies:
async-validator: ~1.8.1                  deepmerge: ^1.2.0                        resize-observer-polyfill: ^1.5.0         
babel-helper-vue-jsx-merge-props: ^2.0.0 normalize-wheel: ^1.0.1                  throttle-debounce: ^1.0.1                

maintainers:
- island205 <island205@gmail.com>
- vivasqiu <vivasqiu@gmail.com>
- baiyaaaaa <286030975@qq.com>
- qingwei.li <cinwell.li@gmail.com>
- jikkai <sonne@asaki.me>
- yi.yang <leopoldthecuber@gmail.com>
- cs1707 <1707@msn.cn>
- iamkun <kunhello@outlook.com>
- yuansu1031 <cao.lei1031@163.com>
- zhiyang-deng <zhiyoung21@gmail.com>

dist-tags:
beta: 1.4.0-beta.1  latest: 2.15.6      legacy: 1.4.13      next: 2.0.0-rc.1    

published 6 months ago by cs1707 <1707@msn.cn>
```

## 全局安装模块

我们可以查看所有已经全局安装的模块。

```shell
npm list -g --depth 0
```

结果:

```shell
/Users/wangchao/.nvm/versions/node/v14.18.1/lib
├── eslint@8.3.0
├── hexo@5.4.0
└── npm@6.14.15
```

## Repo URL

```shell
npm repo <name>
```

**结果**: 跳转到官方库

## 官方文档

```shell
npm docs <name>
```

##
