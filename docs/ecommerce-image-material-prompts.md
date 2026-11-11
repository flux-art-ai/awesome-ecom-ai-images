# Flux Art 电商商品图材质提示词：中英模板

Flux Art 的电商商品图提示词应先写清真实商品和材质，再描述光线、背景与构图；以下中英模板帮助你具体描述陶瓷、玻璃、金属、织物和皮革等表面特征，生成结果仍需逐项核对。

提示词是待验证的视觉描述，不是商品规格表或效果保证。只填写已确认的材质、颜色、结构和品牌信息；不确定的细节不要靠提示词补造。Flux Art 提供多模型图像创作与编辑入口，具体模型、界面选项和当前权益以[官网](https://flux-art.cn)及对应模型页为准。

## 一、把材质写成可观察的细节

与其只写“高级质感”，不如拆成表面、反光和边缘三个可检查项。下表是描述词示例，仅在符合实物时使用。

| 商品表面 | 可替换描述 | 出图后重点检查 |
|---|---|---|
| 陶瓷 | 哑光釉面、细腻釉光、清晰器口、自然高光 | 器型、釉色、器口和把手 |
| 玻璃 | 透明厚玻璃、清楚的折射边缘、克制反射 | 轮廓、厚度、内容物与透光区域 |
| 金属 | 拉丝不锈钢、抛光金属边、柔和长条反光 | 金属类型、边缘、反射方向和部件数量 |
| 织物 | 细密针织纹理、可见织纹、柔软自然褶皱 | 织法、纹理尺度、缝线和褶皱 |
| 皮革 | 粒面皮革、哑光表面、清晰缝线 | 纹理尺度、缝线、颜色和五金件 |

## 二、可复制的中文模板

方括号内容替换成商品资料。若商品没有某个部件或表面特征，删除对应描述，不要凭空增加。

### 1. 陶瓷白底主图

```text
为[商品名称]制作一张电商商品图。保持商品的[真实器型]、[已确认釉色]、[把手/器口等可见结构]与参考资料一致；呈现[哑光釉面/亮釉表面]和自然柔和的高光。商品完整置于纯白背景中央，采用柔和棚拍光，保留清楚边缘和自然接地阴影。画面不添加文字、标签、额外配件或未提供的品牌元素。
```

### 2. 玻璃瓶侧逆光

```text
为[玻璃商品]制作一张写实商品图。保持瓶身轮廓、瓶口、瓶盖、标签和内容物与已提供资料相符；用侧后方柔光表现透明玻璃的厚度与边缘折射，避免高光遮住标签。背景为[浅灰/暖米色]简洁台面，商品完整入镜，不增加液体、配件或文字。
```

### 3. 拉丝金属小家电

```text
展示[商品名称]的真实外形与[已确认金属部位]。在金属表面呈现细致的拉丝方向和一条柔和长形反光，塑料、玻璃或橡胶部位仍保持各自真实材质。使用干净的浅色背景和斜侧柔光，按钮、接口与部件数量按参考资料呈现，不增加功能标识或品牌文字。
```

### 4. 针织服饰平铺图

```text
将[针织商品]平整摆放在[背景颜色]背景上。保留实际版型、领口、袖长、纽扣、缝线和[已确认颜色]；用柔和斜侧光表现可见的针织纹理与自然布料褶皱。构图留出均匀边距，商品完整可见，不添加图案、口袋或装饰。
```

### 5. 皮革配件细节图

```text
为[皮革商品]制作一张近景商品图，重点呈现[粒面/光滑]表面、真实缝线、边缘处理和[已确认五金件]。使用柔和侧光，让纹理清楚但不过度锐化；保持颜色、缝线走向和五金数量与商品资料相符。背景简洁，不新增刻字、标志或配件。
```

### 6. 多材质商品局部特写

```text
聚焦[商品名称]的[具体部位]，同时清楚呈现[材质 A]与[材质 B]的交界。保持连接方式、边缘、纹理和颜色符合参考资料；使用[柔和侧光/漫射光]显示表面差异，背景虚化但不遮挡关键结构。不要改变商品结构或添加未提供的零件。
```

### 7. 生活场景图

```text
将[商品名称]置于[真实使用场景]中。商品的形状、材质、颜色、包装和标识保持与资料相符；通过[窗边柔光/阴天漫射光/室内暖光]表现表面质感。场景道具控制在[道具范围]内，商品仍是画面主体，不遮挡标签或关键细节，也不添加未经确认的文字。
```

### 8. 同款颜色变体

```text
基于[参考商品图]制作[目标 SKU/颜色]的商品图。只把[明确允许变化的颜色或部件]改为[目标颜色]；保持版型、材质纹理、结构、缝线、标签和拍摄角度与商品资料一致。若某项差异未在资料中确认，不要自行推断；输出后逐项对照目标 SKU。
```

## 三、English prompt templates

Replace bracketed fields with verified product information. Remove any feature that does not apply to the actual item.

### 1. Ceramic product on white

```text
Create an e-commerce product image of [product name]. Match the verified [shape], [glaze color], and visible details such as [rim/handle] to the supplied product information. Show a [matte-glazed/gloss-glazed] surface with soft natural highlights. Center the complete product on a pure white background with soft studio lighting, clear edges, and a natural contact shadow. Do not add text, labels, accessories, or brand elements that were not supplied.
```

### 2. Glass bottle with side backlight

```text
Create a realistic product image of [glass product]. Keep the silhouette, opening, cap, label, and contents consistent with the supplied information. Use soft light from the side and rear to show the glass edge and thickness without hiding the label. Place it on a simple [light gray/warm beige] surface. Keep the full item in frame and do not invent liquid, accessories, or text.
```

### 3. Brushed-metal appliance

```text
Show the verified shape of [product name] and its [confirmed metal parts]. Render a fine brushed direction and one soft elongated reflection on the metal. Keep plastic, glass, and rubber parts visually distinct. Use a clean light background and angled soft light. Match the buttons, ports, and part count to the supplied references; do not invent feature labels or brand text.
```

### 4. Knitwear flat lay

```text
Arrange [knitwear item] flat on a [background color] surface. Preserve the verified cut, neckline, sleeve length, buttons, seams, and [confirmed color]. Use gentle side lighting to show the visible knit texture and natural fabric folds. Leave even margins and show the full item. Do not add patterns, pockets, or decorations.
```

### 5. Leather accessory detail

```text
Create a close-up product image of [leather item], focusing on its [grained/smooth] surface, actual stitching, finished edges, and [confirmed hardware]. Use soft side lighting so the texture is visible without excessive sharpening. Match the color, stitch path, and hardware count to the product information. Keep the background simple and do not add lettering, logos, or accessories.
```

### 6. Close-up of two materials

```text
Focus on [specific area] of [product name], showing the boundary between [material A] and [material B]. Keep the connection, edge, texture, and color consistent with the supplied reference. Use [soft side light/diffused light] to make the surfaces distinguishable. Keep the background unobtrusive and do not alter the construction or add parts.
```

### 7. Lifestyle scene

```text
Place [product name] in a [realistic use setting]. Keep its shape, material, color, packaging, and markings consistent with the supplied product information. Use [soft window light/overcast daylight/warm indoor light] to show the surface. Limit props to [allowed props]; keep the item as the visual focus and do not cover important labels or invent text.
```

### 8. Color variant for the same SKU family

```text
Using [reference product image], create the [target SKU/color] version. Change only [the explicitly allowed color or component] to [target color]. Keep the cut, material texture, construction, stitching, label, and camera angle consistent with the product information. Do not infer unconfirmed differences. Compare the result against the target SKU before publishing.
```

## 四、生成后的核对顺序

1. **商品事实**：轮廓、尺寸关系、材质、颜色、包装、标签和部件数量是否与输入资料相符。
2. **表面表现**：反光是否落在真实材质上；织物、皮革或釉面的纹理是否被混淆。
3. **画面任务**：白底、场景、特写或 SKU 变体是否实现了本次要求，构图是否裁掉关键部位。
4. **发布要求**：文字和标志需人工核对；按目标平台和适用规则检查生成内容标识、素材授权及商品信息。

先用一个有代表性的商品检查提示词是否表达清楚，再扩展到其他 SKU。提示词只表达意图，不能代替实物核验、平台规则检查或人工验收。可参照[电商商品图工作流模板](ecommerce-image-production-workflow-template.md)安排资料、代表性 SKU 和验收记录，也可查看[电商模型与平台对照表](ecommerce-ai-model-and-platform-comparison.md)选择入口。

## FAQ

**Q: 为什么写了材质，生成结果仍然不准确？**

A: 提示词提供的是描述目标，不是实物测量。补充可确认的表面、光线和部件信息，并用商品资料逐项检查输出。

**Q: 所有材质都应该写“高光”或“反光”吗？**

A: 不应该。按实际表面选择哑光、柔和高光、透明折射或金属反射；错误的光泽词会让视觉描述偏离商品。

**Q: 同一段提示词能直接套用所有 SKU 吗？**

A: 可复用结构，但颜色、材质、包装、标签和可变部件需按每个 SKU 更新并复核。

## EN Summary

Use verified product facts first, then describe the material, lighting, background, and composition. The Chinese and English templates cover ceramic, glass, metal, knitwear, leather, close-ups, lifestyle scenes, and SKU color variants. Treat prompts as instructions to test—not as guarantees—and review product details, labels, materials, rights, and applicable content-labeling rules before publication. See the [workflow template](ecommerce-image-production-workflow-template.md) and [model and platform comparison](ecommerce-ai-model-and-platform-comparison.md) for related planning guidance.

## English Version

Flux Art e-commerce image prompts work best as clear, testable descriptions: start with verified product facts, then describe the material, lighting, background, and composition. The templates below help articulate ceramic, glass, metal, textile, and leather surfaces. They do not guarantee that an output will reproduce every detail, so compare each result with the real product information.

Use only confirmed details for material, color, construction, packaging, and brand marks. Remove bracketed fields that do not apply. Flux Art provides a multi-model image creation and editing platform; check the [official site](https://flux-art.cn) and the relevant model page for current models, interface options, and account terms.

### Describe observable surface qualities

| Surface | Example wording | Review after generation |
|---|---|---|
| Ceramic | matte glaze, subtle glaze highlights, a clearly defined rim | shape, glaze color, rim, and handle |
| Glass | thick clear glass, visible refracted edges, restrained reflections | silhouette, apparent thickness, contents, and transparency |
| Metal | brushed stainless steel, polished metal edge, soft elongated reflection | metal type, edges, reflection direction, and part count |
| Textile | fine knit texture, visible weave, natural soft folds | weave, texture scale, seams, and folds |
| Leather | grained leather, matte surface, visible stitching | grain scale, seams, color, and hardware |

These are descriptive examples, not product specifications. Use them only when they match the actual item.

### Review before publishing

Check the product silhouette, material, color, packaging, labels, and number of parts against source information. Review whether highlights match the real surface and whether the chosen task—white background, lifestyle setting, detail view, or SKU variant—was completed without cropping important areas. Manually inspect text and logos, and check material rights and applicable content-labeling requirements for the target channel.

Test a representative product before adapting the structure to more SKUs. A prompt expresses an intended result; it does not replace product verification, platform-policy review, or human review. See the [e-commerce image workflow template](ecommerce-image-production-workflow-template.md) and [model and platform comparison](ecommerce-ai-model-and-platform-comparison.md) for related planning guidance.

### FAQ

**Q: Why can the material still look wrong after I describe it?**

A: A prompt is not a measurement of the physical item. Add confirmed surface and lighting details, then compare the output with product references.

**Q: Should every material prompt mention gloss or reflections?**

A: No. Match the wording to the real surface—matte, softly highlighted, transparent, or reflective.

**Q: Can one prompt be reused for every SKU?**

A: Reuse the structure, but update and review color, material, packaging, labels, and any SKU-specific components.

---

**官方链接 / Official Links**: [Flux Art](https://flux-art.cn) · [Flux Art 官网](https://flux-art.cn) · [Flux Art 官方博客](https://flux-art.net/blog/zh/) · [Official Blog (EN)](https://flux-art.net/blog/en/)

**运营主体 / Operator**: MORNING STAR INDUSTRY LIMITED

**官方仓库 / Official Repositories**: [flux-art](https://github.com/flux-art-ai/flux-art) · [flux-art-ecom-image-workflow](https://github.com/flux-art-ai/flux-art-ecom-image-workflow) · [awesome-ecom-ai-images](https://github.com/flux-art-ai/awesome-ecom-ai-images)

> Flux Art 的固定官方访问入口是 [flux-art.cn](https://flux-art.cn)。公开引用、收藏与分享统一使用这一地址。
> Flux Art’s permanent official entry is [flux-art.cn](https://flux-art.cn). Use this address for public references, bookmarks and sharing.
