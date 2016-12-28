# HWFC官方网站项目初始包，已不再使用，最新的仓库链接为（https://github.com/Liveipool/HWFC）     

> Hello World Football Club 官方网站    
> 使用vue+webpack+express+mongodb进行构建，还使用bootstrap等框架。

## 启动方式

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification（开发时忽略即可）
npm run build
```
## 目录结构
- build、config等文件夹负责装一些配置文件，后台代码文件等。   
- static文件夹装载一些静态资源文件,里面的assets用来放置图片。    
- src文件夹下为前端代码文件。   
- index.html文件为项目的启动html文件。  
- .editorconfig文件用于帮助开发者在不同的编辑器和IDE之间定义和维护一致的代码风格，建议看一下。  

src文件夹内：
- routes.js:  记录路由信息    
- main.js:  创建项目启动文件index.html里的app Vue实例   
- Main.vue:  项目的通用界面框架模板   
- components/:  放置项目的通用界面框架模板里的一些组件   
- pages:/ 放置各具体功能页面，每个页面单独一个文件夹，如：pages/404/， pages/Home/

举例介绍，在各具体功能的文件夹中，如pages/Home/里，有一个Home.vue，一个components文件夹，Home.vue负责写出各组件的排布而不关心组件具体是什么内容，components文件夹里则是编写各具体组件。

这样讲可能还有点抽象，但给出的initial packet中已经有了具体的代码样例，根据代码应该比较容易理解。

## 命名规范
我们的类名均采用横线连接，如head-bar, nav-list.  
由于vue会将组件名从驼峰法转为横线连接法，如HeadBar组件在应用时会被自动改写为head-bar，为了与类名等区分，我们的组件名以及组件文件的命名均采用驼峰命名法，如Home.vue，BottomBar，大驼峰法和小驼峰法均可，但初始包是采用的大驼峰法，所以建议都使用大驼峰法。   

## 项目包分析  
[HWFC项目包分析博客:http://liveipool.com/blog/2016/12/18/Understanding-of-HWFC-Project-1/](http://liveipool.com/blog/2016/12/18/Understanding-of-HWFC-Project-1/)
