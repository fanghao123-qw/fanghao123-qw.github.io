
<h1 align="center">
AcadHomepage
</h1>

<div align="center">

[![](https://img.shields.io/github/stars/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/forks/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/issues/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io)
[![](https://img.shields.io/github/license/RayeRen/acad-homepage.github.io)](https://github.com/RayeRen/acad-homepage.github.io/blob/main/LICENSE)  | [中文文档](./docs/README-zh.md) 
</div>

<p align="center">现代化、响应式的学术个人主页模板</p>

<p align="center">
    <br>
    <img src="docs/screenshot.png" width="100%"/>
    <br>
</p>

部分示例：
- [演示页面](https://rayeren.github.io/acad-homepage.github.io/)
- [作者的个人主页](https://rayeren.github.io/)

## 核心特性

- **自动更新 Google Scholar 引用**：利用 Google Scholar 爬虫和 GitHub Actions，本项目可以自动更新作者的引用次数和发表论文的引用数据。
- **支持 Google Analytics**：通过简单的配置即可追踪您主页的访问流量。
- **响应式设计**：主页会自动适配不同的屏幕尺寸和视口。
- **美观简洁的设计**：主页设计美观简洁，非常适合作为学术个人主页。
- **SEO 优化**：搜索引擎优化（SEO）帮助搜索引擎轻松找到您发布在主页上的信息，并在同类网站中进行排名。

## 快速开始

1. Fork 本仓库并重命名为 `USERNAME.github.io`，其中 `USERNAME` 是您的 GitHub 用户名。
1. 配置 Google Scholar 引用爬虫：
    1. 在您的 Google Scholar 页面 URL 中找到您的 Google Scholar ID（例如：https://scholar.google.com/citations?user=SCHOLAR_ID），其中 `SCHOLAR_ID` 就是您的 Google Scholar ID。
    1. 在仓库的 `Settings -> Secrets -> Actions -> New repository secret` 中设置 `GOOGLE_SCHOLAR_ID` 变量，其中 `name=GOOGLE_SCHOLAR_ID`，`value=SCHOLAR_ID`。
    1. 点击仓库的 `Actions`，然后点击 *"I understand my workflows, go ahead and enable them"* 启用工作流。GitHub Actions 会在仓库的 `google-scholar-stats` 分支生成 Google Scholar 引用统计数据 `gs_data.json`。当您更新 main 分支时，此操作会被触发。此外，该操作还会在每天 UTC 时间 08:00 自动执行。
1. 使用 [favicon-generator](https://redketchup.io/favicon-generator) 生成网站图标，并将所有生成的文件下载到 `仓库/images` 目录。
1. 修改主页配置文件 `_config.yml`：
    1. `title`：主页标题
    1. `description`：主页描述
    1. `repository`：USER_NAME/REPO_NAME  
    1. `google_analytics_id`（可选）：Google Analytics ID
    1. SEO 相关配置（可选）：从搜索引擎控制台（如 Google、Bing 和百度）获取这些密钥并粘贴到此处。
    1. `author`：主页作者信息，包括其他网站链接、邮箱、城市和大学等。
    1. 更多配置详情请参阅文件中的注释。
1. 在 `_pages/about.md` 中添加您的主页内容。
    1. 您可以使用与 Jekyll 相同的 HTML+Markdown 语法。
    1. 您可以使用带有 `show_paper_citations` 类名和 `data` 属性的 `<span>` 标签来显示论文的引用次数。将 data 属性设置为 Google Scholar 论文 ID，例如：
        ```html
        <span class='show_paper_citations' data='DhtAFkwAAAAJ:ALROH1vI_8AC'></span>
        ``` 
        > 问：如何获取 Google Scholar 论文 ID？   
        > 答：进入您的 Google Scholar 首页，点击论文名称。然后您可以从 `citation_for_view=XXXX` 中看到论文 ID，其中 `XXXX` 就是所需的论文 ID。
1. 您的主页将发布在 `https://USERNAME.github.io`。

## 本地调试

1. 使用 `git clone` 将仓库克隆到本地。
1. 按照 [安装指南](https://jekyllrb.com/docs/installation/#requirements) 安装 Jekyll 构建环境，包括 `Ruby`、`RubyGems`、`GCC` 和 `Make`。
1. 运行 `bash run_server.sh` 启动 Jekyll 热重载服务器。
1. 在浏览器中打开 http://127.0.0.1:4000。
1. 如果您修改了网站的源代码，热重载服务器会自动刷新页面。
1. 完成主页修改后，使用 `git` 命令 `commit` 更改并 `push` 到远程仓库。

## 致谢

- AcadHomepage 使用了 Font Awesome，遵循 SIL OFL 1.1 和 MIT License 协议。
- AcadHomepage 参考了 GitHub 仓库 [mmistakes/minimal-mistakes](https://github.com/mmistakes/minimal-mistakes)，遵循 MIT License 协议。
- AcadHomepage 参考了 GitHub 仓库 [academicpages/academicpages.github.io](https://github.com/academicpages/academicpages.github.io)，遵循 MIT License 协议。
