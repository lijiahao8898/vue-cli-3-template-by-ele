# vue-template

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve / npm run dev / npm start
```

### Compiles and minifies for production
```
npm run build
```

### Run your tests
```
npm run test
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### 目录结构

```
.
├── README.md
├── babel.config.js
├── package-lock.json
├── package.json
├── public
│   ├── favicon.ico
│   └── index.html
├── src
│   ├── App.vue
│   ├── api
│   │   ├── config.js
│   │   └── index.js
│   ├── assets
│   │   ├── logo.png
│   │   └── style
│   │       ├── config.scss
│   │       └── reset.scss
│   ├── components
│   │   ├── HelloWorld.vue
│   │   └── sider
│   │       └── index.vue
│   ├── element-variables.scss
│   ├── main.js
│   ├── pages
│   │   ├── home
│   │   │   └── index.vue
│   │   └── login
│   │       └── index.vue
│   ├── plugins
│   │   └── element.js
│   ├── routers
│   │   └── index.js
│   └── store
│       ├── index.js
│       └── modules
│           └── system.js
├── tree.text
└── vue.config.js

14 directories, 24 files

```

## Element-ui

### 按需加载
```textmate
npm install babel-plugin-component -D
```
```js
{
  "presets": [["es2015", { "modules": false }]],
  "plugins": [
    [
      "component",
      {
        "libraryName": "element-ui",
        "styleLibraryName": "theme-chalk"
      }
    ]
  ]
}
```

See [element-ui](https://element.eleme.cn/#/zh-CN)
