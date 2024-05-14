# cgd-element-plus

1. 更新版本号 npm run build
2. 搜索 dist/element-plus 文件下'element-plus/替换成'cgd-element-plus/
3. 从 npm 官网上搜索 element-plus 拷贝并替换以下三个文件 attributes.json 和 tags.json 为代码提示文件。记得将 global.d.ts 中路径替换为自己的包名路径。然后就可以发布了。
4. 修改 dist/package.json 中的 name 和 version
5. cd dist/element-plus npm publish 发布
6. https://packages.aliyun.com/npm/npm-registry/guide 根据上面发布到流水线要不然自动化无法打包
