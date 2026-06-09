# Brand DNA — Kathy的品牌基因
> 所有场景、所有页面共享的底层规范。无论哪种设计风格，都不能违背此文件的核心约束。

---

## 🌱 品牌灵魂

### 使命
**Explore · Reframe · Create**
探索世界。重新理解世界。创造属于自己的表达。

### 核心信念
> Life is not about collecting achievements.
> It is about connecting the dots.

人生不是收集奖杯。而是理解经历之间的联系。

### 品牌愿景
Create a space where thoughts can grow naturally.

像花园一样。允许混乱。允许不确定性。允许改变。最终长出属于自己的秩序。

### 品牌隐喻

| 我们不是 | 我们是 |
|---------|--------|
| Second Brain | Knowledge Garden 思想花园 |
| Productivity Tool | Personal Evolution System 个人成长生态系统 |
| Information Storage | Meaning Making 意义生成 |

### 品牌宣言

> We do not collect information. We collect moments.
> We do not build databases. We build connections.
> Every note is a pearl. Every reflection is a thread.
> Over time, they become a story.
> And that story becomes a life.

---

## 🎨 IP固定三色

| 色名 | 色值 | 对应 | 用途 |
| --- | --- | --- | --- |
| **Deep Cocoa** | `#573D32` | 巧克力包装纸 | 主色调、标题、正文重点、品牌识别 |
| **Dusty Rose** | `#D7A1AA` | 草莓奶油 | 标签、情绪表达、卡片点缀、链接悬停 |
| **Vintage Gold** | `#C1A574` | 珍珠线 | 高亮、连接线、编号、装饰元素 |

### 三色比例原则
> **Deep Cocoa 60% · Dusty Rose 30% · Vintage Gold 10%**

* **核心约束**：金色（`Vintage Gold`）永远作为点缀，不作为大面积主色。

---

## 👧 IP形象规范

Kathy 的固定视觉形象（`character.png`），以下元素构成品牌识别核心，**不可更改**：

* **双麻花辫** — 品牌第一识别元素，代表探索与成长。
* **草莓元素** — 出现在帽子、裙摆或配饰中，代表温暖与生活感。
* **奶油白连衣裙** — 品牌核心服装，代表留白与包容。
* **酒红色蝴蝶结** — 品牌视觉焦点，代表勇气与表达。
* **随身笔记本** — 记录与反思的象征。
* **珍珠与金线** — 品牌最高级隐喻，代表知识与连接。

### ✨ 视觉气质要求

整体形象设计与延展应呈现：

* 温柔而坚定
* 像旧书里的女孩
* 有花园感，而非科技感
* 有故事感，而非产品感
* 有人的痕迹，而非 AI 痕迹

### 🚫 禁止事项
* 不允许赛博朋克化或进行未来科技风改造。
* 不允许进行 AI 产品吉祥物风格改造。
* 不允许使用荧光色或高饱和科技配色。

### 素材文件
- **头像** — `assets/avatar.jpg`
- **全身形象** — `character.png`（完整IP形象）

### 使用规则
- 不允许修改形象比例、颜色、元素
- 是否在页面中使用IP形象由用户决定，不强制
- 需要头像时优先用 `assets/avatar.jpg`

---

## 🔤 字体基因

### 核心原则
- **标题用衬线，正文用无衬线** — 混搭产生节奏
- **中英文搭配** — 英文做装饰/标签，中文承载内容
- **字号对比极端** — 大的要很大，小的要真的小

### 推荐字体池

| 场景 | 推荐 | 备注 |
|------|------|------|
| 英文装饰/标题 | `Fraunces` (italic) | 有品质的衬线体 |
| 英文手写/轻松 | `Caveat` | 手绘感、标注、注释 |
| 英文等宽/终端 | `Fira Code` | 技术/终端场景专用 |
| 中文标题首选 | `Huiwen Mincho`（汇文明朝体） | 品牌真正使用的标题字体，需本地ttf文件 |
| 中文标题备选 | `Noto Serif SC` (900) | 无本地字体时的衬线体fallback |
| 中文正文 | `Noto Sans SC` + 系统栈 | 跨平台无衬线 |
| 中文正文系统栈 | `-apple-system, 'PingFang SC', 'Helvetica Neue', sans-serif` | 本地渲染最快 |

### 字号系统（fluid sizing）
- Hero大标题: `clamp(2.8rem, 7vw, 5.5rem)`
- Section标题: `clamp(1.6rem, 4vw, 2.6rem)`
- 卡片标题: `1.15rem ~ 1.4rem`
- 正文: `16px`
- 辅助文字: `0.78rem ~ 0.85rem`
- 大装饰数字: `clamp(3rem, 8vw, 7rem)` + `opacity: 0.12~0.2`

