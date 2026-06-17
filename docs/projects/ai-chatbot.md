# 🤖 ai-chatbot

> Next.js 14 + LangChain + Claude API 智能问答工具

## 📝 简介

一个调用 Claude API 的 AI 智能问答工具，前端使用 Next.js 14 App Router，后端通过 LangChain 封装 Claude 流式输出，实现"打字机"效果。

## 🛠 技术栈

- **Next.js** 14（App Router）
- **TypeScript**
- **TailwindCSS**
- **LangChain** (`@langchain/anthropic`)
- **Claude API** (Anthropic)
- **OpenAI API**（可选切换对比）

## 🚀 在线 Demo

_待补齐_

## 📦 源码仓库

_待创建_

## ✨ 计划核心特性

- 🎯 Next.js 14 App Router（Server Components + Route Handlers）
- 🎯 Claude API 流式输出（SSE）
- 🎯 LangChain 链式调用封装
- 🎯 对话历史管理（localStorage）
- 🎯 可切换 OpenAI / Claude 模型对比
- 🎯 暗色模式 + 响应式设计

## 📸 截图

_待补_

## 🛣️ TODO

- [ ] `pnpm create next-app ai-chatbot --ts --tailwind --app`
- [ ] 申请 Claude API Key
- [ ] 装 LangChain：`pnpm add @langchain/anthropic @langchain/core`
- [ ] 写 `/app/api/chat/route.ts` 流式接口
- [ ] 写 `/app/page.tsx` 聊天 UI
- [ ] 部署到 Vercel（自动）
