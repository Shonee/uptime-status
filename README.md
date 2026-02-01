# uptime-status
基于 uptime api 实现的单HTML页面，展示指定的网站状态

# 使用方法
1. 登录 [uptimerobot](https://uptimerobot.com/) ,进入 API 管理页面，获取复制 Read Only API
2. 修改文件中的配置项（在 <script> 中的 window.Config）：
- ApiKeys: 你的 UptimeRobot API Key
- SiteName: 站点名称
- CountDays: 统计天数
- Navi: 导航菜单
3. 保存提交，开启 Github Pages 页面部署，完成部署后访问即可，如 [uptime-status](https://shonee.github.io/uptime-status/)。

