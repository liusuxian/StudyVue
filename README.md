# StudyVue
learning vue

# HBuilderx内置浏览器不能显示控制台
```
lsof -i:9777 | awk '{print $2}' | tail -n +2 | xargs kill -9
```

### 安装 `npm`
`npm` 全称为 `Node Package Manager`，是一个基于`Node.js`的包管理器，也是整个`Node.js`社区最流行、支持的第三方模块最多的包管理器。
```
npm -v
```

### 由于网络原因 安装 `cnpm`
```
npm install -g cnpm --registry=https://registry.npm.taobao.org
```

### 安装 `vue-cli`
```
cnpm install -g @vue/cli
```

### 安装 `webpack`
`webpack` 是  `JavaScript` 打包器(module bundler)
```
cnpm install -g webpack
```
