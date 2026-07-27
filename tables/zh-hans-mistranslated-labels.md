# zh-hans-mistranslated-labels — 48 changes

| English source | old zh-Hans | new zh-Hans | defect |
|---|---|---|---|
| %lld items would be redacted | %lld 个项目将被编辑 | %lld 个项目将被隐去 | "redacted" mistranslated as "edited". |
| %lld redactions | %lld 次编辑 | %lld 处隐去 | "redactions" mistranslated as "edits". |
| 1 item would be redacted | 1 个项目将被编辑 | 1 个项目将被脱敏 | "redacted" means privacy masking, not "edited"; current zh says the item will be edited. |
| 1 redaction | 1 次编辑 | 1 次脱敏 | "redaction" mistranslated as "edit"; should be masking/redaction count. |
| 6-bit (q6, GGUF-head parity) | 6位（q6，GGUF-head奇偶校验） | 6 位（q6，与 GGUF-head 持平） | "parity" here means quality parity with GGUF-head, not parity checking; current zh says "parity check". |
| Audience | 观众 | 受众 | "Audience" here is the token/JWT aud claim, not spectators; 观众 is a wrong-sense translation. |
| Block | 块 | 阻止 | 'Block' here is the action verb (block a tool/action), not a data block; 块 is a mistranslation. |
| Memory & Recall | 内存与重载 | 记忆与回忆 | Feature is agent memory, not RAM; 'Recall' mistranslated as 'reload' |
| Memory database reopened. | 内存数据库已重新打开。 | 记忆数据库已重新打开。 | Same RAM-vs-memories word-sense error |
| Memory DB open | 内存数据库已打开 | 记忆数据库已打开 | Memory-feature DB mistranslated as in-memory/RAM database |
| Memory store reset. | 内存存储重置。 | 记忆存储已重置。 | RAM-vs-memories error; missing completed aspect |
| Memory store reset. Old file kept at %@. | 内存存储重置。旧文件保存在%@。 | 记忆存储已重置。旧文件保留在 %@。 | Same RAM-vs-memories error in reset toast |
| Net credits | 网络积分 | 净积分 | 'Net' (net amount) mistranslated as 'network' |
| Open Identity | 开放身份 | 打开身份 | "Open" is the verb (open identity settings), not "make public"; 开放身份 misleads. |
| Open Web | 打开网络 | 打开网页 | Button opens the theme's web page; 网络 means "network", should be 网页. |
| Path | 小路 | 路径 | "Path" (file path) mistranslated as "小路" (a footpath/trail). |
| Preview bounded memory context | 预览受限内存上下文 | 预览受限记忆上下文 | "memory" here is agent memory (记忆), not RAM (内存); sibling key uses 记忆. |
| Relay Off | 继电器关闭 | 中继已关闭 | Relay mistranslated as electrical relay (继电器) instead of network relay (中继), inconsistent with sibling status labels. |
| Remove Image | 移除镜像 | 移除图片 | In the theme editor, Image means picture, not container image; 镜像 is wrong. |
| Repro path | 复制路径 | 复现路径 | Repro means reproduction, not copy; current zh reads as 'copy path' |
| Still can't open memory — try Reset. | 仍然无法打开内存 — 尝试重置。 | 仍然无法打开记忆 — 请尝试重置。 | 'memory' here is the agent memory store, not RAM; 内存 means RAM. |
| User Agent | 用户智能体 | 用户代理 | In a request-details pane "User Agent" is the HTTP header, not an AI agent. |
| Waiting to be redeemed | 等待被赎回 | 等待兑换 | "redeemed" means to claim/exchange here; 赎回 is the financial buy-back sense. |
| ~%@ of %.0f GB | ~%1$@ of %2$.0f GB | ~%1$@ / %2$.0f GB | English word 'of' left untranslated in the Chinese string. |
| Duration | 期间 | 时长 | "Duration" (elapsed time label) translated as 期间 ("during a period") instead of 时长. |
| e.g. CUSTOMER | 例如：客户 | 例如：CUSTOMER | The uppercase placeholder-label example CUSTOMER should stay as a literal token, not be translated. |
| Fraction from 0.10 to 1.00. | 分数从0.10到1.00。 | 比例值范围为 0.10 到 1.00。 | 'Fraction' (ratio value) mistranslated as 分数 which reads as 'score' |
| Last signed checks | 最近签署的支票 | 最近的签名校验 | 'checks' here are signed verification checks, not bank cheques. |
| Likes | 偏好 | 点赞 | 'Likes' is the HF like count, not preferences. |
| Listing | 列表 | 条目 | 'Listing' (marketplace entry) mistranslated as 'list'. |
| manual | 手册 | 手动 | "manual" here means the manual/hand-triggered mode, not a handbook; 手册 is the wrong sense. |
| Memory Budget | 内存预算 | 记忆预算 | Likely memories-feature budget, not RAM budget (callsite MemoryView) |
| Model Memory | 模型记忆 | 模型内存 | Server-settings 'Model Memory' is RAM, not memories |
| native | 本地的 | 原生 | "native" should be 原生, not 本地的 which collides with "local". |
| privacy.category.secret | 密钥 | 机密 | Privacy category "secret" means confidential value generally, not cryptographic key. |
| Redacted activity export copied | 已编辑的活动导出已复制 | 已脱敏的活动导出已复制 | Redacted translated as 'edited' instead of 'de-sensitized', contradicting the established 已脱敏 rendering. |
| Reset memory store? | 重置内存存储？ | 重置记忆存储？ | 'memory' is the agent memory feature, not RAM; 内存 means RAM |
| Resolved Plan | 已解决的计划 | 解析后的计划 | 'Resolved' means computed/effective plan, not 'solved' |
| [secret] | [密钥] | [机密] | Masking token for any secret value; "密钥" is too narrow and inconsistent with the corrected category term. |
| A quick tour | 快速浏览 | 快速导览 | In onboarding context "tour" means a guided walkthrough; "浏览" means skim/browse, which misstates the feature. |
| Edit model | 编辑模型 | 图像编辑模型 | Label for the image-edit model picker (noun compound), but 编辑模型 parses as the verb phrase 'edit the model'. |
| Editing | 正在编辑 | 编辑操作 | Effect-class category label mistranslated as an in-progress status (正在编辑). |
| editor.section.identity | 身份 | 基本信息 | Comment explicitly invites a 'basic info' rendering to avoid colliding with the cryptographic Identity key; "身份" recreates the collision. |
| Look and navigate freely; never edit. | 浏览并自由导航；从不编辑。 | 自由查看和导航；绝不编辑。 | Misattached 'freely', term mismatch with the Looking tier label, and unnatural 从不编辑. |
| Recovery Phrase | 恢复助记词 | 助记词 | '恢复助记词' parses as a verb phrase 'recover the mnemonic'; the field label should be the noun 助记词. |
| Support Export | 支持导出 | 导出支持数据 | 'Support' here is attributive (export for support purposes); 支持导出 reads as 'supports exporting'. |
| Terms to avoid during image generation | 图片生成时应避免的术语 | 图片生成时应避免的词语 | 'terms' means words/phrases to avoid in image prompts, not terminology; 术语 is the wrong sense. |
| Zip Bundle | Zip 捆绑包 | Zip 压缩包 | "捆绑包" is a calque of bundle; the conventional zh term for a zip archive is 压缩包. |
