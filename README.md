本次主要结构为
iot-platform-vue/
├── public/               # 静态资源目录（如 index.html）
├── src/
│   ├── api/              # 封装所有后端请求接口
│   ├── assets/           # 图片、图标等静态资源
│   ├── components/       # 公共组件（如分页、弹窗等）
│   ├── router/           # 路由配置（菜单跳转）
│   ├── store/            # Vuex 状态管理（用户信息、Token等）
│   ├── utils/            # 工具函数（如格式化时间、校验等）
│   ├── views/            # 页面视图（每个模块对应一个文件夹）
│   ├── App.vue           # 根组件
│   └── main.js           # 项目入口文件
├── .env                  # 环境变量配置
├── package.json          # 项目依赖和脚本命令
├── vue.config.js         # Webpack 配置（端口、代理等）
