# mpvue-vant

> mpvue+vant+scss 开发微信小程序

## Build Setup

```bash
# mpvue官网
http://mpvue.com/mpvue/

# vant官网
https://youzan.github.io/vant-weapp/#/intro

# iview官网
https://weapp.iviewui.com/docs/guide/start

# 初始化项目
vue init mpvue/mpvue-quickstart myproject
cd myproject

# 安装依赖
npm install

# 引入vant组件库
git clone https://github.com/youzan/vant-weapp.git
组件放到新建文件夹下static/vant

# 页面使用vant组件
"usingComponents": {
    "van-row": "/static/vant/row/index",
    "van-col": "/static/vant/col/index"
},

# 引入iview组件库
git clone git@github.com:TalkingData/iview-weapp.git
组件放到新建文件夹下static/vant

# 页面使用iview组件
"usingComponents": {
    "i-button": "/static/iview/button/index",
    "i-load-more": "/static/iview/load-more/index"
},

# 安装scss预处理器
npm install node-sass sass-loader --save-dev

# 开发时构建
npm run dev

# 打包构建
npm run build

# 指定平台的开发时构建(微信、百度、头条、支付宝)
npm run dev:wx
npm run dev:swan
npm run dev:tt
npm run dev:my

# 指定平台的打包构建
npm run build:wx
npm run build:swan
npm run build:tt
npm run build:my

# 生成 bundle 分析报告
npm run build --report
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
