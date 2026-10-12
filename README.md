# 文案

> 带货文案写不出转化？这个库收集 AI 带货脚本和 UGC 视频文案模板，每条都写清楚能帮你解决什么、怎么用它搞钱。
>
> A curated collection of copywriting prompts & skills for viral short videos, gathered from practitioners sharing on X.
> 
> Each entry answers two questions: what problem it solves (and who it's for), and how to make money with it.
> 
> Star counts verified via GitHub API on 2026-10-12. Continuously updated.

## 条目

### AI UGC 视频 Prompt 库（cliprise/awesome-ai-ugc-video-prompts）

**核心提炼**
- 解决什么问题：AI 拍不出"像真人"的带货视频——手持感、口播话术、测评开箱怎么写 prompt，这个库按场景拆好模板，还附 FTC 合规和虚假证言避坑提示。
- 核心用法（4 步）：1) 按场景选模板（hook→body→close、开箱/测评/讲解等）；2) 填入产品名、卖点、时长等变量；3) 生成 UGC 风格 prompt，丢进 AI 视频工具出片；4) 换话术变量做 A/B 测款。
- 什么时候用 / 常见坑：做 TikTok/Reels 带货广告、请真人模特太贵时；坑：AI 假证言会违规（FTC 要求披露），别让 AI 模特说"我用了三个月"这类编造体验的话。

**适用场景**：做 DTC 电商、APP 推广、美妆/快消带货的营销团队和独立站卖家。

**怎么用它搞钱**：UGC 广告代投 / 带货——给品牌接 UGC 风格广告片代制按条收费，或给自己带货矩阵批量出广告素材。

**来源**：[cliprise/awesome-ai-ugc-video-prompts](https://github.com/cliprise/awesome-ai-ugc-video-prompts) · ⭐47 · 更新于 2026-04-28

### 100 个短视频钩子公式（rediumvex/viral-hooks-skill）

**核心提炼**
- 解决什么问题：视频前 3 秒没钩子就被划走——100 个按心理学分类的钩子公式，直接套自己的脚本生成 3 个备选钩子。
- 核心用法（4 步）：1) 把 skill 装到 `.claude/skills`（git clone 即可）；2) 粘一段脚本或只给主题；3) 让它从 10 类心理触发器（好奇缺口、反常识、故事、自白等）里挑选；4) 每次给 3 个钩子变体并标注适合平台。
- 什么时候用 / 常见坑：脚本已写好但开头平淡、完播率上不去时；坑：3 个钩子别选同一类别，最佳组合是截停型（否定/数据/提问）+ 留人型（故事/自白）。

**适用场景**：Reels/TikTok/Shorts 创作者、短视频代运营、任何要做高完播率内容的人。

**怎么用它搞钱**：短视频钩子代写/代运营服务；给客户账号批量优化旧视频开头，按条收费。

**来源**：[rediumvex/viral-hooks-skill](https://github.com/rediumvex/viral-hooks-skill) · ⭐101 · 更新于 2026-05-05

### AI 短视频脚本生成 Skill（FeiFei-AIDev/ai-script-generation-skill）

**核心提炼**
- 解决什么问题：AI 教程/效率技巧类创作者选题难、口播文案写不顺——给主题一次出 5 个 30–40 秒脚本，标题、口播、画面建议、时长全配齐。
- 核心用法（4 步）：1) 复制 skill 到 `~/.codex/skills` 或 `.claude/skills`；2) 输入主题，可附参考素材；3) 一次拿到 5 个角度（干货型/痛点共鸣/悬念反转/对比冲击/热点借势）；4) 挑一个按完整口播和画面建议直接拍。
- 什么时候用 / 常见坑：做 AI 工具教程、提效技巧内容时；坑：`references/hot.md` 热点库要定期更新，旧的热点等于没用。

**适用场景**：做小红书/抖音/视频号 AI 教程号、知识付费引流、效率工具推广的创作者。

**怎么用它搞钱**：AI 教程号矩阵起号（脚本成本降到零）；接 AI 工具商单，按视频收费。

