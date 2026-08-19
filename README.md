# My Life OS v1.2 Stable

稳定测试版：JS/CSS 已直接内置进 index.html，避免 GitHub Pages / Safari 继续混用旧版 app.js 与 style.css。

## 上传
把本目录 3 个文件上传到仓库根目录并覆盖：index.html、manifest.webmanifest、README.md。
旧的 app.js、style.css、sw.js 可以删除；即使暂时保留也不会被 v1.2 调用。

打开页面顶部应看到 `v1.2 Stable · JS 内置`。点击任意按钮时会短暂显示 `点击正常`，用于判断交互事件是否执行。
