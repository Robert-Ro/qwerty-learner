# 项目分析

## 依赖库分析

```json
{
  "@floating-ui/react": "^0.20.1", // ui lib
  "@headlessui/react": "^1.7.13", // ui lib
  "@headlessui/tailwindcss": "^0.1.2", // ui style
  "@radix-ui/react-progress": "^1.0.2", // ui
  "@radix-ui/react-radio-group": "^1.1.2", // ui
  "@radix-ui/react-scroll-area": "^1.0.3", // ui
  "@radix-ui/react-slider": "^1.1.1", // ui
  "canvas-confetti": "^1.6.0", // Canvas Confetti 万花桶动画
  "classnames": "^2.3.2",
  "daisyui": "^3.5.1", // tailwindcss ui lib
  "dayjs": "^1.11.8",
  "dexie": "^3.2.3", // indexDB wrapper
  "dexie-export-import": "^4.0.7", // indexDB 相关
  "dexie-react-hooks": "^1.1.3", // indexDB 相关
  "echarts": "^5.4.2", // 图表库
  "file-saver": "^2.0.5", // 文件保存
  "howler": "^2.2.3", // 声音库
  "html-to-image": "^1.11.11",
  "immer": "^9.0.21", // js 对象操作
  "jotai": "^2.0.3", // react状态管理库
  "mixpanel-browser": "^2.45.0", // 用户分析sdk
  "pako": "^2.1.0", // zlib  for js
  "react": "^18.2.0",
  "react-activity-calendar": "^2.0.2", // 日历功能组件
  "react-app-polyfill": "^3.0.0", // polyfill
  "react-dom": "^18.2.0",
  "react-hotkeys-hook": "^4.3.7", // hotkey✨✨✨
  "react-router-dom": "^6.8.2", // 路由
  "react-timer-hook": "^3.0.5", // react倒计时管理
  "react-tooltip": "^5.18.0", // tooltip组件
  "source-map-explorer": "^2.5.2", // sourcemap分析
  "swr": "^2.0.4", // 数据获取，类似React Query
  "typescript": "^4.0.3",
  "use-immer": "^0.9.0", // immer with react hooks
  "use-sound": "^4.0.1", // 声音效果 with react hooks
  "xlsx": "^0.18.5" // excel操作库
}
```

## 项目目录结构

- `@types`/`typing`目录存储一些类型定义，这个可以提取处理出来
- 常见的目录结构
- 路由组件下细分该功能所需的`components`, `hooks`

## 路由

## 状态管理
