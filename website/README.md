# HhCompile.github.io

👤 **个人作品集 / 个人信息展示站** · [https://hhcompile.github.io](https://hhcompile.github.io)

8 年前端开发经验 · 高级前端开发工程师 / 前端架构师 · Vue 3 / TypeScript / LowCodeEngine

<!-- 部署后录屏后，把 docs/screenshot.png 提交上来，再取消下面这行注释 -->
<!-- ![Preview](docs/screenshot.png) -->

## ✨ 站点结构

单页 SPA，6 个区块：

- **Hero** — 一句话身份 + 城市
- **About** — 2 段自我描述
- **Skills** — 13 个技术栈标签
- **Experience** — 4 段工作经历
- **Projects** — 5 个代表性项目
- **Contact** — GitHub / 邮箱 / 个人博客

## 🛠 技术栈

- **Vue 3** + **TypeScript** + **Vite 8**
- 纯 CSS 暗色主题（无 UI 库依赖）
- GitHub Actions 自动部署到 GitHub Pages
- `vue-tsc` 严格类型检查

## 🚀 本地开发

```bash
npm install
npm run dev          # http://localhost:5173
```

## 📦 构建

```bash
npm run build        # 输出到 dist/
npm run preview      # 本地预览构建产物
```

## 🚢 部署（合并后）

本工程已合并入主仓 [HhCompile](https://github.com/HhCompile/HhCompile)，源码位于仓库 `website/` 子目录。

部署 workflow 位于**主仓根** `.github/workflows/deploy.yml`（GitHub Actions 仅执行仓库根目录下的 workflow，不执行子目录 workflow）：

1. 推送到 `HhCompile` 仓库 `main` 分支
2. workflow 在 `website/` 下执行 `npm ci` → `npm run build`
3. 上传 `website/dist` 并发布到 GitHub Pages（https://hhcompile.github.io）

首次部署需在仓库 **Settings → Pages → Source** 选择 **"GitHub Actions"**。

## ✏️ 修改个人信息

所有内容集中在 [`src/data/profile.ts`](src/data/profile.ts)，按结构修改后 `git push` 即可触发自动部署。

## 📄 License

MIT
