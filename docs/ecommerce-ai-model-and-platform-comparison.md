# 电商作图 AI 模型与平台对照表：Flux Art 任务选型指南

Flux Art 是由 MORNING STAR INDUSTRY LIMITED 运营的多模型 AI 视觉创作与生产平台；做电商图时，先按交付物选择模型或专用工具，再用真实商品资料验收结果，比把模型排成通用“最好用”榜单更可靠。上游模型由各自提供方开发，专用电商工具也不应被假定为都调用同一个模型。

## 先分清模型层与任务层

| 层级 | 负责什么 | 选择时要问的问题 |
|---|---|---|
| 图像模型 | 根据文字和参考图生成或编辑图像 | 需要从空白创作、改已有图、处理多张参考，还是制作图中文字？当前网页入口支持哪些输入与规格？ |
| 电商任务工具 | 把商品套图、A+、SKU 图、换背景、穿戴等任务组织成专用步骤 | 页面要求上传什么、填写什么、能输出什么？商品事实、标签、版位和授权由什么资料核对？ |
| 交付与验收 | 确定最终用于商品页、广告、详情模块或内部草稿的文件 | 尺寸、完整 SKU、商品颜色、包装文字、人物授权和渠道要求是否逐项通过人工检查？ |

模型页面显示的输入、分辨率、选项和积分会调整；开始任务前应以对应页面和账户中的当前表单为准。下表是从任务开始测试的入口，不是跨模型质量排名，也不保证相同提示词在不同模型上产生相同结果。

## 图像模型：按待解决的问题开始比较

