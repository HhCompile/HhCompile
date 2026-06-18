# 🔖 bookmark-manager-web

> 浏览器书签管理 Web 应用：AI 智能整理 + 浏览器同步 + 数据可视化 + 私密保险箱

## 📝 简介

一个完整的浏览器书签管理方案。日常我们浏览器书签越攒越乱，这个工具帮你：

- 🔄 同步 Chrome 书签
- 🤖 AI 智能整理（去重 / 分类 / Tag）
- 📊 看到书签"健康度"（死链 / 重复 / 长期未用）
- 🔐 私密书签加密存储

## 🛠 技术栈

**Frontend**
- React 18.3.1（Composition API）
- TypeScript 5
- Vite 6.3.5
- Tailwind CSS 4
- Radix UI + shadcn/ui 模式
- Motion (Framer Motion 继任者)
- React Router 6

**Tooling**
- pnpm（workspace 模式）
- Jest + Testing Library
- ESLint + Prettier

**Backend（规划中）**
- Node.js + Express / Fastify
- 数据持久化（SQLite / PostgreSQL）
- 浏览器扩展 API 集成

## 🚀 在线 Demo

_待补齐（当前为本地开发版本）_

## 📦 源码仓库

<https://github.com/HhCompile/bookmark-manager-web>

## ✨ 核心特性

| 功能 | 描述 | 状态 |
|---|---|---|
| 多视图书签管理 | 列表 / 卡片 / 树形 3 种模式 | ✅ |
| Chrome 书签同步 | 浏览器扩展对接 | ✅ |
| AI 智能整理 | 自动分类 + Tag 建议 | ✅ |
| Tag 云可视化 | 高频标签云图 | ✅ |
| 数据可视化 | 健康度 / 活跃度分析 | ✅ |
| 私密保险箱 | 加密存储敏感书签 | ✅ |
| 任务管理器 | 批量操作 | ✅ |
| 阅读模式 | 书签文章转阅读视图 | ✅ |

## 📊 技术亮点

### 1. 完整的工程化体系
- pnpm workspace（虽然 server 占位中，结构已就绪）
- 严格的 TypeScript 类型
- ESLint + Prettier + Husky（如果配了）
- Jest 单元测试

### 2. 现代化 UI
- Tailwind CSS 4（新原子化引擎）
- Radix UI 提供无样式可访问性
- shadcn/ui 模式（copy-paste 而非依赖）
- Motion 流畅动画

### 3. AI 协作开发
- `AGENTS.md` 项目级 AI 协作指南
- `.claude/` `.kimi/` `.trae/` 多 AI 工具配置
- AI 参与：智能整理 / Tag 建议 / 阅读模式优化

## 📸 截图

<!-- 部署后截图上传 -->
<!-- ![Home](screenshot-home.png) -->

_待补_

## 🛣️ TODO

- [ ] 部署在线 demo（Vercel）
- [ ] 截图上传到 `docs/`
- [ ] 补 Chrome 浏览器扩展
- [ ] 接入真实后端（替换 mocks）
- [ ] 增加数据导入/导出
- [ ] 移动端适配（PWA）

## 📝 复盘

- **开发周期**：~3 个月（断断续续）
- **技术选型思路**：追求"现代化 + 长期可维护"，避免流行但小众的库
- **下一步**：补充截图 + 部署 demo，让作品集"看得到"
