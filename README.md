#创建uniapp项目

首先全局安装 vue-cli

npm install -g @vue/cli

然后使用vue命令生成uniapp使用正式版

vue create -p dcloudio/uni-preset-vue echocloud-vue-uniapp

使用alpha版
vue create -p dcloudio/uni-preset-vue#alpha echocloud-alpha-vue-uniapp

使用Vue3/Vite版

创建以 javascript 开发的工程（如命令行创建失败，请直接访问 gitee:https://gitee.com/dcloud/uni-preset-vue/repository/archive/vite.zip 下载模板）
npx degit dcloudio/uni-preset-vue#vite echocloud-alpha-vitejs-uniapp

创建以 typescript 开发的工程（如命令行创建失败，请直接访问 gitee:https://gitee.com/dcloud/uni-preset-vue/repository/archive/vite-ts.zip 下载模板）
npx degit dcloudio/uni-preset-vue#vite-ts echocloud-alpha-vitets-uniapp

npx简单介绍

由于npm 5.2.0版本的npx预先绑定在npm中，所以这是现在的一种标准。npx也是一个CLI工具，它的目的是让安装和管理托管在npm注册表中的依赖更容易。现在可以很容易地运行任何基于Node.js的可执行文件，而你通常会通过npm安装这些文件


创建项目

# echocloud-vue-uniapp

## Project setup
```
yarn install
```

### Compiles and hot-reloads for development
```
yarn serve
```

### Compiles and minifies for production
```
yarn build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
