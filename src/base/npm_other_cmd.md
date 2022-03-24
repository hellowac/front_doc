# 其他常用命令

## 初始化package.json

```shell
npm init
```

## 帮助

```shell
npm help
npm -h
```

## 清除缓存

```shell
npm cache clean
```

## 验证缓存

```shell
npm cache verify
```

## script

```shell
npm run <command>
```

## 其他

### 可选参数说明

```shell
--save      // 将模块依赖关系写入到package.json文件的dependencies参数中
-dev        // 将模块依赖关系写入到package.json文件的devDependencies参数中
-g          // 表示全局
@+version   // 安装指定版本
```

### 参考网站

- NPM官网: <https://docs.npmjs.com/cli/npm>
- NPM中文网: <https://www.npmjs.com.cn/cli/npm/>
- 菜鸟教程: <http://www.runoob.com/nodejs/nodejs-npm.html>
