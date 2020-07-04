# chattrbox

《Web开发权威指南》书中的第3个demo

## commands

```bash
npm install --save-dev nodemon
--save-dev # 安装开发环境依赖 devDependencies

# 查看 package 的 repository 地址
npm fund
npm fund nodemon

# 配置npm的registry地址 && 验证是否成功
npm config set registry https://registry.npm.taobao.org
npm config get registry
npm info express

npm start   # 不用run，因为npm假定start脚本一定存在
npm run dev # 自定义的npm脚本需要显示地强调你想要run这些脚本

npm install --save ws
--save # dependencies 生产环境依赖

npm install -g babel-cli
npm install --save-dev babel-core
npm install --save-dev babel-preset-es2015
npm install --save-dev browserify babelify watchify
babel app/scripts/src/app.js -o app/scripts/dist/main.js


```

## 本地运行项目

```bash
# 进到项目 chattrbox，运行
npm run dev

# 打开一个新的终端，运行
browser-sync start --server --browser "Google Chrome" --files "stylesheets/*.css, *.html, scripts/*.js"

```

## 问题

exit 0

exit 1

## 最佳实践

先报错，早返回
示例能给出最好的说明
