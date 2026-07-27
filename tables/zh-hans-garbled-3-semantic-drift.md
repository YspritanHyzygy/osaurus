# zh-hans-garbled-3-semantic-drift — 97 changes

| English source | old zh-Hans | new zh-Hans | defect |
|---|---|---|---|
| not enabled for this agent | 此智能体未启用 | 未对此智能体启用 | Reads as "this agent is not enabled" instead of "not enabled for this agent" — subject flipped. |
| permission policy is deny | 权限策略被拒绝 | 权限策略为拒绝 | Translation says the policy "was denied" instead of "the policy is set to deny". |
| Required to type into other applications | 需要输入到其他应用程序中 | 向其他应用程序输入文字所需 | Reversed meaning: zh reads as an instruction to type, not a permission rationale |
| Reset to default theme | 已重置为默认主题 | 重置为默认主题 | zh adds 已 (already done), turning an action label into a completed-state message |
| Revoked | 撤销 | 已撤销 | Status label reads as imperative verb; needs 已撤销 to distinguish from Revoke |
| Rolled back to the default theme | 回滚到默认主题 | 已回滚到默认主题 | Completed-action toast missing 已, reads as imperative |
| Router | 路由器 | 路由 | Model-routing feature translated as hardware router |
| Router Account | 路由器账户 | 路由账户 | Router (model routing service) mistranslated as hardware router |
| Router usage appears here after a hosted model request is billed. | 托管模型请求计费后，路由器使用情况将显示在此处。 | 托管模型请求计费后，路由使用情况将显示在此处。 | Same Router-as-hardware mistranslation |
| Run a local signing check to inspect the redacted request shape. | 运行本地签名检查以查看已编辑的请求形态。 | 运行本地签名检查以查看脱敏后的请求形态。 | redacted mistranslated as edited, losing privacy meaning |
| Run Diagnostics below tests the saved connection against its endpoint. | 运行诊断以测试保存的连接与其端点。 | 下方的“运行诊断”会针对其端点测试已保存的连接。 | Descriptive sentence turned imperative; 'against its endpoint' misread as coordinate object |
| Schedule this agent to run on a recurring cadence — perfect for daily briefings or automated check-ins. | 将此智能体安排为按周期重复运行——非常适合每日简报或自动签到。 | 将此智能体安排为按周期重复运行——非常适合每日简报或自动定期汇报。 | "check-ins" means periodic status reports, not attendance sign-in (签到) |
| Seconds before auto-dismiss. Empty uses default 5s | 自动关闭前几秒。空值使用默认5秒 | 自动关闭前的秒数。留空则使用默认 5 秒 | "Seconds before auto-dismiss" is a field description meaning "number of seconds"; 「自动关闭前几秒」 reads as "a few seconds before closing" |
| Self-scheduled | 自我计划 | 自调度 | Inconsistent with sibling key using 自调度; 计划 drifts from 'scheduled' |
| Self-scheduling | 正在自我计划 | 自调度 | Toggle title mistranslated as progressive state '正在自我计划'; should be feature name 自调度 |
| Showing %lld-%lld of %lld loaded | 显示 %lld-%lld 共 %lld 已加载 | 显示已加载 %3$lld 行中的第 %1$lld-%2$lld 行 | '共 %lld 已加载' dangling at end is ungrammatical and ambiguous |
| Sign in (or sign up free) at huggingface.co | 在 huggingface.co 登录（或免费注册）。 | 在 huggingface.co 登录（或免费注册） | Trailing full stop absent in en and in the parallel github.com key |
| Some buffered turns hit the retry cap and were dead-lettered. Check Recent Activity for the failing reason, then backfill or re-ingest after fixing the model/configuration problem. | 部分缓冲轮次达到重试上限并已进入死信队列。请查看近期活动了解失败原因，然后在修复模型/配置问题后回填或重新填充。 | 部分缓冲轮次达到重试上限并已进入死信队列。请查看近期活动了解失败原因，然后在修复模型/配置问题后回填或重新导入。 | "re-ingest" mistranslated as "重新填充" (refill), losing the data-ingestion meaning. |
| Speed/quality budget for block-diffusion models (DiffusionGemma). 16 ≈ 2× faster than the model default and stays coherent; below 12 quality degrades. Ignored by ordinary models. | 块扩散模型（DiffusionGemma）的速度/质量预算。设为 16 时速度约为模型默认值的 2 倍，且保持画面连贯；低于 12 时质量下降。对常规模型无效。 | 块扩散模型（DiffusionGemma）的速度/质量预算。设为 16 时速度约为模型默认值的 2 倍，且输出保持连贯；低于 12 时质量下降。对常规模型无效。 | "stays coherent" refers to text output; zh added "画面" (visual/picture), wrong for a text diffusion model. |
| Start chatting now while Osaurus finishes setting up local AI. | Osaurus 完成本地 AI 设置时，您现在就可以开始聊天。 | Osaurus 正在完成本地 AI 设置，你现在就可以开始聊天。 | zh reads as "when setup completes" but en means "while setup is still in progress"; also uses 您. |
| SUCCESS: Authorized (Found %lld+ contacts) | 成功：已授权（找到 %lld 个联系人） | 成功：已授权（找到 %lld+ 个联系人） | Dropped the '+' after %lld, changing at-least count to exact count |
| The unreadable database is moved to ~/.osaurus/quarantine/ (never deleted) and a fresh, empty memory store is created so memory and search work again. Distilled facts and episodes in the old file stay in quarantine — export a plaintext backup first if you might recover the key. | 无法读取的数据库已被移动到 ~/.osaurus/quarantine/ 目录（不会被删除），并创建了一个全新的空内存存储，以便记忆和搜索功能再次正常工作。旧文件中的提炼事实和情节保留在隔离区——如果您可能需要恢复密钥，请先导出纯文本备份。 | 无法读取的数据库会被移至 ~/.osaurus/quarantine/（绝不会被删除），并创建一个全新的空记忆存储，以便记忆和搜索恢复正常。旧文件中的提炼事实和情景会保留在隔离区——如果你可能找回密钥，请先导出纯文本备份。 | future/behavior description rendered in past tense as if already done; episodes rendered with the banned 情节; uses 您 |
| Tight Fit | 紧凑适配 | 空间紧张 | 'Tight Fit' (model barely fits in memory) rendered as UI-layout-sounding '紧凑适配', inconsistent with sibling strings. |
| Transcript turn forgotten. | 转录已失效。 | 已忘记该转录回合。 | 'forgotten' (removed via Forget) mistranslated as 'expired/invalid'. |
| Turns reached memory, but distillation is skipping. | 已到记忆轮次上限，但蒸馏正在跳过。 | 回合已进入记忆，但蒸馏被跳过。 | Invents a 'limit reached' meaning absent from the English. |
| Unsupported local model type: hunyuan_v1_dense. Osaurus needs vmlx Hunyuan Dense support before this model can run locally. | 不支持的本地模型类型：hunyuan_v1_dense。Osaurus 需要 vmlx Hunyuan Dense 支持才能在此模型上本地运行。 | 不支持的本地模型类型：hunyuan_v1_dense。Osaurus 需要 vmlx Hunyuan Dense 支持后，此模型才能在本地运行。 | Rendered as "run locally on this model" instead of "this model can run locally". |
| Up to 48 runs/day · as often as every 5 min · no quiet hours. | 每天最多48次运行 · 每5分钟一次 · 无安静时段。 | 每天最多 48 次运行 · 最快每 5 分钟一次 · 无安静时段。 | "as often as every 5 min" (upper bound) rendered as a fixed "every 5 min". |
| View in Insights | 洞察视图 | 在洞察中查看 | Action "View in Insights" rendered as the noun phrase "Insights view". |
| Where Osaurus listens for client requests. Changes restart the server. | Osaurus监听客户端请求的地方。更改后需要重启服务器。 | Osaurus 监听客户端请求的位置。更改会重启服务器。 | EN states changes restart the server automatically; ZH implies the user must restart it manually. |
| Writes a plaintext copy of every database, attachment, and config under ~/.osaurus to a folder you choose. Recommended before reinstalling macOS or moving Macs. | 将~/.osaurus下的每个数据库、附件和配置的明文副本写入您选择的文件夹。建议在重新安装 macOS 或移动 Mac 之前使用。 | 将 ~/.osaurus 下每个数据库、附件和配置的明文副本写入你选择的文件夹。建议在重新安装 macOS 或更换 Mac 前进行。 | "moving Macs" means migrating to a new Mac, not physically moving one; also spacing and 您. |
| You were charged %@. | 您被收取了%@。 | 本次已扣费 %@。 | Awkward calque passive; also uses "您" and lacks spacing around placeholder. |
| Your private model is paused | 您的私有模型下载已暂停 | 你的私有模型已暂停 | Adds "download" not present in source, narrowing the meaning; uses 您. |
| %@ use direct networking. | %@ 使用直连网络 | %@ 使用直连网络。 | Trailing period dropped, inconsistent with the sibling proxy-endpoint string which keeps it. |
| %dm %ds left | 剩余 %dm %ds | 剩余 %d 分 %d 秒 | Keeps English unit suffixes m/s while the sibling key translates them to 分/秒. |
| %ds left | 剩余 %ds | 剩余 %d 秒 | Keeps English s suffix while sibling "%llds remaining" translates it to 秒. |
| %lld of %lld categorized | %2$lld 个中 %1$lld 个已分类 | 已分类 %1$lld / %2$lld 个 | Awkward inverted phrasing, inconsistent with the batch-wide "X / Y" pattern for count-of-total strings. |
| + Enter to save | + Enter 保存 | + 按 Enter 保存 | Sibling keys use the "+ 按 Enter …" pattern; this one drops "按", breaking consistency within the same hint-text family. |
| 1 document has no category | 1 个文档没有类别 | 1 个文档未设置分类 | Within the same KnowledgeView, "category" is rendered as 分类 in two sibling strings but 类别 here; unify. |
| Allow masked screenshots to reach a cloud model | 允许屏蔽敏感信息后的截图发送到云端模型。 | 允许屏蔽敏感信息后的截图发送到云端模型 | English is a period-less toggle label but zh adds a full stop, inconsistent with sibling toggle labels. |
| Azure often requires manual deployment IDs because /models may be unavailable. | Azure 通常需要手动部署 ID，因为 /models 可能不可用。 | Azure 通常需要手动填写部署 ID，因为 /models 可能不可用。 | "手动部署 ID" is parsed as 'manually deploy the ID'; needs 填写 to disambiguate that the IDs are manually entered. |
| Browser Use is off by default and only custom agents can use it. Open a custom agent's Subagents tab and flip on Browser Use — optionally with a dedicated model for browsing. Review or reset each agent's session in the new Browser settings tab. | 浏览器使用默认关闭，仅自定义智能体可使用。打开自定义智能体的「子智能体」标签页，开启浏览器使用 — 可选择专用浏览模型。在新建的浏览器设置标签页中查看或重置每个智能体的会话。 | 浏览器使用默认关闭，仅自定义智能体可使用。打开自定义智能体的“子智能体”标签页，开启浏览器使用 — 可选择专用浏览模型。在新增的“浏览器”设置标签页中查看或重置每个智能体的会话。 | Corner brackets vs curly quotes inconsistency; 新建的 misreads "new" (newly added in this release) as user-created; 智能体/代理 term drift. |
| Built-in sources that need no key. Always available as backup when no provider answers. | 无需密钥的内置来源。当没有提供商响应时始终可用作备选。 | 无需密钥的内置源。当没有提供商响应时始终可用作备选。 | 内置来源 vs 内置源 for the same concept on the same settings screen. |
| Bundle incomplete | 捆绑不完整 | 捆绑包不完整 | Sibling diagnostic string in ModelCompatibilityDiagnostics.swift; must align with 捆绑包完整 / 捆绑包不完整. |
| Checking runtime compatibility… | 检查运行时兼容性... | 正在检查运行时兼容性… | missing progressive marker used by sibling status strings, and ASCII '...' instead of the ellipsis character in en |
| Cloning base environment | 克隆基础环境 | 正在克隆基础环境 | progress status rendered without the progressive marker, reading like a command; siblings use 正在 |
| Could not create a secure login challenge | 无法创建安全登录验证。 | 无法创建安全登录验证 | Trailing full stop added where the English has none; sibling error titles have no period. |
| Describe the image... | 描述图片... | 描述图片… | Uses ASCII three dots while every other ellipsis in the batch uses the proper … character. |
| Diagnosing... | 诊断… | 正在诊断… | Progress label loses the progressive marker; sibling -ing strings all use 正在. |
| Encrypted %lld stores at rest. | 已加密 %lld 个存储。 | 已对 %lld 个存储启用静态加密。 | The at-rest qualifier is dropped though siblings consistently render it as 静态. |
| Encrypted 1 store at rest. | 已加密 1 个存储。 | 已对 1 个存储启用静态加密。 | Singular variant drops the at-rest qualifier as well. |
| Everything this agent can do — flip an ability and watch the startup context respond. | 此智能体能做的一切 — 翻转一项能力，观察启动上下文的响应。 | 此智能体能做的一切 — 切换一项能力，观察启动上下文的响应。 | agent must be 智能体; flip should be 切换 not 翻转 |
| Experimental: when the server eviction policy is Flexible (Multi Model) and memory projections say both fit, load the helper model alongside the chat model instead of unloading and reloading it — skipping the swap round-trip on high-RAM Macs. Tight RAM or the Strict policy always falls back to the normal handoff. | 实验性功能：当服务器驱逐策略设为「灵活（多模型）」且内存预测显示两个模型都能容纳时，将辅助模型与聊天模型并行加载，而非先卸载再重新加载——在大内存 Mac 上跳过换入换出的往返开销。内存紧张或采用严格策略时，始终回退至常规交接流程。 | 实验性功能：当服务器驱逐策略设为“灵活（多模型）”且内存预测显示两个模型都能容纳时，将辅助模型与聊天模型并行加载，而非先卸载再重新加载——在大内存 Mac 上跳过换入换出的往返开销。内存紧张或采用严格策略时，始终回退至常规交接流程。 | Corner brackets used for the policy name while the rest of the batch uses curly quotes. |
| Expose this agent to the public internet via a relay tunnel so external services can reach it. | 通过中继隧道将此智能体公开到公共互联网，以便外部服务能够访问它。 | 通过中继隧道将此智能体暴露到公网，以便外部服务能够访问它。 | Expose rendered as 公开 here but 暴露 elsewhere in the same feature family. |
| Extract credits | 提取积分 | 网页提取额度 | '提取积分' parses as the action 'withdraw points' instead of 'credits for the extract feature' |
| Image Only | 仅图像 | 仅图片 | 图像 conflicts with the dominant 图片 rendering of Image/Images/Image Generation in the same file and batch |
| Let the agent generate and edit images with a local model using the `image` tool. | 允许智能体使用本地模型，通过 image 工具生成和编辑图像。 | 允许智能体使用本地模型，通过 `image` 工具生成和编辑图像。 | Backticks around `image` dropped in zh; inconsistent with `tool_choice` row which keeps them. |
| Loading files… | 加载文件... | 正在加载文件… | Half-width dots instead of ellipsis and missing the 正在 pattern used by all sibling Loading strings. |
| Loading model card… | 加载模型卡片... | 正在加载模型卡片… | Same ellipsis/prefix inconsistency as Loading files…. |
| Local bundle ready | 本地捆绑包已就绪。 | 本地捆绑包已就绪 | Trailing period added to a status label that has none in English or in sibling labels. |
| Local handoff and RAM-safety for spawn jobs are system settings in Settings → Subagents. | 本地移交与生成任务的内存安全设置，属于系统设置，可在“设置 → 子智能体”中配置。 | 本地交接与生成任务的内存安全属于系统设置，可在“设置 → 子智能体”中配置。 | Footnote says 移交 but the section it points to is titled 交接; the reference must match the section title. |
| Maximum response tokens | 最大响应词元数 | 最大响应 Token 数 | Token rendered three ways (Token/令牌/词元) across sibling Max-Token settings strings. |
| min | 最小值 | 最小 | Paired min/max labels on the same row rendered inconsistently (最小值 vs 最大). |
| No agents yet — create one in the Agents tab | 还没有智能体 - 请在“智能体”标签页创建一个 | 还没有智能体 — 请在“智能体”标签页创建一个 | ASCII hyphen used where the batch consistently renders the em dash as “ — ”. |
| No installed plugin owns this capture capability. | 没有安装的插件拥有此捕获功能。 | 没有任何已安装的插件拥有此捕获能力。 | “没有安装的插件” can be parsed as “plugins that are not installed”, inverting the meaning; capability is better rendered 能力. |
| Pass an onClearChat handler to enable /clear | 传入 onClearChat 处理器以启用 /clear | 传入 onClearChat 处理程序以启用 /clear | "handler" rendered as 处理器 (processor) here but 处理程序 in the sibling string; inconsistent terminology in adjacent strings. |
| Paste text to test… | 粘贴文本进行测试... | 粘贴文本进行测试… | Trailing ellipsis rendered as ASCII "..." while the source uses the ellipsis character "…". |
| Read | 读 | 读取 | Standalone label '读' is inconsistent with the sibling copy that uses 读取/写入 for the Read/Write allowlists. |
| Remove "%@" from your custom tools? Agents will no longer be able to use its tools. | 从你的自定义工具中移除"%@"？智能体将无法再使用其工具。 | 从你的自定义工具中移除“%@”？智能体将无法再使用其工具。 | AI 'Agents' should be 智能体; straight quotes should be curly. |
| Remove Model | 删除模型 | 移除模型 | Remove is consistently 移除 elsewhere; 删除 conflates Remove with Delete on a destructive control. |
| Required for transcription | 转录需要 | 转录所需 | Reads truncated on its own; sibling strings in the same settings tab use the ……所需 pattern |
| Retry plugin load? | 重新加载插件？ | 重试加载插件？ | Loses the retry-after-failure meaning and breaks pairing with the 仍然重试 button |
| Rows the agent (or you) deleted would appear here, ready to restore. | 智能体（或你）删除的行会显示在此处，准备恢复。 | 智能体（或你）删除的行会显示在此处，随时可以恢复。 | agent should be 智能体 per glossary and file-internal consistency |
| Runs | 运行 | 运行记录 | Noun label for run history collides with the verb button Run→运行. |
| Sandbox enabled — container not running | 沙盒已启用 - 容器未运行 | 沙盒已启用 — 容器未运行 | Em dash degraded to hyphen-minus, inconsistent with sibling strings. |
| Sandbox is active — click to disable. Right-click for settings. | 沙盒处于活动状态 - 点击可禁用。右键打开设置。 | 沙盒处于活动状态 — 点击可禁用。右键打开设置。 | Same hyphen-for-em-dash degradation as sibling string. |
| Saved today; the request pipeline will start enforcing these in a follow-up. | 今日已保存；请求管道将在后续步骤中开始强制执行这些设置。 | 目前这些设置仅会被保存；请求管道将在后续更新中开始强制执行。 | "Saved today" means "for now these are only saved"; 今日已保存 reads as a dated timestamp, and 后续步骤 mistranslates "follow-up" (release) |
| Scanning… | 扫描… | 正在扫描… | Progressive-state label dropped 正在, inconsistent with sibling 正在扫描已安装的模型… and the 正在… pattern used batch-wide |
| Secret "%@" has no keychain id (expected name=keychain-id). | 密钥 "%@" 没有钥匙串 ID（期望 name=keychain-id）。 | 密钥“%@”没有钥匙串 ID（应为 name=keychain-id）。 | Straight ASCII quotes kept in zh where the library uses curly quotes; 期望 is stiff for "expected" |
| Send the bot a message (or add it to a group and post there), then load pending chats and senders. | 向机器人发送消息（或将其添加到群组并在那里发布），然后加载待处理的聊天和发送者。 | 向机器人发送消息（或将其添加到群组并在群里发言），然后加载待处理的聊天和发送者。 | '发布' misreads 'post there' (send a message in the group) as formal publishing |
| Share anonymous usage data to help improve Osaurus | 分享匿名使用数据以帮助改进 Osaurus | 共享匿名使用数据以帮助改进 Osaurus | Sibling toggle keys use 共享; this onboarding row uses 分享 for the same setting |
| Show fewer | 显示更少 | 收起 | Same collapse action as 'Show Less'=收起; 显示更少 inconsistent and stiff |
| Show less | 显示更少 | 收起 | Sibling key 'Show Less' uses 收起; 显示更少 is a stiff literal rendering |
| Starting host API bridge | 正在启动宿主 API 桥接 | 正在启动主机 API 桥接 | "host bridge" is rendered as 主机桥 elsewhere in this batch but 宿主…桥接 here; same component, inconsistent term. |
| SUCCESS: Process is trusted for Accessibility. | 成功：该进程已通过辅助功能验证。 | 成功：该进程已被授予辅助功能权限。 | trusted for Accessibility means granted Accessibility trust, not passed a verification. |
| Text-to-Speech | 文字转语音 | 文本转语音 | Same feature translated inconsistently (文字转语音 vs 文本转语音) within the batch. |
| The file isn't a readable database (corruption or a key mismatch). Reset to recreate it; the original is quarantined. | 该文件不是一个可读的数据库（可能已损坏或密钥不匹配）。请重置以重新创建它；原始文件已被隔离。 | 该文件不是可读的数据库（可能已损坏或密钥不匹配）。请重置以重新创建它；原始文件会被隔离。 | "is quarantined" (what Reset will do) rendered as already-done 已被隔离. |
| The link will stop working. Anyone trying to use it will be turned away. | 该链接将停止工作。任何尝试使用它的人将被拒绝访问。 | 该链接将失效。任何尝试使用它的人都将被拒绝访问。 | Anglicism 停止工作 for a link; sibling key uses the idiomatic 失效. |
| This is optional. Agents can still search and read these documents.<br><br>To let agents filter by category, move them into a folder (the folder name becomes the category) or add a `type:` line to their frontmatter.<br><br> | 此项为可选配置。即使不设置分类，智能体仍可搜索和读取这些文档。<br><br>若要让智能体按分类筛选，可将文档移入对应文件夹（文件夹名即为分类），或在文档的前置元数据中添加 `type:` 字段。 | 此项为可选配置。即使不设置分类，智能体仍可搜索和读取这些文档。<br><br>若要让智能体按分类筛选，可将文档移入对应文件夹（文件夹名即为分类），或在文档的前置元数据中添加 `type:` 字段。<br><br> | Trailing "\n\n" present in the source key was dropped in the translation. |
| This will remove '%@' and delete its API key from Keychain. | 这将移除「%@」并从钥匙串中删除其 API 密钥。 | 这将移除“%@”并从钥匙串中删除其 API 密钥。 | Corner brackets 「」 are nonstandard for zh-Hans and inconsistent with sibling strings using curly quotes. |
| Toast notifications are working! | 通知消息已生效！ | Toast 通知正常工作！ | Drops 'Toast' (sibling keeps it) and 'are working' drifts to 'has taken effect'. |
| Voice Detection: Disabled — Click to enable | 语音检测：已禁用 - 点击启用 | 语音检测：已禁用 — 点击启用 | EN em dash downgraded to a spaced hyphen, inconsistent with other strings in the batch that keep —. |
| Voice Detection: Listening — Click to disable | 语音检测：正在聆听 - 点击禁用 | 语音检测：正在聆听 — 点击禁用 | Same em-dash-to-hyphen downgrade as the sibling voice-detection strings. |
| Voice Detection: Ready — Click to disable | 语音检测：就绪 - 点击禁用 | 语音检测：就绪 — 点击禁用 | Same em-dash-to-hyphen downgrade as the sibling voice-detection strings. |
| Warming up — prefilling context… | 预热 — 填充上下文… | 预热 — 预填充上下文… | "prefilling" rendered as plain 填充, dropping the pre- sense and diverging from sibling string's 预填充. |
| Watched Folder | 监控文件夹 | 受监视的文件夹 | 监控 vs 监视 terminology split within the same Watchers feature; also reads as verb-object instead of the noun "folder being watched". |
| Your databases are not encrypted by Osaurus. macOS FileVault protects them at rest. | 您的数据库未被Osaurus加密。macOS FileVault在静止状态下保护它们。 | 你的数据库未由 Osaurus 加密。macOS FileVault 会在静态存储时保护它们。 | Missing CJK-Latin spacing around product names; inconsistent "at rest" terminology; uses 您. |
| Your wallet for Osaurus-routed services - add credits and track every request and top-up. | 用于Osaurus路由服务的钱包 - 添加积分并跟踪每个请求和充值。 | 你的 Osaurus 路由服务钱包 — 添加积分，并跟踪每笔请求与充值。 | Missing CJK-Latin spacing around "Osaurus"; awkward hyphen carried over. |
