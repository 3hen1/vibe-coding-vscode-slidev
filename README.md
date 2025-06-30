# Vibe Coding VS Code Slidev

基于 [Slidev](https://github.com/slidevjs/slidev) 构建的 VS Code 和 AI 编程演示文稿。

## 🚀 开发

安装依赖并启动开发服务器：

```bash
pnpm install
pnpm dev
```

访问 <http://localhost:3030> 查看幻灯片。

编辑 [slides.md](./slides.md) 文件即可看到实时更改。

## 📦 构建

```bash
# 本地构建
pnpm build:local

# GitHub Pages 构建（包含正确的 base 路径）
pnpm build
```

## 🌐 部署到 GitHub Pages

1. 将代码推送到 GitHub 仓库
2. 在仓库设置中启用 GitHub Pages
3. 选择 "GitHub Actions" 作为部署源
4. 每次推送到 main 分支时会自动部署

## 📖 了解更多

- [Slidev 文档](https://sli.dev/)
- [Vue.js 文档](https://vuejs.org/)
