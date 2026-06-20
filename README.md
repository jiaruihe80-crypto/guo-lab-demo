# 郭开喆个人学术主页

这是基于 `academicpages/academicpages.github.io` 组织的 Jekyll 个人主页，用于后续部署到 GitHub Pages。

## 内容结构

- `_config.yml`：站点和作者信息
- `_data/navigation.yml`：顶部导航
- `_pages/about.md`：个人简介
- `_pages/research.md`：研究方向
- `_pages/publications.md`：论文发表
- `_pages/cv.md`：履历
- `_pages/contact.md`：联系信息

## academicpages 结构

项目按 `academicpages/academicpages.github.io` 的 Jekyll 结构组织：`_config.yml` 管理站点与作者信息，`_data/navigation.yml` 管理导航，主要页面放在 `_pages/` 中。首页由 `_pages/about.md` 的 `permalink: /` 提供。

## 本地预览

安装 Ruby 和 Bundler 后运行：

```bash
bundle install
bundle exec jekyll serve --host 127.0.0.1 --port 4000
```

然后访问 `http://127.0.0.1:4000`。

## GitHub Pages 部署

后续注册 GitHub 账号后，可创建一个新的仓库，将本项目推送上去，并在仓库 Settings -> Pages 中启用 GitHub Pages。此项目使用 `github-pages` 和 `jekyll-remote-theme`，适合直接部署为 GitHub Pages 站点。
