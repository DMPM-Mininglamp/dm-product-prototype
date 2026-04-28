# OctoPush GitHub Pages Review

这是稳定公网发布版，不依赖本机 tunnel。

## 交互

- 评审人打开 GitHub Pages 链接。
- 添加原型或 PRD 评论。
- 点击「提交 Issue」。
- 页面会打开 GitHub 新建 Issue 页面，并预填标题、标签和正文。
- 评审人确认提交。

说明：静态 Pages 页面不能安全地内置 GitHub token，所以这里不从浏览器直接调用 GitHub API；这样不会泄漏 token，也不会依赖本地服务。
