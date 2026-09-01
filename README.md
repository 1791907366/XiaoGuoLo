# XiaoGuoLo — PbootCMS 后台美化

一个开箱即用的 **PbootCMS 后台界面美化包**：现代卡片化布局、圆角、柔和阴影、蓝色主题，登录页采用毛玻璃（Glassmorphism）设计。纯前端美化，**不动任何业务逻辑与数据**，覆盖即用、随时可还原。

## ✨ 特性

- 🔑 **登录页**：深蓝渐变 + 动态浮动光斑背景，毛玻璃登录卡片，蓝色渐变登录按钮
- 🧭 **顶部导航栏**：白色底 + 细边框 + 柔和阴影，Logo 深色打底并带版本徽章
- 📂 **侧边栏**：深色菜单、悬停高亮，桌面端可折叠、移动端自动隐藏
- 🎨 **整体风格**：全后台统一蓝色主题，表格 / 按钮 / 卡片圆角 + 柔和阴影，现代字体
- 🧹 **清理缓存页**：圆角胶囊按钮，悬停微动效

## 📦 适用版本

- PbootCMS 3.x（本包基于官方默认后台模板 `apps/admin/view/default` 结构）

## 🚀 安装

1. **备份**（强烈建议）：复制网站根目录 `apps/admin/view/default` 文件夹到别处
2. **覆盖**：将本仓库 `apps/admin/view/default` 下的文件，按相同目录结构覆盖到网站对应位置
3. **清缓存**：登录后台 → 清理缓存 → 清理所有缓存
4. **刷新**：浏览器 `Ctrl + F5` 强制刷新后重新登录

> 📖 详细图文教程见 [`docs/后台美化教程.html`](docs/后台美化教程.html)

## 📁 目录结构

```
XiaoGuoLo
├── apps/admin/view/default/   # 后台模板文件（按 PbootCMS 目录结构存放）
│   ├── index.html             # 登录页面
│   ├── common/                # 公共头部 head.html / 底部 foot.html
│   ├── css/                   # 样式 comm.css（整体）/ login.css（登录页）
│   ├── js/                    # 脚本 comm.js / mylayui.js
│   └── content/               # 清理缓存页 delecache.html
└── docs/                      # 使用教程（HTML）
```

## ⚠️ 说明

- 本美化只涉及后台**外观**，不包含也不修改任何业务数据
- PbootCMS 升级覆盖模板后需重新应用本包
- 如遇问题，可在仓库 Issues 中反馈

## 📄 开源协议

[MIT](LICENSE) © 2026 XiaoGuoLo

## 打赏二维

<p align="center">
  <img src="/donate.png" width="380" alt="donate">
</p>

<p align="center"><strong>开发不易，你的支持让我走的更远</strong></p>
