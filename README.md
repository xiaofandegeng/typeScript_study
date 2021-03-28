#   ts的环境搭建

- 新建目录

```
npm init -y  //创建package.json文件
npm i typescript  //安装ts文件
npx tsc --init  //ts文件初始化

在package.json的scripts里面添加这个
    "prestart": "tsc",
    "start": "node index.js"

npm start //将ts文件转换为js文件并执行
```