# supermall

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

一、划分目录结构
assets 资源
  css (引用了两个css文件)
    normalize.css 通过npm添加的 npm install --save normalize.css
    base.css

  img

commponents  公共组件
  分两类  common
          content

views
  category
  home

router

store  公共状态管理

network  网络相关

common   放公共的js文件

3、
vue.config.js  配置全局别名
.editorconfig  配置全局代码样式（风格）

4、项目模块划分: tabbar -> 路由映射关系

