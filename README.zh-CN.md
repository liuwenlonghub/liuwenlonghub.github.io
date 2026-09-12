# Evan Liu - Physical AI 与机器人

本仓库包含 Evan Liu 的个人作品集网站，内容聚焦于 Physical AI、机器人、硬件、嵌入式系统和软件开发。

[English](README.md) | [简体中文](README.zh-CN.md)

## 项目概览

这是一个轻量级静态网站，包含以下部分：

- **首屏**：介绍网站对 Physical AI 和机器人的关注方向。
- **项目**：展示定制硬件、嵌入式系统和智能物理系统相关工作。
- **关于**：介绍 Evan 的工程背景和当前兴趣。
- **归档**：保存早期作品，包括 320kbps.com 的历史记录。
- **当前方向**：总结目前正在探索的领域。

## 项目结构

```text
.
├── index.html        # 页面结构和内容
├── style.css         # 布局、字体、响应式行为和视觉样式
├── README.md         # 英文项目说明
└── README.zh-CN.md   # 中文项目说明
```

## 本地运行

这是一个静态网站，不需要构建步骤或安装依赖。

### 方式一：直接打开文件

在浏览器中打开 `index.html`。

### 方式二：使用本地 HTTP 服务器

在项目目录中运行：

```bash
python3 -m http.server 8000
```

然后在浏览器中访问 <http://localhost:8000>。

## 自定义内容

- 在 `index.html` 中修改页面内容和导航链接。
- 在 `style.css` 中调整布局、颜色、字体和响应式规则。
- 项目地址确定后，将 `href="#"` 占位链接替换为实际项目 URL。

## 部署

本网站可以部署到任何静态托管服务。GitHub Pages 是适合本仓库的选择：将仓库根目录发布为网站源目录，托管服务会自动使用 `index.html` 作为入口页面。

## 外部链接

- [GitHub](https://github.com/liuwenlonghub)
- [Twitter / X](https://x.com/liuwenlong)
- [wonderful.today](http://wonderful.today)