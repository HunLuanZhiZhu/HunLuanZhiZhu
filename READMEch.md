# HunLuanZhiZhu

🌐 **个人网站 / Browser Lab：** https://zyh.sryze.cc/  
GitHub Pages 备用地址：https://hunluanzhizhu.github.io/

[English Version](./README.md)

> 本页由 **GPT-5.6 Sol 网页版** 根据我当前 GitHub 仓库总结生成。总结重点放在真正具有代表性的个人项目上，不把镜像、克隆、临时同步或不能代表本人主要方向的仓库当作核心项目。

## 个人网站 — Browser Lab

我的个人网站并不是一个单纯的个人介绍页，而更接近一个持续扩展的 **浏览器实验室 / 作品索引**。

网站仓库：

**https://github.com/HunLuanZhiZhu/hunluanzhizhu.github.io**

它把我的交互实验、研究展示、AI 生成与评测、图形实验、小游戏、工具和部分实际应用统一放到一个可以直接在浏览器访问的入口中。

网站根首页本身就是一个完整作品：采用纯静态 HTML，样式、字体与 JavaScript 大量内联，运行时不依赖前端框架或构建系统；各个独立项目放在 `/projects/` 下，可以直接作为浏览器应用运行。

目前网站中可以看到的代表内容包括：

- **Minecraft Web**：使用 Rust + Bevy + WebAssembly 实现的浏览器 3D 沙盒实验。
- **霓虹脉冲**：基于 Canvas 的街机式闪避游戏。
- **组会 PPT 合集**：把研究组会讲稿直接做成网页演示，并提供聚合索引和阅读展示。
- **GUON Optimizer**：围绕优化器与大模型展开的研究/讽刺性实验项目。
- **心韵深辨（ECG AI Local）**：在浏览器本地运行的 ECG / AI 实验，涉及 TensorFlow.js 与脉冲神经网络相关思路。
- **AI 连续版 · 滑动变祖器**：结合 AI、视频与 Canvas 交互的校准实验。
- **AI 游戏生成评测**：把 AI 游戏生成结果与评测过程以网页形式发布，涉及 Godot 与 WebAssembly。
- **动态 SVG 鹈鹕**：围绕 SVG 与动画绘制的实验。
- **Blender 3D**：Blender、glTF 与 WebGL 相关的 3D 展示实验。
- **Open Design Test**：使用 WebGL2、着色器等技术进行的开放设计实验。
- 网站中还包含少量客户项目和实用工具。

首页本身也包含大量交互设计：项目分类与搜索、中英文切换、程序生成图形、WebGL 星空、交互动效、键盘导航、响应式布局、动效开关等。

因此，对我来说，这个网站更像是整个 GitHub 的可视化入口：

**研究成果 + AI 实验 + 图形与游戏 + 工具 + 浏览器工程**

如果想最快了解我在做什么，个人网站比单独查看某一个仓库更直观。

## 关于我

我是一名偏研究型的 AI 开发者。相比只把现有模型当作黑盒调用，我更关注算法机制本身，以及怎样把论文、想法和实验真正落成可以运行、修改、验证和复用的工程实现。

从目前仓库中比较稳定的一条工作链路是：

**论文 → 机制分析 → 复现 → 修改 → 实验 → 工程化 → 自动化**

我的项目既包括优化算法、强化学习等研究代码，也包括智能体工具、大模型接口基础设施、浏览器实验和研究展示系统。

## 代表仓库

### AdaNCFGD

基于 PyTorch 的自适应分数阶梯度下降优化器，并包含脉冲神经网络相关实现。

这个项目比较能代表我对优化机制、训练过程以及“把实验算法做成可复用软件”的兴趣。

https://github.com/HunLuanZhiZhu/AdaNCFGD

### mini-proxy

使用 Rust 编写的轻量 AI 接口代理，同时兼容 OpenAI 风格、Anthropic 风格和 Responses 风格协议。

其中包含流式转发、自动重试、模型映射、请求清洗、思考强度配置和协议适配等功能，代表了我在 AI 系统工程和基础设施这一侧的兴趣。

https://github.com/HunLuanZhiZhu/mini-proxy

### .agents

我的个人 AI 智能体技能与工作流集合。

里面组织了可复用技能、智能体行为约束、版本锁定、研究与生产力工具。它代表我近来的一个明显方向：不再只把 AI 当聊天界面，而是把智能体当成可以编程和组合的研究基础设施。

https://github.com/HunLuanZhiZhu/.agents

### Auto-zcode-research-in-sleep

围绕 AI 智能体自动化研究、自动化编程流程进行的实验。

https://github.com/HunLuanZhiZhu/Auto-zcode-research-in-sleep

### ZCode-Game-Studios

围绕 AI 辅助游戏生成与评测的项目，与个人网站中的 AI 游戏生成评测页面相互关联。

https://github.com/HunLuanZhiZhu/ZCode-Game-Studios

### liang-intensity-calibrator

一个 AI 相关的交互校准项目，同时也作为网页作品发布在个人网站中。

https://github.com/HunLuanZhiZhu/liang-intensity-calibrator

## 研究与工程兴趣

目前仓库中比较明显的方向包括：

- 优化算法与神经网络训练；
- 强化学习与多智能体方法；
- 脉冲神经网络；
- AI 智能体与自动化研究流程；
- 大模型接口基础设施与不同模型协议适配；
- 浏览器原生交互系统；
- AI 辅助图形、游戏与设计实验；
- 论文复现、实验与研究展示。

这些方向背后的共同点不是固定使用某一种语言或框架，而是按问题选择合适的算法、工具和工程层级。

## 当前方向

从近期仓库的变化来看，一个比较明显的转变是：

**研究 AI 系统**

逐渐变成：

**构建能够帮助我继续研究、编程、实验和创作的 AI 系统**

个人网站负责把这些结果以可交互的方式公开展示，而 GitHub 仓库保存更底层的实验、工具和研究实现。

---

本页由 **GPT-5.6 Sol 网页版** 基于 **HunLuanZhiZhu** 当前 GitHub 仓库总结生成。
