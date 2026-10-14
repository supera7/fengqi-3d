# 冯契学术成就陈列室 · 3D 导览

静态网站，无需构建。把本文件夹整体上传到任意静态托管（如 GitHub Pages 仓库根目录）即可访问 index.html。

- index.html：页面本体，3D 模型用 Three.js 0.160（从 cdn.jsdelivr.net 加载）
- assets/：陈列室及所在建筑实景照片，带 -s 的是缩略图

修改展区文字或照片：编辑 index.html 中 `window.ZONES` 数组。
本地预览：在本文件夹运行 `python3 -m http.server`，打开 http://localhost:8000

