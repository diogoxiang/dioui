# dioui
dioUI vue components  web2.0 版 模块集合  可单独使用. 也可集成使用





## lerna manage packages 

```js
 // 例如使用yarn管理包  
lerna bootstrap --npm-client=yarn 

lerna add babel   //该命令会在package-1和package-2下安装babel
lerna add react --scope=package-1 // 该命令会在package-1下安装react
lerna add package-2 --scope=package-1 // 该命令会在package-1下安装package-2
```

## CMD cli

```js
    lerna bootstrap： // 安装依赖
    lerna publish：// 发布和更新package
```


#### commit 编写标准

命名统一为：`<type>(<scope>): <subject>`

```
  1. type — 提交 commit 的类型
      ○ feat: 新功能
      ○ fix: 修复问题
      ○ docs: 修改文档
      ○ style: 修改代码格式，不影响代码逻辑
      ○ refactor: 重构代码，理论上不影响现有功能
      ○ perf: 提升性能
      ○ test: 增加修改测试用例
      ○ chore: 修改工具相关（包括但不限于文档、代码生成等）
      ○ deps: 升级依赖
  2.  scope — 修改文件的范围，可选，包括但不限于 doc / plugins 等。
  3. subject — 用一句话清楚的描述这次提交做了什么。
```

