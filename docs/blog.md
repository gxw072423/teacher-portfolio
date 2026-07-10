# 📝 技术文章

分享我在编程学习与教学过程中的思考与总结。

---

## 📖 文章列表

<div style="display: grid; gap: 1.5rem; margin: 1.5rem 0;">

<div style="border: 1px solid #BBDEFB; border-radius: 12px; padding: 1.5rem; transition: box-shadow 0.3s;">
<div style="display: flex; justify-content: space-between; align-items: center;">

<div style="flex: 1;">

### 🎯 编程初学者最容易犯的 5 个错误

<span style="color: #666; font-size: 0.85rem;">📅 2025-07</span>
<span style="background: #E3F2FD; color: #1565C0; padding: 0.2rem 0.6rem; border-radius: 12px; font-size: 0.8rem; margin-left: 0.5rem;">教学心得</span>

从实际教学经验出发，总结初学者常见的思维陷阱和纠正方法。

</div>

<div style="flex: 0 0 auto; margin-left: 1rem;">
<a href="#article1" style="text-decoration: none; color: #1565C0; font-weight: 500;">阅读全文 →</a>
</div>

</div>
</div>

<div style="border: 1px solid #BBDEFB; border-radius: 12px; padding: 1.5rem;">
<div style="display: flex; justify-content: space-between; align-items: center;">

<div style="flex: 1;">

### 🎨 从 Figma 到代码：设计师的前端入门指南

<span style="color: #666; font-size: 0.85rem;">📅 2025-06</span>
<span style="background: #E3F2FD; color: #1565C0; padding: 0.2rem 0.6rem; border-radius: 12px; font-size: 0.8rem; margin-left: 0.5rem;">设计 + 开发</span>

如何利用 Figma 的设计能力降低前端学习门槛，让视觉思维成为编程的助力。

</div>

<div style="flex: 0 0 auto; margin-left: 1rem;">
<a href="#article2" style="text-decoration: none; color: #1565C0; font-weight: 500;">阅读全文 →</a>
</div>

</div>
</div>

<div style="border: 1px solid #BBDEFB; border-radius: 12px; padding: 1.5rem;">
<div style="display: flex; justify-content: space-between; align-items: center;">

<div style="flex: 1;">

### 🤖 AI 时代，编程老师会被取代吗？

<span style="color: #666; font-size: 0.85rem;">📅 2025-07</span>
<span style="background: #E3F2FD; color: #1565C0; padding: 0.2rem 0.6rem; border-radius: 12px; font-size: 0.8rem; margin-left: 0.5rem;">行业思考</span>

探讨 AI 工具对编程教育的影响，以及新时代编程教师应该具备的核心能力。

</div>

<div style="flex: 0 0 auto; margin-left: 1rem;">
<a href="#article3" style="text-decoration: none; color: #1565C0; font-weight: 500;">阅读全文 →</a>
</div>

</div>
</div>

<div style="border: 1px solid #BBDEFB; border-radius: 12px; padding: 1.5rem;">
<div style="display: flex; justify-content: space-between; align-items: center;">

<div style="flex: 1;">

### 📐 Vue 响应式原理——用动画解释给你看

<span style="color: #666; font-size: 0.85rem;">📅 2025-05</span>
<span style="background: #E3F2FD; color: #1565C0; padding: 0.2rem 0.6rem; border-radius: 12px; font-size: 0.8rem; margin-left: 0.5rem;">前端原理</span>

用 Figma 制作的图解动画，一步步拆解 Vue 3 的响应式系统是怎么工作的。

</div>

<div style="flex: 0 0 auto; margin-left: 1rem;">
<a href="#article4" style="text-decoration: none; color: #1565C0; font-weight: 500;">阅读全文 →</a>
</div>

</div>
</div>

</div>

---

## 📝 文章全文

### <span id="article1">🎯 编程初学者最容易犯的 5 个错误</span>

---

#### 错误一：只看不写

很多学生花大量时间看视频、看教程，但从来不自己动手敲代码。

> **正确做法**：每看 10 分钟教程，至少花 20 分钟自己敲。编程是**肌肉记忆**，不是知识记忆。

#### 错误二：害怕报错

看到红色报错就慌，不敢看错误信息，直接复制去问别人。

> **正确做法**：**错误信息是最好的老师**。先静下心读一遍——大多数报错都直接告诉你问题在哪一行、是什么问题。

#### 错误三：复制粘贴综合征

从 StackOverflow 或 AI 工具复制代码，能用就行，不深究原理。

