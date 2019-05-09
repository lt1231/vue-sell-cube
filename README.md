### vue-sell-cube
### 项目已使用vue2.5重构。
### 本项目来源于慕课网黄轶老师的Vue.js2.5+cube-ui重构饿了么App https://coding.imooc.com/learn/list/74.html。



### 项目技术栈
***
*  vue-cli搭建项目脚手架
*  cube-ui 实现页面布局，及所有的动画效果
*  vue
*  vue-axios实现跨域
*  stylus
*  webpack实现项目的打包构建
### 采用mock数据来模拟服务端交互
### 项目介绍：此项目共有商品页，商品详情页、评价页，商家页，共四个模块。具体页面及功能如下图
***
* 商品页，加入购物车动画

![11.gif](http://upload-images.jianshu.io/upload_images/4249223-8d462b93150db24e.gif?imageMogr2/auto-orient/strip)

* 弹出购物车 商品详情页

![2222.gif](http://upload-images.jianshu.io/upload_images/4249223-71b66b4249d868bd.gif?imageMogr2/auto-orient/strip)

* 分类切换 图片左右滑动

![3333.gif](http://upload-images.jianshu.io/upload_images/4249223-f0921b44740f6d4f.gif?imageMogr2/auto-orient/strip)

###安装
***
项目地址：（`git clone`）
```shell
git clone https://github.com/lt1231/vue-sell-cube.git
```
通过`npm`安装本地服务第三方依赖模块(需要已安装[Node.js](https://nodejs.org/))

```
npm install
```
启动服务(http://localhost:8080)

```
npm run dev
```
发布代码

```
npm run build
```
### 安装注意
安装 vue-cli
```
npm install -g vue-cli
```
安装 vue-cli eslint
```
npm install -g eslint
```
安装依赖 friendly-errors-webpack-plugin
```
npm install friendly-errors-webpack-plugin --save-dev
```
###目录结构
***
<pre>
├── build              // 构建服务和webpack配置
├── config             // 项目不同环境的配置
├── dist               // 项目build目录
├── index.html         // 项目入口文件
├── package.json       // 项目配置文件
├── src                // 生产目录
│   ├── assets         // 图片资源
│   ├── common          // 公共的css js 资源
│   ├── components     // 各种组件
│   ├── App.vue         // 主页面 
│   └── main.js        // Webpack 预编译入口
</pre>

###实现的功能
***
* 商品滚动 ，商品滚轮滚动
* 商品联动
* 加入购物车，移除购物车
* 显示评论 评论筛选
* 图片左右滑动
* 商品详情  父子组件的通信
* 等等
