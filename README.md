# GROK EXTRA

每日 9:00 · 上海。静态站，由 GitHub Pages 从 `main` 分支根目录发布。

https://afterlifebar.github.io/grok-daily/

## 仓库结构

- `index.html`、`style.css` 在根目录。`.nojekyll` 避免 Jekyll 处理。
- 每期页面：`issues/YYYY-MM-DD.html`（从 `templates/issue.html` 复制，替换 `{{…}}` 占位符）。
- 图片：`img/YYYY-MM-DD/`。封面与配图先压成 JPG，宽不超过 1080px，封面质量约 80、不超过 300KB；配图高度不超过 1600px。不要做长图，不要外链原图，不要内嵌 base64，只用相对路径。
- 新的一期替换首页「最新一期」（封面 + 标题）。更早的期数写在 `ISSUES` 注释下，两行：小字「第 N 期 · 日期」，标题用正文色。不要把最新一期再列进往期。

Pages：Settings → Pages → Deploy from branch → `main` / `(root)`。
