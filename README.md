# yyxy-landing

yyxy.loc.cc 的落地页，纯静态单页，无构建步骤。

- 入口：`index.html`
- 部署：Cloudflare Pages，项目名 `yyxy-landing`
- 自定义域名：`yyxy.loc.cc`（Yunamo 里 CNAME @ → `yyxy-landing.pages.dev`）
- 邮箱入口指向 https://mail.oco.icu

本地部署：`wrangler pages deploy . --project-name yyxy-landing`
