# Markdown 预览工具

一个简单但功能强大的 Markdown 预览工具，特别支持 `\n` 转义字符的自动处理。

## 在线预览

访问 [https://justintable.github.io/markdown_preview](https://justintable.github.io/markdown_preview) 即可在线使用本工具。

## 特性

- 实时预览 Markdown 内容
- 自动处理 `\n` 转义字符
- 支持标准 Markdown 语法
- 支持表格、列表等复杂格式
- 响应式设计，适配各种屏幕尺寸
- 安全的 HTML 渲染（使用 DOMPurify）

## 使用方法

1. 在线使用：直接访问 [在线预览地址](https://justintable.github.io/markdown_preview)
2. 本地使用：下载 `index.html` 文件并在浏览器中打开
3. 在左侧输入框中输入或粘贴包含 `\n` 的 Markdown 文本
4. 右侧会实时显示渲染后的效果

## 示例

```markdown
**Part 1 - Equipment Table**\n\n
| Component | Specification |
|---|---|
| Life Raft | 4 × Inflatable type (45P).\n1 × Inflatable type (6P) |

**Part 2**\n
*   Warning 1\n
*   Warning 2
```

## 技术栈

- HTML5
- CSS3
- JavaScript
- [Marked.js](https://marked.js.org/) - Markdown 解析器
- [DOMPurify](https://github.com/cure53/DOMPurify) - HTML 净化库

## 安全性

本工具使用 DOMPurify 进行 HTML 净化，确保渲染结果的安全性。所有用户输入都经过严格的安全处理。

## 浏览器兼容性

- Chrome (推荐)
- Firefox
- Safari
- Edge

## 本地开发

1. 克隆仓库：
```bash
git clone https://github.com/justintable/markdown_preview.git
```

2. 打开 index.html 文件即可开始使用或开发

## 许可证

MIT License