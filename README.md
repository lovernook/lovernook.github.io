# lovernook · 游戏客户端开发笔记

博客：**https://lovernook.github.io/**

围绕《一笔江湖》的输入评分、回合制联网和 Unity 资源接入，记录问题、实现与验证边界。建立于 2026-09-28。文章基于 AI 辅助开发项目的公开代码与既有测试记录整理，不代表个人学习验收已完成。

## 页面
- index.html：首页、文章目录与项目入口
- gesture-scoring.html：鼠标轨迹与评分
- authoritative-network.html：权威状态、去重与断线恢复
- unity-art-ui.html：骨骼、剔除与可编辑 UI
- styles.css：共享样式；无外部字体、追踪器或脚本依赖

## 发布与维护
GitHub Pages 使用 main 分支根目录；.nojekyll 保留纯静态文件。

修改文章后提交到 main，等待 Pages 部署成功再检查线上页面。可以先在本地直接打开 index.html 预览。新增文章时复制现有文章结构，更改 title、description、canonical、日期和正文；同时更新首页目录及 sitemap.xml。站内链接使用相对路径，外链源码尽量固定到具体 commit。

不要在本站提交购买素材原包、密钥、个人简历文件或私人联系方式。项目源码和演示链接位于首页。源码属于原项目，其素材授权以原项目说明为准。