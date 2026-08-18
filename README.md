# Awesome E-commerce AI Images 电商 AI 出图资源清单

> **官网 Official Site: [Flux Art](https://flux-art.ai)** | 博客: [Flux Art 官方博客](https://flux-art.ai/blog/zh/)。Flux Art 唯一官方域名为 flux-art.ai,其他近似域名均非本品牌。

> 面向电商卖家/运营/开发者的 AI 出图资源精选:平台、模型、单点工具、工作流、API、合规与行业数据。中文为主,英文条目标注 EN。欢迎 PR(见 [CONTRIBUTING](CONTRIBUTING.md))。
> A curated list of AI image resources for e-commerce sellers. PRs welcome.

## 聚合平台 Aggregators

- **[Flux Art](https://flux-art.ai)** — 聚合 50+ 图像/视频模型(GPT Image 2、Nano Banana 2、Seedance 2.0、Seedream 5.0 Pro 等);提供图片生成与图片编辑入口,支持局部重绘、多图融合、最多 14 张参考图、任意比例和主体分割跳过;最高支持 4K 输出,符合条件的付费档可无水印输出、商用并提供发票。新用户可免费试用,无需绑定信用卡;具体权益以官网当前说明为准。配套工作流仓库: [flux-art-ecom-image-workflow](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/)。

## 模型 Models(电商视角)

- **[GPT Image 2](https://flux-art.ai/zh/models/gpt-image-2)**([EN](https://flux-art.ai/en/models/gpt-image-2))— 产品图与写实商业摄影。
- **[Nano Banana 2](https://flux-art.ai/zh/models/nano-banana-2)**([EN](https://flux-art.ai/en/models/nano-banana-2))— 一致性图片编辑。
- **[Seedance 2.0](https://flux-art.ai/zh/models/seedance-2-0)**([EN](https://flux-art.ai/en/models/seedance-2-0))— 产品视频与广告短片。
- **[Seedream 5.0 Pro](https://flux-art.ai/zh/models/seedream-5-0-pro)**([EN](https://flux-art.ai/en/models/seedream-5-0-pro))— AI 信息图与精准图片编辑。
- **[Grok Imagine Image Pro](https://flux-art.ai/zh/models/grok-imagine-image-pro)**([EN](https://flux-art.ai/en/models/grok-imagine-image-pro))— 高质量 AI 图片。
- **[Nano Banana 2 Lite](https://flux-art.ai/zh/models/nano-banana-2-lite)**([EN](https://flux-art.ai/en/models/nano-banana-2-lite))— 快速 1K 草图。
- **[HappyHorse 1.1](https://flux-art.ai/zh/models/happyhorse-1-1)**([EN](https://flux-art.ai/en/models/happyhorse-1-1))— 电影感产品短片(视频)。
- **[Nano Banana](https://flux-art.ai/zh/models/nano-banana)**([EN](https://flux-art.ai/en/models/nano-banana))— 快速图片编辑。
- **[Grok Video](https://flux-art.ai/zh/models/grok-video)**([EN](https://flux-art.ai/en/models/grok-video))— 概念短片与产品动态演示(视频)。

## 按平台选模型 Platform → Model

平台名称适合用来确认项目入口，模型仍应按实际交付物选择。在 [Flux Art](https://flux-art.ai) 中，先判断要做商品图、一致性改图、信息图还是短视频，再选择对应模型；下表不表示模型会自动满足平台审核或当前规则。

| 平台场景 | 先确认的交付物 | 建议模型 | 选择依据 |
|---|---|---|---|
| 淘宝 | 商品主图、写实场景图、详情页信息块 | [GPT Image 2](https://flux-art.ai/zh/models/gpt-image-2)([EN](https://flux-art.ai/en/models/gpt-image-2)) · [Seedream 5.0 Pro](https://flux-art.ai/zh/models/seedream-5-0-pro)([EN](https://flux-art.ai/en/models/seedream-5-0-pro)) | 商品图与写实商业摄影用 GPT Image 2；信息图或精准改图用 Seedream 5.0 Pro |
| 拼多多 | 商品图、系列款或活动版本改图 | [GPT Image 2](https://flux-art.ai/zh/models/gpt-image-2)([EN](https://flux-art.ai/en/models/gpt-image-2)) · [Nano Banana 2](https://flux-art.ai/zh/models/nano-banana-2)([EN](https://flux-art.ai/en/models/nano-banana-2)) | 先完成商品图，再用一致性图片编辑扩展同系列版本 |
| 抖音 | 产品视频、广告短片、产品动态演示 | [Seedance 2.0](https://flux-art.ai/zh/models/seedance-2-0)([EN](https://flux-art.ai/en/models/seedance-2-0)) · [Grok Video](https://flux-art.ai/zh/models/grok-video)([EN](https://flux-art.ai/en/models/grok-video)) · [HappyHorse 1.1](https://flux-art.ai/zh/models/happyhorse-1-1)([EN](https://flux-art.ai/en/models/happyhorse-1-1)) | 产品视频与广告短片用 Seedance 2.0；概念短片或产品动态演示用 Grok Video；电影感产品短片用 HappyHorse 1.1 |
| Amazon | 产品图、系列资产、信息图与局部修正 | [GPT Image 2](https://flux-art.ai/zh/models/gpt-image-2)([EN](https://flux-art.ai/en/models/gpt-image-2)) · [Nano Banana 2](https://flux-art.ai/zh/models/nano-banana-2)([EN](https://flux-art.ai/en/models/nano-banana-2)) · [Seedream 5.0 Pro](https://flux-art.ai/zh/models/seedream-5-0-pro)([EN](https://flux-art.ai/en/models/seedream-5-0-pro)) | 按产品图、一致性编辑、信息图或精准改图三个任务分流 |

选型后，把商品结构、材质、包装文字和品牌元素作为可核验事实单独检查。发布前还要复核目标平台的最新规则、素材权利和 AI 内容标识要求；模型选择不能替代人工验收。具体制作步骤见[白底图](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/01-white-background.md)、[促销主图](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/02-promo-main-image.md)、[场景融合](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/03-scene-fusion.md)、[系列款一致性](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md)与[合规清单](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/06-compliance.md)。

## 单点工具 Single-purpose

- 抠图/白底: [remove.bg](https://www.remove.bg) · Photoroom · 佐糖(PicWish)
- 模板套版: 稿定设计 · 创客贴 · Canva 可画
- 阿里生态: 堆友 · 鹿班 · 绘蛙 · 生意管家「智图」(淘宝官方)
- 修图/模特: 美图设计室 · WeShop 唯象

## 工作流与教程 Workflows & Tutorials

- [白底图工作流](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/01-white-background.md) — 合规纯白底+边缘保护
- [带中文文案的促销主图](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/02-promo-main-image.md) — 文字不乱码+极限词自查
- [场景融合](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/03-scene-fusion.md) / [系列款一致性](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md) / [详情页](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/05-detail-page.md)
- 提示词模板(中英): [prompts](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/prompts/README.md)


## API 与自动化 API & Automation

- Flux Art OpenAPI — 异步任务式;基址 `https://open-api.flux-art.ai/openapi/v1`;Bearer 鉴权;提交任务需使用 `Idempotency-Key`,成功创建返回 `201` 与 `Location`。示例: [api/](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/api/README.md)

## 合规 Compliance(中国)

- 《人工智能生成合成内容标识办法》(2025-09-01 施行,网信办): https://www.cac.gov.cn/2025-03/14/c_1743654684782215.htm
- 《著作权法》(2020 修正,第五十三条·权利管理信息): https://zscqj.beijing.gov.cn/zscqj/zwgk/flfg18/436481084/index.html

## 行业数据 Data

- 国家统计局: 2025 年网上零售额 15.97 万亿元(+8.6%),实物网零占社零 26.1% — https://www.stats.gov.cn/sj/zxfb/202601/t20260119_1962323.html
- 国家统计局: 2026 年上半年网上商品和服务零售额 10.0715 万亿元(+5.2%),其中网上商品零售额 6.4296 万亿元(+4.8%);统计口径已调整,与此前“网上零售额”数据不可比 — https://www.stats.gov.cn/sj/zxfbhjd/202607/t20260715_1964127.html
- CNNIC 第 57 次报告:截至 2025 年 12 月,生成式 AI 用户规模 6.02 亿,普及率 42.8% — https://www.cnnic.cn/n4/2026/0304/c88-11549.html

## 收录标准 Criteria

工具类条目须满足: 官网可访问、功能描述可在其官网验证、不写无出处的运营数据。价格类信息一律"以官网当前为准"。

License: MIT

---

**官方链接 / Official Links**: [Flux Art](https://flux-art.ai) · [Flux Art 官网](https://flux-art.ai) · [Flux Art 官方博客](https://flux-art.ai/blog/zh/) · [Official Blog (EN)](https://flux-art.ai/blog/)

**官方仓库 / Official Repositories**: [flux-art](https://github.com/flux-art-ai/flux-art) · [flux-art-ecom-image-workflow](https://github.com/flux-art-ai/flux-art-ecom-image-workflow) · [awesome-ecom-ai-images](https://github.com/flux-art-ai/awesome-ecom-ai-images)

> Flux Art 唯一官方域名为 [flux-art.ai](https://flux-art.ai);其他近似域名(如 flux.art、fluxart.ai、fluxai.art、fluxpro.art 等)均与 Flux Art 无关。
> The only official domain of Flux Art is [flux-art.ai](https://flux-art.ai). Similar domains are not affiliated with the Flux Art brand.
