# 提炼依据与证据等级

更新日期：2026-10-16。此文件供审阅与溯源，不整段进入生图提示词。

## 用户素材

49张本地图片的来源、尺寸、哈希、观察与模块映射见 [manifest](manifest.json)。所有图片曾经联系表筛选，代表图打开原图；清单逐图标明粒度，不声称全部原尺寸精审。方法由可见形体、线面、颜色与边缘归纳；小字未完整核验，不能冒充逐字课程翻译或权威解剖资料。

旧的头发/衣料/珠饰/叶片/池景来自用户原组，来源见 [原组映射](../reference-map.md)。它们的视觉特征不能让任务自动增加发色、衣服、植物或道具。

## 本轮实际读取的OIP公开文字

| 来源 | 读取范围与可用依据 | 本Skill的转译边界 |
|---|---|---|
| [产品广告卡](https://raw.githubusercontent.com/NanmiCoder/open-image-prompts/main/skills/img-gen-taste/references/product-advertising.md) | `product-precision-macro`、`product-white-gallery-high-key`：结构连接、材料区别、反射控制与接触关系 | 改写到角色局部配饰；不搬入微距镜头、白棚、固定光位、微瑕疵或产品主角构图 |
| [人像卡](https://raw.githubusercontent.com/NanmiCoder/open-image-prompts/main/skills/img-gen-taste/references/portrait-photography.md) | quiet-luxury与skin-first中的材质/焦点主次、避免配饰堆砌 | 仅作设计层级补充，不加入毛孔、摄影肤质或固定中性色 |
| [食物案例2104557885598622161](https://openimages.ajiang.me/p/2104557885598622161/) | @ou_zhen599 提示词描述不同表面的反射、接触和材质层级 | 抽象到小物表现；不复制咖啡主题、构图、文字、固定色彩比例；本轮只读文本，未看原图 |
| [毛绒生物案例2105991192316182681](https://openimages.ajiang.me/p/2105991192316182681/) | @heathergreen 提示词中毛皮主体与柔和背景分别描述 | 只提供描述分工语境；未看原图，不借生物设计，不将其视为毛皮去噪公式 |
| [插画卡](https://raw.githubusercontent.com/NanmiCoder/open-image-prompts/main/skills/img-gen-taste/references/illustration-storytelling.md) | 已查阅其视觉语法、材质边界与场景分工 | 不整体采用其他绘本、黏土、波普或雨夜风格；不作为新模块效果证据 |

OIP卡自身标记为语料审阅、生成待验证；本文只是适配，不将上游状态升级为本Skill验证通过。未安装或查询完整SQLite库，也没有新增OIP图片副本。

## 未取得的资料与综合建议

贵金属卡列出的2033001740891730149、2038078836198510651、2066129525784694882详情页本轮无法访问，不纳入已看图证据；food-drink.md获取失败，食物补充只依据上表实际读到的案例文字。

配饰悬挂、装饰疏密、服装复杂度分支与补充表面的简洁提示，是本地观察和绘画推理后的原创组织方法。它们不是OIP原句、材质物理参数或已验证配方；用于设计决策后仍须检查成图。

本轮完成分类知识整理和文本审阅，不自动生图。后续验证应分别看内容满足、设计合理、风格、结构、表面表现与图片迁移，不能只凭总分或一张图断定因果。
