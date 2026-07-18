# Markdown 笔记本（手机版 PWA）

一个单文件 HTML 的 Markdown 笔记本，支持：
- 多页面管理（新建/导入/删除）
- 所见即所得工具栏（标题/加粗/颜色/高亮/列表/引用）
- 数学公式渲染（MathJax，行内 + 块级）
- 自动保存到浏览器 localStorage
- PWA：可"添加到主屏幕"当 App 用

## 访问地址
部署到 GitHub Pages 后，访问：
```
https://<你的用户名>.github.io/md-notebook/
```

## 本地使用
直接双击 `index.html` 在浏览器打开（注意：file:// 下 PWA 离线缓存不生效，需通过 HTTPS 访问才完整可用）。