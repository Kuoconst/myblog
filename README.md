✨ 个人博客
 
基于 Firefly 主题定制的 Astro 静态博客，自用为主，已做个性化样式与功能裁剪。
 
 
 
📌 上游项目
 
- 原主题 Firefly：https://github.com/CuteLeaf/Firefly
- 底层模板 Fuwari：https://github.com/saicaca/fuwari
 
🚀 本地运行
 
环境要求： Node.js >= 22 、 pnpm >= 11 
 
bash
  
# 安装依赖
pnpm install

# 启动本地开发服务器
pnpm dev
 
 
启动后访问  http://localhost:4321  即可实时预览。
 
📁 目录说明
 
- 站点全局配置： src/config/  目录
- 博客文章存放： src/content/posts/ 
- 支持标准 Markdown 及主题扩展语法
 
⚙️ 文章头部配置
 
yaml
  
---
title: 文章标题
published: 2024-01-01
description: 文章简述
tags: [标签1, 标签2]
category: 分类
draft: false
---
 
 
🛠️ 常用命令
 
-  pnpm build  — 构建生产版本，产物输出至  dist  目录
-  pnpm new-post 文件名  — 快速创建一篇新文章
-  pnpm check  — 校验代码与配置文件
-  pnpm preview  — 本地预览构建完成的站点
 
📤 部署
 
纯静态站点，可直接部署到 Vercel、Netlify、GitHub Pages 等平台。
 
📄 开源协议
 
沿用原项目 MIT 开源协议。
