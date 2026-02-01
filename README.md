# uptime-status
基于 uptime api 实现的单HTML页面，展示指定的网站状态

## 使用方法
1. 登录 [uptimerobot](https://uptimerobot.com/) ,进入 API 管理页面，获取复制 Read Only API
2. 修改文件中的配置项（在 <script> 中的 window.Config）：
- ApiKeys: 你的 UptimeRobot API Key
- SiteName: 站点名称
- CountDays: 统计天数
- Navi: 导航菜单
3. 保存提交，开启 Github Pages 页面部署，完成部署后访问即可，如 [uptime-status](https://shonee.github.io/uptime-status/)。
<img width="2010" height="1356" alt="image" src="https://github.com/user-attachments/assets/7a18ea85-2558-4b33-a7e4-d5da4006d34f" />


## 参考项目
- [Qikaile/uptime-status: 基于 UptimeRobot api 时时监控主机、网站、端口等在线状态；](https://github.com/Qikaile/uptime-status?tab=readme-ov-file) 
- [JLinMr/Uptime-Status: 优雅的站点状态监控面板](https://github.com/JLinMr/Uptime-Status) Node.js + Vue 开发，UptimeRobot API + Tencent EdgeOne 部署
- [lixiaomuicon/UptimeRobot: UptimeRobot网站状态监控](https://github.com/lixiaomuicon/UptimeRobot?tab=readme-ov-file) 
- [shaoyouvip/uptime: 一个基于 UptimeRobot API 的在线状态面板 | 站点监测 | 状态检测 | An online status panel based on the UptimeRobot API | UptimeRobot, status, site](https://github.com/shaoyouvip/uptime)  HTML + js 开发，vercel 或 cf 部署
- [geekyouth/uptime-status: 🤞✨基于 UptimeRobot api 时时监控主机、网站、端口等在线状态 💕💖 | https://up.java666.cn/ | https://stats.uptimerobot.com/OJRWxTANwN](https://github.com/geekyouth/uptime-status)  HTML + js 开发，vercel、netlify 部署
- [nianshu2022/Uptime-Monitor: 基于 Cloudflare Workers + D1 构建的轻量级网站监控系统。支持 SSL/域名过期检测、钉钉报警、自定义状态页。](https://github.com/nianshu2022/Uptime-Monitor) 
- [upptime/upptime: ⬆️ GitHub Actions uptime monitor & status page by @AnandChowdhary](https://github.com/upptime/upptime) 
- [songquanpeng/stats-cards: 在 README 中展示你在知乎，GitHub，B 站，LeetCode，掘金，CSDN，牛客等网站的数据，也可用于服务状态监控. Show your LeetCode & GitHub stats in GitHub Profile.](https://github.com/songquanpeng/stats-cards)
- [lyc8503/UptimeFlare: ✔ Free and serverless uptime monitoring / status page on Cloudflare Workers, with Geo-specific checks](https://github.com/lyc8503/UptimeFlare) 


- [不蒜子 - 极简网页计数器](https://busuanzi.ibruce.info/)
- [自建不蒜子 - 网站访问量统计](https://busuanzi.9420.ltd/)
- [busuanzi/README.zh_CN.md at main · soxft/busuanzi](https://github.com/soxft/busuanzi/blob/main/README.zh_CN.md) 
- [自建 不蒜子 API](https://busuanzi.icodeq.com/) 


