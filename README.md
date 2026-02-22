# 🧰 AI JSON 工具箱

一个纯前端的 AI JSON 工具箱，集成 DeepSeek API，提供 JSON 处理和 AI 辅助功能。

## 功能

- **JSON 格式化/压缩** — 语法高亮、错误提示
- **JSON → TypeScript** — 自动推断类型定义，支持嵌套对象和数组
- **JSON → CSV** — 数组数据一键转表格，支持下载
- **JSON Diff 对比** — 逐行对比两段 JSON 的差异
- **AI 解释 JSON** — 使用 DeepSeek 分析 JSON 结构和含义
- **AI 生成 JSON** — 用自然语言描述需求，AI 生成示例数据

## 使用

1. 直接用浏览器打开 `index.html`
2. AI 功能需要在右上角填入 [DeepSeek API Key](https://platform.deepseek.com/)（自动保存到 localStorage）

## 技术栈

- 纯 HTML + CSS + JavaScript，无任何依赖
- DeepSeek API（`deepseek-chat` 模型）
- 响应式设计，支持移动端

## License

MIT
