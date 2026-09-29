# TwilightSinging.github.io

个人静态博客脚手架：**晚霞的笔记**（暂定名，可随时改）。

站点地址：<https://TwilightSinging.github.io/>

## 结构

```
.
├── index.html          # 首页
├── about.html          # 关于
├── css/style.css       # 样式（配色为临时 dusk/amber，易改）
├── posts/
│   ├── index.html      # 文章列表
│   ├── go-hello-modules.html
│   └── lab-share-stub.html
└── README.md
```

纯 HTML / CSS，无构建步骤。GitHub Pages 可直接从仓库根目录提供静态文件。

## 如何启用 GitHub Pages

本仓库名为 `TwilightSinging.github.io`（`<username>.github.io`），属于用户级 Pages 站点：

1. 将站点文件放在 **默认分支（`main`）的根目录**。
2. 打开仓库 **Settings → Pages**。
3. Source 选择 **Deploy from a branch**。
4. Branch 选 **`main`**，文件夹选 **`/ (root)`**，保存。
5. 稍等一两分钟后访问 <https://TwilightSinging.github.io/>。

若首次创建后尚未自动开启 Pages，按上述步骤手动勾选一次即可。推送后部署通常需要几分钟。

## 本地预览

在本目录启动任意静态服务器，例如：

```bash
python3 -m http.server 8080
```

浏览器打开 `http://localhost:8080`。

## 后续

- 替换占位中文内容为真实 Go 笔记 / 实验分享
- 调整 `css/style.css` 中的配色与布局（文件顶部有 provisional 注释）
- 若需要 Markdown 工作流，可再接入简单生成器（如 Jekyll / Hugo），当前刻意保持零构建

## License

内容版权归 TwilightSinging。代码脚手架可自由改用。
