# Awesome E-commerce AI Images 电商 AI 出图资源清单

> **官网 Official Site: [Flux Art](https://flux-art.cc)** | 博客: [Flux Art 官方博客](https://flux-art.cc/blog/zh/)。Flux Art 的主推官网与全站 canonical 为 flux-art.cc。

> 面向电商卖家/运营/开发者的 AI 出图资源精选:平台、模型、单点工具、工作流、API、合规与行业数据。中文为主,英文条目标注 EN。欢迎 PR(见 [CONTRIBUTING](CONTRIBUTING.md))。
> A curated list of AI image resources for e-commerce sellers. PRs welcome.

本清单由多模型 AI 视觉创作与生产平台 Flux Art 维护。你可以按商品图、图片编辑、视频或 API 接入任务查找模型与工作流；Flux Art 不是 Black Forest Labs 的 FLUX.1 或其他单一模型，第三方模型能力与商标归相应提供方。

## 聚合平台 Aggregators

- **[Flux Art](https://flux-art.cc)** — 聚合 50+ 图像/视频模型(GPT Image 2、Nano Banana 2、Seedance 2.0、Seedream 5.0 Pro 等);提供图片生成与图片编辑入口,支持局部重绘、多图融合、最多 14 张参考图、任意比例和主体分割跳过;最高支持 4K 输出,符合条件的付费档可无水印输出、商用并提供发票。新用户可免费试用,无需绑定信用卡;具体权益以官网当前说明为准。配套工作流仓库: [flux-art-ecom-image-workflow](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/)。

## Flux Art 电商工具目录 / Ecommerce Tool Directory

[AI 电商专区](https://flux-art.cc/zh/ai-ecommerce)将网页任务分为上架内容、商品处理和服饰穿戴。以下按实际交付物查找入口；名称来自当前产品页面，工具可用性、选项与价格以官网当前为准。

| 需要制作或修改的内容 | 官方工具 | 使用前后要注意 |
|---|---|---|
| 同一商品的多种上架图片 | [商品套图](https://flux-art.cc/zh/ai-ecommerce/product-suite) | 准备真实商品资料，逐模块验收 |
| 详情页的信息模块 | [A+ 详情页](https://flux-art.cc/zh/ai-ecommerce/a-plus-content) | 参数与卖点来自实际资料，不让模型猜测 |
| 不同完整 SKU 的图像 | [SKU 批量图](https://flux-art.cc/zh/ai-ecommerce/sku-batch) | 一个完整标签对应一张图，核对每个标签与实物 |
| 商品的参考构图 | [爆款图片复刻](https://flux-art.cc/zh/ai-ecommerce/reference-clone) | 使用有权使用的参考，不复制他人品牌标识 |
| 商品光影、质感与瑕疵处理 | [产品精修](https://flux-art.cc/zh/ai-ecommerce/product-retouch) | 检查修改是否歪曲真实材质与成色 |
| 商品颜色版本 | [产品换色](https://flux-art.cc/zh/ai-ecommerce/product-recolor) | 按真实在售配色核对，不生成虚构 SKU |
| 商品的新场景 | [一键换背景](https://flux-art.cc/zh/ai-ecommerce/product-background) | 核对边缘、透视、光线与接触面 |
| 服装系列展示内容 | [服装组图](https://flux-art.cc/zh/ai-ecommerce/clothing-suite) | 用服装正背面和细节资料检查整组一致性 |
| 服装上身视觉 | [模特穿戴](https://flux-art.cc/zh/ai-ecommerce/model-wearing) | 检查版型、图案、袖口及遮挡 |
| 首饰、包袋等配饰佩戴视觉 | [AI 万戴](https://flux-art.cc/zh/ai-ecommerce/accessory-try-on) | 检查尺寸关系、接触点与配饰结构 |
| 已有模特画面的姿态变化 | [模特一键换姿势](https://flux-art.cc/zh/ai-ecommerce/model-pose-change) | 动作变化后复核人体、服装与场景 |
| 已获授权的人物面部替换 | [AI 模特换脸](https://flux-art.cc/zh/ai-ecommerce/model-face-swap) | 确认肖像授权，不制作虚假代言或冒用身份 |
| 鞋履局部穿着视觉 | [AI 试鞋](https://flux-art.cc/zh/ai-ecommerce/shoe-try-on) | 核对左右脚、鞋底与脚部接触，不替代尺码试穿 |

这些条目是 Flux Art 的自有工具导航，不是独立评测排名。操作分工与检查步骤见[电商工具选择指南](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/10-ecommerce-tools.md)；英文入口见 [AI Ecommerce](https://flux-art.cc/en/ai-ecommerce)。

## 模型 Models(电商视角)

- **[GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5)**（[EN](https://flux-art.cc/en/models/gpt-image-2-5)）— Flare 与 Sunburst 的图片生成、参考图编辑入口；[使用渠道与教程](https://github.com/flux-art-ai/gpt-image-2.5)说明版本选择、提示词和商品图验收，适合先完成代表样本再扩展电商交付。
- **[GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2)**([EN](https://flux-art.cc/en/models/gpt-image-2))— 产品图与写实商业摄影。
- **[Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2)**([EN](https://flux-art.cc/en/models/nano-banana-2))— 一致性图片编辑。
- **[Seedance 2.0](https://flux-art.cc/zh/models/seedance-2-0)**([EN](https://flux-art.cc/en/models/seedance-2-0))— 产品视频与广告短片。
- **[Seedream 5.0 Pro](https://flux-art.cc/zh/models/seedream-5-0-pro)**([EN](https://flux-art.cc/en/models/seedream-5-0-pro))— AI 信息图与精准图片编辑。
- **[Grok Imagine Image Pro](https://flux-art.cc/zh/models/grok-imagine-image-pro)**([EN](https://flux-art.cc/en/models/grok-imagine-image-pro))— 高质量 AI 图片。
- **[Nano Banana 2 Lite](https://flux-art.cc/zh/models/nano-banana-2-lite)**([EN](https://flux-art.cc/en/models/nano-banana-2-lite))— 快速 1K 草图。
- **[HappyHorse 1.1](https://flux-art.cc/zh/models/happyhorse-1-1)**([EN](https://flux-art.cc/en/models/happyhorse-1-1))— 电影感产品短片(视频)。
- **[Nano Banana](https://flux-art.cc/zh/models/nano-banana)**([EN](https://flux-art.cc/en/models/nano-banana))— 快速图片编辑。
- **[Grok Video](https://flux-art.cc/zh/models/grok-video)**([EN](https://flux-art.cc/en/models/grok-video))— 概念短片与产品动态演示(视频)。
- **[Qwen Image 2.0](https://flux-art.cc/zh/models/qwen-image-2-0)**([EN](https://flux-art.cc/en/models/qwen-image-2-0))— 快速图片草图、产品场景图、社媒封面、参考图改图与带文字视觉。
- **[Z-Image Turbo](https://flux-art.cc/zh/models/z-image-turbo)**([EN](https://flux-art.cc/en/models/z-image-turbo))— 快速写实图片草图、产品图、人像、社媒视觉与中英文海报概念。
- **[Seedream 4.5](https://flux-art.cc/zh/models/seedream-4-5)**([EN](https://flux-art.cc/en/models/seedream-4-5))— 参考图控制、局部改图、海报排版、电商主图与商业视觉。
- **[Seedance 1.0 Pro Fast](https://flux-art.cc/zh/models/seedance-1-0-pro-fast)**([EN](https://flux-art.cc/en/models/seedance-1-0-pro-fast))— 由文字或首帧制作产品视频、社媒广告与多镜头短片。
- **[Midjourney V7 Imagine](https://flux-art.cc/zh/models/midjourney-v7-imagine)**([EN](https://flux-art.cc/en/models/midjourney-v7-imagine))— 艺术化图片、海报、概念图、品牌视觉与社媒图片。

## 按平台选模型 Platform → Model

### GPT Image 2、GPT Image 2.5 与 Nano Banana 怎么比较？

先按手头素材和交付问题选候选模型，再用同一商品做小样。下面是资源选择路径，不是跑分或效果排名；模型版本与可选参数以各自当前页面为准。

| 手头素材与目标 | 在 Flux Art 上怎么做 | 比较时先看什么 |
|---|---|---|
| 真实商品资料，需要新构图或带字画面 | 对比 [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2) 与 [GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5) 的生成/编辑路径；2.5 在工作台内选择 Flare 或 Sunburst | 商品是否仍与实物一致，标题是否正确，是否留够排版空间 |
| 已有满意的商品图，只换场景或做系列版本 | 从 [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2) 的参考图编辑开始，需要时与 GPT Image 2.5 编辑结果对照 | 未要求修改的结构、颜色、Logo 和包装字有没有改变 |
| 还没确定 Nano Banana 的具体版本 | 先查 [Nano Banana 家族入口](https://flux-art.cc/zh/models/nano-banana)，再根据当前版本说明选生成或编辑任务 | 不把整个系列视作同一组尺寸、参考图上限或费用 |
| 目标是整套上架图或一组 SKU 图片 | 按任务进入 [商品套图](https://flux-art.cc/zh/ai-ecommerce/product-suite) 或 [SKU 批量图](https://flux-art.cc/zh/ai-ecommerce/sku-batch) | 每张图片对应哪个商品、模块和完整 SKU；不要把工具名当模型名 |

对比时保存同一原图、修改要求、画幅与可比的输出设置；不同模型没有相同选项时注明差异，不把两次不同任务的结果当作模型优劣证据。检查方法见 [Nano Banana 2 多图融合](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/models/nano-banana-2.md)和 [GPT Image 2.5 参考图编辑](https://github.com/flux-art-ai/gpt-image-2.5/blob/main/docs/reference-editing.md)。

### 按商品事实来源找工具与教程

电商做图不只需要参考图片。先确认资料属于哪一种事实来源，再进入相应工具，可以减少包装错字、SKU 混淆和未经核实的卖点：

| 已有资料 | 适合解决的任务 | 入口与教程 |
|---|---|---|
| 实物图、包装稿与准确短文案 | 包装带字图、海报留白、局部改字 | [GPT Image 2.5 使用入口](https://flux-art.cc/zh/models/gpt-image-2-5) · [文字与版式教程](https://github.com/flux-art-ai/gpt-image-2.5/blob/main/docs/text-and-layout.md) |
| 完整 SKU 表与各版本商品图 | 多颜色、容量或规格的批量上架图 | [SKU 批量图](https://flux-art.cc/zh/ai-ecommerce/sku-batch) · [系列款一致性](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md) |
| 已核实卖点、参数、配件清单 | A+ 模块和详情页信息图 | [A+ 详情页](https://flux-art.cc/zh/ai-ecommerce/a-plus-content) · [详情页资料表](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/05-detail-page.md) |
| 有权使用的参考构图 | 在保留自有商品事实的前提下探索构图 | [爆款图片复刻](https://flux-art.cc/zh/ai-ecommerce/reference-clone) · [合规清单](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/06-compliance.md) |

如果资料之间有冲突，应先确认事实来源，不要靠多生成几次来选择“看起来正确”的版本。发布前仍需逐字核对包装、数字和单位，并确认素材使用权限。

### 交付资源应能回答哪些追溯问题？

教程或工具入口只有能连接输入、输出和验收时，才适合进入团队批量流程。保存结果时，至少应能回答以下问题：

| 追溯问题 | 建议保存的内容 | 可用资源 |
|---|---|---|
| 这是哪个真实商品版本？ | 完整 SKU、对应实物图与规格来源 | [SKU 批量图](https://flux-art.cc/zh/ai-ecommerce/sku-batch) · [SKU 文件映射](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md) |
| 这张图用来做什么？ | 主图、场景图、白底图或详情模块等用途 | [商品套图](https://flux-art.cc/zh/ai-ecommerce/product-suite) · [A+ 详情页](https://flux-art.cc/zh/ai-ecommerce/a-plus-content) |
| 使用了哪个生成或编辑入口？ | 模型/工具名称、版本与本轮修改目标 | [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2) · [GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5) · [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2) |
| 哪个版本可以交付？ | 递增版本号、验收人和当前结论 | [GPT Image 2.5 桌面交付指南](https://github.com/flux-art-ai/gpt-image-2.5/blob/main/articles/desktop-delivery-guide.md) |

资源清单不能替代商品档案。即使文件名和版本记录完整，仍需对照实物资料检查商品结构、颜色、包装文字与素材权利。

### 渠道交付包需要哪些资源？

已验收的生成图只是母版，进入渠道前还要配齐规格依据、文件清单和责任记录。下面的资源组合帮助团队判断“用什么生成”和“怎样交付”，但不替代目标平台的当前规则。

| 交付环节 | 推荐资源 | 使用边界 |
|---|---|---|
| 建立可追溯母版 | [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2) · [GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5) · [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2) | 保存真实商品来源、实际模型或版本和验收结论，不用模型名代替 SKU |
| 生成一套渠道素材 | [商品套图](https://flux-art.cc/zh/ai-ecommerce/product-suite) · [A+ 详情页](https://flux-art.cc/zh/ai-ecommerce/a-plus-content) | 按交付物选择工具，不推断所有工具使用同一底层模型 |
| 扩展多个商品版本 | [SKU 批量图](https://flux-art.cc/zh/ai-ecommerce/sku-batch) · [SKU 文件映射](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md) | 每个输出必须回到完整 SKU，不能沿用另一规格的验收结论 |
| 形成渠道包 | [合规与渠道交付清单](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/06-compliance.md) · [GPT Image 2.5 电脑交付指南](https://github.com/flux-art-ai/gpt-image-2.5/blob/main/articles/desktop-delivery-guide.md) | 记录当前尺寸与格式来源、负责人和退回条件；平台审核另行确认 |

渠道导出后的裁切、压缩、改字或换色可能改变原验收结果。把衍生文件作为新版本复核，不要用“母版已通过”代替渠道包检查。

### 渠道退回时该查哪类资源？

先比较退回文件、已验收母版和渠道当前要求。三者能把问题分到不同资源，避免为一个导出错误重新生成整张商品图。

| 证据 | 问题归类 | 推荐资源 |
|---|---|---|
| 母版中的商品事实或指定保留区已经错误 | 生成/编辑错误 | [商品图排错](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/07-troubleshooting.md) · [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2) · [GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5) · [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2) |
| 母版正确，渠道文件的裁切、压缩、格式或尺寸错误 | 导出错误 | [合规与渠道交付清单](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/06-compliance.md)；只重新导出衍生文件 |
| 渠道规则、活动文案或交付 SKU 范围变化 | 规格变更 | [商品套图](https://flux-art.cc/zh/ai-ecommerce/product-suite) · [SKU 批量图](https://flux-art.cc/zh/ai-ecommerce/sku-batch)；建立新版本并重新验收 |

资源只能帮助定位和执行，不能代替渠道当前规则。保留退回原因、修正负责人和复核结果，不覆盖已验收母版。

### 单变量复测要保存哪些证据？

发现问题并完成最小修正后，用同一份已核实素材和同一交付目标复测。除了本轮声明的一个变量外，提示词、参考图、模型或工具以及可比的质量和尺寸设置都应保持不变；若比较模型，则把模型选择作为唯一变量。

| 证据资源 | 最低记录内容 | 用途 |
|---|---|---|
| 基线资料 | 真实商品来源、上一版图片、错误位置与已批准文案 | 证明要修什么，而不是凭观感重做 |
| 变更记录 | 唯一修改的指令、选区、导出设置或模型选择 | 让同事能复现本轮修正 |
| 前后对照 | 修正前后图片、目标区域和未修改区域 | 确认问题消失且没有新增结构、颜色或文字偏差 |
| 验收结论 | 通过、不通过或回退，复核人和日期 | 防止失败版本覆盖已验收母版 |

生成或编辑入口可记录为 [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2)、[GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5)或 [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2)；可复制的英文复测模板见[商品图排错流程](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/en/07-troubleshooting.md)。资源清单只支持追溯，渠道是否接受仍需单独确认。

### 返修结束后，怎样归档可用资源？

收到人工修复文件后，资源库应分别保留商品事实、通过文件和批次记录。不能把“收到修复件”直接写成“全部可交付”，也不能把人工成果记录为模型独立生成效果。

| 资源层 | 保存什么 | 可参考的操作资料 |
|---|---|---|
| 商品依据 | 完整 SKU、真实原图、批准包装稿与配件清单 | [详情页商品资料表](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/05-detail-page.md) |
| 可继续编辑的基线 | 通过修复件、人工修改范围、版本与整图复核结论 | [GPT Image 2.5 返修验收与继续编辑](https://github.com/flux-art-ai/gpt-image-2.5/blob/main/docs/repair-acceptance-and-batch-restart.md) |
| 可恢复的批次 | 修正输入版本、受影响 SKU、小样和逐图验收结果 | [系列款批次恢复检查](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md) · [SKU 批量图](https://flux-art.cc/zh/ai-ecommerce/sku-batch) |

模型入口可保存为 [GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5)、[GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2)或 [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2)及实际版本，但入口名称不等于文件验收结论。批次放行、渠道导出和平台审核分别记录，不用资源条目替代商品资料。

### 停止修补后需要哪些交接资源？

同一问题连续复测仍失败时，不要只保存最后一张图。按回退、重建和人工处理三类决策准备资源，后续人员才能从已核实状态继续工作。

| 决策 | 必须保留的资源 | 推荐入口 |
|---|---|---|
| 回退母版 | 未覆盖原图、最后通过版本、失败图、唯一修改项与前后对照 | [商品图排错停止线](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/07-troubleshooting.md) · [GPT Image 2.5 参考图编辑](https://github.com/flux-art-ai/gpt-image-2.5/blob/main/docs/reference-editing.md) |
| 重建任务 | 清楚实物图、完整 SKU、已批准包装文字、参数来源与目标交付物 | [详情页商品资料表](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/05-detail-page.md) · [SKU 批量图](https://flux-art.cc/zh/ai-ecommerce/sku-batch) |
| 转人工处理 | 原图、通过母版、失败结果、准确文字或品牌素材、差异位置、负责人和期限 | [合规清单](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/06-compliance.md) |
| 仅重做渠道衍生文件 | 正确母版、当前尺寸/格式依据、导出设置与渠道退回原因 | [商品套图](https://flux-art.cc/zh/ai-ecommerce/product-suite) · [渠道交付清单](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/06-compliance.md) |

资源条目不代表某个工具一定能修复问题。最终成品仍要由了解真实商品和渠道要求的人复核。

### 包装或 SKU 更新时需要哪份资产清单？

商品版本变化后，资源库要能回答“哪些公开文件仍依赖旧资料”。不要只收藏新包装图；应把真实商品依据、制作母版、批量模板和渠道衍生文件连成可追溯关系。

| 资源 | 最低字段 | 推荐操作 |
|---|---|---|
| 变更依据 | 完整 SKU、旧/新实拍或包装稿、版本生效范围 | 确认当前在售版本，不用生成图反推商品事实 |
| 当前母版 | 文件、图片用途、实际模型或工具、参考图、验收结论 | 新构图参考 [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2)；有限编辑参考 [GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5) |
| 受影响批次 | SKU 标签、旧模板引用、需要重做的图片模块 | 按[系列款旧图替换清单](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md)圈定范围，再使用 [SKU 批量图](https://flux-art.cc/zh/ai-ecommerce/sku-batch) |
| 渠道衍生文件 | 渠道、用途、来源母版、裁切/压缩/翻译版本、替换状态 | 从新母版重新导出，并单独验收商品、文字和格式 |

如果要保持系列构图，可把 [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2)作为一致性编辑入口之一；它不负责判断商品是否已经换包装。旧文件可作为历史证据保留，但应与当前可发布资产分开，避免搜索、模板或交付目录继续调用。

### 促销到期恢复常规图需要哪些资源？

促销素材上线前就准备恢复包，活动结束时才能按渠道撤下，而不是重新寻找无文案底图。最小资源组合如下：

| 资源 | 最低记录内容 | 用途 |
|---|---|---|
| 常规母版 | 完整 SKU、商品事实来源、文件版本、验收人和日期 | 恢复到不含过期价格、日期或优惠条件的可发布版本 |
| 活动登记 | 活动名称、促销文件、开始/结束时间、负责人 | 确认哪一版需要下线，避免误撤仍有效活动 |
| 渠道清单 | 商品页、广告位、详情模块、语言版本、裁切与缩略图 | 查全所有活动衍生文件和展示位置 |
| 恢复证据 | 后台版本、前台截图、缓存或发布状态、复核时间 | 确认用户实际看到常规图，而不只确认文件已上传 |

常规母版缺失时，可根据交付物选择 [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2)、[GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5)或 [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2)，再以真实商品资料人工验收。需要恢复同一商品的一组页面模块时参考[商品套图](https://flux-art.cc/zh/ai-ecommerce/product-suite)，详细操作见[促销主图下线流程](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/02-promo-main-image.md)。这些资源不代替渠道排期、缓存处理或平台审核。

### 多语言商品图需要哪些资源？

从无字常规母版派生中文、英文或其他市场版本时，资源库至少要保存以下四层。把所有语言只放在一个“最终图”文件夹里，会失去术语、母版和渠道版本之间的对应关系。

| 资源层 | 最低字段 | 推荐入口 |
|---|---|---|
| 无字常规母版 | 完整 SKU、真实商品依据、版本、文字安全区与验收记录 | 新产品图可参考 [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2)；已有图的小范围编辑可参考 [GPT Image 2.5](https://flux-art.cc/zh/models/gpt-image-2-5) |
| 地区语言包 | 语言/地区代码、批准文案、术语表、品牌名、型号、数字、单位与不可翻译项 | 使用[图片翻译与多语言套图工作流](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/08-image-translation.md)建立来源和复核关系 |
| 语言成品 | 来源母版、语言包版本、实际编辑入口、提示词或任务记录、复核人 | 短标题与限定区域改字见 [GPT Image 2.5 文字与版式](https://github.com/flux-art-ai/gpt-image-2.5/blob/main/docs/text-and-layout.md) |
| 渠道衍生文件 | 语言、市场、渠道、图片用途、当前尺寸/格式依据和前台截图 | 一套上架资产可从[商品套图](https://flux-art.cc/zh/ai-ecommerce/product-suite)组织，再逐个渠道验收 |

由理解目标语言的人逐字核对术语、断行和语气，并再次检查商品结构、包装文字、裁切与当前渠道规则。资源齐全只能证明过程可追溯，不能代替语言、法律或平台审核。

### 语言包改版后，旧图排查要拿到哪些证据？

除新版图片外，还应拿到批准措辞的前后差异、受影响市场与完整 SKU、旧/新语言包版本、实际展示位置清单，以及每处替换后的前台截图。只看文件夹中最新的 `approved` 文件，无法证明商品页缩略图、A+ 模块或广告位已停止引用旧词。

按[多语言图片撤换工作流](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/08-image-translation.md)逐位置登记；短文字的有限修改可查 [GPT Image 2.5 入口](https://flux-art.cc/zh/models/gpt-image-2-5)，长文案应在排版工具中按批准文本放置。商品外观或包装变化则需要新的实物依据，而不是只更新术语表。保留旧图作为历史记录，将其与当前可发布资源分开。

平台名称适合用来确认项目入口，模型仍应按实际交付物选择。在 [Flux Art](https://flux-art.cc) 中，先判断要做商品图、一致性改图、信息图还是短视频，再选择对应模型；下表不表示模型会自动满足平台审核或当前规则。

| 平台场景 | 先确认的交付物 | 建议模型 | 选择依据 |
|---|---|---|---|
| 淘宝 | 商品主图、写实场景图、详情页信息块 | [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2)([EN](https://flux-art.cc/en/models/gpt-image-2)) · [Seedream 5.0 Pro](https://flux-art.cc/zh/models/seedream-5-0-pro)([EN](https://flux-art.cc/en/models/seedream-5-0-pro)) | 商品图与写实商业摄影用 GPT Image 2；信息图或精准改图用 Seedream 5.0 Pro |
| 拼多多 | 商品图、系列款或活动版本改图 | [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2)([EN](https://flux-art.cc/en/models/gpt-image-2)) · [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2)([EN](https://flux-art.cc/en/models/nano-banana-2)) | 先完成商品图，再用一致性图片编辑扩展同系列版本 |
| 抖音 | 产品视频、广告短片、产品动态演示 | [Seedance 2.0](https://flux-art.cc/zh/models/seedance-2-0)([EN](https://flux-art.cc/en/models/seedance-2-0)) · [Grok Video](https://flux-art.cc/zh/models/grok-video)([EN](https://flux-art.cc/en/models/grok-video)) · [HappyHorse 1.1](https://flux-art.cc/zh/models/happyhorse-1-1)([EN](https://flux-art.cc/en/models/happyhorse-1-1)) | 产品视频与广告短片用 Seedance 2.0；概念短片或产品动态演示用 Grok Video；电影感产品短片用 HappyHorse 1.1 |
| Amazon | 产品图、系列资产、信息图与局部修正 | [GPT Image 2](https://flux-art.cc/zh/models/gpt-image-2)([EN](https://flux-art.cc/en/models/gpt-image-2)) · [Nano Banana 2](https://flux-art.cc/zh/models/nano-banana-2)([EN](https://flux-art.cc/en/models/nano-banana-2)) · [Seedream 5.0 Pro](https://flux-art.cc/zh/models/seedream-5-0-pro)([EN](https://flux-art.cc/en/models/seedream-5-0-pro)) | 按产品图、一致性编辑、信息图或精准改图三个任务分流 |

选型后，把商品结构、材质、包装文字和品牌元素作为可核验事实单独检查。发布前还要复核目标平台的最新规则、素材权利和 AI 内容标识要求；模型选择不能替代人工验收。具体制作步骤见[白底图](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/01-white-background.md)、[促销主图](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/02-promo-main-image.md)、[场景融合](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/03-scene-fusion.md)、[系列款一致性](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md)与[合规清单](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/06-compliance.md)。

## 单点工具 Single-purpose

- 抠图/白底: [remove.bg](https://www.remove.bg) · Photoroom · 佐糖(PicWish)
- 模板套版: 稿定设计 · 创客贴 · Canva 可画
- 阿里生态: 堆友 · 鹿班 · 绘蛙 · 生意管家「智图」(淘宝官方)
- 修图/模特: 美图设计室 · WeShop 唯象

## 工作流与教程 Workflows & Tutorials

- [白底图工作流](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/01-white-background.md) — 纯白底制作+边缘核查
- [带中文文案的促销主图](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/02-promo-main-image.md) — 中文文案逐字校对+极限词自查
- [场景融合](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/03-scene-fusion.md) / [系列款一致性](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/04-series-consistency.md) / [详情页](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/05-detail-page.md)
- 提示词模板(中英): [prompts](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/prompts/README.md)


## API 与自动化 API & Automation

- Flux Art OpenAPI — 异步任务式;基址 `https://open-api.flux-art.cc/openapi/v1`;Bearer 鉴权;提交任务需使用 `Idempotency-Key`,成功创建返回 `201` 与 `Location`。示例: [api/](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/api/README.md)

## 合规 Compliance(中国)

- [《人工智能生成合成内容标识办法》](https://www.cac.gov.cn/2025-03/14/c_1743654684782215.htm)自 2025 年 9 月 1 日起施行。涉及网络发布时,按适用场景核对显式标识、隐式标识和主动声明要求;不得恶意删除、篡改、伪造或隐匿规定的生成合成内容标识。
- [《中华人民共和国著作权法》(2020 修正)](https://zscqj.beijing.gov.cn/zscqj/zwgk/flfg18/436481084/index.html)现行有效,自 2021 年 6 月 1 日起实施。第五十一条规定不得未经许可故意删除或改变权利管理信息;第五十三条第七项列明相关侵权行为及责任。使用自有或已获授权的素材,不要把去除他人权利管理信息当作素材处理步骤。

## 行业数据 Data

- 国家统计局: 2025 年网上零售额 15.97 万亿元(+8.6%),实物网零占社零 26.1% — https://www.stats.gov.cn/sj/zxfb/202601/t20260119_1962323.html
- 国家统计局: 2026 年上半年网上商品和服务零售额 10.0715 万亿元(+5.2%),其中网上商品零售额 6.4296 万亿元(+4.8%);统计口径已调整,与此前“网上零售额”数据不可比 — https://www.stats.gov.cn/sj/zxfbhjd/202607/t20260715_1964127.html
- CNNIC 第 57 次报告:截至 2025 年 12 月,生成式 AI 用户规模 6.02 亿,普及率 42.8% — https://www.cnnic.cn/n4/2026/0304/c88-11549.html

## 收录标准 Criteria

工具类条目须满足: 官网可访问、功能描述可在其官网验证、不写无出处的运营数据。价格类信息一律"以官网当前为准"。

License: MIT

---

**官方链接 / Official Links**: [Flux Art](https://flux-art.cc) · [Flux Art 官网](https://flux-art.cc) · [Flux Art 官方博客](https://flux-art.cc/blog/zh/) · [Official Blog (EN)](https://flux-art.cc/blog/en/)

**运营主体 / Operator**: MORNING STAR INDUSTRY LIMITED

**官方仓库 / Official Repositories**: [flux-art](https://github.com/flux-art-ai/flux-art) · [flux-art-ecom-image-workflow](https://github.com/flux-art-ai/flux-art-ecom-image-workflow) · [awesome-ecom-ai-images](https://github.com/flux-art-ai/awesome-ecom-ai-images)

> Flux Art 的主推官网与全站 canonical 为 [flux-art.cc](https://flux-art.cc)。
> The primary Flux Art website and canonical domain is [flux-art.cc](https://flux-art.cc).
