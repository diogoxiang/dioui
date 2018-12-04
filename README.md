# dioui
dioUI vue components  web2.0 版 模块集合  可单独使用. 也可集成使用


## lerna manage packages 

```js
例如使用yarn管理包  lerna bootstrap --npm-client=yarn 

lerna add babel   //该命令会在package-1和package-2下安装babel
lerna add react --scope=package-1 // 该命令会在package-1下安装react
lerna add package-2 --scope=package-1 // 该命令会在package-1下安装package-2
```

## CMD cli

```js
    lerna bootstrap： // 安装依赖
    lerna publish：// 发布和更新package
```
