# Json-format-web

一个轻量级的浏览器端 JSON 格式化工具，纯 HTML/CSS/JavaScript 单文件实现，无需安装，双击打开即可使用。
A lightweight browser-side JSON formatter, implemented in a single file using pure HTML/CSS/JavaScript. No installation required — just double-click to open.

解决网页在线JSON格式化，文本框小，广告多等问题
Solve issues such as online JSON formatting on web pages, small text boxes, and excessive advertisements

## 功能 / Features

- **JSON 格式化 / JSON Format** — 将 JSON 文本美化缩进输出 / Pretty-print JSON with indentation
- **JSON 压缩 / JSON Minify** — 将 JSON 文本压缩为单行，也支持非 JSON 文本的空白压缩 / Minify JSON to a single line; also supports compressing whitespace for non-JSON text
- **添加转义 / Add Escape** — 将 `"` 转义为 `\"` / Escape double quotes by adding backslash
- **去除转义 / Remove Escape** — 将 `\"` 还原为 `"` / Remove escape backslashes before double quotes
- **可折叠 Tree 视图 / Collapsible Tree View** — 右侧面板以树形结构展示 JSON，支持展开/折叠 / Display JSON as a collapsible tree in the right panel
- **行号显示与搜索 / Line Numbers & Search** — 左侧编辑器带行号，支持关键词搜索与跳转 / Editor with line numbers, keyword search and navigation
- **错误行标注 / Error Line Highlight** — JSON 解析失败时红色标注错误行号和位置 / Highlight error line and position in red when parsing fails
- **渐进增强 / Progressive Enhancement** — 联网时自动加载 CodeMirror 6 增强编辑体验，离线时使用原生 textarea，核心功能不受影响 / Automatically loads CodeMirror 6 for enhanced editing when online; falls back to native textarea offline — core features always work

## 使用方法 / Usage

直接在浏览器中打开 `index.html` 即可使用，无需任何服务器或构建工具。

Open `index.html` directly in your browser. No server or build tools needed.
