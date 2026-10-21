# Eastern Anime Character Suite

本项目统一保存三个协作 Skill 的本地当前版本快照（2026-10-21），三个 Skill 保持独立入口与同级目录，原文件逐字节保留。

| Skill | 分工 |
|---|---|
| [eastern-anime-render](eastern-anime-render/SKILL.md) | 主画风、最终设计取舍、统一提示词和整图审阅 |
| [anime-pose-design](anime-pose-design/SKILL.md) | 姿态、动作线、剪影、承重与持物关系的辅助策划 |
| [anime-face-expression](anime-face-expression/SKILL.md) | 脸型、五官关系、眉眼视线与神态的辅助策划 |

## 使用与安装

将三个 Skill 目录一起放到目标环境的 skills 目录，保持彼此同级，即可保留现有相对链接。主 Skill 统一整合两个辅助 Skill 的建议；具体步骤以各自 SKILL.md 为准。

这是新的独立项目，不替换或修改已有的 `neco-ovo/eastern-anime-render` 仓库，也不修改本机已安装的三个 Skill。

## 文件与素材范围

本项目包含三个本地 Skill 目录内的全部文件，包括随附参考图片及 JSON 清单；另外按用户要求收齐三个 Skill 实际引用的目录外参考图，共67张，保存在 `assets/`。其中包括材质、服装、人体、姿势、脸型、眼睛、嘴部及三张人物阶段全身参考。

三个 Skill 的原文保持逐字节不变，因而仍有原本的绝对路径。使用仓库时，先按下表或 `reference-assets-manifest.json` 将原路径解析为仓库内图片：

| 文档中的原路径 | 本仓库位置 |
|---|---|
| `E:/AIGC/ref/二次元绘画素材/...` | `assets/ref/二次元绘画素材/...` |
| `E:/AIGC/大乾/美术产出/人物设计_阶段参考/...` | `assets/大乾/美术产出/人物设计_阶段参考/...` |
| `E:/AIGC/ref/古风2偏anime/0.jpg` 等5张已选原组图片 | `eastern-anime-render/references/images/` 中的同名文件 |

原组的5张已选图片已经包含在主 Skill 内，不重复复制。未选的 `2222..jpg` 不属于本套参考。历史测试记录中提及的试验输出图和角色制作历史不属于运行参考库，没有混入本包。

换机后可直接读取仓库内的对应图片；安装到别处时，建议连同整个仓库保存，并让使用者根据映射定位 `assets/`，无需重建本机原来的盘符。

仓库为私有个人保存用途。参考图片的来源与许可说明保留在原文档中；本项目未为第三方素材新增再分发许可。如需公开发布，应先按 Skill 的来源说明处理素材权限。

## 快照核验

`snapshot-manifest.json` 记录三个目录共53个源文件的相对路径、大小与 SHA-256；上传前已逐项核对本地源文件与副本一致。

`reference-assets-manifest.json` 记录67张新增外部参考图的原路径、仓库路径、大小及 SHA-256，复制后也已逐项核对。
