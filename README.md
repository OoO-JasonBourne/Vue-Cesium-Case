# vue-cesium

## Project setup
```
npm install or npm i
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).



### 项目简介

### 项目流程

##### 1. 引入Cesium 
    npm i cesium -S, 将 cesium/build/Cesium 放到 public 目录下
    在 Public/index.html 中引入 Cesium
    <link rel="stylesheet" href="./Cesium/Widgets/widgets.css">
    <script src="./Cesium/Cesium.js"></script>

##### 2. 引入 vue-draggable-resizable组件，可移动框
    npm i vue-draggable-resizable -S
    注册组件
##### 3. 引入
