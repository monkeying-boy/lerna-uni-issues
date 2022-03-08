# lerna-uni-issues

## 安装依赖
```shell
yarn bootstrap
```

## bug 复现步骤
切换目录到 `cd ./examples/uni`，执行 `yarn dev:mp-weixin` 或者 `yarn build:mp-weixin`。将 `dist/dev/mp-weixin` 添加到微信开发者工具中。

> 打包后 `src` 同级目录会新增一个 `packages` 文件。 