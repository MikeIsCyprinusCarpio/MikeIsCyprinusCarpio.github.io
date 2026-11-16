# 个人主页

使用 GitHub Pages 内置的 Jekyll 构建，直接编辑 Markdown 即可更新。

## 填写内容

1. 打开 `index.md`，点击铅笔按钮编辑。
2. 替换个人介绍、项目、文章和联系方式，也可自由增删栏目。
3. 点击 Commit changes 保存，等待 GitHub Pages 构建更新。

`#` 表示主标题，`##` 表示栏目标题，`###` 表示项目标题。链接写作 `[显示文字](https://example.com)`。上传图片到 `assets/`，通过 `![图片说明](/assets/文件名.jpg)` 引用。

修改站点名称和搜索摘要时，同步编辑 `_config.yml` 的 `title` 和 `description`，以及 `index.md` 顶部同名字段。可在 `_layouts/default.html` 中修改页头链接，在 `assets/style.css` 中调整样式。

## 首次发布

仓库名使用 `MikeIsCyprinusCarpio.github.io`，公开可见。

在仓库 Settings → Pages 中，选择 Deploy from a branch，再选择 `main` 和 `/ (root)`，点击 Save。构建成功后访问 https://mikeiscyprinuscarpio.github.io/ 。

## 文件

- `index.md` 存放主页正文。
- `_config.yml` 存放站点设置。
- `_layouts/default.html` 存放页面结构。
- `assets/style.css` 存放响应式样式，并跟随系统切换深浅色。
