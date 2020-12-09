<h1 align="center">modp-front</h1>

## 简介
modp-front是一个后台管理系统的前端页面展示，是由vue-cli4和elemnet-ui搭建实现的。
使用了vue3框架，内部采用了组件化开发模式，尽可能使得每个组件都遵循单一功能原则
项目采用弹性盒（flex）布局，故而在移动端也有着较好的显示效果

## 演示()
[账号密码](admin/admin)


## 开发
```bash
# 克隆项目
git clone git@github.com:HTree/modp-front.git

# 进入项目目录
cd modp-front

# 安装依赖
npm install

# 建议不要用 cnpm 安装 会有各种诡异的bug 可以通过如下操作解决 npm 下载速度慢的问题
npm install --registry=https://registry.npm.taobao.org

# 启动服务
npm run serve
```

浏览器访问 http://localhost:8080

## 发布

```bash
# 构建生产环境
npm run build
```  
## 备注

```javascript
// 页面查看顺序(登录页（views/Login）-> 首页(views/Home/Dashboard))，其中views/Home为其他页面的公共引用部分
// 与后端交互接口（请查看service/index.ts，数据由mock.js产生；实际开发请查看util/request.ts）
// 根据vue-cli示例，主页面index.vue中会采用vue2的写法
```
