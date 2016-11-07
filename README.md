# Warlord

前端测试集成方案。

## 下载
```
npm install -g warlord
```
## 使用
直接进入项目根目录进行使用

## API

warlord run lint 跑lint测试
warlord run test 跑自动测试
warlord run coverage 测试覆盖率
warlord run chrome 跑chrome测试
warlord run browsers 跑浏览器测试
bee-tools run dep 下载依赖
bee-tools run update 更新依赖
bee-tools run pub 发布npm包

如果mac使用bee-tools提示`env: node\r: No such file or directory`
请下载dos2unix
```
$brew install dos2unix
$cd /usr/local/lib/node_modules/bee-tools/bin
$sudo dos2unix warlord.js warlord-run.js
```

### 依赖
- karma
- mocha
- karma的浏览器插件
- gulp
- eslint