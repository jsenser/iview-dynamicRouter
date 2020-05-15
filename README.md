<p align="center">
  <a href="https://www.iviewui.com">
    <img width="200" src="https://file.iviewui.com/logo-new.svg">
  </a>
</p>

# iView DynamicRouter

<a href="https://github.com/vuejs/vue">
  <img src="https://img.shields.io/badge/vue-2.5.10-brightgreen.svg?style=flat-square">
</a>
<a href="https://github.com/iview/iview">
  <img src="https://img.shields.io/badge/iview-3.1.3-brightgreen.svg?style=flat-square">
</a>
<a href="https://github.com/iview/iview-admin/tree/template">
  <img src="https://img.shields.io/badge/iview--admin-template-brightgreen">
</a>

- #### 基于<a href="https://github.com/iview/iview-admin/tree/template" target="_blank">iview-admin(branch:template)</a>，动态获取路由数据，经数据处理后生成动态路由和菜单的【后端动态路由模板】  
- <a href="https://simon9124.github.io/iview-dynamicRouter" target="_blank">在线预览</a>
- <a href="https://simon9124.github.io/iview-dynamicRouter-doc" target="_blank">使用文档（更新中）</a>
- userName：super_admin / visitor
- password：any / any

如果这个模板或模板中的代码段能够在开发中帮助到你，请在右上角star一下，非常感谢～  
If the template can help you in your work, please give a ⭐️ for motivation

## 目录结构

```bash
- config  开发相关配置
- public  打包所需静态资源
- src
  - api  AJAX请求   -> 追加：动态获取路由方法
  - assets  项目静态资源
  - icons  自定义图标资源
  - images  图片资源
  - components  业务组件
  - config  项目运行配置
  - directive  自定义指令
  - libs  封装工具函数   -> 追加：若干路由数据处理函数
  - locale  多语言文件
  - mock  mock模拟数据   -> 追加：路由列表、路由层级、角色列表 等数据
  - router  路由配置   -> 有较多改动
  - store  Vuex配置   -> 有较多改动
  - view  页面文件   -> 追加：template.vue 和 screent.vue 页面模板
  - tests  测试相关
```

## 安装使用

```bash
# 克隆项目
git clone https://github.com/simon9124/iview-dynamicRouter

# 进入项目目录
cd vue-element-admin

# 安装依赖
npm install

# 本地开发 启动项目
npm run dev
```

启动完成后，在控制台可监听【当前路由】和【左侧菜单】：
<img src="https://mmbiz.qpic.cn/mmbiz_png/Tlm6c1DNgXQMvtNjibjXM4hxUhrRpicuaRaHw2ibHmia0ZPvCkfia5ckocfK1w4CJwejVEJ95d4A54UzZI3hnEge6sA/0?wx_fmt=png">
