# 陈多伟的个人博客 · Duowei Chen Blog

基于 **Hugo** + **GitHub Actions** + **GitHub Pages** 构建的个人博客，用来记录生活、思考、行业经验，以及我在不同阶段的成长。

在线访问 👉 [https://chenduowei.github.io/](https://chenduowei.github.io/)

---

## ✨ 项目简介

这是我从大学时代保留下来的个人博客，经过重构与优化，目前采用了**单仓库 + GitHub Actions 云端自动化部署**的现代极简架构。

博客特点：

- **极速构建**：使用 **Hugo** 静态引擎，秒级渲染页面
- **现代美观**：基于 **LoveIt** 主题，干净、响应式、支持深色模式切换
- **自动化部署**：源码推送即自动编译构建，无需本地生成静态文件
- **功能完备**：支持全文搜索、代码高亮、文章归档与标签体系
- **独立可控**：数据完全由 Markdown 掌控，轻量且适合长期写作

---

## 🛠 技术栈

- **Hugo**：Go 语言实现的超高性能静态网站生成器
- **GitHub Actions**：云端 CI/CD 自动化构建与部署
- **GitHub Pages**：静态站点托管
- **LoveIt Theme**：优雅、极简、功能丰富的 Hugo 主题
- **Markdown**：纯文本写作

---

## 🚀 本地开发与预览

如果你需要在本地编写文章或预览效果：

```powershell
# 1. 克隆项目
git clone [https://github.com/chenduowei/chenduowei.github.io.git](https://github.com/chenduowei/chenduowei.github.io.git)
cd chenduowei.github.io

# 2. 本地实时预览（包含草稿）
hugo server -D
```

访问本地地址：`http://localhost:1313`

---

## 📦 部署架构与发布流程

本项目采用了 **GitHub Actions 云端自动化构建** 的最佳实践，彻底去除了本地手动编译及 `public/` 提交的繁琐步骤。

```text
[本地编写 Markdown] ──(git push)──> [GitHub 源码仓库] ──(Actions 云端编译)──> [GitHub Pages 上线]
```

### 极简发布三步法

写完文章（确保 `draft: false`）后，在终端运行以下三行命令即可：

```powershell
git add .
git commit -m "feat: 发布新文章"
git push
```

云端 Actions 会在 30 秒内自动完成编译并更新博客。

---

## 🧭 项目目录结构

```text
.
├── content/          # 博客文章与页面源码（Markdown）
│   └── posts/        # 文章主目录
├── config.toml       # Hugo 全局配置文件
├── themes/           # LoveIt 主题目录
├── static/           # 静态资源（图片、favicon 等）
├── .github/          # GitHub Actions 自动化部署工作流配置
└── .gitignore        # Git 忽略配置（包含 public/ 等编译目录）
```

---

## 🌱 项目收获

通过长期维护这个博客，我建立了：

- 一套完全自动化、无痛感的写作与发布流程
- 对 Hugo 架构与 GitHub CI/CD 自动化构建的深入理解
- 一个长期独立属于自己、不受平台限制的思考与文字空间

---

## 📬 联系方式

- **GitHub**：[https://github.com/chenduowei](https://github.com/chenduowei)
- **Email**：`duowei_chen@outlook.com`

> “文字是一个人最长期、最隐秘、最诚实的自我。”