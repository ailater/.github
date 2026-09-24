# AI Later

一个人打磨的纯 Rust 开源组织，当前只有一个目标：做好 **[LaterMD](https://github.com/ailater/LaterMd)** —— 跨平台、版本化、可对话、可演化的 Markdown 知识工作台。

> Markdown 是内容层，AI 是智能层，Git 是时间层。

## 🧭 产品路线

- **P0（进行中）**：左右双栏实时预览 / 新建打开保存 / GFM + 代码高亮 / 导出 HTML / 三平台打包（Windows 11 · macOS 14 · Linux）
- **P1**：AI 流式写作与摘要
- **P2**：Git 只读集成（状态 / 历史 / diff / 回滚）

## 🦀 技术路线

- 纯 Rust GUI：egui + eframe（wgpu 渲染）
- 单一 Markdown 解析器：pulldown-cmark
- 版本化：git2

## 🔗 链接

- [LaterMD 主仓库](https://github.com/ailater/LaterMd) · MIT License