**来源**：[FeiFei-AIDev/ai-script-generation-skill](https://github.com/FeiFei-AIDev/ai-script-generation-skill) · ⭐52 · 更新于 2026-06-25

### 爆款视频逆向工程（yanlinyi101/Video-Script-Reverse-Engineering-Pro）

**核心提炼**
- 解决什么问题：看到爆款却拆不出它的底层逻辑——把爆款文案喂给 AI，逆向出可复用的结构模板（CSV），再按同一骨架生成原创内容。
- 核心用法（5 步）：1) 填入 Gemini API Key；2) 粘一段想模仿的爆款视频文案；3) AI 拆解结构/钩子/节奏，输出 CSV 结构模板；4) 按模板生成 3–4 个新选题；5) 输出纯口播文案（适配提词器）+ 标题/置顶评论等发布物料。
- 什么时候用 / 常见坑：对标账号出爆款、自己想复制但怕变成抄袭时；坑：需要 Gemini API Key 才能用；复刻的是"骨架"不是换皮，主题和案例得换成自己的，否则还是抄。

**适用场景**：做仿写爆款、账号冷启动、需要快速复制爆款结构的内容团队和个人创作者。

**怎么用它搞钱**：爆款复制代运营（给商家/博主做对标账号的爆款复刻），按爆款条数或月费收费。

**来源**：[yanlinyi101/Video-Script-Reverse-Engineering-Pro](https://github.com/yanlinyi101/Video-Script-Reverse-Engineering-Pro) · ⭐33 · 更新于 2026-03-18

## 收录标准

- 来源：X 博主实战分享（原帖 / 评论区 / 引用链）及 GitHub 高星项目
- 收录线：star > 20 且一年内有更新；不达标的条目移除
- 每条格式：核心提炼（解决什么问题 / 核心用法 3–5 步 / 什么时候用和常见坑）+ 适用场景 + 怎么用它搞钱 + 来源
- Star 数为 2026-10-12 经 GitHub API 核验；持续收录中
- 去重：同一项目只收录一次，不堆 raw 链接

## 相关分类

- 总索引：[x-viral-video-skills](https://github.com/kkone1238899/x-viral-video-skills) —— 13 个分类导航
- [x-viral-video-scripts](https://github.com/kkone1238899/x-viral-video-scripts) —— 编剧 / 脚本
- [x-viral-video-hooks](https://github.com/kkone1238899/x-viral-video-hooks) —— 标题 / 5 秒钩子
- [x-viral-video-creative-direction](https://github.com/kkone1238899/x-viral-video-creative-direction) —— 创意总监
- [x-viral-video-directing](https://github.com/kkone1238899/x-viral-video-directing) —— 导演
- [x-viral-video-replication](https://github.com/kkone1238899/x-viral-video-replication) —— 复制爆款
- [x-viral-video-breakdown](https://github.com/kkone1238899/x-viral-video-breakdown) —— 拉片
- [x-viral-video-pipeline](https://github.com/kkone1238899/x-viral-video-pipeline) —— 流水线 / 生产管线
- [x-viral-video-de-ai](https://github.com/kkone1238899/x-viral-video-de-ai) —— 去 AI 味
- [x-viral-video-characters](https://github.com/kkone1238899/x-viral-video-characters) —— 人物构建
- [x-viral-video-editing](https://github.com/kkone1238899/x-viral-video-editing) —— 视听剪辑技巧
- [x-viral-video-prompt-opt](https://github.com/kkone1238899/x-viral-video-prompt-opt) —— 提示词优化
- [x-viral-video-showcase](https://github.com/kkone1238899/x-viral-video-showcase) —— X 病毒视频合集

## 投稿

发现好的文案 prompt / skill，欢迎提 Issue 或 PR（格式见 CONTRIBUTING.md）。

## 更新日志

- 2026-10-12：条目改小节格式（核心提炼/适用场景/怎么用它搞钱/来源）；seedance-viral-forge 因 star 18 未达收录线删除，替换为 rediumvex/viral-hooks-skill；新增 FeiFei-AIDev/ai-script-generation-skill、yanlinyi101/Video-Script-Reverse-Engineering-Pro；共 4 条
- 2026-10-11：首版，2 个项目，持续收录中
