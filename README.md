# JavTube Server Heroku

使用本项目可以快速将`JavTube`后端部署至[`Heroku`](https://heroku.com)云平台。

## 一键部署

[![Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## 具体说明

> 没有Heroku账号的需要先[注册](https://signup.heroku.com/)

- 点击本页面中的[一键部署](#一键部署)按钮创建应用

![deploy](images/deploy.png)

- 在`App name`中输入自定义的应用名
- **建议**将地区选择为美国（`United States`）
- 在`Config Vars`中重新输入新的`TOKEN`并**复制**
- 点击`Deploy app`完成部署

![create](images/create.png)

- 右键**复制**View中的地址（`JavTube Server URL`）

![view](images/view.png)

- 点击View，出现类似如下的页面即为成功部署

![page](images/page.png)

- 在JavTube插件中分别粘贴进之前复制的`JavTube Server URL`与`TOKEN`，即可完成插件配置

![plugin](images/plugin.png)
