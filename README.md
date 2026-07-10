# 郭笑玮 — 编程教师个人作品集

基于 **Python MkDocs + Material Design** 构建的个人作品集网站。

## 🚀 本地运行

```bash
pip install -r requirements.txt
mkdocs serve
```

打开 http://localhost:8000 预览。

## 📦 部署到 GitHub Pages

```bash
mkdocs gh-deploy
```

## 📂 项目结构

```
teacher-portfolio/
├── mkdocs.yml          # 配置文件
├── docs/               # 内容文件
│   ├── index.md        # 首页
│   ├── about.md        # 关于我
│   ├── projects.md     # 项目作品
│   └── blog.md         # 技术文章
├── requirements.txt    # Python 依赖
└── README.md
```

## 🛠️ 技术栈

- **Python 3.12** + **MkDocs 1.6**
- **Material for MkDocs 9.7** — Material Design 主题
- **GitHub Pages** — 静态站点托管
