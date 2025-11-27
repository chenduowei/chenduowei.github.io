# 陈多伟的个人博客 · Duowei Chen Blog

基于 **Hugo** + **GitHub Pages** 构建的个人博客，用来记录生活、思考、建筑行业经验，以及我在不同阶段的成长。

在线访问 👉 https://chenduowei.github.io/

---

## ✨ 项目简介

这是我从大学时代保留下来的个人博客，经过 2025 年重新整理、优化与升级。  
它保持了 **极简、快速、可长期维护** 的特性，适合作为我个人写作与表达的主阵地。

博客特点：

- 使用 **Hugo** 静态生成：构建速度极快  
- **LoveIt** 主题：现代、干净、响应式  
- **GitHub Pages** 部署：稳定、省心、免费  
- 支持代码高亮、搜索、评论、标签体系、文章归档等全部核心功能  
- 完全开源，可持续更新

---

## 🛠 技术栈

- **Hugo**：Go 语言实现的高性能静态博客框架  
- **GitHub Pages**：托管与自动部署  
- **LoveIt 主题**：极简、优雅、可高度定制  
- **Markdown**：文章内容全部 Markdown 编写  
- **Utterances**：评论功能，基于 GitHub Issue  

---

## 📚 功能特性

- **文章系统**  
  - 自动生成目录、阅读时间、字数统计  
  - 代码高亮、数学公式、表格、相册、引用  
  - 支持草稿模式与多语言

- **归档与导航**  
  - 分类、标签、年份归档  
  - 文章永久链接（slug/filename），结构稳定

- **主题定制**  
  - 首页个人简介  
  - 社交链接与头像展示  
  - 深色/浅色主题自动切换  
  - Favicon / Logo 自定义  
  - 自定义 Footer、Meta 数据

- **评论系统**  
  - Utterances（GitHub 账户即可评论）

- **搜索**  
  - 基于 Fuse.js 的全文搜索

---

## 🚀 本地开发

```bash
# 克隆项目
git clone https://github.com/chenduowei/hugo-blog-source.git
cd hugo-blog-source

# 本地预览（包含草稿）
hugo server -D
```

访问 http://localhost:1313

---

## 📦 部署说明

项目采用 **代码分仓** 的最佳实践：

| 仓库 | 作用 |
|------|------|
| **hugo-blog-source** | 文章 + 模板 + 配置（主仓库） |
| **chenduowei.github.io** | 存放 Hugo 构建后的 `public/` 静态文件 |

部署方式：

```bash
# 构建静态文件
hugo -D

# 将 public/ 推送到 chenduowei.github.io 仓库
cd public
git add .
git commit -m "Update site"
git push
```

GitHub Pages 会自动无服务器部署。

---

## 🧭 目录结构（精简版）

```
.
├── content/             # 博客文章（Markdown）
├── config.toml          # 博客全局配置
├── themes/              # LoveIt 主题
├── static/              # 图片、图标、自定义资源
├── assets/              # CSS & JS（可自定义）
└── public/              # 构建后的静态文件（部署目录）
```

---

## 🌱 项目收获

通过维护这个博客，我获得了：

- 对 Hugo 系统的深入理解  
- 对 GitHub Pages 部署流程的熟练掌握  
- 更高效的 Markdown 写作能力  
- 能自由定制主题、前端样式与构建逻辑  
- 一个长期属于自己的写作空间  

它不仅是技术项目，也是我记录生活与思考的地方。

---

## 🗺 未来计划

- 添加社交分享功能  
- 优化 SEO（Meta、结构化数据）  
- 文章批量迁移 & 旧文章整理  
- 深度定制 LoveIt 主题（布局、性能、交互）  
- 支持评论系统（Utterances）  
- 移动端体验优化  
- 持续更新博客文章  

---

## 📬 联系方式

GitHub：https://github.com/chenduowei  
Email：duowei_chen@outlook.com

如果你对 Hugo 架构、博客搭建或静态网站感兴趣，也欢迎交流。

“文字是一个人最长期、最隐秘、最诚实的自我。”  
—— 这就是我继续写博客的理由。
