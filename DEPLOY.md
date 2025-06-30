# GitHub Pages 部署指南

## 🎯 配置 GitHub Pages

1. **前往 GitHub 仓库设置**
   - 访问：https://github.com/3hen1/vibe-coding-vscode-slidev
   - 点击 "Settings" 标签

2. **启用 GitHub Pages**
   - 在左侧菜单中找到 "Pages"
   - 在 "Source" 部分，选择 "GitHub Actions"
   - 保存设置

3. **等待自动部署**
   - GitHub Actions 会自动触发部署
   - 在 "Actions" 标签中可以查看部署进度
   - 首次部署大约需要 2-5 分钟

4. **访问您的网站**
   - 部署完成后，网站将在以下地址可用：
   - **https://3hen1.github.io/vibe-coding-vscode-slidev**

## 🔄 自动部署

每次推送到 `main` 分支时，GitHub Actions 会自动：

1. 安装依赖 (`pnpm install`)
2. 构建项目 (`pnpm run build`)
3. 部署到 GitHub Pages

## 🛠️ 本地开发

```bash
# 安装依赖
pnpm install

# 启动开发服务器
pnpm dev

# 本地构建测试
pnpm build:local

# 预览构建结果
pnpm preview
```

## 📁 部署配置说明

### GitHub Actions 工作流
- `.github/workflows/deploy.yml` - 自动部署配置
- 使用 Node.js 18 和 pnpm 8
- 支持缓存以加快构建速度

### Slidev 配置
- `package.json` - 包含正确的 base 路径配置
- `slidev.config.ts` - Slidev 特定配置
- 构建输出到 `dist` 目录

### 路径配置
- 生产环境：`/vibe-coding-vscode-slidev/`
- 开发环境：`/`

## 🔧 故障排除

### 如果部署失败：

1. **检查 Actions 日志**
   - 访问仓库的 "Actions" 标签
   - 点击失败的工作流查看详细错误

2. **常见问题及解决方案**
   - ❌ **pnpm 找不到**：确保工作流中 pnpm 在 Node.js 之前安装
   - ❌ **依赖安装失败**：确保 `pnpm-lock.yaml` 文件已提交
   - ❌ **构建失败**：检查 Node.js 版本兼容性（使用 Node.js 18）
   - ❌ **路径错误**：验证 base 路径配置正确

3. **最近修复的问题**
   - ✅ 修复了 pnpm 安装顺序问题
   - ✅ 添加了 packageManager 字段
   - ✅ 优化了权限配置

4. **重新触发部署**
   - 推送新的提交到 `main` 分支
   - 或在 GitHub Actions 中手动重新运行工作流

## 🎨 自定义域名（可选）

如果您有自定义域名：

1. 在仓库根目录创建 `public/CNAME` 文件
2. 文件内容为您的域名（如：`slides.yourdomain.com`）
3. 在域名 DNS 设置中添加 CNAME 记录指向 `3hen1.github.io`

## 📊 网站状态

- **仓库**：https://github.com/3hen1/vibe-coding-vscode-slidev
- **网站**：https://3hen1.github.io/vibe-coding-vscode-slidev
- **构建状态**：[![Deploy to GitHub Pages](https://github.com/3hen1/vibe-coding-vscode-slidev/actions/workflows/deploy.yml/badge.svg)](https://github.com/3hen1/vibe-coding-vscode-slidev/actions/workflows/deploy.yml)
