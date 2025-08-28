# My Blog

这是一个基于 Jekyll 的个人博客网站，支持部署到 GitHub Pages 和 Cloudflare Pages。

## 特性

- 响应式设计，支持移动端和桌面端
- 支持 Markdown 写作
- 支持代码高亮
- 支持分类和标签
- 支持评论系统
- 支持 SEO 优化

## 本地开发

1. 安装 Ruby 和 Jekyll
2. 克隆本仓库
3. 运行 `bundle install`
4. 运行 `bundle exec jekyll serve`
5. 访问 http://localhost:4000

## 部署说明

### GitHub Pages
- 直接推送到 main 分支即可自动部署

### Cloudflare Pages
- 连接 GitHub 仓库
- 构建命令: `jekyll build`
- 构建输出目录: `_site`
