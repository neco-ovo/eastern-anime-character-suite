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

本项目包含三个本地 Skill 目录内的全部文件，包括随附参考图片及 JSON 清单。没有额外导入 Skill 目录外的原始素材、角色项目或制作历史。

部分参考文档及素材清单引用本机 `E:/AIGC/ref/...`、`E:/AIGC/大乾/...` 等绝对路径；这些外部依赖不在本快照中，换机使用时需自行提供对应素材或配置路径。保留原文有助于准确还原当前本地版本，不代表跨机器开箱即用。

仓库为私有个人保存用途。参考图片的来源与许可说明保留在原文档中；本项目未为第三方素材新增再分发许可。如需公开发布，应先按 Skill 的来源说明处理素材权限。

## 快照核验

`snapshot-manifest.json` 记录三个目录共53个源文件的相对路径、大小与 SHA-256；上传前已逐项核对本地源文件与副本一致。
