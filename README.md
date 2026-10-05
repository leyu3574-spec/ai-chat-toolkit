# 🧰 AI 对话工具箱

**把你的 Claude / ChatGPT 聊天记录吃干抹净**：浏览对话、生成年度报告、分享精美长图 —— 一个单文件，三种玩法。

![在线试用](https://img.shields.io/badge/在线试用-GitHub_Pages-6C4CF1) ![单文件](https://img.shields.io/badge/单文件-零安装-success) ![离线](https://img.shields.io/badge/离线-数据不出本机-blue)

👉 **在线试用**：https://leyu3574-spec.github.io/ai-chat-toolkit/

## ✨ 功能

### 📖 对话浏览
- 导入官方导出的 `conversations.json`（Claude / ChatGPT 都支持，自动识别）
- 对话列表 + 标题搜索，点击即读
- Markdown 渲染：代码块、粗体、列表，还原阅读体验

### 📊 年度报告（AI Wrapped）
- 📈 核心数据：总对话数、总消息数、你的提问 vs AI 的回复、总字数、估算 Token
- 🟩 **活跃热力图**：GitHub 绿格子风格，一年中的每一天
- 🕐 **24 小时作息**：你最常在几点和 AI 聊天（深夜党现形）
- 📅 **月度趋势**：每个月的消息量变化
- ☁️ **话题词云**：从你的提问中提取年度关键词
- 🎯 趣味统计：最长的一次对话、高峰时段、数据跨度
- ⬇️ **一键生成分享卡片**（1080px PNG，直接发小红书）

### 🖼️ 长图分享
- 任选一条对话，生成 1080px 精美长图
- 三种主题：☀️ 浅色 / 🌙 深色 / 📜 纸质

## 🚀 使用

1. 导出对话：
   - **Claude**：设置 → 导出对话，下载 `conversations.json`
   - **ChatGPT**：设置 → 数据控制 → 导出数据，解压后找到 `conversations.json`
2. 打开本工具，把文件拖进来
3. 浏览、看报告、生成长图，随意玩

> 🔒 **隐私**：纯前端单文件应用，所有解析和统计都在你的浏览器本地完成，不上传任何数据。你可以断网使用。

## 🛠️ 技术

- 零依赖，单 HTML 文件（`index.html`）
- 图表全部手绘 Canvas：热力图、柱状图、词云
- 中文关键词提取：n-gram + 停用词过滤 + 词频统计

## 📄 License

MIT
