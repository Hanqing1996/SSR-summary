#### SSR 参考
* [react 的页面渲染是JS负责进行的；而SSR是是服务器端直接返回HTML让浏览器直接渲染。](https://zhuanlan.zhihu.com/p/76967335)
---
#### 静态资源包括哪些?
> images, CSS files, and JavaScript files

#### [express 访问静态资源](http://expressjs.com/en/starter/static-files.html)
> 如何以URL形式访问express服务器目录下的静态资源文件夹



#### [Web静态资源缓存及优化](https://zhuanlan.zhihu.com/p/30780216)
* 对静态资源的要求
1. 页面以最快的速度获取到所有必须静态资源，渲染飞快；
2. 服务器上静态资源未更新时再次访问不请求服务器；
3. 服务器上静态资源更新时请求服务器最新资源，加载又飞快。



---
#### 浏览器请求种类
1. 静态资源请求：比如请求html,css,js,img等静态资源，其作用在于把应用前台UI渲染出来。
2. 接口请求, 也就是请求后台接口，返回JSON格式数据。

