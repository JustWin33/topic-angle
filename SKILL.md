---
name: topic-angle
description: Analyze AI, technology, product, startup, business, model-release, tool, or developer-workflow material for Chinese-language X/Twitter publishing. Use when the user asks whether material is worth posting, wants a strong Chinese-audience angle, hooks or titles, a post-format recommendation, fact-checking risks, follow-up replies, or infographic ideas.
---

# Topic Angle

Turn raw material into the strongest publishable angle for Chinese-speaking tech audiences. Do not mechanically summarize the source. Optimize for relevance, clarity, and credibility rather than hype.

## Workflow

1. Read the supplied material and identify its core confirmed claim.
2. Verify timely, uncertain, or consequential claims when tools and sources are available. Prefer official announcements, documentation, repositories, filings, or first-party statements.
3. Separate confirmed facts, reasonable inferences, and speculation. Never turn an inference into a fact.
4. Score the material on the seven dimensions below.
5. Identify what changes for ordinary users, creators, developers, and AI-tool users.
6. Select one main angle that can be expressed clearly in a single sentence.
7. Generate hooks, recommend a format, write the opening, and flag risks.

If the user requests only part of the analysis, return that subset. Otherwise use the complete output structure.

## Evaluation

Score each dimension from 1 to 5 and briefly justify the score:

- 信息差：大多数目标读者是否还不知道？
- 实用性：读者能否据此采取行动？
- 争议性：是否会引发有意义的讨论？
- 新鲜度：是否及时，或近期重新变得重要？
- 传播性：能否用一句清晰的话讲明白？
- 中文圈适配度：中文读者是否有明确的关注理由？
- 配图潜力：是否适合截图、卡片或信息图表达？

Use the total score only as a heuristic. A narrow but highly useful angle can still be worth publishing. Choose one verdict: `值得发`、`可以发，但要换角度`、`不建议发`、`需要先事实核查`.

## Output

### 1. 是否值得发

State the verdict, show the seven scores, and explain the decisive reasons concisely.

### 2. 最适合中文圈的角度

Give the best angle in one sentence. Make it specific enough to become the main post; avoid vague topic labels.

### 3. 普通人最关心什么

List 3 to 5 concrete implications. Prioritize whether the material saves money or time, lowers a barrier, changes a workflow, creates a new risk, or shifts what users can do. Distinguish impacts on ordinary users, creators, developers, and AI-tool users where relevant.

### 4. 可写标题 / 开头

Generate five distinct options:

1. 反常识型
2. 信息差型
3. 工具流型
4. 普通人视角型
5. 收藏干货型

Keep them natural and defensible. Avoid empty hype such as“震撼发布”“彻底颠覆”“全网首发”“普通人必须知道”“不看后悔”“王炸”或“爆了”.

### 5. 推荐发布形式

Choose one: `单帖`、`主帖 + 自我回复`、`长线程`、`X Article`、`信息图`、`多图卡片`、`视频口播稿`. Explain why it fits the information density and audience behavior.

### 6. 推荐主帖切入

Write one polished Chinese opening with a strong first sentence and a clear reason to continue reading. Keep it natural, sharp, non-official, and suitable for Chinese tech X without becoming clickbait.

### 7. 后续自我回复方向

Give 3 to 5 follow-up reply ideas that add evidence, examples, comparisons, instructions, or implications instead of repeating the main post.

### 8. 风险提醒

Identify:

- claims that still need verification;
- wording that should not be stated as certain;
- likely exaggerations or missing context;
- where qualifiers such as“目前看”“据官方文档”“从截图看”或“尚未完全确认”are appropriate.

When verification is incomplete, say so plainly and recommend what primary source would resolve it.

### 9. 配图建议

State whether visuals help, what source screenshots or diagrams to use, whether a 5:2 infographic fits, a proposed infographic headline, and the suggested content modules. Do not recommend decorative visuals that add no information.
