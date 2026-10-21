# 参考图映射

来源：用户提供的本地参考图，2026-10-16。原始目录 E:/AIGC/ref/古风2偏anime。分析依据图像本身，作者及具体制作软件未经核实。

安装包随附私人工作副本，路径相对于 Skill 根目录：

| ID | 图片路径 | 参考作用 |
|---|---|---|
| R1 | references/images/0.jpg | 辅助依据：精密细饰与宽阔大面对照；不覆盖6的画法或复制具体光位 |
| R2 | references/images/5..jpg | 历史风格依据；仍可按需提取衣料、皮肤或植物局部，不参与本版核心定义 |
| R3 | references/images/6..jpg | 默认核心：连续底色与异色薄层、曲形节奏、薄擦与干刷和细描的组织及断续色边；不固定配色 |
| R4 | references/images/111.jpg | 辅助依据：选择性结构线与前后色形呼应，不取代6的整体画法 |
| R5 | references/images/333.jpg | 历史风格依据；仍可按需使用头发与弯折衣料局部，不参与本版核心定义 |

本版默认整体风格依据为R3；整体图允许时优先选用，用户仅文字或仅材质要求优先。R1、R4仅按相容补充需要选用，不固定每次传三张，也不因此省略有用图；所有选中图按分类库上限规则传入，不设固定混合权重。R2、R5仍保留为局部材质或用户另行指定的参考。图片区分整体画法与局部材质职责，不能把原图身份、衣着、道具及构图偷渡到新图。

目录中的 2222..jpg 未由用户选入本组且未分析，不使用。

## 局部材质辅助参考

优先使用以下原像素裁切，路径相对于 Skill 根目录。裁切没有缩放、调色或生成补画。保留局部形体上下文，不将其中人物、道具或配色自动带入新图。

| 图片 | 原来源与裁切框（左、上、右、下） | 用途 |
|---|---|---|
| references/images/sleeve-drape-original.png | 5..jpg；80,335,475,900 | 垂坠衣料、宽亮面与柔韧转折 |
| references/images/sleeve-bent-arm-original.png | 333.jpg；90,480,600,815 | 肘部受力和圆转衣褶 |
| references/images/hair-volume-original.png | 333.jpg；250,10,735,480 | 发束体积及低对比细分 |
| references/images/oip-ink-bamboo-original.png | OIP 2098686915092631789 首图；120,0,675,300 | 可选背景的竹影笔形、淡浓层次；不传递纸纹给人物 |

OIP 裁切来源：https://openimages.ajiang.me/p/2098686915092631789/ ，作者页面标注 @DeepBlueX0。原图地址：https://media.openimages.relakkesyang.org/images/2098686915092631789/1.jpg 。

新增材质裁切：

| 图片（相对于 Skill 根目录） | 原来源与裁切框 | 范围 |
|---|---|---|
| references/images/leaf-plane-original.png | 5..jpg；25,620,195,755 | 莲叶色面，不代表所有叶种 |
| references/images/water-context-original.png | 5..jpg；0,870,150,1108 | 池景水色与倒影语境，混有植物，非纯水材质 |
| references/images/jewelry-response-original.png | 0.jpg；625,265,980,555 | 珠饰与金属局部反射，混有织物 |

适用边界及调用方式见 [材质参考](materials.md)。`hair-cloth-study.png` 是历史生成示意板，不是原像素裁切，不作为默认材质参考；测试取舍见 [记录](validation.md)。

原图中可见署名、水印及使用声明；仅作为用户本地视觉分析与风格参考保存，不宣称获得再分发许可。发布 Skill 时应先移除未获许可的图片副本，改为用户自行提供的参考路径。不要编辑原图来去除署名或遮挡。
