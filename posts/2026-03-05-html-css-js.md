---
title: HTML/CSS/JS 基础回顾
date: 2026-03-05
type: 学习笔记
---

今天回顾了前端三件套的核心知识。

## HTML：语义化标签

像 `<article>`、`<section>`、`<aside>` 这些标签能让页面结构更清晰，也有利于 SEO 和无障碍访问。

## CSS：现代特性

- **CSS 变量**（自定义属性）配合 `clamp()` 可以做响应式字体
- **Grid 布局**比 Flexbox 更适合二维布局场景
- `backdrop-filter: blur()` 实现磨砂玻璃效果

```css
:root {
  --primary: #0f8b8d;
  font-size: clamp(14px, 2vw, 18px);
}
```

## JavaScript：ES6+ 标配

模板字符串、解构赋值、箭头函数、`async/await` 这些已经是现代开发标配了。

```javascript
const greet = (name) => `Hello, ${name}!`;
const [first, ...rest] = [1, 2, 3, 4];
```
