---
{"dg-publish":true,"permalink":"/tokipdocs/","tags":["gardenEntry"],"dgHomeLink":true,"dgShowFileTree":true,"dgEnableSearch":true}
---

This is tokipdocs.


项目结构分析结果：

1. 项目类型：

- 基于Eleventy(11ty)的静态知识管理系统/数字花园
- 使用Nunjucks模板引擎和Sass预处理

2. 核心目录结构：

- src/  ├──  helpers/ # 工具函数 │ ├── filetreeUtils.js # 文件树处理 │ ├── linkUtils.js # 链接和图谱处理 │ ├── userSetup.js # 用户自定义配置 │ ├── userUtils.js # 用户工具函数 │ └── utils.js # 通用工具函数 └── site/ # 网站内容 ├── _data/ # 数据文件 ├── _includes/ # 模板组件 ├── notes/ # Markdown笔记 ├── styles/ # SCSS样式 └── img/ # 图片资源

3. 主要功能特点：

- 高级Markdown支持(数学公式、UML、任务列表等)
- 笔记间链接和知识图谱
- 响应式图片处理(自动生成webp)
- 自定义标注(callout)和嵌入(transclusion)功能
- 搜索和标签系统
- RSS feed生成
- 支持Netlify和Vercel部署

4. 技术栈：

- 核心: Eleventy 2.0
- Markdown处理: markdown-it及其插件
- 样式: Sass
- 模板: Nunjucks
- 图片优化: @11ty/eleventy-img