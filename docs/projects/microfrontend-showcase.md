# 🧩 microfrontend-showcase

> qiankun 微前端脚手架（Vue 3 主应用 + React 子应用）

## 📝 简介

演示企业级微前端架构落地能力：一个 qiankun 基座 + Vue 3 主子应用 + React 独立子应用，验证多技术栈在同页面无冲突共存。

## 🛠 技术栈

- **qiankun** 2.x（蚂蚁金服微前端框架）
- **Vue 3**（主应用基座）
- **React 18**（子应用 A）
- **Vue 3**（子应用 B）
- **Webpack 5** / **Vite** 5
- **TypeScript**

## 🚀 在线 Demo

_待补齐_

## 📦 源码仓库

_待创建（建议 monorepo: pnpm workspace）_

## ✨ 计划核心特性

- 🎯 qiankun 基座应用（路由 + 菜单 + 子应用注册）
- 🎯 React 18 子应用（暴露 bootstrap/mount/unmount）
- 🎯 Vue 3 子应用（同上）
- 🎯 主子应用间通信（initGlobalState）
- 🎯 独立部署各子应用到 Vercel

## 📸 截图

_待补_

## 🛣️ TODO

- [ ] 起 3 个独立项目（main-app / vue-sub / react-sub）
- [ ] main-app 装 qiankun + 配 registerMicroApps
- [ ] vue-sub / react-sub 暴露生命周期
- [ ] 联调主子应用切换
- [ ] 各应用独立部署