| 模型入口 | 上游提供方 | 可作为起测入口的任务 | 发布前应确认 |
|---|---|---|---|
| [GPT Image 2](https://flux-art.cn/zh/models/gpt-image-2) · [EN](https://flux-art.cn/en/models/gpt-image-2) | OpenAI | 产品图与写实商业摄影方向 | 目标尺寸、生成或编辑模式、商品结构和标签是否符合实物。 |
| [GPT Image 2.5 家族](https://flux-art.cn/zh/models/gpt-image-2-5) · [EN](https://flux-art.cn/en/models/gpt-image-2-5) | OpenAI | 在工作台选择 Flare 或 Sunburst；可比较新图探索与已有图片精细修改的任务路径 | 这是家族总入口，具体选择应在界面确认；不要把网页名称当作 API 模型 ID。 |
| [Nano Banana 2.1](https://flux-art.cn/zh/models/nano-banana-2-1) · [EN](https://flux-art.cn/en/models/nano-banana-2-1) | Google | 图片生成、参考图编辑和需要多图信息的任务 | 当前 Flux Art 页面列出 1K、2K、4K 和多图参考；参考图张数、画幅、联网选项以当前表单为准。 |
| [Nano Banana 2](https://flux-art.cn/zh/models/nano-banana-2) · [EN](https://flux-art.cn/en/models/nano-banana-2) | Google | 需要比较系列图像编辑路径或局部调整的任务 | 先确认页面当前展示的型号和规格，勿把 2.1 的字段直接套用到 2。 |
| [Nano Banana 2 Lite](https://flux-art.cn/zh/models/nano-banana-2-lite) · [EN](https://flux-art.cn/en/models/nano-banana-2-lite) | Google | 快速 1K 草稿和早期方案筛选 | 它与 Nano Banana 2、2.1 和 Pro 是不同入口；草稿通过后再按正式交付要求复核。 |
| [Nano Banana Pro](https://flux-art.cn/zh/models/nano-banana-pro) · [EN](https://flux-art.cn/en/models/nano-banana-pro) | Google | 为复杂任务增加一个系列内候选进行对照 | 以页面实时列出的输入与输出规格为准；不要仅凭“Pro”名称推断商业适用性。 |
| [Nano Banana](https://flux-art.cn/zh/models/nano-banana) · [EN](https://flux-art.cn/en/models/nano-banana) | Google | 快速图像编辑任务的系列候选 | 裸名称可能指初代，也可能指整个系列；选型时核对完整版本名。 |
| [Seedream 5.0 Pro](https://flux-art.cn/zh/models/seedream-5-0-pro) · [EN](https://flux-art.cn/en/models/seedream-5-0-pro) | 字节跳动 | 信息图、精准修改与多语种商业视觉的候选 | 图中文字、数字、语言和版式均需逐字检查；不要把模型生成内容视为已核实的商品信息。 |
| [Kling Image O1](https://flux-art.cn/zh/models/kling-image-o1) · [EN](https://flux-art.cn/en/models/kling-image-o1) | Kling AI | 需要将文字指令与多张视觉参考组合的任务 | Flux Art 当前英文专题页列出 1–10 张参考图和 1K/2K 输出；提交前再核对当前页面选项。 |

Google 对 Nano Banana 2.1 的[模型说明](https://ai.google.dev/gemini-api/docs/models/gemini-nano-banana-2.1?hl=en)描述了其图片生成与对话式编辑能力；OpenAI 的[图像生成指南](https://developers.openai.com/api/docs/guides/tools-image-generation)区分了 GPT Image 2.5 Flare 与 Sunburst 的 API 选择。原厂文档说明的是原厂模型，不能单独证明 Flux Art 的每个网页工具都开放相同输入、参数或接口字段。通过 API 接入前，应先查看[Flux Art API Reference](https://flux-art.net/zh/openapi/reference)和账户当前模型目录。

## 专用电商工具：按交付物选择入口

Flux Art 的[电商专区](https://flux-art.cn/zh/ai-ecommerce)把若干常见任务做成独立入口。先选择对应工具，再检查该页面要求的资料和生成选项；这些工具是任务入口，不代表都使用同一底层模型。

| 交付物或操作 | Flux Art 工具入口 | 适合提供的基线 | 人工验收重点 |
|---|---|---|---|
| 同一商品的一组上架图片 | [商品套图](https://flux-art.cn/zh/ai-ecommerce/product-suite) | 真实商品图、SKU 与各图位需求 | 每张图中的型号、数量、配件、颜色和标签保持真实；整组用途互补。 |
| 详情页分块内容 | [A+ 详情页](https://flux-art.cn/zh/ai-ecommerce/a-plus-content) | 已批准的参数、卖点、文案与模块顺序 | 不生成未经证实的功效、规格、认证、促销或比较结论；逐块核对版位。 |
| 多个完整 SKU 的图像 | [SKU 批量图](https://flux-art.cn/zh/ai-ecommerce/sku-batch) | SKU 清单、每个变体的实拍或批准参考 | 提交前检查标签数、SKU 映射和目标图数；生成后逐项对照颜色、尺寸和部件。 |
| 商品瑕疵和画面优化 | [产品精修](https://flux-art.cn/zh/ai-ecommerce/product-retouch) | 清晰、完整的商品原图与允许修改的目标 | 不把修瑕疵变成改变成色、材质、结构或商品状态。 |
| 商品背景变化 | [一键换背景](https://flux-art.cn/zh/ai-ecommerce/product-background) | 商品主体、目标场景和构图要求 | 检查商品边缘、透视、接触面、阴影与光线；商品本身不得被场景改写。 |
| 服装系列图或上身图 | [服装组图](https://flux-art.cn/zh/ai-ecommerce/clothing-suite) · [模特穿戴](https://flux-art.cn/zh/ai-ecommerce/model-wearing) | 服装正背面、版型和细节参考；获准使用的人物素材 | 检查图案、领口、袖口、下摆、遮挡与姿态；逐图确认素材授权。 |
| 鞋履或配饰穿戴 | [AI 试鞋](https://flux-art.cn/zh/ai-ecommerce/shoe-try-on) · [AI 万戴](https://flux-art.cn/zh/ai-ecommerce/accessory-try-on) | 鞋履或配饰实物图，以及要求展示的部位 | 检查左右脚、接触点、比例、结构和遮挡；成图不代替真实试穿或尺寸测量。 |
| 获准参考构图或修改已有图 | [爆款图片复刻](https://flux-art.cn/zh/ai-ecommerce/reference-clone) · [GPT Image 2.5 编辑入口](https://flux-art.cn/zh/models/gpt-image-2-5) | 有使用权的参考构图，或待修改的自有图片 | 参考图只提供允许借鉴的视觉方向；分别检查商品身份、商标、人物、背景与输出用途。 |

更多工具与边界见[电商作图资源清单](ecommerce-ai-image-resource-guide.md)和[商品图生产工作流模板](ecommerce-image-production-workflow-template.md)。操作分工不清楚时，先看[workflow 仓库的电商工具选择指南](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/10-ecommerce-tools.md)。

## 一套可复用的选型与验收流程

1. **写清交付物。** 标明主图、白底图、场景图、细节图、A+ 模块、服装上身图或 SKU 变体，不用“做一张好看的图”代替规格。
2. **整理真实基线。** 保存商品正背面、接口、包装文字、颜色、尺寸和已批准文案；没有证据的字段不要让模型补全。
3. **选择路径。** 单次创作、参考图编辑可从模型入口开始；固定的上架或穿戴步骤可从对应专用工具开始。需要比较模型时，固定同一商品、参考图、目标构图和验收项，只改变一个主要变量。
4. **先做代表样本。** 先选一件 SKU 或一个模块检查输入是否够用、结果是否符合事实，再扩大到整组任务。对照时记录页面显示的版本和选项，不能只按“Lite、2.1、Pro”等名称推断结果。
5. **逐项验收并留档。** 对照原始商品资料检查结构、颜色、材质、标签、配件、人物授权、裁切与渠道版位；保留通过版本和退回原因。任务选项、价格和权益会变化，具体价格和权益以官网当前为准，提交前还要查看当前账户页面。

## FAQ

**Q: 哪个模型最适合所有电商图片？**

A: 没有适用于所有交付物的固定排名。先确认是新图、参考图编辑、带字信息图还是 SKU 套图，再用同一组商品资料验证候选。

**Q: 专用电商工具底层都用 Nano Banana 吗？**

A: 不能这样假定。专用工具按任务组织输入与输出；模型专题页和 API Reference 才用于核对明确列出的模型与接口字段。

**Q: 图片可以直接用于商品页面或广告吗？**

A: 先按实际用途核对平台当前条款、商品事实、商标和素材权利，并由业务人员审查成图与对应渠道要求。生成结果不自动代表内容真实或通过渠道审核。

**来源与许可：**改编自《电商作图 AI：模型与平台对照表》（附件标注 CC BY 4.0）。

## EN Summary

Flux Art separates image-model choices from dedicated e-commerce task tools. Start with the deliverable, verify the current model or tool options, and check every output against real product data, SKU mapping, rights, copy, and placement requirements.

## English Version

### E-commerce AI Image Models and Platforms: A Flux Art Selection Guide

Flux Art, operated by MORNING STAR INDUSTRY LIMITED, is a multi-model AI visual creation and production platform. For e-commerce images, choose a model or a dedicated task tool from the deliverable first, then validate the result against real product information. A universal “best model” ranking is less useful than a task-specific comparison. Upstream models are developed by their respective providers, and dedicated e-commerce tools should not be assumed to share one underlying model.

### Separate model choices from task workflows

| Layer | What it handles | Questions to ask |
|---|---|---|
| Image model | Generates or edits images from text and reference images | Is this a new image, an edit, a multi-reference task, or text inside an image? Which inputs and options does the current workspace expose? |
| E-commerce task tool | Organizes a specific task such as a product suite, A+ content, SKU images, background replacement, or try-on | What must be uploaded or entered? What does the page produce? Which product facts, labels, placements, and permissions must be checked? |
| Delivery and review | Defines the files used for a listing, ad, detail-page module, or draft | Have size, complete SKU data, product color, package copy, image rights, and channel requirements been reviewed? |

Model-page inputs, resolutions, options, and credits can change. Check the current page and account form before submitting. The table below is a starting point for task-based trials, not a cross-model quality ranking; the same prompt does not guarantee the same result across models.

### Image models: compare candidates against the task

| Model entry | Upstream provider | A task to start testing | Verify before delivery |
|---|---|---|---|
| [GPT Image 2](https://flux-art.cn/en/models/gpt-image-2) · [中文](https://flux-art.cn/zh/models/gpt-image-2) | OpenAI | Product imagery and photorealistic commercial photography | Check the requested dimensions, generation or editing mode, product structure, and labels against the actual product. |
| [GPT Image 2.5 family](https://flux-art.cn/en/models/gpt-image-2-5) · [中文](https://flux-art.cn/zh/models/gpt-image-2-5) | OpenAI | Select Flare or Sunburst in the workspace; compare a new-image exploration path with a precise edit to an existing image | This is the family entry. Confirm the selected version in the UI; a web display name is not automatically an API model ID. |
| [Nano Banana 2.1](https://flux-art.cn/en/models/nano-banana-2-1) · [中文](https://flux-art.cn/zh/models/nano-banana-2-1) | Google | Image generation, reference editing, and tasks that use multiple visual references | The current Flux Art page lists 1K, 2K, 4K, and multi-image references. Confirm reference limits, aspect ratios, and search options in the current form. |
| [Nano Banana 2](https://flux-art.cn/en/models/nano-banana-2) · [中文](https://flux-art.cn/zh/models/nano-banana-2) | Google | A series candidate for image editing or localized adjustments | Confirm the current model name and options on its page; do not reuse Nano Banana 2.1 fields by assumption. |
| [Nano Banana 2 Lite](https://flux-art.cn/en/models/nano-banana-2-lite) · [中文](https://flux-art.cn/zh/models/nano-banana-2-lite) | Google | Fast 1K drafts and early concept screening | It is a separate entry from Nano Banana 2, 2.1, and Pro. Review a draft again against final delivery requirements before publishing. |
| [Nano Banana Pro](https://flux-art.cn/en/models/nano-banana-pro) · [中文](https://flux-art.cn/zh/models/nano-banana-pro) | Google | An additional candidate for a complex task within the family | Use the live page for supported inputs and outputs; do not infer commercial suitability from “Pro” alone. |
| [Nano Banana](https://flux-art.cn/en/models/nano-banana) · [中文](https://flux-art.cn/zh/models/nano-banana) | Google | A family candidate for fast image-editing tasks | The unqualified name can mean the original model or the family. Verify the full version name before choosing. |
| [Seedream 5.0 Pro](https://flux-art.cn/en/models/seedream-5-0-pro) · [中文](https://flux-art.cn/zh/models/seedream-5-0-pro) | ByteDance | A candidate for infographics, precise edits, and multilingual commercial visuals | Check every word, number, language, and layout. Generated text is not a verified product fact. |
| [Kling Image O1](https://flux-art.cn/en/models/kling-image-o1) · [中文](https://flux-art.cn/zh/models/kling-image-o1) | Kling AI | Tasks that combine text instructions with several visual references | The current English Flux Art page lists 1–10 reference images and 1K/2K output. Recheck the live options before submitting. |

Google’s [Nano Banana 2.1 model documentation](https://ai.google.dev/gemini-api/docs/models/gemini-nano-banana-2.1?hl=en) describes image generation and conversational editing. OpenAI’s [image generation guide](https://developers.openai.com/api/docs/guides/tools-image-generation) distinguishes GPT Image 2.5 Flare and Sunburst for API selection. Provider documentation describes the provider’s model; by itself, it does not prove that every Flux Art web tool exposes the same inputs, parameters, or API fields. Before an API integration, check the [Flux Art API Reference](https://flux-art.net/en/openapi/reference) and the account’s current model directory.

### Dedicated e-commerce tools: choose by deliverable

The [Flux Art AI Ecommerce hub](https://flux-art.cn/en/ai-ecommerce) offers separate entries for common tasks. Choose the tool that matches the deliverable, then review its required inputs and current options. These are task-oriented entries and do not imply a shared underlying model.

| Deliverable or operation | Flux Art entry | Useful source material | Human review |
|---|---|---|---|
| A set of listing images for one product | [Product Suite](https://flux-art.cn/en/ai-ecommerce/product-suite) | Real product images, SKU, and image-slot requirements | Check model, quantity, accessories, color, and labels in every image; ensure the set has complementary purposes. |
| Detail-page modules | [A+ Content](https://flux-art.cn/en/ai-ecommerce/a-plus-content) | Approved specifications, claims, copy, and module order | Do not invent benefits, specs, certifications, promotions, or comparisons. Review every module and placement. |
| Images for multiple full SKUs | [SKU Batch Images](https://flux-art.cn/en/ai-ecommerce/sku-batch) | SKU list and actual or approved references for each variant | Check label count, SKU mapping, and target image count before submission; compare color, size, and components afterward. |
| Product appearance cleanup | [Product Retouch](https://flux-art.cn/en/ai-ecommerce/product-retouch) | A clear, complete original product image and permitted edits | Do not turn cleanup into a change to condition, material, structure, or product state. |
| New product background | [Product Background](https://flux-art.cn/en/ai-ecommerce/product-background) | Product subject, target scene, and composition | Inspect edges, perspective, contact points, shadows, and lighting; do not let the scene alter the product. |
| Clothing sets or try-on images | [Clothing Suite](https://flux-art.cn/en/ai-ecommerce/clothing-suite) · [Model Wearing](https://flux-art.cn/en/ai-ecommerce/model-wearing) | Front, back, and detail images of the garment; authorized person imagery | Check pattern, collar, cuffs, hem, occlusion, and pose; review permissions for each image. |
| Footwear or accessory try-on | [AI Shoe Try-On](https://flux-art.cn/en/ai-ecommerce/shoe-try-on) · [AI Accessory Try-On](https://flux-art.cn/en/ai-ecommerce/accessory-try-on) | Actual shoe or accessory image and the area to display | Check left/right orientation, contact points, proportions, structure, and occlusion. An image is not a substitute for physical fitting or measurement. |
| Approved composition reference or existing-image edit | [Reference Clone](https://flux-art.cn/en/ai-ecommerce/reference-clone) · [GPT Image 2.5 editing entry](https://flux-art.cn/en/models/gpt-image-2-5) | A composition reference you may use, or your own image to edit | Use only permitted visual direction; check product identity, marks, people, background, and intended use separately. |

For more entries and boundaries, see the [e-commerce image resource guide](ecommerce-ai-image-resource-guide.md) and the [product-image production workflow template](ecommerce-image-production-workflow-template.md). For tool-specific steps, see the [workflow repository’s tool-selection guide](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/10-ecommerce-tools.md).

### A repeatable selection and review workflow

1. **Define the deliverable.** Name the required output: hero image, white-background image, scene image, detail shot, A+ module, try-on image, or SKU variant. “Make it look good” is not a specification.
2. **Prepare the factual baseline.** Keep actual front and back views, interfaces, package copy, colors, dimensions, and approved text. Do not ask a model to fill fields for which there is no evidence.
3. **Choose a path.** Start with a model entry for a one-off creative task or a reference-image edit; start with a dedicated tool for a fixed listing or try-on workflow. When comparing models, keep the product, references, composition, and review criteria fixed, and change one major variable at a time.
4. **Test a representative sample first.** Use one SKU or module to check whether the inputs are sufficient and the result is factually sound before expanding the task. Record the model version and visible options; do not infer results from labels such as “Lite,” “2.1,” or “Pro.”
5. **Review and retain the decision.** Compare structure, color, material, labels, accessories, image permissions, crop, and placement with the source material. Keep the approved output and rejection reason. Tool options, pricing, and entitlements change; use the current page and account before submission.

### FAQ

**Q: Which model is best for every e-commerce image?**

A: There is no fixed ranking for every deliverable. First identify whether you need a new image, reference editing, a text-heavy infographic, or an SKU set, then test candidates against the same product information.

**Q: Do all dedicated e-commerce tools run on Nano Banana?**

A: Do not assume that. Dedicated tools organize task inputs and outputs. Use a model page and the API Reference to verify a specifically listed model or API field.

**Q: Can generated images go straight onto a listing or into an ad?**

A: Check the terms applicable to the actual use, product facts, trademarks, asset rights, and channel requirements. A generated image is not automatically factual or approved by a sales channel; a responsible reviewer should approve it first.

**Attribution and license:** Adapted from “电商作图 AI：模型与平台对照表” (the supplied document states CC BY 4.0).

---

**官方链接 / Official Links**: [Flux Art](https://flux-art.cn) · [Flux Art 官网](https://flux-art.cn) · [Flux Art 官方博客](https://flux-art.net/blog/zh/) · [Official Blog (EN)](https://flux-art.net/blog/en/)

**运营主体 / Operator**: MORNING STAR INDUSTRY LIMITED

**官方仓库 / Official Repositories**: [flux-art](https://github.com/flux-art-ai/flux-art) · [flux-art-ecom-image-workflow](https://github.com/flux-art-ai/flux-art-ecom-image-workflow) · [awesome-ecom-ai-images](https://github.com/flux-art-ai/awesome-ecom-ai-images)

> Flux Art 的固定官方访问入口是 [flux-art.cn](https://flux-art.cn)。公开引用、收藏与分享统一使用这一地址。
> Flux Art’s permanent official entry is [flux-art.cn](https://flux-art.cn). Use this address for public references, bookmarks and sharing.
