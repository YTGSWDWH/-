#### node.js是一个基于Chrome V8引擎的JavaScript运行环境,现在可以运行在任何装有Node.js的环境中
#### Express框架本身是对Node.js中的HTTP模块进行的一层抽象
### Express的主要功能
* 设置中间件来响应HTTP请求
* 定义路由表执行不同的HTTP请求动作
* 通过向模板传递参数动态渲染HTML页面
### 状态码
* 200表示请求成功
* 300系列表示重定向
* 400系列表示客户端错误
* 500系列表示服务端错误
#### Vue.js是构建Web页面的JavaScript库，通过简洁的API提供高效的数据绑定和灵活的组件系统
#### 如果想要使用Vue.js编写程序，需要Webpack打包工具将.vue文件编译成普通的JavaScript文件，再通过页面的引入去执行这个JavaScript文件
### express请求支持的常见HTTP方法
* get()：请求指定的页面信息，并返回实体主体
* post()：向指定资源提交数据处理请求(例如提交表单或者上传文件)。数据包含在请求体中。POST请求可能会创建新资源或者修改已有资源。
* all()：捕获所有请求的方法，它会在所有该地址的请求前执行
#### 路由的路径可以传递参数。在定义路径时，通过“:”标记来确定参数的名称。之后可以通过res参数中params对象获取该参数，res为响应，req为请求
### 新建Express应用
* 构建不包含模板显示功能的Express服务：express --no-view 项目
* 构建使用服务器端渲染模板的Express服务：express --view <模板引擎>
### 启动Express项目
* Windows cmd：SET DEBUG=myapp:* & npm start
* vscode终端：$env:DEBUG='myapp:* '; npm start
### next()：把控制权交给下一个处理程序(handler)
