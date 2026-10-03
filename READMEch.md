<div align="center">

<img src="./assets/profile-banner.svg" width="100%" alt="HunLuanZhiZhu — AI Research, Agent Systems and Browser Lab" />

<br/>

<a href="https://zyh.sryze.cc/"><img src="https://img.shields.io/badge/浏览器实验室-zyh.sryze.cc-0d1117?style=for-the-badge&logo=googlechrome&logoColor=white" alt="个人网站"/></a>
<a href="https://github.com/HunLuanZhiZhu"><img src="https://img.shields.io/badge/GitHub-HunLuanZhiZhu-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"/></a>
<a href="./README.md"><img src="https://img.shields.io/badge/English-README.md-2563eb?style=for-the-badge" alt="English version"/></a>

<br/><br/>

**AI 研究 · 优化算法 · 智能体基础设施 · 浏览器实验**

</div>

---

## 🧪 个人网站 — Browser Lab

> **https://zyh.sryze.cc/**  
> GitHub Pages 备用地址：https://hunluanzhizhu.github.io/

我的个人网站不是传统意义上的“个人简介页”，而是一个持续扩展的 **浏览器实验室 / 公开作品索引**。

研究展示、交互实验、图形、小游戏、AI 生成与评测、工具和小型应用，都尽量以“可以直接打开使用”的形式放进浏览器里。

网站本身也刻意保持轻量：根首页使用纯静态 HTML，大量 CSS / JavaScript / 字体直接内联，不依赖运行时前端框架；各个实验则独立放在 <code>/projects/</code> 下。

<table>
<tr>
<td width="50%" valign="top">

### 🧱 Minecraft Web
**Rust · Bevy · WebAssembly**

编译到 WASM 的浏览器 3D 沙盒实验。

[打开项目 →](https://zyh.sryze.cc/projects/minecraft-web/)

</td>
<td width="50%" valign="top">

### 📚 组会 PPT 合集
**Slides · KaTeX · SVG · WebGL**

把研究组会讲稿直接发布为网页演示，并提供独立的场次聚合索引。

[打开项目 →](https://zyh.sryze.cc/projects/group-meeting-ppts/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎮 AI 游戏生成评测
**Benchmark · Godot · WASM**

把 AI 生成游戏与游戏制作流程的评测结果直接发布到浏览器中。

[打开项目 →](https://zyh.sryze.cc/projects/game-studio-eval-s2/)

</td>
<td width="50%" valign="top">

### ❤️ 心韵深辨 · ECG AI Local
**TensorFlow.js · SNN · Local AI**

在浏览器本地运行的 ECG / AI 实验，探索客户端推理与神经建模。

[打开项目 →](https://zyh.sryze.cc/projects/ecg-ai-local/)

</td>
</tr>
<tr>
<td width="50%" valign="top">

### 🎛️ Liang Intensity Calibrator
**AI · Video · Canvas**

结合 AI 生成内容、视频与浏览器图形交互的校准实验。

[打开项目 →](https://zyh.sryze.cc/projects/liang-intensity-calibrator/)

</td>
<td width="50%" valign="top">

### ✨ Open Design Test
**WebGL2 · Shader · Interactive Design**

围绕程序生成视觉、交互和着色器效果展开的浏览器图形实验。

[打开项目 →](https://zyh.sryze.cc/projects/open-design-test/)

</td>
</tr>
</table>

<div align="center">

[**进入完整 Browser Lab →**](https://zyh.sryze.cc/)

</div>

首页本身也是实验的一部分：项目分类与搜索、中英文切换、程序生成图形、WebGL 效果、动效控制、响应式布局、键盘导航以及一些刻意打磨的小交互都直接实现在页面里。

---

## 🔬 我主要在做什么

<table>
<tr>
<td width="33%" valign="top">

### 研究
优化算法、强化学习、脉冲神经网络、论文复现、实验性模型与训练方法。

</td>
<td width="33%" valign="top">

### 智能体系统
可复用智能体技能、自动研究 / 自动编程流程、大模型接口基础设施、工作空间工具。

</td>
<td width="33%" valign="top">

### 浏览器工程
WebAssembly、WebGL、Canvas、SVG、浏览器原生 Demo、小游戏和交互式研究展示。

</td>
</tr>
</table>

<div align="center">

**论文 → 机制 → 复现 → 修改 → 实验 → 工程化 → 自动化**

</div>

---

## 🚀 代表仓库

<table>
<tr>
<td width="50%" valign="top">

### [AdaNCFGD](https://github.com/HunLuanZhiZhu/AdaNCFGD)
基于 PyTorch 的自适应分数阶梯度下降优化器，并包含脉冲神经网络相关实现。

<code>优化算法</code> · <code>PyTorch</code> · <code>SNN</code> · <code>研究软件</code>

</td>
<td width="50%" valign="top">

### [mini-proxy](https://github.com/HunLuanZhiZhu/mini-proxy)
使用 Rust 编写的大模型 API 轻量代理，兼容 OpenAI、Anthropic 与 Responses 风格接口，并处理流式转发、重试、模型映射和请求适配。

<code>Rust</code> · <code>AI API</code> · <code>SSE</code> · <code>基础设施</code>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [.agents](https://github.com/HunLuanZhiZhu/.agents)
我的可复用 AI 智能体技能和工作流层：技能组织、行为约束、版本锁定，以及研究 / 生产力工具。

<code>智能体</code> · <code>技能</code> · <code>自动化</code> · <code>工作流</code>

</td>
<td width="50%" valign="top">

### [Auto-zcode-research-in-sleep](https://github.com/HunLuanZhiZhu/Auto-zcode-research-in-sleep)
围绕 AI 智能体自动研究、自动编程流程展开的实验。

<code>智能体</code> · <code>研究自动化</code> · <code>编程</code>

</td>
</tr>
<tr>
<td width="50%" valign="top">

### [ZCode-Game-Studios](https://github.com/HunLuanZhiZhu/ZCode-Game-Studios)
围绕 AI 辅助游戏生成与评测的项目，与个人网站上的公开评测页面相互关联。

<code>AI</code> · <code>游戏</code> · <code>评测</code>

</td>
<td width="50%" valign="top">

### [liang-intensity-calibrator](https://github.com/HunLuanZhiZhu/liang-intensity-calibrator)
AI 相关交互校准项目，同时以可直接访问的网页作品发布在个人网站中。

<code>AI</code> · <code>交互</code> · <code>Canvas</code> · <code>视频</code>

</td>
</tr>
</table>

---

## 🧰 技术栈与工具

<div align="center">

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" />
<img src="https://img.shields.io/badge/Rust-000000?style=flat-square&logo=rust&logoColor=white" />
<img src="https://img.shields.io/badge/WebAssembly-654FF0?style=flat-square&logo=webassembly&logoColor=white" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=111827" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" />
<img src="https://img.shields.io/badge/WebGL-990000?style=flat-square&logo=webgl&logoColor=white" />
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" />

</div>

---

## 🧭 当前方向

<div align="center">

### 研究 AI 系统  
↓  
### 构建能够帮助我继续研究、编程、实验和创作的 AI 系统

</div>

个人网站是这套过程最直观的展示面，而 GitHub 仓库保存更底层的算法、智能体工作流、基础设施和实验实现。

---

<div align="center">

<sub>
本页由 <b>GPT-5.6 Sol 网页版</b> 根据 <b>HunLuanZhiZhu</b> 当前 GitHub 仓库总结生成。<br/>
镜像、克隆以及不能代表本人主要方向的仓库不会被作为核心项目介绍。
</sub>

</div>
