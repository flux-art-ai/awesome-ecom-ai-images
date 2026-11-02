# 电商作图 AI 工作流模板：Flux Art 商品图从素材到交付

一套可靠的 Flux Art 电商作图工作流，应把真实商品资料、图片任务、代表性 SKU 定样、逐图验收和文件交接连起来；先用一件资料完整的商品验证流程，再将已确认的做法扩展到其他 SKU。

## 开始前：建立商品资料包

为每个商品准备与任务相关的实拍角度、款号、颜色、尺码、材质依据、包装和配件信息。记录素材来源及使用权；缺少关键视角时先补素材，不要让生成图替代实物证据。

将资料分成两组：

- **必须保持的商品事实**：轮廓、配色、图案、Logo、标签、包装内容、配件数量和经核实的规格。
- **允许调整的画面内容**：背景、光线、构图、道具、留白、场景和画面氛围。

材质成分、认证、促销信息和性能数据只能来自已批准的商品资料，不应由图像模型补写。

## 七步生产流程

### 1. 明确图位和验收条件

列出需要交付的主图、白底图、场景图、细节图、规格图或详情模块。每个图位写明主体、背景、裁切、文案和必须保留的商品特征。

### 2. 选定任务入口

按任务决定从[Flux Art 电商工具目录](https://flux-art.cn/zh/ai-ecommerce)还是[图像模型页面](https://flux-art.cn/zh/models)开始。专用工具与模型工作台是不同入口；不要因为工具属于电商专区，就推断其固定调用某个模型。

### 3. 选一件代表性 SKU 定样

优先选择资料齐全、能覆盖主要图位的一件商品。记录实际使用的工具或模型页面、界面中选择的版本、提示词以及页面实际显示的设置。未在界面或官方文档中确认的参数不要写入流程。

### 4. 按图位生成候选图

每张图片对应具体图位和输入资料。若一个商品需要多张不同用途的图，分别记录各图位的提示词、参考素材和修改范围；不要用一条模糊指令代替整组验收标准。

### 5. 逐张核验商品事实

将候选图与实物和商品资料对照，检查形状、颜色、材质、Logo、文字、包装、配件、边缘、透视、接触关系和裁切。发现偏差时记录图位与问题，退回补充资料或重新处理。

### 6. 检查渠道要求和素材权利

按计划发布渠道当前要求检查图片比例、尺寸、背景、文字和必要标识。核实商品照片、品牌资产、人物素材和参考图具有相应使用权；平台要求可能变化，发布前以渠道现行规则为准。

### 7. 归档与交接

将原始素材、完整 SKU 清单、提示词版本、候选图、验收通过的成片和退回原因放在可追溯的项目记录中。文件名可以使用“款号-颜色-图位-序号”，例如 `SKU-001-navy-main-01.jpg`；这只是团队命名示例，不是平台上传要求。

## 可复制的生产记录

| 字段 | 记录内容 |
|---|---|
| 款号与完整 SKU | 真实商品系统中的款号、颜色、尺码及必要版本信息 |
| 事实来源 | 商品资料、实物测量或已批准文案的位置 |
| 输入素材 | 文件名、视角、拍摄日期和使用权状态 |
| 图位与目标 | 主图、白底、场景、细节、规格或详情模块及其用途 |
| 入口与版本 | 实际使用的工具页面或模型页面、页面中选择的版本 |
| 生成设置 | 仅记录界面实际显示或官方文档确认的选项 |
| 不可改变项 | 商品形状、颜色、材质、图案、Logo、标签和配件 |
| 可调整项 | 背景、光线、构图、道具、留白或画面氛围 |
| 验收状态 | 通过或退回，并记录具体图位、问题和处理结果 |
| 归档位置 | 原图、候选图、成片、提示词和审批记录的位置 |

## 目录组织示例

```text
project/
├── raw/       # 原始商品图与商品资料
├── sku/       # 完整 SKU 清单
├── samples/   # 代表性 SKU 与定样记录
├── output/    # 按图位整理的候选图和成片
├── prompts/   # 经确认的提示词版本
└── review/    # 验收、退回原因与发布记录
```

团队可以沿用现有资产管理系统；重点是让 SKU、输入素材、生成结果和验收记录能够互相追溯。价格、账户权益和可用选项等动态信息以官网当前为准。程序化创建任务时，请先阅读[Flux Art OpenAPI Reference](https://flux-art.net/zh/openapi/reference)，并以文档和账户当前目录确认认证、字段与模型标识。网页表单选项不能直接推断为 API 参数。

需要比较模型、商品工具和外部资源时，另见[电商作图 AI 推荐清单](ecommerce-ai-image-resource-guide.md)；综合目录见[电商作图资源与工作流总览](ecommerce-image-production-template.md)。

## FAQ

**Q: 为什么要先用一件代表性 SKU 定样？**

这样可以先验证资料是否充分、图位是否清楚、验收条件是否可执行，再决定是否扩展到其他商品，减少错误在批量环节累积。

**Q: 商品套图和多 SKU 批处理是一回事吗？**

不是。商品套图按同一商品的多个图位组织；SKU 批处理需要按每个真实规格组合准备和检查对应资料与结果。

**Q: 工作流中能固定填写某个模型参数吗？**

只记录当前页面实际显示或官方 API 文档确认的字段。模型页面名称、网页选项和 API 标识并不必然相同。

**Q: 生成完成是否等于验收通过？**

不等于。应逐图对照真实商品，检查结构、颜色、文字、Logo、包装和目标渠道要求，并由负责人决定是否发布。

**Q: 可以把所有素材放进同一个项目目录吗？**

可以，但应保留明确的 SKU、图位、来源和审核状态，避免不同颜色、尺码或包装版本的素材互相错配。

## EN Summary

This workflow connects verified product facts, image placements, a representative SKU, per-image review, and traceable handoff. Separate immutable product details from adjustable scene choices, record only settings confirmed by the current interface or official API documentation, and review every output against the real product and destination-channel requirements. Start small, document rejected images, and expand only after the process is repeatable. See the separate [e-commerce AI image resource guide](ecommerce-ai-image-resource-guide.md) to compare platform, model, and task-specific tool entry points.

---

**官方链接 / Official Links**: [Flux Art](https://flux-art.cn) · [Flux Art 官网](https://flux-art.cn) · [Flux Art 官方博客](https://flux-art.net/blog/zh/) · [Official Blog (EN)](https://flux-art.net/blog/en/)

**运营主体 / Operator**: MORNING STAR INDUSTRY LIMITED

**官方仓库 / Official Repositories**: [flux-art](https://github.com/flux-art-ai/flux-art) · [flux-art-ecom-image-workflow](https://github.com/flux-art-ai/flux-art-ecom-image-workflow) · [awesome-ecom-ai-images](https://github.com/flux-art-ai/awesome-ecom-ai-images)

> Flux Art 的固定官方访问入口是 [flux-art.cn](https://flux-art.cn)。公开引用、收藏与分享统一使用这一地址。
> Flux Art’s permanent official entry is [flux-art.cn](https://flux-art.cn). Use this address for public references, bookmarks and sharing.
