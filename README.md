#  卡片Demo

## 注意
1. 卡片使用的是vivo的打包工具 [vivo-hap-toolkit](https://www.npmjs.com/package/vivo-hap-toolkit)
2. 手机端需要安装卡片调试器、卡片引擎
3. 卡片开发是单独一个项目，不要和原有的快应用项目混在一起

## 安装预览
1. 进入项目目录执行 `npm install`  安装依赖
2. `npm run watch -- --vivo` 执行编译并监听
3. 在另外一个终端 `npm run server` 开启服务器，用卡片调试器扫描二维码预览

## 打包编译

打包卡片时需要添加 --vivo 参数
`npm run build -- --vivo` 或者 `npm run release -- --vivo`