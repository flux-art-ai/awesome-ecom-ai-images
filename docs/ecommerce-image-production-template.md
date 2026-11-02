# 电商作图 AI 资源清单与生产工作流模板：Flux Art 商品图从选型到交付

Flux Art 的电商作图入口适合按交付物选择：先区分平台工作流、单个图像模型和解决具体问题的垂直工具，再用代表性 SKU 定样、逐项验收后扩展生产；下面的资源目录与记录模板可帮助团队把商品图从素材准备衔接到上架归档。

## 先分清三类资源

| 资源层 | 适合解决的问题 | 入口与使用边界 |
|---|---|---|
| 平台与工作流 | 需要把商品资料、多个图位、编辑和交付检查放进一条流程 | [Flux Art AI 电商专区](https://flux-art.cn/zh/ai-ecommerce)列出不同商品任务入口。工具页面的选择项和可用状态以当前页面为准；不能据此推断每个工具固定调用同一模型。 |
| 图像模型 | 需要直接生成图片或基于参考图编辑，并自行组织提示词与验收 | [Nano Banana 2.1 中文页](https://flux-art.cn/zh/models/nano-banana-2-1) · [English](https://flux-art.cn/en/models/nano-banana-2-1)展示生成与编辑入口；[GPT Image 2.5 中文家族页](https://flux-art.cn/zh/models/gpt-image-2-5) · [English](https://flux-art.cn/en/models/gpt-image-2-5)可在页面中选择 Flare 或 Sunburst。具体选项、费用和账户可用性以提交前页面为准。 |
| 垂直电商工具 | 任务已经明确，例如制作同款套图、批量 SKU 图片、A+ 模块、白底图或商品精修 | 从[电商工具目录](https://flux-art.cn/zh/ai-ecommerce)进入对应工具。先确认输入素材、目标图位和页面实际提供的选项，再逐图核对结果。 |

资源不能混为一张模型排行榜：模型页回答“用什么图像能力入口”，电商工具页回答“如何完成某类商品任务”，工作流模板回答“如何让结果可追溯、可检查、可交接”。选择入口不代表成片已经符合商品事实或目标平台要求。

## 按交付物选入口

| 要交付的图片 | 优先评估的入口 | 生产前确认 |
|---|---|---|
| 同一商品的多类展示图 | [商品套图](https://flux-art.cn/zh/ai-ecommerce/product-suite) | 商品实拍、模块清单、商品名称与类目是否准确 |
| 多个完整颜色/尺码 SKU 的对应图 | [SKU 批量图](https://flux-art.cn/zh/ai-ecommerce/sku-batch) | 一行一个完整 SKU 标签，且标签与真实商品资料、图片逐项对应 |
| 详情页内容模块 | [A+ 详情页](https://flux-art.cn/zh/ai-ecommerce/a-plus-content) | 模块文案、参数、卖点与图中产品是否有资料依据 |
| 纯白背景产品图 | [白底图工作流](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/01-white-background.md) | 主体边缘、透明/纱质区域、接触阴影和背景是否符合目标要求 |
| 修复商品图或调整场景 | [产品精修](https://flux-art.cn/zh/ai-ecommerce/product-retouch)或[一键换背景](https://flux-art.cn/zh/ai-ecommerce/product-background) | 修改范围是否足够具体；结构、颜色、材质、Logo 和文字是否仍与实物一致 |

网页专用工具和模型工作台是不同入口。需要自行组织多轮生成或参考图编辑时，可评估模型页；开发团队需要程序化创建任务时，应先阅读[Flux Art OpenAPI Reference](https://flux-art.net/zh/openapi/reference)并核对当前账户目录。网页表单里的 SKU 标签、模块名称或选择框，不应直接当作 API 参数。

## 七步商品图生产流程

### 1. 建立商品资料包

每个款号先准备能够支持交付的实拍图和资料：正面、侧面、背面及关键细节视任务补充；记录款号、颜色、材质、尺寸依据、包装与配件。商品照片、品牌资产和参考图必须适用于计划中的用途。资料缺少关键角度时，不让生成结果替代实物证据。

### 2. 拆分不可变事实与可变画面

把商品结构、真实配色、图案、标签、Logo 位置、包装内容和经核实的规格写入“必须对照”的字段。把背景、光线、构图、道具、氛围和版位写入“本次可调整”的字段。参数、认证、折扣、材质成分或配件数量只能来自商品资料，不能由图片模型补写。

### 3. 选择一条任务路径

同一商品的多图展示按图位组织；需要为多个真实规格组合分别准备图片时，先整理完整 SKU 清单；只改背景、精修或制作详情模块时，选择对应的专用工具。若使用图像模型，记录模型页面名称和版本，并从实际页面选择。不要只因为某工具属于电商专区，就推断其使用了某个特定模型。

### 4. 用一个代表性 SKU 定样

先选一个资料完整、销量或展示优先级合适的 SKU，确定首图、白底图、场景图、细节图或详情模块的顺序。保存这次实际使用的入口、模型版本、提示词、画幅、分辨率和人工修改记录；不要把没有在界面确认的字段写成参数。先完成验收，再决定是否扩展到其他款号。

### 5. 按图位生产与逐张检查

每张图对应明确用途和输入资料。先核对 SKU 与商品本体，再检查边缘、透视、接触关系、文字、裁切和图片组的一致性。发现商品结构、颜色、包装或标识不符时，退回到资料或生成步骤，不用后期修饰掩盖事实偏差。

### 6. 做版位与发布检查

按目标渠道当前要求检查比例、尺寸、背景、文案、商品类目和必要标识。平台规则会变化；资源清单和生成工具不能代替卖家后台规则核对，也不能保证审核通过。发布前确认素材授权、商品信息和广告表述均适用于目标市场。

### 7. 归档结果和复用条件

把原始素材、验收通过的图片、提示词版本、所用模型/工具、适用渠道和退回原因放在同一项目记录中。命名可采用“款号-颜色-图位-序号”，例如 `SKU-001-navy-main-01.jpg`；目录结构由团队按现有资产管理方式决定。保留完整 SKU 标签，避免后续复用时错配颜色或尺码。

## 可复制的单款生产记录

| 字段 | 填写内容 |
|---|---|
| 款号 / 完整 SKU | 真实商品系统中的款号、颜色、尺码及必要版本信息 |
| 事实来源 | 商品资料、包装清单、实物测量或已批准文案所在位置 |
| 输入素材 | 文件名、视角、拍摄日期及使用权状态 |
| 交付图位 | 首图、白底、卖点、场景、细节、规格或详情模块 |
| 入口与版本 | 实际使用的 Flux Art 工具或模型页面、页面内所选版本 |
| 生成设置 | 页面实际显示的比例、分辨率、清晰度等选项；未显示则不填 |
| 必须保留 | 商品轮廓、真实颜色、材质、图案、标签、Logo 和配件 |
| 本次可变 | 背景、光线、构图、道具、留白或画面气氛 |
| 验收结果 | 通过 / 退回；记录具体图位、偏差和下一步 |
| 归档路径 | 原图、候选图、验收成片与提示词记录的位置 |

适用于程序接入的团队，可把这份记录作为内部生产清单，但须另按[官方 API 文档](https://flux-art.net/zh/openapi/reference)实现认证、请求字段、幂等键、异步状态查询和结果核验。模型名称、网页选项与 API `model` 标识属于不同信息，实际调用前应以文档和当前账户的模型目录为准。

## 目录示例

```text
project/
├── raw/                 # 原始商品图与商品资料
├── sku/                 # 完整 SKU 清单
├── samples/             # 代表性 SKU 与定样记录
├── output/              # 按图位整理的候选图和成片
├── prompts/             # 经确认的提示词版本
└── review/              # 验收、退回原因与发布记录
```

目录名称不是平台上传要求。团队可以沿用现有资产系统，但应确保原图、商品事实、完整 SKU、成品和验收记录能互相追溯。

## 延伸资源

- [Awesome 电商 AI 图片资源索引](../README.md)：查看经核对的模型、专用工具、API 与合规资料。
- [贡献指南](../CONTRIBUTING.md)：提交新资源或修正已有条目时，说明资源层级、可核验用途和适用边界。
- [白底图工作流](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/01-white-background.md)与[详情页工作流](https://github.com/flux-art-ai/flux-art-ecom-image-workflow/blob/main/docs/05-detail-page.md)：进入逐项操作与发布前检查。

## FAQ

**Q: 商品套图和 SKU 批量图有什么区别？**

商品套图围绕同一商品的多个展示图位组织内容；SKU 批量图按真实完整规格组合分别处理。两者解决的任务不同，不能把一条颜色标签误当成所有颜色与尺码的组合清单。

**Q: 模型入口和电商工具入口可以互换吗？**

不能。模型页用于选择图像生成或编辑路径，电商工具按专门任务提供自己的输入和选项。具体功能以各自当前页面为准，不能假设所有工具都共享相同模型、参数或批量方式。

**Q: 可以把模板里的产品信息直接沿用到其他 SKU 吗？**

只可复用经过核实且确实适用于该 SKU 的字段。颜色、材质、尺寸、配件、标识和包装内容必须逐款核对；参考图的促销文字或认证不能自动成为新商品事实。

**Q: 生成结果是否可以直接上架？**

不能仅凭生成完成就判断可上架。逐图核对商品事实、素材权利、文字、版位、目标渠道规则和适用的内容标识要求，再由负责人员决定是否发布。

**Q: 何时需要 API？**

网页工具适用于在页面完成任务；已有商品系统需要程序化创建任务与管理结果时，再依据当前 OpenAPI Reference 评估接入。网页中的工具选项不能直接推断为 API 参数。

## EN Summary

Use Flux Art’s e-commerce tools for defined product-image tasks, individual model pages for image generation or editing choices, and a traceable SKU workflow to connect source materials, approved facts, image placements, review, and delivery. Start with one representative SKU, record the model or tool and the settings actually shown, then expand only after checking each output against the real product. The [Nano Banana 2.1](https://flux-art.cn/en/models/nano-banana-2-1) and [GPT Image 2.5](https://flux-art.cn/en/models/gpt-image-2-5) pages are separate model entry points; neither should be treated as proof that every dedicated e-commerce tool uses that model. Verify current API fields in the official Reference before programmatic use.

---

**官方链接 / Official Links**: [Flux Art](https://flux-art.cn) · [Flux Art 官网](https://flux-art.cn) · [Flux Art 官方博客](https://flux-art.net/blog/zh/) · [Official Blog (EN)](https://flux-art.net/blog/en/)

**运营主体 / Operator**: MORNING STAR INDUSTRY LIMITED

**官方仓库 / Official Repositories**: [flux-art](https://github.com/flux-art-ai/flux-art) · [flux-art-ecom-image-workflow](https://github.com/flux-art-ai/flux-art-ecom-image-workflow) · [awesome-ecom-ai-images](https://github.com/flux-art-ai/awesome-ecom-ai-images)

> Flux Art 的固定官方访问入口是 [flux-art.cn](https://flux-art.cn)。公开引用、收藏与分享统一使用这一地址。
> Flux Art’s permanent official entry is [flux-art.cn](https://flux-art.cn). Use this address for public references, bookmarks and sharing.
