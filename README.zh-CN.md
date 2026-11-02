# Evan Liu - Physical AI 与机器人

[English](README.md) | [简体中文](README.zh-CN.md)

本仓库包含 Evan Liu 的个人作品集网站，内容聚焦于 Physical AI、机器人、硬件、嵌入式系统和软件开发。

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

本网站是纯静态站点，无需安装依赖或执行构建命令，可以部署到任何静态托管服务。GitHub Pages 和 Cloudflare Pages 均可直接发布仓库根目录，托管服务会使用 `index.html` 作为入口页面。

### GitHub Pages

将仓库根目录设为网站源目录即可，无需额外构建配置。

### Cloudflare Pages

在 Cloudflare 控制台中创建 Pages 项目并连接此 Git 仓库，然后使用以下构建设置：

| 设置 | 值 |
| --- | --- |
| 框架预设 | None |
| 根目录 | 仓库根目录（默认值） |
| 构建命令 | 留空 |
| 构建输出目录 | `.` |

无需配置环境变量。保存设置后，Cloudflare Pages 会直接发布仓库根目录；之后推送到生产分支时会自动重新部署，Pull Request 也可以生成预览部署。

如需使用自定义域名，请在 Pages 项目的 **Custom domains（自定义域名）** 中添加并完成 DNS 配置。仓库中的 `CNAME` 文件不会自动配置 Cloudflare Pages 的自定义域名。

## 外部链接

- [GitHub](https://github.com/liuwenlonghub)
- [Twitter / X](https://x.com/liuwenlong)
- [wonderful.today](http://wonderful.today)