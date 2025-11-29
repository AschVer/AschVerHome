# create-valaxy

示例: [valaxy.site](https://valaxy.site)

## 使用方法

```bash
# 安装
npm i
# 或 pnpm i

# 启动
npm run dev
# 或 pnpm dev
```

访问 `http://localhost:4859/`，开始使用吧！

### 配置

修改 `valaxy.config.ts` 来自定义你的博客。

中英文文档即将到来！

> 请稍等片刻。

### Docker

```bash
docker build . -t your-valaxy-blog-name:latest
```

## 项目结构

在大多数情况下，你只需要在 `pages` 文件夹中工作。

### 主要文件夹

- `pages`: 你的所有页面
  - `posts`: 在这里编写你的文章，会被统计为文章
- `styles`: 覆盖主题样式，`index.scss`/`vars.csss`/`index.css` 会自动加载
- `components`: 自定义你的 Vue 组件（会自动加载）
- `layouts`: 自定义布局（在 md 文件中使用 `layout: xxx`）
- `locales`: 自定义国际化

### 其他

- `.vscode`: 推荐一些有用的插件和设置，你可以预览图标/国际化/类...
- `.github`: GitHub Actions 用于自动构建并部署到 GitHub Pages
- `netlify.toml`: 用于 [netlify](https://www.netlify.com/)
- `vercel.json`: 用于 [vercel](https://vercel.com/)
