# Awesome Vibe Coding

这个仓库用来收集Vibe Coding相关的资料。

## 关于Vibe Coding概念

Vibe Coding是一种新型的编程方式，由AI辅助完成代码编写，让开发者能够更专注于创意和解决方案，而非代码细节。

- [Andrej Karpathy的观点](https://x.com/karpathy/status/1886192184808149383) - "有一种新的编程方式，我称之为“氛围编程”，就是完全沉浸其中，拥抱指数级增长，甚至忘记代码的存在。之所以可能，是因为 LLMs（例如 Cursor Composer w Sonnet）已经太强大了。我还用 SuperWhisper 和 Composer 交流，几乎不碰键盘。我总是要求最简单的事情，比如“将侧边栏的填充减半”，因为我懒得找。我总是“接受所有”，不再看差异。当出现错误信息时，我只是复制粘贴，不加评论，通常就能解决。代码已经超出了我的理解范围，我不得不花些时间仔细阅读。有时 LLMs 无法修复错误，我就只能绕过它，或者要求随机更改直到问题消失。对于一次性周末项目来说还不错，但仍然很有趣。我正在做一个项目或网页应用，但这根本不是编程——我只是看东西、说东西、运行东西、复制粘贴东西，而且它大部分都能正常工作。"。
- 扩展资料阅读：
  - [什么是氛围编程 (vibe coding)？](https://cloud.google.com/discover/what-is-vibe-coding?hl=zh-CN)

## 目录

- [AI IDE](#AI IDE)
- [命令行助手](#命令行助手)
- [编辑器插件](#编辑器插件)
- [云端开发环境](#云端开发环境)
- [移动应用](#移动应用)
- [本地应用](#本地应用)
- [团队协作解决方案](#团队协作解决方案)
- [专业开发工具](#专业开发工具)
- [AI编程文档工具](#ai编程文档工具)
- [任务管理工具](#任务管理工具)
- [新闻和社交媒体](#新闻和社交媒体)
- [Vibe Coding经验分享](#vibe-coding经验分享)

## AI IDE

- **[Cursor](https://cursor.com/)** - 基于VS Code构建的AI优先编辑器，提供智能代码补全和重构功能，支持多种大语言模型，目前最流行的AI IDE之一。

- **[Zed](https://zed.dev/)** - 使用Rust开发的高性能编辑器，具有120fps渲染速度和原生AI辅助功能，专为人类和AI协作设计。

- **[Void](https://voideditor.com/)** - 注重隐私的开源编辑器，支持本地托管AI模型和检查点可视化。

- **[codebuddy](https://cloud.tencent.com/product/codebuddy)** - 集成前后端和数据库自动化生成，支持Figma设计转代码。

- **[通义灵码](https://tongyi.aliyun.com/lingma)** - 阿里巴巴推出的多语言代码助手，支持主流IDE集成。

- **[百度智能编程](https://comate.baidu.com/)** - 提供端到端开发自动化，支持多种编程语言和开发环境。

- **[JetBrains AI](https://www.jetbrains.com/idea/)** - 为IntelliJ IDEA等产品提供的智能编程辅助功能。

- **[Windsurf](https://codeium.com/windsurf)** - Codeium推出的智能编辑器，"开发者和AI真正流畅协作的编码体验，感觉像魔法一样"。

- **[Kiro](https://kiro.dev)** - 从原型到生产的AI IDE，提出了先写好文档再写代码的模式。

## 命令行助手

- **[claudecode](https://claude.ai/code)** - 支持全代码库感知的终端工具，集成Git工作流。

- **[谷歌终端助手](https://ai.google.dev/gemini-api/docs/cli)** - 支持百万级上下文窗口的命令行工具，强化Shell脚本自动化。

- **[Aider](https://aider.chat/)** - 结对编程终端工具，集成Git功能，专注代码补丁和导航。

- **[Warp](https://www.warp.dev/)** - 重新设计的终端应用，支持自然语言命令和智能补全。

- **[阿里通义编程模型](https://github.com/QwenLM/Qwen3-Coder)** - 支持多种编程语言的高级代码理解和生成模型。

- **[iflow命令行](https://github.com/iflow-ai/iflow-cli)** - 为开发者提供任务编排和流程自动化的智能工具。

- **[Goose](https://block.github.io/goose/)** - 本地AI代理，允许使用任何LLM并添加任何MCP服务器作为扩展。

- **[MyCoder.ai](https://github.com/drivecore/mycoder)** - 开源AI编程助手，集成Git和GitHub，具有并行执行和自我修改功能。

- **[RA.Aid](https://github.com/ai-christianson/RA.Aid)** - 基于LangGraph代理任务执行框架构建的独立编码代理。

- **[CodeSelect](https://github.com/maynetee/codeselect)** - 基于Python的命令行工具，高效地将项目源代码传输给AI。

- **[Crush](https://github.com/charmbracelet/crush)** - "终端中的魅力AI编码代理"，生成命令行界面。

## 编辑器插件

- **[GitHub编程助手](https://github.com/features/copilot)** - 支持14种编程语言的智能代码建议工具，集成多种IDE。

- **[Continue](https://github.com/continuedev/continue)** - 开源的多模型集成插件，支持内联代码聊天和项目上下文。

- **[代码搜索助手](https://sourcegraph.com/cody)** - 提供多仓库代码搜索和解释功能，支持自定义提示。

- **[智能代码审查](https://graphite.dev/)** - 优化PR工作流，提供即时AI代码审查和分支管理。

- **[本地AI补全](https://www.tabnine.com/)** - 支持本地部署的代码补全工具，适应个人编码风格。

- **[大上下文编程](https://augmentcode.com/)** - 支持20万+上下文令牌的企业级代码助手，符合SOC2标准。

- **[Cline](https://cline.bot/)** - 可以使用CLI和编辑器的AI助手，适用于VS Code。

- **[Roo Code](https://github.com/RooVetGit/Roo-Code)** - Cline的分支，具有额外功能和增强。

- **[avante.nvim](https://github.com/yetone/avante.nvim)** - Neovim插件，模拟Cursor AI IDE的行为，提供AI驱动的代码建议。

- **[prompt-tower](https://github.com/backnotprop/prompt-tower)** - 帮助构建包含多个代码块的提示工具。

- **[Superdesign.dev](https://www.superdesign.dev/)** - 开源设计代理。

## 云端开发环境

- **[V0设计转代码](https://v0.app/)** - Vercel推出的自然语言转React UI工具，内置现代组件库。

- **[WebContainers开发](https://bolt.new/)** - 浏览器内全栈应用开发环境，无需本地安装。

- **[自然语言应用构建器](https://lovable.dev/)** - 从文本描述快速创建全栈网络应用的无代码平台。

- **[多语言云IDE](https://replit.com/ai)** - 支持多种编程语言的浏览器IDE，提供实时协作和错误修复。

- **[WordPress智能构建](https://codewp.ai/)** - 专为WordPress设计的AI网站构建工具。

- **[CHAI.new](https://chai.new)** - 通过提示快速构建任何AI代理并部署（代理、应用、API）。

- **[Create](https://www.create.xyz/)** - "将你的文字转化为网站、工具、应用和产品"。

- **[Trickle AI](https://www.trickle.so/)** - "轻松构建令人惊叹的网站、AI应用和表单"。

- **[Tempo](https://www.tempo.new/)** - "使用AI构建React应用，速度提升10倍"。

- **[Softgen](https://softgen.ai/)** - "描述你的愿景，给出指示，构建全栈Web应用"。

- **[Lazy AI](https://getlazy.ai/)** - "使用提示构建可靠的业务应用"。

- **[HeyBoss](https://www.heyboss.xyz/)** - "在几分钟内构建应用和网站"。

- **[Creatr](https://getcreatr.com/)** - "在几秒钟内创建和部署Web应用和登陆页面"。

- **[Rork](https://rork.app/)** - "快速构建任何移动应用"。

- **[Firebase Studio](https://studio.firebase.google.com/)** - 谷歌的基于云的开发环境，帮助构建和发布生产质量的全栈AI应用。

- **[Napkins.dev](https://www.napkins.dev/)** - 截图转代码。

- **[HeroUI Chat](https://heroui.chat/)** - 无论设计经验如何，都能生成漂亮的应用。

- **[Rocket.new](https://www.rocket.new/)** - "无需代码，构建Web和移动应用速度提升10倍"。

## 移动应用

- **[VibeCode](https://www.vibecodeapp.com/)** - 构建应用的应用。

## 本地应用

- **[Dyad](https://www.dyad.sh/)** - 免费、本地、开源的AI应用构建器。

## 团队协作解决方案

- **[OpenAI编程平台](https://openai.com/codex/)** - 提供云端智能体和私有部署选项的综合代码生成系统。

- **[自主软件工程师](https://devin.ai/)** - 提供端到端自动化的团队级AI编程助手。

- **[多智能体协作空间](https://replit.com/)** - 支持多用户协作的自然语言编程环境。

- **[AWS开发助手](https://aws.amazon.com/q/developer/)** - 原生集成AWS服务的编码智能体。

- **[企业级代码助手](https://www.ibm.com/products/watsonx-code-assistant)** - 为受监管行业定制的大型机开发自动化工具。

## 专业开发工具

- **[代码仓库管理](https://github.com/repo-prompt/repo-prompt)** - Mac原生的AI文件和代码管理工具。

- **[安全代码分析](https://snyk.io/product/deepcode-ai/)** - 提供快速代码安全分析和修复建议。

- **[前端性能优化](https://umami.is/)** - 专注于前端优化和性能分析的AI工具。

- **[错误诊断系统](https://traceroot.ai/)** - 自动进行根因分析和补丁建议。

- **[可视化代码审查](https://coldeco.ai/)** - 为AI生成的代码提供可视化检查和审查功能。

## AI编程文档工具

- **[CodeGuide](https://www.codeguide.dev/)** - 为AI编码项目创建详细文档。

- **[AGENTS.md](https://agents.md/)** - 一种简单、开放的格式，用于指导编码代理。

## 任务管理工具

- **[Boomerang Tasks](https://docs.roocode.com/features/boomerang-tasks)** - 自动将复杂项目分解为更小、更易管理的部分。

- **[Claude Task Master](https://github.com/eyaltoledano/claude-task-master)** - 一个AI驱动的任务管理系统，可以集成到Cursor、Lovable、Windsurf、Roo等工具中。

## 新闻和社交媒体

> 此部分按时间倒序排列，最新条目在顶部。

- [程序员的提示工程手册](https://addyo.substack.com/p/the-prompt-engineering-playbook-for)
- [什么是vibe coding？计算机科学家解释AI编写代码的含义及其可能带来的风险](https://theconversation.com/what-is-vibe-coding-a-computer-scientist-explains-what-it-means-to-have-ai-write-computer-code-and-what-risks-that-can-entail-257172)
- [与LLM结对编程，适用于高级工程师](https://pmbanugo.me/blog/peer-programming-with-llms)
- [代码之道 | Rick Rubin](https://www.thewayofcode.com/)
- [Vibe Coding工具现状（2025年5月）| LinkedIn](https://www.linkedin.com/pulse/state-vibe-coding-tools-may-2025-nufar-gaspar-x1znf/?trackingId=iJSsdxE4R9OECPT43FtBww%3D%3D)
- [Vibe coding MenuGen | karpathy](https://karpathy.bearblog.dev/vibe-coding-menugen/)
- [两家出版商和三位作者未能理解"vibe coding"的含义](https://simonwillison.net/2025/May/1/not-vibe-coding/)
- [并非所有AI辅助编程都是vibe coding（但vibe coding很棒）](https://simonwillison.net/2025/Mar/19/vibe-coding/)
- [使用Replit的Vibe Coding 101 - DeepLearning.AI](https://www.deeplearning.ai/short-courses/vibe-coding-101-with-replit/)
- ["vibe coding"思维病毒解释...由Fireship - YouTube](https://www.youtube.com/watch?v=Tw18-4U7mts)
- [软件开发的未来会基于氛围吗？- Ars Technica](https://arstechnica.com/ai/2025/03/is-vibe-coding-with-ai-gnarly-or-reckless-maybe-some-of-both/)
- [Vibe Coding - 人人都能"说"计算机编程 - The New Stack](https://thenewstack.io/vibe-coding-where-everyone-can-speak-computer-programming/)
- [A.I.和Vibecoding帮助我创建了自己的软件 - 纽约时报](https://www.nytimes.com/2025/02/27/technology/personaltech/vibecoding-ai-software-programming.html)
- [Reddit: r/vibecoding](https://www.reddit.com/r/vibecoding/)
- [Reddit: r/ChatGPTCoding](https://www.reddit.com/r/ChatGPTCoding/)

## Vibe Coding经验分享

- [《vibe coding经验分享——一份Vibe Coding深度依赖患者生存指南》](https://linux.do/t/topic/844593/1)

## Vibe Coding救援服务

- https://vibe-coding-rescue.zhaixingren.cn/

## 如何贡献

欢迎提交PR添加新工具或更新现有信息。请确保您的贡献符合以下标准：

- 工具应当有实际可用的产品或至少是公开测试版
- 提供简洁准确的描述和官方链接
- 说明工具的主要特点和适用场景

## 许可证

本项目采用MIT许可证