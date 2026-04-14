# Ralph：自主式 AI 开发循环完全指南

![Ralph Course Banner](https://img.shields.io/badge/Language-Zh_CN-blue)
![Modules](https://img.shields.io/badge/Modules-6-green)
![Difficulty](https://img.shields.io/badge/Difficulty-Beginner--Intermediate-orange)

---

## 📖 课程简介

这是一门关于 **Ralph** 的交互式课程。Ralph 是一种自主式 AI 开发工作流，它让 AI 能够跨多次迭代完成复杂任务。

**你将学会：**

- Ralph 的核心设计哲学：Fresh instance, persistent memory
- 如何将大需求拆解成可执行的小故事
- Ralph 的各个"演员"（文件）如何协同工作
- 数据在迭代间如何流动
- 如何利用记忆机制让 AI 学习成长
- 调试和问题排查技巧

### 谁适合这门课程？

- 想用 AI 进行开发的开发者
- 对 AI 编程工作流感兴趣的人
- 想要了解如何让 AI 记住学习成果的人

---

## 🏗️ 项目结构

```
ralph-course/
├── index.html          # 课程主页
├── styles.css          # 样式文件
├── main.js             # 交互逻辑
├── modules/            # 6个模块
│   ├── 01-intro.html   # 模块1：Ralph 是什么？
│   ├── 02-actors.html  # 模块2：Ralph 的演员
│   ├── 03-data-flow.html # 模块3：数据如何流动
│   ├── 04-memory.html  # 模块4：内存的秘密
│   ├── 05-patterns.html # 模块5：聪明的技巧
│   └── 06-debugging.html # 模块6：当问题发生时
└── build.sh            # 构建脚本
```

---

## 🚀 快速开始

### 本地运行

```bash
# 进入项目目录
cd ralph-course

# 启动本地服务器（Python）
python3 -m http.server 8000

# 或使用 Node.js
npx serve .

# 或使用 PHP
php -S localhost:8000
```

然后在浏览器打开 [http://localhost:8000](http://localhost:8000)

### 在线查看

直接打开 `index.html` 文件即可在浏览器中查看课程。

---

## 📚 课程大纲

### 模块 1：Ralph 是什么？

理解自主式 AI 开发循环的核心思想。

- Ralph 的核心设计哲学
- 解决什么问题
- 真实场景演示
- 为什么适合 vibe coders

### 模块 2：认识 Ralph 的"演员"

每个文件都有它的角色。

- 工作流层：ralph.sh、prompt.md、CLAUDE.md
- 数据层：prd.json、progress.txt、AGENTS.md
- Git 层：Git History、Branch

### 模块 3：数据如何流动

从任务挑选到完成的完整路径。

- 一次迭代的完整生命周期
- 代码 ↔ 自然语言翻译
- 数据流图解析
- 场景模拟

### 模块 4：内存的秘密

Ralph 如何在无状态 AI 实例间传递知识。

- progress.txt：学习日志
- AGENTS.md：代码库指南
- Git History：变更历史
- 归档机制

### 模块 5：聪明的技巧

Ralph 如何避免常见陷阱。

- 故事拆分：小而可完成
- 验收标准：必须可验证
- 质量检查：永远不能绕过
- 自动归档和错误处理

### 模块 6：当问题发生时

调试技巧和解决方案。

- 常见问题诊断
- 调试策略
- 最佳实践

---

## 🎯 关键概念

### Fresh Instance, Persistent Memory

这是 Ralph 最核心的设计哲学。每次迭代启动的都是全新的 AI 实例（没有上下文记忆），但通过三个"记忆载体"让知识跨迭代传递：

1. **progress.txt** - 迭代日志，只追加不覆盖
2. **AGENTS.md** - 项目指南，汇总代码库模式
3. **Git History** - 代码变更历史

### 用户故事（User Story）

每个用户故事应该：
- 小到可以在一次迭代内完成
- 只有一个职责
- 有明确的验收标准
- 优先级可排序

### 验收标准（Acceptance Criteria）

必须是可验证的，例如：
- `Typecheck passes` - 类型检查通过
- `Tests pass` - 测试通过
- `Verify in browser` - 浏览器验证

---

## 🛠️ 交互功能

课程包含多种交互元素：

- **测验**：每个模块后都有小测验巩固知识
- **拖拽练习**：匹配文件与职责
- **对话模拟**：理解各组件如何交互
- **动画演示**：可视化数据流动
- **Bug 挑战**：找出代码中的问题

---

## 🔗 相关资源

- [Ralph 项目](https://github.com/) - 主要代码库
- [Claude Code](https://claude.ai/) - AI 开发工具
- [Amp](https://amp.computer/) - AI 开发平台

---

## 📄 许可证

本项目遵循 MIT 许可证。详见 [LICENSE](LICENSE) 文件。

---

## 🙏 致谢

- Ralph 团队
- 所有贡献者

---

## 📬 反馈

欢迎提交 Issue 或 Pull Request 来改进这个课程！