# zh-hans-term-consistency — 170 changes

| English source | old zh-Hans | new zh-Hans | defect |
|---|---|---|---|
| %@ router balance. Click to open the wallet. | 路由器余额 %@。点击打开钱包。 | 路由余额 %@。点击打开钱包。 | "router" (model routing service) translated as hardware network router. |
| A bigger starting context means longer model warm-up and a slower first token. | 更大的起始上下文意味着更长的模型预热和更慢的首个 token。 | 更大的起始上下文意味着更长的模型预热和更慢的首个 Token。 | LLM-context "token" left in English; glossary requires 词元. |
| A regular or secret credential header is configured for this provider. | 为此提供程序配置了常规或秘密的凭证标头。 | 为此提供商配置了常规或保密的凭证标头。 | "provider" rendered 提供程序, deviating from majority term 提供商. |
| A stdio MCP provider needs a command before it can launch. | 一个 stdio MCP 提供程序需要一条命令才能启动。 | 一个 stdio MCP 提供商需要一条命令才能启动。 | "provider" rendered 提供程序 instead of majority term 提供商. |
| Action | 行动 | 操作 | "Action" rendered as 行动, inconsistent with 操作 used everywhere else in the app. |
| After each chat, the agent distills the conversation into a short summary. Episodes accumulate here so the agent can recall past sessions. | 每次聊天后，智能体会将对话提炼成简短的摘要。情节会在此累积，以便智能体回忆起过去的会话。 | 每次聊天后，智能体会将对话提炼成简短的摘要。情景会在此累积，以便智能体回忆起过去的会话。 | "Episodes" must be 情景 per glossary, not 情节. |
| Agent workspace root | 智能体工作空间根 | 智能体工作区根 | "workspace" rendered 工作空间 instead of glossary term 工作区. |
| All buffered turns have been distilled (or purged). The pipeline is healthy when episodes are growing. | 所有缓冲的对话轮次均已提炼（或清除）。当数据片段持续增长时，表明管道运行正常。 | 所有缓冲的对话轮次均已提炼（或清除）。当情景持续增长时，表明管道运行正常。 | "episodes" rendered as 数据片段 instead of the glossary term 情景. |
| Already have a provider? Connect it | 已有服务商？连接它 | 已有提供商？连接它 | "provider" must be 提供商 per glossary; 服务商 deviates. |
| App allowlist | 应用白名单 | 应用允许列表 | "Allowlist" is rendered 允许列表 elsewhere in this batch but 白名单 here; same concept in the same Computer Use settings section should use one term. |
| App name (e.g. Mail) | 应用名称（例如邮件） | 应用名称（例如“邮件”） | Mail is the app name; library convention quotes system app names (“邮件”), and unquoted 邮件 reads as the common noun. |
| Apple Silicon is required | Apple 硅芯片是必需的 | 需要 Apple Silicon | "Apple Silicon" is a brand name and should not be literally translated as 硅芯片. |
| AppleScript runs on this Mac. The first time the agent controls an app, macOS asks you to allow Automation for Osaurus. Download AppleScript models in Settings → Computer Use → Models. | AppleScript 在此 Mac 上运行。当智能体首次控制某个应用时，macOS 会要求你允许 Osaurus 的自动化权限。请在「设置 → 电脑使用 → 模型」中下载 AppleScript 模型。 | AppleScript 在此 Mac 上运行。当智能体首次控制某个应用时，macOS 会要求你允许 Osaurus 的自动化权限。请在「设置 → 电脑操作 → 模型」中下载 AppleScript 模型。 | "Computer Use" is rendered 电脑使用 here but 电脑操作 in the adjacent string; feature name must be consistent. |
| Auth required | 需要授权 | 需要身份验证 | "Auth" here is authentication (cf. sibling key 身份验证); 授权 means authorization. |
| Backfill history | 补全历史 | 回填历史 | Inconsistent with 回填 used for every other 'Backfill' string in the same view. |
| Batch this many tokens before sending an SSE chunk to the client. | 在向客户端发送 SSE 数据块之前，先按此数量批量累积 token。 | 在向客户端发送 SSE 数据块之前，先按此数量批量累积 Token。 | LLM 'tokens' should be 词元 per glossary. |
| BatchEngine max batch size. 1 keeps the compile fast-path engaged; >1 enables continuous batching. | 批量引擎最大批处理大小。设为 1 可保持编译快速路径启用；大于 1 则启用连续批处理。 | BatchEngine 最大批处理大小。设为 1 可保持编译快速路径启用；大于 1 则启用连续批处理。 | 'BatchEngine' is a code/component name and should not be translated. |
| Benchmark proof is not meaningful until the runtime blocker is resolved. | 基准证明在运行时阻塞问题解决之前是没有意义的。 | 在运行时阻塞问题解决之前，基准验证没有意义。 | 'Benchmark proof' translated two different ways across related strings. |
| Blank = engine default | 空白 = 引擎默认值 | 留空 = 引擎默认值 | 空白 deviates from the majority 留空 rendering of 'Blank'. |
| Blank = model default (48) | 空白 = 模型默认值（48） | 留空 = 模型默认值（48） | 空白 deviates from the majority 留空 rendering of 'Blank'. |
| Block Size (tokens) | 块大小（token 数） | 块大小（Token 数） | 'tokens' in KV-cache context should be 词元; 块 for Block is correct here. |
| Body SHA-256 | 正文 SHA-256 | 请求体 SHA-256 | In the billing ledger this 'Body' is the HTTP request body (sibling key Body Template = 请求体模板); 正文 suggests message text instead. |
| Click to make this a secret value | 点击以将其设为密钥值 | 点击以将其设为保密值 | 'secret value' means a masked/confidential value, not a cryptographic key; 密钥值 is misleading |
| Client Secret | Client 密钥 | 客户端密钥 | OAuth 'Client Secret' is conventionally 客户端密钥; half-translated form is nonstandard |
| Codec | 编码器 | 编解码器 | Codec should be 编解码器 (as in the sibling string), 编码器 means only 'encoder' |
| Connect a provider | 连接服务商 | 连接提供商 | provider rendered 服务商, deviating from majority term 提供商. |
| Connecting... | 正在连接... | 连接中… | Same status string translated two ways (正在连接... vs 连接中…) with ASCII dots retained; should unify. |
| Consolidation Interval | 合并间隔 | 整合间隔 | Consolidation rendered 合并 here but 整合 in the sibling string; inconsistent. |
| Context budget: %@ tokens | 上下文预算：%@ tokens | 上下文预算：%@ Token | LLM "tokens" left in English instead of glossary term 词元. |
| Context window for remote models | 远程模型的上下文长度 | 远程模型的上下文窗口 | "context window" rendered as 上下文长度, inconsistent with sibling strings using 窗口 and blurring the distinction from Context limit. |
| Conversation history, pinned facts, and episode summaries. | 对话历史、置顶事实和会话摘要。 | 对话历史、置顶事实和情景摘要。 | episode rendered 会话 (session) instead of glossary term 情景. |
| Copy Response | 复制回复 | 复制响应 | In the Insights request/response pane, Response means API response; 回复 reads as chat reply and breaks the 请求/响应 pairing. |
| Copy the probe result and check the provider logs. | 复制探测结果并检查提供者日志。 | 复制探测结果并检查提供商日志。 | provider should be 提供商 per glossary, not 提供者 |
| Couldn't reach this model on Hugging Face. The repo may be private, gated, removed, or temporarily unreachable. Adding a Hugging Face token from the Catalog tab helps with gated repos and rate limits. | 无法在 Hugging Face 上访问此模型。该存储库可能是私有的、受限的、已删除或暂时无法访问。在“目录”标签页中添加 Hugging Face 令牌有助于访问受限存储库并缓解速率限制。 | 无法在 Hugging Face 上访问此模型。该仓库可能是私有的、受限的、已删除或暂时无法访问。在“目录”标签页中添加 Hugging Face 令牌有助于访问受限仓库并缓解速率限制。 | repo should be 仓库 per glossary, not 存储库 |
| Create a new secret key | 创建一个新的密钥 | 创建一个新的 Secret key | secret key vs API key collapse into the same Chinese term, losing the distinction between two different console entries. |
| Credits | 信用 | 积分 | glossary mandates credits→积分; 信用 is explicitly banned |
| Custom JSON channel `%@` is configured, but custom HTTP execution is not enabled yet. | 自定义 JSON 通道 `%@` 已配置，但尚未启用自定义 HTTP 执行。 | 自定义 JSON 频道 `%@` 已配置，但尚未启用自定义 HTTP 执行。 | channel is 频道 elsewhere in agent-channel strings; 通道 is inconsistent |
| Days episodes are kept before pruning. 0 keeps them forever | 剧集在被清理前保留的天数。设为 0 则永久保留。 | 情景在被清理前保留的天数。设为 0 则永久保留。 | "episodes" here means memory episodes (MemoryView), not TV episodes; glossary mandates 情景. |
| Default recent-message count for channel/thread reads. Clamped to 1-100. | 频道/线程读取的默认最近消息数。限制在 1-100 之间。 | 频道/子区读取的默认最近消息数。限制在 1-100 之间。 | Discord's official zh-CN term for thread is 子区; 线程 reads as a technical thread in this Discord-only string. |
| Delete Provider? | 删除供应商？ | 删除提供商？ | Glossary maps provider→提供商; this key uses 供应商, inconsistent with sibling strings. |
| Denoising steps | 去噪步骤 | 去噪步数 | "steps" is a numeric step count; sibling key uses 步数, this one uses 步骤. |
| Direct | 直接 | 直连 | "Direct" describes a request transport mode; the standard zh network term is 直连, while bare 直接 is semantically dangling as a label. |
| Dispatch to an agent is turned off. Enable it and pick an agent in the channel settings. | 分发到智能体已关闭。在频道设置中启用并选择一个智能体。 | 分派到智能体已关闭。请在频道设置中启用并选择一个智能体。 | Inconsistent rendering of 'dispatch' (分发 vs 分派) for the same feature. |
| Distillation is failing before writing episodes. | 蒸馏在写入片段之前失败。 | 蒸馏在写入情景之前失败。 | Glossary requires Episode→情景; translation uses 片段. |
| Distillation ran but produced no usable episode. | 蒸馏已运行但未产生可用片段。 | 蒸馏已运行但未产生可用情景。 | Glossary requires Episode→情景; translation uses 片段. |
| Draft message | 草稿信息 | 起草消息 | Inconsistent with sibling strings that translate "message" as 消息. |
| Draft tokens with a fast helper model and verify with the main model in a single step. Engaged per request when the model supports it. | 使用快速辅助模型生成草案 token，并由主模型在单步中校验。模型支持时按请求启用。 | 使用快速辅助模型生成草案 Token，并由主模型在单步中校验。模型支持时按请求启用。 | LLM-context "token" must be 词元 per glossary. |
| Drop tokens less likely than P × the top token. | 丢弃概率低于（顶部 token 概率 × P）的 token。 | 丢弃概率低于（顶部 Token 概率 × P）的 Token。 | LLM-context "token" must be 词元 per glossary. |
| Edit the provider and enter the executable. | 编辑提供者并输入可执行文件。 | 编辑提供商并输入可执行文件。 | Glossary requires provider→提供商; translation uses 提供者. |
| Edit the provider and save an API key or secret Authorization header. | 编辑该提供程序并保存 API 密钥或秘密的授权标头。 | 编辑该提供商并保存 API 密钥或机密 Authorization 标头。 | provider→提供商 per glossary; also keep "Authorization" as the literal header name. |
| Empty — Computer Use is allowed in any app. | 空 — 任何应用中都允许使用计算机。 | 留空 — 任何应用中都允许使用计算机。 | 'Empty' (leave the allowlist blank) rendered as bare 空, inconsistent with the established 留空 convention. |
| Enable the provider before testing or selecting its models. | 在测试或选择其模型之前，请先启用该提供程序。 | 在测试或选择其模型之前，请先启用该提供商。 | provider should be 提供商 per glossary, not 提供程序 |
| Episode disabled. | 剧集已禁用。 | 情景已禁用。 | Episode must be 情景, 剧集 (TV episode) is wrong |
| Episode forgotten. | 剧集已遗忘。 | 情景已遗忘。 | Episode must be 情景, not 剧集 |
| Episode Retention | 情节保留 | 情景保留 | Episode must be 情景 per glossary, not 情节 |
| Episode was not found. | 未找到该集。 | 未找到该情景。 | Episode must be 情景, 该集 deviates |
| Episode: %@. %@, %@ | 片段：%@。%@，%@ | 情景：%@。%@，%@ | Episode must be 情景, not 片段 |
| Episodes | 情节 | 情景 | Episodes must be 情景 per glossary |
| Fetches the signed router /models endpoint and hides stale prices. | 获取已签名的路由器 /models 端点并隐藏过时的价格。 | 获取路由服务已签名的 /models 端点，并隐藏过时的价格。 | 'router' is the model-routing service, not a hardware network router; 路由器 misleads |
| Generate a new 256-bit key and re-encrypt every artifact. The old key is destroyed. | 生成一个新的256位密钥，并重新加密所有文件。旧密钥将被销毁。 | 生成一个新的 256 位密钥，并重新加密所有制品。旧密钥将被销毁。 | artifact→文件 here vs 制品 in the sibling key; inconsistent terminology |
| Generative Greetings | 生成问候 | 生成式问候 | 'Generative' should be 生成式; current title reads as an imperative action |
| History, facts & episodes | 历史、事实和片段 | 历史、事实与情景 | 'episodes' should be 情景 per glossary, not 片段. |
| How many prompt tokens are prefilled per step. | 每一步预填充的提示 token 数量。 | 每一步预填充的提示 Token 数量。 | LLM 'tokens' should be 词元 per glossary. |
| How many tokens the draft model proposes before the main model verifies. | 主模型校验前，草案模型先提议的 token 数量。 | 主模型校验前，草案模型先提议的 Token 数量。 | LLM 'tokens' should be 词元 per glossary. |
| Hugging Face responded with %@. For a gated or private repo, add a Hugging Face access token from the Catalog tab; otherwise try again in a moment. | Hugging Face 返回了 %@。对于受限或私有存储库，请在“目录”标签页中添加 Hugging Face 访问令牌；否则请稍后再试。 | Hugging Face 返回了 %@。对于受限或私有仓库，请在“目录”标签页中添加 Hugging Face 访问令牌；否则请稍后再试。 | 'repo' should be 仓库 per glossary, not 存储库. |
| Image generation and editing models live in Images settings. | 图像生成和编辑模型位于「图像」设置中。 | 图片生成和编辑模型位于“图片”设置中。 | References the Images tab which is translated 图片 elsewhere; 图像 here breaks navigation consistency |
| Inferences | 推断 | 推理 | LLM inference is 推理 (cf. 'Inference Details'→推理详情); 推断 means deduction |
| Invalid response from provider | 来自提供商的无效回复 | 提供商返回的响应无效 | 'response' here is an HTTP/API response; standard term is 响应, not 回复. |
| Key Required | 需要Key | 需要密钥 | 'Key' left untranslated; repo majority uses 密钥. |
| Keychain key: not found | 钥匙串钥匙：未找到 | 钥匙串密钥：未找到 | Encryption 'key' should be 密钥, not 钥匙. |
| Keychain key: present | 钥匙串钥匙：存在 | 钥匙串密钥：存在 | Encryption 'key' should be 密钥, not 钥匙. |
| Latest distillation produced no usable episode. | 最新蒸馏未产生可用片段。 | 最新蒸馏未产生可用情景。 | Glossary maps 'episode' to 情景, not 片段. |
| Lower = focused. Higher = creative. 0 picks the single most-likely token. | 数值越低，输出越专注；数值越高，越具创造性。设为 0 则始终选取概率最高的单个 token。 | 数值越低，输出越专注；数值越高，越具创造性。设为 0 则始终选取概率最高的单个 Token。 | LLM-sampling token should be 词元 per glossary. |
| Max output tokens per subagent | 每个子智能体的最大输出令牌数 | 每个子智能体的最大输出 Token 数 | LLM output tokens mistranslated as 令牌 (auth token); should be 词元. |
| MCP Server Hub diagnostics | MCP Server Hub 诊断 | MCP 服务器中心诊断 | "MCP Server Hub" is translated as "MCP 服务器中心" elsewhere; keep consistent. |
| Model downloads use your account's higher rate limits and gated-repo access. | 模型下载将使用您账户更高的速率限制和受限存储库访问权限。 | 模型下载会使用你账户更高的速率限制和受限仓库访问权限。 | repo should be 仓库 per glossary; uses 您 |
| No agents to grant yet. Create an agent, then enable Knowledge for it in its Features section. | 暂无可授予的智能体。请先创建智能体，然后在其“特性”部分中为其启用知识。 | 暂无可授予的智能体。请先创建智能体，然后在其“功能”部分中为其启用知识。 | "Features" rendered 特性 here but 功能 elsewhere; inconsistent UI navigation term. |
| No buffered turns and no episodes — check per-agent memory. | 没有缓冲的对话轮次，也没有片段——请检查每个智能体的记忆。 | 没有缓冲的对话轮次，也没有情景——请检查每个智能体的记忆。 | episodes should be 情景 per glossary, not 片段. |
| No episodes yet | 还没有情节 | 还没有情景 | Glossary requires Episode→情景; 情节 is explicitly banned. |
| No live tool-call proof is recorded for this exact bundle yet. | 此特定包尚未记录实时工具调用验证。 | 此特定捆绑包尚未记录实时工具调用证明。 | proof rendered 验证 here but 证明 in sibling strings (lines 105/111); bundle rendered 包 here but 捆绑包 at line 106. |
| No OAuth tokens are saved for this provider. | 没有为此提供者保存OAuth令牌。 | 没有为此提供商保存 OAuth 令牌。 | provider should be 提供商 per glossary; also fixes missing CJK-Latin spacing. |
| No prompt | 无提示 | 无提示词 | "无提示" ambiguous; sibling key uses 提示词 |
| No providers to reorder. | 没有可重新排序的供应商。 | 没有可重新排序的提供商。 | provider should be 提供商 per glossary, not 供应商 |
| No request captured for this row | 没有捕获该行的请求 | 未捕获此行的请求 | Same pane as line 881; negation style (没有捕获 vs 未捕获) inconsistent within one detail pane. |
| No response body captured | 没有捕获响应体 | 未捕获响应正文 | Adjacent sibling at line 881 uses 未捕获请求正文; this one at line 883 uses 没有捕获响应体 — same panel, inconsistent rendering of 'body' and negation. |
| No xAI OAuth tokens are saved for this provider. | 没有为此提供者保存 xAI OAuth 令牌。 | 没有为此提供商保存 xAI OAuth 令牌。 | provider should be 提供商, not 提供者 |
| Not enough free disk space for cold provisioning | 冷启动配置所需空闲磁盘空间不足 | 冷预配所需的可用磁盘空间不足 | "cold provisioning" rendered as "cold-start configuration"; inconsistent with 预配 |
| Not provisioned | 未配置 | 未预配 | "未配置" collides with "Not configured"; sibling key uses 未预配 |
| of the model's ~%@ token window (%@) | 占模型约 %1$@ token 窗口的 %2$@ | 占模型约 %1$@ Token 窗口的 %2$@ | LLM-context "token" left untranslated; glossary requires 词元. |
| On Device | 设备上 | 设备端 | "设备上" awkward as a label; sibling uses 设备端 |
| Only Accepted Tokens Enter Base Cache | 仅接受的 token 进入基础缓存 | 仅已接受的 Token 进入基础缓存 | LLM-context token should be 词元 per glossary. |
| Only consider the K most-likely tokens per step. | 每步仅考虑概率最高的 K 个 token。 | 每步仅考虑概率最高的 K 个 Token。 | Sampling tokens are LLM tokens; use 词元 per glossary. |
| Osaurus couldn't connect to a model just now. Retry the connection, run a private model on this Mac, or use your own provider. | Osaurus 暂时无法连接模型。请重试连接、在这台 Mac 上运行私有模型，或使用你自己的服务商。 | Osaurus 暂时无法连接模型。请重试连接、在这台 Mac 上运行私有模型，或使用你自己的提供商。 | Uses 服务商 for provider while the corpus standard is 提供商 (lines 36, 110, 124). |
| Osaurus Router is off | Osaurus 路由器已关闭 | Osaurus 路由已关闭 | Inconsistent with sibling key rendering "Osaurus Router" as Osaurus 路由 in the same view. |
| Permanently delete identity, pinned facts, episodes, and conversation history. | 永久删除身份、固定事实、情节和对话历史。 | 永久删除身份、固定事实、情景和对话历史。 | "episodes" must be 情景 per glossary, not 情节. |
| Pick from the smallest set of tokens whose probabilities sum to P. | 从概率总和达到 P 的最小 token 集合中进行选取。 | 从概率总和达到 P 的最小 Token 集合中进行选取。 | LLM "tokens" left in English; glossary requires 词元. |
| README | 自述 | README | README is a conventional file name usually kept untranslated; 自述 alone is nonstandard. |
| Recent distillation attempts are failing. Check Recent Activity for the error details. | 最近的蒸馏尝试都失败了。检查近期活动以了解错误详情。 | 最近的蒸馏尝试都失败了。检查“最近活动”以了解错误详情。 | References the 'Recent Activity' section translated as 最近活动 in the same view; 近期活动 breaks the cross-reference. |
| Remove from allowlist | 从白名单中移除 | 从允许列表中移除 | 'allowlist' is rendered 允许列表 elsewhere; 白名单 diverges. |
| Remove model? | 删除模型？ | 移除模型？ | Remove is consistently 移除 elsewhere in this batch; 删除 conflates with Delete and implies data destruction |
| Removes this entry from the list. | 从列表中删除此条目。 | 从列表中移除此条目。 | Same Remove/删除 inconsistency as above |
| Reorder providers | 重新排序供应商 | 重新排序提供商 | provider should be 提供商 per glossary |
| Reorder Providers | 重新排序供应商 | 重新排序提供商 | provider should be 提供商 per glossary |
| Repository unavailable | 存储库不可用 | 仓库不可用 | repository should be 仓库 per glossary; 存储库 deviates |
| Responses endpoint with streaming support | 支持流式输出的响应端点 | 支持流式输出的 Responses 端点 | 'Responses' is the API endpoint name and should stay in English |
| Reusable prompt shortcuts invoked by typing / in the chat input | 通过在聊天输入框中输入 / 调用的可重复使用提示词快捷指令 | 在聊天输入框中输入 / 即可调用的可复用提示词快捷指令 | Reusable rendered 可重复使用 here but 可复用 elsewhere in the batch; long attributive pile-up. |
| Reuse cached prompt prefixes across requests for faster TTFT. When off, GPU and disk reuse are also disabled. | 跨请求重用缓存的提示前缀，以缩短首 token 生成时间 (TTFT)。关闭时，GPU 和磁盘重用也将被禁用。 | 跨请求重用缓存的提示前缀，以缩短首个 Token 生成时间（TTFT）。关闭时，GPU 和磁盘重用也将被禁用。 | LLM-context token left untranslated; glossary requires 词元 |
| Reveal this agent's sandbox home folder in Finder. | 在访达中显示此智能体的沙盒主目录。 | 在 Finder 中显示此智能体的沙盒主目录。 | Finder rendered as 访达, inconsistent with majority 在 Finder 中显示 |
| Run sandbox provisioning on an Apple Silicon Mac. | 在 Apple 硅芯片 Mac 上运行沙盒配置。 | 在搭载 Apple 芯片的 Mac 上运行沙盒配置。 | Apple Silicon rendered as nonstandard Apple 硅芯片 |
| Running AppleScript that controls another app needs macOS Automation permission. The first time an agent controls an app, macOS asks you to allow it for Osaurus. You can prime the System Events grant now. | 运行控制其他应用的 AppleScript 需要 macOS 自动化权限。当智能体首次控制某个应用时，macOS 会要求你允许 Osaurus 对其进行控制。你可以现在预先授予系统事件权限。 | 运行控制其他应用的 AppleScript 需要 macOS 自动化权限。当智能体首次控制某个应用时，macOS 会要求你允许 Osaurus 对其进行控制。你可以现在预先授予 System Events 权限。 | System Events is a process name and should stay untranslated |
| Sandboxed MCP servers require macOS 26 or later and will fail to start on this Mac. Choose Host to run this provider — note it will then run without sandbox protection. | 沙盒 MCP 服务器需要 macOS 26 或更高版本，在这台 Mac 上将无法启动。选择“主机”来运行此提供方 — 注意它将在没有沙盒保护的情况下运行。 | 沙盒 MCP 服务器需要 macOS 26 或更高版本，在这台 Mac 上将无法启动。选择“主机”来运行此提供商 — 注意它将在没有沙盒保护的情况下运行。 | "provider" should be 提供商 per glossary, not 提供方 |
| Schedule Info | 调度信息 | 计划信息 | 调度 conflicts with 计划 used for Schedule in the same view |
| Scheduled | 已排程 | 已计划 | 排程 is a Traditional-Chinese usage; library majority uses 计划 for Schedule |
| Schedules | 日程 | 计划任务 | 日程 suggests calendar agenda; sibling keys use 计划/计划任务 for the same feature |
| Schedules & watchers | 调度和监视器 | 计划任务和监视器 | Sibling key translates Schedules as 计划任务; 调度 is inconsistent |
| Scheduling | 安排 | 计划 | Section header 安排 is vague and breaks the 计划 terminology used across the Schedule family |
| Shared workspace | 共享工作空间 | 共享工作区 | workspace should be 工作区 per glossary, not 工作空间 |
| Shows exact tool exposure states, token estimates, and export | 显示精确的工具暴露状态、token 估算和导出 | 显示精确的工具暴露状态、Token 估算和导出 | LLM-context 'token' should be 词元 per glossary |
| Silence Timeout | 静音超时 | 静默超时 | "Silence" here means absence of speech (静默), not mute (静音); the current rendering points to the wrong concept in a voice-transcription setting. |
| Speak Tool | 说话工具 | 朗读工具 | Feature reads replies aloud; sibling strings use 朗读, so 说话工具 is inconsistent and vague. |
| Stable id used by agent_channel tools. Native provider ids are reserved. | agent_channel 工具使用的稳定 ID。本地提供者 ID 已保留。 | agent_channel 工具使用的稳定 ID。原生提供商 ID 已被保留。 | "provider" should be 提供商 per glossary; "native" rendered as 本地 (local) rather than 原生. |
| Start on free Osaurus Cloud credits — you can download a model anytime later. | 先使用免费的 Osaurus Cloud 额度——之后可随时下载模型。 | 先使用免费的 Osaurus Cloud 积分——之后可随时下载模型。 | Product "credits" should be 积分 per glossary, not 额度. |
| Stdio providers launch a local subprocess instead of sending HTTP traffic through URLSession. | Stdio 提供程序会启动本地子进程，而不是通过 URLSession 发送 HTTP 流量。 | Stdio 提供商会启动本地子进程，而不是通过 URLSession 发送 HTTP 流量。 | 'provider' should be 提供商 per glossary; 提供程序 deviates. |
| Stop the sandbox, remove %@, and start the sandbox again. | 停止沙箱，移除%@，然后重新启动沙箱。 | 停止沙盒，移除 %@，然后重新启动沙盒。 | 'sandbox' should be 沙盒 per glossary; also missing spaces around %@. |
| Switch to Host for trusted tools or start the sandbox runtime. | 切换到主机以使用受信任的工具或启动沙箱运行时。 | 切换到主机以使用受信任的工具，或启动沙盒运行时。 | 'sandbox' should be 沙盒 per glossary. |
| The model ran but returned no usable episode for at least one session. | 模型已运行但至少一个会话未返回可用片段。 | 模型已运行，但至少有一个会话未返回可用情景。 | episode rendered as 片段 instead of the glossary term 情景 |
| The plugin's `osr_host_api` mirror struct does not match the host's v6 layout — most often the v5 `log_structured` slot is skipped, which shifts every later slot by 8 bytes. The plugin then dispatches `host->free_string` to the wrong host trampoline and `libc free()` aborts on a non-malloc pointer, killing the host. See `docs/plugins/HOST_API.md → Mirror Struct Audit` and `docs/plugins/ABI_VERSIONS.md` for the pinned offsets and the documented v1..v6 evolution. | 插件的 `osr_host_api` 镜像结构体与主机的 v6 布局不匹配——最常见的是跳过了 v5 的 `log_structured` 槽位，导致之后的每个槽位都偏移了 8 个字节。随后插件会将 `host->free_string` 分派到错误的主机跳板，`libc free()` 在一个非 malloc 指针上中止，从而导致主机崩溃。有关固定偏移量以及记录在案的 v1..v6 演进，请参阅 `docs/plugins/HOST_API.md → Mirror Struct Audit` 和 `docs/plugins/ABI_VERSIONS.md`。 | 插件的 `osr_host_api` 镜像结构体与宿主的 v6 布局不匹配——最常见的是跳过了 v5 的 `log_structured` 槽位，导致之后的每个槽位都偏移了 8 个字节。随后插件会将 `host->free_string` 分派到错误的宿主跳板，`libc free()` 在一个非 malloc 指针上中止，从而导致宿主崩溃。有关固定偏移量以及记录在案的 v1..v6 演进，请参阅 `docs/plugins/HOST_API.md → Mirror Struct Audit` 和 `docs/plugins/ABI_VERSIONS.md`。 | "host" rendered 主机 here but 宿主 in sibling plugin strings in the same view; inconsistent within the family. |
| The provider is configured but no tools are registered yet. | 提供者已配置，但尚未注册任何工具。 | 提供商已配置，但尚未注册任何工具。 | provider rendered as 提供者 instead of 提供商 |
| The sandbox image and Containerization runtime are supported on Apple Silicon. | Apple 硅芯片支持沙盒映像和容器化运行时。 | Apple 芯片支持沙盒映像和 Containerization 运行时。 | Apple Silicon should be Apple's official 「Apple 芯片」; Containerization is a framework name |
| The setupComplete flag is false, so tool and agent startup still require provisioning. | 设置完成标志为false，因此工具和智能体启动仍需要配置。 | setupComplete 标志为 false，因此工具和智能体的启动仍需要完成配置。 | code identifier setupComplete translated away; missing spacing around false |
| The stdio provider is missing a command. | stdio 提供者缺少一个命令。 | stdio 提供商缺少命令。 | provider rendered as 提供者; article "a" literally translated |
| The token or secret header is stored outside plain provider config. | 令牌或密钥头存储在明文提供者配置之外。 | 令牌或密钥标头存储在明文提供商配置之外。 | provider rendered as 提供者 instead of 提供商 |
| This will permanently delete your identity, all pinned facts, episodes, and conversation history. This cannot be undone. | 这将永久删除您的身份、所有固定的事实、剧集和对话历史记录。此操作无法撤销。 | 这将永久删除你的身份、所有固定的事实、情景和对话历史记录。此操作无法撤销。 | 'episodes' mistranslated as TV-series '剧集'; glossary requires '情景'. |
| Tokens Per Chunk | 每块令牌数 | 每块 Token 数 | LLM 'tokens' rendered as auth-token '令牌' instead of '词元'. |
| Tokens per paged block. | 每个分页块包含的 token 数。 | 每个分页块包含的 Token 数。 | LLM 'tokens' left as English 'token' instead of glossary '词元'. |
| Too Large | 太大 | 过大 | '太大' inconsistent with sibling badge strings using '过大'. |
| Tools from installed plugins and connected providers | 已安装插件和连接提供者的工具 | 来自已安装插件和已连接提供商的工具 | 'providers' rendered as '提供者' instead of glossary '提供商'. |
| Transcribed text will appear here... | 转录的文本将显示在此处... | 转写的文本将显示在此处... | '转录' inconsistent with '转写' used throughout the same settings tab. |
| Transcript turn was not found. | 未找到该转录记录。 | 未找到该转录回合。 | 'turn' rendered '记录', inconsistent with the corrected '转录回合' family. |
| Transcription Behavior | 转录行为 | 转写行为 | 'Transcription' inconsistently rendered '转录' where siblings use '转写'. |
| Try a different term, like “hotkey” or “transcription”. | 尝试其他术语，如“快捷键”或“转录”。 | 尝试其他术语，如“快捷键”或“转写”。 | Search-term example '转录' won't match the actual UI label '转写'. |
| Unknown tab | 未知标签页 | 未知选项卡 | Settings tab rendered as browser-style 标签页; library majority uses 选项卡. |
| Update with a curator | 使用维护者更新 | 使用策展人更新 | "curator" (knowledge-curation role) rendered as 维护者 (maintainer), a meaning shift. |
| URL or repository | URL或存储库 | URL 或仓库 | Glossary: repository→仓库, not 存储库; also missing space after URL. |
| Use Test to launch initialize/listTools and record a health snapshot. | 使用“测试”来启动 初始化/工具列表，并记录健康快照。 | 使用“测试”来启动 initialize/listTools，并记录健康快照。 | initialize/listTools are MCP method names and must stay untranslated; stray space. |
| Use Test to run HTTP/SSE initialize/listTools and record a health snapshot. | 使用测试运行 HTTP/SSE 初始化/工具列表 并记录健康快照。 | 使用“测试”运行 HTTP/SSE initialize/listTools 并记录健康快照。 | initialize/listTools are MCP method names and must stay untranslated; stray space in output. |
| Using pattern rules only | 仅使用正则规则 | 仅使用模式规则 | "pattern rules" rendered as 正则规则 (regex rules), inconsistent with sibling string 模式规则 in the same PrivacyView. |
| View All %lld Episodes | 查看全部 %lld 个情节 | 查看全部 %lld 个情景 | Glossary: Episode→情景, not 情节. |
| Warming up — loading model… | 热身 — 加载模型… | 预热 — 正在加载模型… | Sibling keys translate "Warming up" as 预热; 热身 deviates from majority usage. |
| Warming up — prefilling context %lld%% (%lld/1 token) | 预热中 — 预填充上下文 %lld%%（%lld/1 token） | 预热中 — 预填充上下文 %1$lld%%（%2$lld/1 Token） | LLM-context "token" left in English; sibling key uses 词元. |
| When you add credits or use an Osaurus Router model, it shows up here with its amount. If this Mac made a request, you can jump to the chat or Insights. | 当您添加积分或使用Osaurus路由器模型时，它会连同金额显示在这里。如果这台 Mac 提出了请求，您可以跳转到聊天或 Insights。 | 当你添加积分或使用 Osaurus Router 模型时，它会连同金额显示在这里。如果这台 Mac 发出过请求，你可以跳转到对应聊天或 Insights。 | "Osaurus Router" is a product name and should stay untranslated; also spacing and 您. |
| Workspace | 工作空间 | 工作区 | Glossary/majority usage is 工作区, not 工作空间. |
| Workspace mount | 工作空间挂载 | 工作区挂载 | Glossary/majority usage is 工作区, not 工作空间. |
| %.1f tok/s | %.1f 词元/秒 | %.1f Token/秒 |  |
| %lld tokens | %lld 个词元 | %lld 个 Token |  |
| ~%lld tokens | 约 %lld 个词元 | 约 %lld 个 Token |  |
| Catalog: ~%lld, Full: ~%lld tokens | 目录：~%1$lld，完整：~%2$lld 个词元 | 目录：~%1$lld，完整：~%2$lld 个 Token |  |
| Input tokens | 输入词元 | 输入 Token |  |
| Maximum cached tokens per chat slot for this memory mode. | 此记忆模式下每个聊天槽的最大缓存词元数。 | 此记忆模式下每个聊天槽的最大缓存 Token 数。 |  |
| No local benchmark proof is recorded here yet. A passing row needs visible output, token/s, RAM status, cancellation, and cache evidence. | 这里尚未记录本地基准测试证明。通过的行需要可见的输出、词元/秒、RAM 状态、取消操作以及缓存证据。 | 这里尚未记录本地基准测试证明。通过的行需要可见的输出、Token/秒、RAM 状态、取消操作以及缓存证据。 |  |
| Output tokens | 输出词元 | 输出 Token |  |
| Per-Session KV Cap (tokens) | 每会话KV限制（词元数） | 每会话KV限制（Token 数） | Missing spaces around "KV". |
| Token usage | 词元使用量 | Token 使用量 |  |
| Tokens | 词元 | Token |  |
| tokens %lld | 词元 %lld | Token %lld |  |
| Tokens of memory context injected per turn | 每轮注入的记忆上下文词元数 | 每轮注入的记忆上下文 Token 数 |  |
| tokens used | 已用词元 | 已用 Token |  |
| TTFT %.0fms | 首词元延迟 %.0f 毫秒 | 首 Token 延迟 %.0f 毫秒 |  |
| TTFT %.2fs | 首词元延迟 %.2f 秒 | 首 Token 延迟 %.2f 秒 |  |
| Warming up — prefilling context %lld%% (%lld/%lld tokens) | 预热 — 上下文预填充 %1$lld%% (%2$lld/%3$lld 词元) | 预热 — 上下文预填充 %1$lld%% (%2$lld/%3$lld Token) |  |
