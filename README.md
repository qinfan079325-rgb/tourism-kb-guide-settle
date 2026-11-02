# 导游报账计算器 · 帽子云静态前端

本仓库供帽子云静态网站部署使用。页面同源请求 `/api/*`，由帽子云网关反向代理到 Cloudflare Worker `guide-settle.qinfan079325.workers.dev`（存储仍在 Cloudflare KV）。

源码与 Worker：`tourism-kb-model/web/guide-settle/`。
