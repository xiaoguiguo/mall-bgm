# mall-bgm

## Project setup
```
npm install
```
安装项目需要的组件

### Compiles and hot-reloads for development
```
npm run serve
```
启动项目

### Compiles and minifies for production
```
npm run build
```
打包

# package.json
babel-polyfill      // 使低版本的浏览器支持ES6的语法
mavon-editor        //支持markdown编辑器
vue-cropperjs       //对图片的裁剪
vue-quill-editor    //富文本编辑器
vue-schart          //图表组件
vuedraggable        //拖动组件
vue-i18n            //国际化组件
element-ui          //样式组件
vuerouter           //路由

# 项目文件说明
app.vue     //根文件
main.js     //引入全局变量，组件，样式，包括
index.js    //引入自定义组件（.vue），通过路由实现跳转，没个
xxx.vue     //自定义组件，每个自定义组件都需要export导出，被其他js文件引用

# 模拟登录功能，跳转到首页
暂时使用localstorage来存储用户名密码
