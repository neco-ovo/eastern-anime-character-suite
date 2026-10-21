# 仓库使用入口

先读README.md了解三个Skill的协作及参考图路径映射。三个Skill目录保留当前本地快照，不因迁移路径自动改写其画风或设计要求。

遇到Skill正文、参考文档或JSON中的本机图片绝对路径时，查reference-assets-manifest.json的source_path与repository_path，将其解析为本仓库内的实际图片；E:/AIGC/ref/二次元绘画素材/整体映射到assets/ref/二次元绘画素材/；人物阶段参考映射到assets/大乾/美术产出/人物设计_阶段参考/。原组0.jpg、5..jpg、6..jpg、111.jpg、333.jpg已在主Skill的references/images/内。实际查看与传图时使用解析后的绝对文件路径。

历史测试输出目录仅为记录，不是缺失的运行参考依赖。勿改动用户原有eastern-anime-render远程仓库。