> **正确做法**：可以借助 AI 工具，但**每一行你都要能解释给别人听**。解释不了的代码，不是你的代码。

#### 错误四：追求"最优解"

在基础还不扎实时，纠结于算法优化、设计模式、架构选择。

> **正确做法**：先让代码**跑起来**，再让代码**变好**。过早优化是万恶之源。

#### 错误五：孤军奋战

一个人闷头学，不与别人交流，不展示自己的代码。

> **正确做法**：参与开源社区、写技术文章、和同学做代码评审（Code Review）。教会别人的同时，你学到的更多。

---

### <span id="article2">🎨 从 Figma 到代码：设计师的前端入门指南</span>

---

作为一个从 Figma 转向前端开发的人，我想分享一些跨界的经验。

#### 为什么设计师学前端有天然优势？

1. **你已经懂了布局** — Flexbox 和 Grid 本质上就是 Figma 的 Auto Layout
2. **你已经懂了层级** — z-index 就是图层面板的数字版
3. **你已经懂了组件** — Figma Components = 前端组件，概念完全一致
4. **你已经懂了交互** — 原型连线 ≈ 事件处理逻辑

#### 学习路径建议

```
Figma 组件思维
    ↓
HTML 结构（盒模型、语义化）
    ↓
CSS 布局（Flexbox、Grid）
    ↓
JavaScript 基础（变量、函数、事件）
    ↓
Vue/React 组件开发
    ↓
成为一个"设计工程双修"的全能开发者
```

#### 关键心态

不要把自己当成"转行"，而是**拓展技能边界**。设计能力永远是你的差异化优势——大多数程序员做不到好看的设计，而你可以。

---

### <span id="article3">🤖 AI 时代，编程老师会被取代吗？</span>

---

这是每个编程教育者都需要面对的问题。我的答案是：

> **不会被取代，但必须转型。**

#### AI 擅长什么？

- ✅ 生成样板代码
- ✅ 解释已知概念
- ✅ 调试简单错误
- ✅ 提供代码审查建议

#### AI 做不了什么？

- ❌ 理解学生的**真实困惑点**（有时候学生自己都说不清哪里不懂）
- ❌ 根据学生表情/语气**调整教学节奏**
- ❌ 设计**循序渐进的学习路径**
- ❌ 激发**学习动力**和保持**学习热情**
- ❌ 传授**实际项目经验**和工程思维方式

#### 新时代编程教师的核心能力

1. **AI 协作教学** — 教学生如何与 AI 高效协作，而非禁止使用
2. **思维训练** — 从"教语法"转向"教思维"
3. **项目驱动** — 通过真实项目让学生理解工程全流程
4. **软技能培养** — 沟通、协作、代码评审、技术写作
5. **个性化指导** — AI 提供通用答案，老师提供个性化反馈

---

### <span id="article4">📐 Vue 响应式原理——用动画解释给你看</span>

---

Vue 3 的响应式系统是其核心特性。让我用最简单的语言解释清楚。

#### 一句话概括

> 你把数据放进 Vue，Vue 帮你盯着。数据一变，页面自动跟着变。

#### 三个核心概念

```
数据 (data)           →  你关心的值
副作用 (effect)       →  数据变化时要做什么
依赖追踪 (tracking)  →  Vue 偷偷记录"谁用了谁"
```

#### 图解流程

```
┌─────────────┐
│  修改数据    │
│  data.x = 5 │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│  Proxy 拦截  │  ← Vue 3 用 Proxy 监听数据变化
│  set trap   │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│  通知依赖    │  ← "喂，用到了 x 的那个组件，你要更新了！"
│  trigger    │
└──────┬──────┘
       │
       ▼
┌─────────────┐
│  重新渲染    │  ← 页面自动更新，只改变化的部分
│  re-render  │
└─────────────┘
```

#### 类比理解

把 Vue 的响应式系统想象成**外卖订单跟踪**：

- **数据** = 你的订单
- **Proxy** = 快递系统的跟踪模块
- **副作用** = 每当订单状态变化时，给你的手机发通知
- **视图** = 你手机上看到的订单状态页面

你不需要手动刷新页面看状态，系统会自动通知你——这就是"响应式"的本质。

---

<div style="text-align: center; margin: 2rem 0; padding: 1.5rem; background: #E3F2FD; border-radius: 12px;">

### 📬 想了解更多？

我会持续更新技术文章，欢迎关注我的 [GitHub](https://github.com/gxw072423) 或通过邮件联系。

[✍️ 联系我](about.md#_5){ .md-button }

</div>
