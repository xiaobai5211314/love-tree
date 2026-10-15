# 爱心树 · 恋爱时光纪念馆 (love.21212121.xyz)

[![Deploy](https://github.com/xiaobai5211314/love-tree/actions/workflows/deploy.yml/badge.svg)](https://github.com/xiaobai5211314/love-tree/actions/workflows/deploy.yml)
[![Website](https://img.shields.io/badge/online-love.21212121.xyz-blue)](https://love.21212121.xyz)

> HTML5 Canvas 动态绽放爱心树与恋爱相伴时光计时器（自 2019-05-20 起），支持手机端动态缩放与触控交互。

---

## 🌐 访问地址
- 官方独立域名：[https://love.21212121.xyz](https://love.21212121.xyz)
- 生产服务器根目录：`/www/wwwroot/love.21212121.xyz/`

## 🛠️ 技术栈与特性
- **动画引擎**：HTML5 Canvas / Jscex 异步树生成 / jQuery / CSS3
- **又拍云 CDN 加速**：
  - 核心脚本库（jQuery, Jscex 体系）全部托管于又拍云存储：`https://guzhicdn.21212121.xyz/asite/assets/vendor/love_tree/`。
  - 背景音乐（`520.mp3`，2.84MB）全量迁移至又拍云 CDN：`https://guzhicdn.21212121.xyz/asite/assets/audio/520.mp3`，极大提升移动端首屏秒开率。
- **站群互联**：界面左上角集成高质感品牌胶囊导航（`xb-brand-pill-container`），直达岁月静好博客主站（`https://21212121.xyz`）与全景导航站（`https://nav.21212121.xyz`）。

## 🚀 自动部署与 CI/CD
本项目已配置 GitHub Actions 自动化持续集成：
- 当向 `main` 分支提交（Push）或合并代码时，GitHub Actions 会自动通过安全 SSH 密钥同步最新代码至生产服务器 `/www/wwwroot/love.21212121.xyz`。

## 📄 授权与许可
详细规范请参考 [AGENTS.md](./AGENTS.md)。
Personal Open Source Project · All Rights Reserved.
