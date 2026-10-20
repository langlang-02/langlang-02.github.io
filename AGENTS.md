# 仓库贡献指南

## 项目结构与模块组织

本仓库是 Zhenglang Weng 的个人学术网站，使用 Jekyll 和 Academic Pages 主题构建，部署于 GitHub Pages。

- `_pages/` 存放独立页面；`_posts/`、`_portfolio/`、`_publications/`、`_talks/` 和 `_teaching/` 存放各类内容条目。
- `_layouts/` 和 `_includes/` 定义 Liquid 模板；`_sass/` 存放主题样式，`assets/` 存放 CSS 和 JavaScript。
- `_config.yml` 管理网站配置；`_data/` 存放导航等结构化数据。
- `images/` 存放图片；`files/` 存放供下载的文档；`markdown_generator/` 包含论文和报告内容的生成工具。
- `_site/` 和 `.sass-cache/` 是已被 Git 忽略的生成目录，请修改对应源文件。

## 构建、测试与本地开发命令

安装 Ruby、Bundler 和 Node.js 后，在仓库根目录执行以下命令：

- `bundle install`：安装 Ruby 依赖。
- `bundle exec jekyll serve -l -H localhost`：启动本地预览并自动刷新，访问 `http://localhost:4000`。修改 `_config.yml` 后需重启服务。
- `bundle exec jekyll build`：将静态网站生成到 `_site/`，并检查构建错误。
- `npm install`：安装 JavaScript 依赖和构建工具。
- `npm run build:js`：打包并压缩 JavaScript，输出到 `assets/js/main.min.js`。
- `npm run watch:js`：监听 JavaScript 源文件变化并自动重新打包。

## 代码风格与命名约定

保持与相邻 Markdown、Liquid、JavaScript 和 SCSS 代码一致的风格。YAML 使用两个空格缩进，其他文件沿用现有缩进。确保文件头部的 YAML 元数据有效，并保留既有永久链接。博客文章按 `YYYY-MM-DD-descriptive-title.md` 命名；新增内容和资源使用有描述性的名称，以连字符分隔单词。修改 JavaScript 时，编辑 `assets/js/_main.js` 等源文件，再重新生成打包文件。项目目前未配置专用格式化或代码检查工具。

## 测试指南

项目目前未配置专用测试框架、测试命名约定或覆盖率要求。修改后运行 Jekyll 构建，并在本地以桌面和移动端宽度检查受影响页面。确认导航、图片和文档链接正常，并检查浏览器控制台是否报错。修改脚本后需重新打包 JavaScript。

## 提交与拉取请求规范

近期提交使用简短、小写的英文动作描述，例如 `rearrange portfolio` 和 `add video link in excerpt`。请沿用该风格，明确说明修改内容，并保持每次提交范围集中。提交拉取请求时，说明变更、关联相关 issue、记录已完成的验证；涉及可见布局变化时附上截图。提交前检查生成内容和下载文件，切勿包含凭据或私人文档。
