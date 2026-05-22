# 德州扑克胜率计算器 PWA Demo

基于产品文档构建的演示应用，技术栈选型：React + Vite + TypeScript。

## 运行

1. 安装依赖

```bash
npm install
```

2. 启动开发服务器

```bash
npm run dev
```

3. 构建发布

```bash
npm run build
```

## 功能

- 输入手牌与公共牌
- 实时计算胜率、平局率、失败率
- 简单结果解释
- PWA 支持 manifest 与 service worker

## 目录

- `src/App.tsx`：核心页面与胜率计算逻辑
- `public/manifest.json`：PWA manifest
- `public/sw.js`：离线缓存 service worker
