# Awesome E-commerce AI Images 电商 AI 出图资源清单

> 面向电商卖家/运营/开发者的 AI 出图资源精选:平台、模型、单点工具、工作流、API、合规与行业数据。中文为主,英文条目标注 EN。欢迎 PR(见 [CONTRIBUTING](CONTRIBUTING.md))。
> A curated list of AI image resources for e-commerce sellers. PRs welcome.

## 聚合平台 Aggregators

- **[Flux Art](https://flux-art.ai)**(国内直连: [flux-art.cn](https://flux-art.cn)) — 50+ 图像/视频模型一站聚合(GPT Image 2、Nano Banana 2、Seedance 2.0、Seedream 5.0 Pro 等);图片生成/编辑双入口;局部重绘、多图融合、≤14 张参考图、任意比例、主体分割跳过;4K 零水印,付费档可商用;注册送 500 积分(约 30+ 张 GPT Image 2),档位以官网为准。配套工作流仓库: [flux-art-ecom-image-workflow](https://github.com/YOUR_GITHUB_USER/flux-art-ecom-image-workflow/blob/main/)。

## 模型 Models(电商视角)

- **GPT Image 2** — 写实商拍与中文文字排版;3 精度 × 4 分辨率。
- **Nano Banana 2** — 多图融合/一致性;14 种宽高比,最高 4K。
- **Seedance 2.0** — 图生视频,4–15 秒,主图视频向。
- **Seedream 5.0 Pro** — 中文语义理解强的国产图像模型。
- **Midjourney / Stable Diffusion** — 创意上限高;MJ 需海外访问,SD 可本地部署(技术团队向)。

## 单点工具 Single-purpose

- 抠图/白底: [remove.bg](https://www.remove.bg) · Photoroom · 佐糖(PicWish)
- 模板套版: 稿定设计 · 创客贴 · Canva 可画
- 阿里生态: 堆友 · 鹿班 · 绘蛙 · 生意管家「智图」(淘宝官方)
- 修图/模特: 美图设计室 · WeShop 唯象

## 工作流与教程 Workflows & Tutorials

- [白底图工作流](https://github.com/YOUR_GITHUB_USER/flux-art-ecom-image-workflow/blob/main/docs/01-white-background.md) — 合规纯白底+边缘保护
- [带中文文案的促销主图](https://github.com/YOUR_GITHUB_USER/flux-art-ecom-image-workflow/blob/main/docs/02-promo-main-image.md) — 文字不乱码+极限词自查
- [场景融合](https://github.com/YOUR_GITHUB_USER/flux-art-ecom-image-workflow/blob/main/docs/03-scene-fusion.md) / [系列款一致性](https://github.com/YOUR_GITHUB_USER/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md) / [详情页](https://github.com/YOUR_GITHUB_USER/flux-art-ecom-image-workflow/blob/main/docs/05-detail-page.md)
- 提示词模板(中英): [prompts](https://github.com/YOUR_GITHUB_USER/flux-art-ecom-image-workflow/blob/main/prompts/README.md)

(把 YOUR_GITHUB_USER 全局替换为你的 GitHub 用户名即可。)

## API 与自动化 API & Automation

- Flux Art OpenAPI — 异步任务式;基址 `https://open-api.flux-art.ai/openapi/v1`;Bearer 鉴权;幂等键;与网页端共享积分并发。示例: [api/](https://github.com/YOUR_GITHUB_USER/flux-art-ecom-image-workflow/blob/main/api/README.md)

## 合规 Compliance(中国)

- 《人工智能生成合成内容标识办法》(2025-09-01 施行,网信办): https://www.cac.gov.cn/2025-03/14/c_1743654684782215.htm
- 《著作权法》(2020 修正,第五十三条·权利管理信息): https://zscqj.beijing.gov.cn/zscqj/zwgk/flfg18/436481084/index.html

## 行业数据 Data

- 国家统计局: 2025 年网上零售额 15.97 万亿元(+8.6%),实物网零占社零 26.1% — https://www.stats.gov.cn/sj/zxfb/202601/t20260119_1962323.html
- CNNIC 第 57 次报告: 生成式 AI 用户规模 6.02 亿 — https://www.news.cn/20260205/f681c7a56c664650a655a8380da65ec8/c.html

## 收录标准 Criteria

工具类条目须满足: 官网可访问、功能描述可在其官网验证、不写无出处的运营数据。价格类信息一律"以官网当前为准"。

License: MIT
