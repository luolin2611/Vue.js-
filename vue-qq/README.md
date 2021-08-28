# vue-qq————仿手机QQ单页面应用



项目地址 `https://github.com/jiangqizheng/vue-MiniQQ`


## 项目已实现功能

* 对话功能——想着既然是QQ总要能进行对话交流，所以在项目中接入了图灵聊天机器人，可以与列表中的每个人物进行对话。
* 左滑删除——左滑删除相关消息。
* 搜索页面——点击右上角搜索按钮，能够进入搜索页面，输入对应的单词或者数字，动态查找好友。
* 项目中数据流动由vuex进行控制



## 技术栈

*  vue-cli
*  vue2
*  vue-router
*  vuex
*  axios
*  stylus
*  webpack2
*  muse-ui


### 目录结构

<pre>
.
├── README.md           
├── build                 // 构建服务和webpack配置,转发聊天机器人以及ajax获取用户数据相关内容
├── config                // 项目不同环境的配置
├── dist                  // 项目build目录
├── index.html            // 项目入口文件
├── package.json          // 项目配置文件
├── mockdata.json         // 项目模拟数据
├── src
│   ├── common            // 公用的css样式
│   ├── components        // 各种组件
│   ├── router            // 存放路由的文件夹
│   ├── vuex	            // 存放Vuex的相关
│   ├── muse-ui.config.js // muse-ui单组件加载配置
│   ├── App.Vue           // 模板文件入口
│   └── main.js           // Webpack 预编译入口
├── static                // css js 和图片资源
│   


</pre>


## Build Setup


``` bash
# 安装
npm install

# 运行（端口8888）
npm run dev

# 发布
npm run build
