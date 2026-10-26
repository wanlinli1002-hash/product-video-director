# 第三方来源与许可说明

本页面是发布摘要。下述文件路径均位于完整安装包解压后的 product-video-director 目录内；请下载 [完整 ZIP](product-video-director-v1.3.0.zip) 查阅原始许可证和固定版本清单。

本技能按用户选择，仅参考并选择性改编以下五个 MIT 项目的部分规则与模板。中文模块经过重新组织与适配；没有把任何上游技能完整复制进来，也不包含上游自动执行或媒体生成工作流。

原始许可证文本分别保存在 `third_party/licenses/`。具体源文件、固定提交、Git blob SHA 和本地适配目标见 来源清单（ZIP 内：third_party/manifest.json）；模块取舍见 选用说明（ZIP 内：references/upstream-selection.md）。这些固定版本用于溯源，不代表持续跟踪上游更新。

| 上游项目 | 原始版权声明 | 本地原文许可证 |
| --- | --- | --- |
| [Ethanxwang/tvc-director](https://github.com/Ethanxwang/tvc-director) | Copyright (c) 2026 Ethan Wang | MIT（ZIP 内：third_party/licenses/tvc-director.MIT.txt） |
| [Samin12/ai-storyboard-video-starter](https://github.com/Samin12/ai-storyboard-video-starter) | Copyright (c) 2026 | MIT（ZIP 内：third_party/licenses/storyboard-video-starter.MIT.txt） |
| [seaartpublic/skills](https://github.com/seaartpublic/skills) | Copyright (c) 2026 Seaart AI | MIT（ZIP 内：third_party/licenses/seaart-skills.MIT.txt） |
| [Standed/Seedance2.5](https://github.com/Standed/Seedance2.5) | Copyright (c) 2026 Standed | MIT（ZIP 内：third_party/licenses/seedance-continuity.MIT.txt） |
| [talki-io/prompt-optimizer](https://github.com/talki-io/prompt-optimizer) | Copyright (c) 2026 talki-io | MIT（ZIP 内：third_party/licenses/talki-prompt-optimizer.MIT.txt） |

Samin12 许可证中的版权行未列出姓名；此处与本地许可文件按原文保留，未自行补写。

复制、分发本技能中对应的实质改编内容时，应保留相应版权和许可声明。上游 MIT 许可中的无担保条款继续适用。本项目与上游作者没有被声明的合作或背书关系。

现有 60 个场景及其 180 套变体来自本项目之前整理的内容，不是上述上游仓库提供的场景库。中间关键帧按需配置、每帧完整独立输出、满意片段锁定、私有项目保存等，是本项目按用户需求追加或扩展的要求。

本次没有引入 Samuel-Shek、linshenkx、promptfoo 或其他未选项目的代码、模板或依赖。对源文件的审阅及许可证核对不构成对生成图片、视频质量或模型兼容性的实测。


1.3.0 继续保留上述原始许可及固定来源；新增工作流、逐段素材准备和需求访谈是面向本项目需求的整理与扩展。创作者与官方资料的链接、访问范围及经验适用边界见 ZIP 内 `references/creator-sources.md`；未把精选案例解释为成功率证明，也未复制完整教程或额外打包其他技能。