---

## ✨ 气质关键词

设计出来的东西应该让人觉得：

- **温柔但有力量** — 安静、坚定、有自己的节奏
- **有思考深度** — 不只展示结果，也展示思维过程
- **不像AI** — 这是最高优先级的约束
- **有设计师眼光** — 细节讲究、间距精确、色彩克制
- **有学院感但不严肃** — 兼具研究者的理性与创作者的温度
- **真实而真诚** — 保留成长痕迹，而非完美包装
- **允许不确定性** — 留白、生长感、探索感
- **个人品牌感** — 一看就知道是 Kathy 的作品

---

## 🎨 配色扩展原则

当主色不够用时：

* 背景永远偏暖：`#FAF6F0`（暖白纸）、`#F5EFE6`（奶油纸）
* 文字永远非纯黑：用 `#2B241F`（墨棕）或 `#3A312B`
* 次要文字：`#5C5148`、`#8B8075`
* 绝不用纯黑 `#000` 或纯白 `#fff`
* 强调金：`#C9A86A`、`#D4B06A`（高亮、连接线、Badge）
* 情绪粉：`#D8B4A0`（仅用于 Reflection、情绪类内容点缀）
* 暗色场景底色：`#1B1816`、`#23201D`（仅适用于 HTML 全屏页面，3:4 卡片场景禁止深色底）
* 纸张纹理、烫金质感优先于高饱和纯色
* 径向渐变制造层次，不用纯平色

---

## 🚫 通用禁忌清单

| 类型 | 禁止 |
|------|------|
| 配色 | 蓝紫渐变、cyan、neon、纯黑白、AI常用的冷灰蓝调、黑色/深色版面（仅3:4卡片场景禁止，HTML全屏页面不受限） |
| 字体 | Inter/Roboto/Arial等overused字体（除非明确是终端风格辅助字体）、monospace充当"技术感" |
| 布局 | 所有section居中、千篇一律卡片网格、cards嵌套cards |
| 动效 | bounce/elastic、animate width/height、无限循环动画 |
| 装饰 | glassmorphism、圆角矩形+阴影千篇一律、渐变文字、AI光效 |
| 整体 | 看起来像AI生成的通用模板、generic Landing Page模板感 |
| 排版 | 行间距/字间距必须肉眼检查，不允许出现过松或过紧的异常节奏 |
| 图片 | AI生成的stock photo风、过度滤镜、无意义装饰图 |
| 默认样式 | HTML默认blockquote、默认border-left引用块、无样式ul/ol列表、默认table——所有组件必须从components.md选用，绝不允许浏览器默认渲染 |

### 自检问题

做完设计后问自己：

1. 这个页面截图发到Twitter上，会不会被人评论"又是AI做的"？
2. 能不能一眼认出这是 Kathy 的？
3. 有没有哪个部分让你觉得"见过很多次了"？

---

## 📐 通用间距原则

- Section之间: `clamp(80px, 12vh, 160px)`
- 内容块之间: `clamp(40px, 6vw, 100px)`
- 卡片内padding: `clamp(28px, 3vw, 44px)`
- 元素间gap: `clamp(24px, 3vw, 48px)`
- 全部用 `clamp()` 做fluid sizing
- `max-width: 1300px` + `margin: 0 auto` 约束内容宽度

---

## 📱 响应式通用规则

- 断点: 900px（两栏→单栏）、600px（字号微缩）
- 移动端是"重新排列"不是"缩小"
- 尊重 `prefers-reduced-motion`
- 移动端不隐藏内容——adapt不amputate

---

## 🔍 细节规范

- **选中文本高亮**：`::selection { background: #C9A86A; color: #2B241F; }`
- **引用/重点内容**：使用古董金 `#C9A86A` 或巧克力棕 `#5A3E36` 强调，不使用高饱和强调色
- **链接悬停**：使用金色下划线、烫金边框或轻微底色高亮，不用直接变色
- **分隔线**：优先使用细金线、虚线或纸张纹理分隔，不使用粗实线
- **卡片边框**：低对比暖灰边框 `#E5DDD2`，避免纯黑描边
- **阴影原则**：柔和扩散阴影，模拟纸张堆叠感，不使用互联网产品常见的大阴影
- **圆角原则**：8–16px，自然柔和，避免过度圆润的 App 风格
- **图标风格**：线性、手绘、书籍批注感优先，避免科技感图标
- **动效原则**：缓慢、克制、有呼吸感；避免弹跳、炫酷转场和过度反馈

---

*This is the foundation. Every scene file builds on top of this.*
