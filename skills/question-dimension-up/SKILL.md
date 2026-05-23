---
name: question-dimension-up
description: Audit, score, analyze, answer, and upgrade business, industry, startup, investment, strategy, market, competitive landscape, PMF, profit model, value chain, and founder-research questions using a McKinsey-style hypothesis-driven, MECE, 3C, value-chain, profit-pool, and extreme-scenario SOP. Use when the user asks whether a question is good, requests 提问升维, wants a direct structured answer to an industry question, or asks to reason about an industry/company/startup problem through this SOP.
---

# Question Dimension-Up SOP

Use this skill to turn a raw business or industry question into a sharper research-quality answer. The goal is not only to answer the question, but to audit whether the question is good and then upgrade the user's understanding of the industry structure behind it.

## Output Contract

Always use this six-part structure unless the user explicitly asks for a different format:

```text
## 1. 问题得分
## 2. 分析问题
## 3. 引申问题
## 4. 回答
## 5. 问题升维
## 6. 追问
```

Write in Chinese by default when the user asks in Chinese. Keep the answer concise enough to be readable, but do not compress away the reasoning depth. For substantial business questions, section 4 must usually be at least 500 Chinese characters and preserve a complete answer logic.

Section 1 must include a direct judgment of the question's nature. Use a strict tone. Do not praise the user's question by default. If the score is below 50, the first sentence after the score should directly say one of:

- 这不是一个好问题。
- 这是一个比较初级的问题。
- 这是一个偏小白的问题。
- 这个问题建立在一个可能错误的理解上。

Then classify why the question is weak:

1. 行业理解不足: the user lacks basic industry structure, key actors, value chain, or business model context.
2. 提问思维不足: the user may know the topic, but asks in a vague, surface-level, non-hypothesis, non-structured, or non-verifiable way.
3. 理解错误: the question rests on a false premise, confused causality, wrong comparison, wrong metric, or mistaken concept.

If more than one applies, name the primary cause first and mention the secondary cause briefly.

## Scoring

Score the raw question on a 100-point scale:

- 假设性 Hypothesis, 30 points: Does the question contain a testable causal or strategic hypothesis?
- 结构度 Structure, 30 points: Does it use or imply systematic decomposition such as MECE, 3C, value chain, cost structure, supply-demand, or competition?
- 洞察力 Insight, 40 points: Does it touch profit pools, pricing power, key success factors, survival constraints, or industry endgame?

Ratings:

- 0-30: 青铜级，初级/资料搜集型
- 31-50: 白银级，表层业务问题
- 51-70: 黄金级，业务关系型
- 71-90: 钻石级，商业洞察型
- 91-100: 王者级，终局推演型

Default to a stricter score than a generous one. A question should not exceed 50 unless it has at least one concrete business variable, such as customer segment, use case, CAC, retention, pricing, margin, channel, workflow, budget, competition, value chain, or unit economics. A question should not exceed 70 unless it contains or strongly implies a testable hypothesis and a structural lens. A question should not exceed 85 unless it touches profit pool, pricing power, KSF, endgame, or extreme scenario.

Common score calibration:

- 15-30: asks "what is X", "how do I do X", "is X useful", "how to make a hit", "what is the trend" without context or variables.
- 25-40: has a real business topic but remains generic, broad, or tool-like.
- 40-55: sees a business activity or pain point but lacks hypothesis, segmentation, or economic mechanism.
- 55-70: identifies an important business relationship, but does not yet touch profit pool, pricing power, or structural control points.
- 70-85: has a clear hypothesis and structural variables; answerable through business analysis.
- 85+: rare; requires a sharp endgame, extreme-scenario, profit-pool, or power-structure question.

In section 1, include the total score, rating, a direct quality judgment, the primary weakness classification, and a short reason. If useful, mention the main deduction: too broad, no hypothesis, weak structure, missing profit pool, no extreme scenario, unclear unit economics, etc.

## Section Guidance

### 1. 问题得分

State the score and level directly. Then give the question nature judgment and weakness classification. Do not start with praise. Do not over-explain the scoring matrix unless the user asks.

Good pattern:

```text
**28 分，青铜级，初级/资料搜集型。**

这不是一个好问题。主要问题属于「提问思维不足」，其次是「行业理解不足」：它只问了一个动作怎么做，但没有说明目标客户、商业模式、转化链路、内容要影响的经营变量，也没有任何可验证假设。
```

For higher-quality questions, still avoid flattery:

```text
**76 分，钻石级，商业洞察型。**

这个问题已经进入商业机制层，但还没有把变量压到利润池、定价权或极端竞争场景。主要问题属于「提问思维仍可继续压实」。
```

### 2. 分析问题

Diagnose what the user is really asking. This section should be materially stronger than a summary. Identify:

- the apparent question versus the real question
- hidden assumptions
- likely false signals or misleading metrics
- missing industry variables
- where the question sits in the value chain or competitive system
- what must be distinguished before answering

Use McKinsey-style framing: turn vague questions into issue trees and business variables. Name the core tension in one sentence.

For low-score questions, explicitly explain why the question is shallow before improving it. Acceptable direct language includes:

- 这个问题停留在动作层，没有进入商业机制层。
- 这个问题把结果当目标，但没有定义结果对商业模式的价值。
- 这个问题缺少对象、场景、变量和验证标准。
- 这个问题的前提可能不成立，需要先纠偏。

### 3. 引申问题

Give 3-5 sharper derivative questions. These should not be generic. Cover different analytical angles:

- profit pool / value chain / pricing power
- hypothesis-driven variable testing
- extreme scenario / KSF / endgame
- unit economics / CAC / LTV / margin / cash flow when relevant
- customer workflow / budget / switching cost when relevant

Each question should be answerable through research, interviews, or data.

### 4. 回答

Answer the original question directly and deeply. Preserve a complete reasoning chain rather than only giving a punchline.

For industry/startup/business questions, usually include:

- direct thesis
- mechanism chain
- segmentation of causes
- leading indicators or proof points
- why common interpretations are wrong or incomplete
- what kind of company/player survives

Use clear causal chains when helpful:

```text
早期信号
→ 误判机制
→ 经营变量暴露
→ 竞争/成本/组织压力
→ 结果
```

Do not stop at "it depends." If there are multiple cases, create a practical typology and state which type has better odds.

### 5. 问题升维

This section must teach the user how to understand the industry at a higher level. Do not merely list "原问题/升维后问题." Explain the structural lens.

Upgrade from phenomenon to structure:

- from "what happened" to "which industry mechanism produced it"
- from "does the product work" to "where does value accrue in the value chain"
- from "growth" to "sustainable profit and pricing power"
- from "feature" to "workflow/system/control point"
- from "company success" to "industry endgame under extreme conditions"

Useful structural lenses:

- Value chain: upstream, midstream, downstream, channel, customer, data, infrastructure
- Profit pool: who captures gross margin, net margin, budget, or cash flow
- Pricing power: who can raise price without losing demand
- 3C: customer need, company capability, competitor response
- KSF: what capability determines survival under stress
- Control points: data, workflow, budget, distribution, cost, compliance, switching cost, decision rights

End this section with a sharper upgraded question if it naturally follows, but the main value is the explanatory frame.

### 6. 追问

Give the next 5-8 questions the user should ask. These should be operational and researchable. Prioritize the one best follow-up first.

Good follow-ups test:

- retention over time
- willingness to pay
- workflow integration
- budget ownership
- gross margin and unit economics
- acquisition repeatability
- switching cost
- competitor/platform response
- customer loss if the product disappears

## Quality Bar

Good output should feel like a strategy analyst's answer, not a listicle. It should help the user see why the original question matters, what hidden structure drives the answer, and what to ask next.

Avoid:

- generic trend commentary
- only restating the user's question
- giving three shallow "引申问题"
- making section 5 a simple before/after rewrite
- answering with only slogans and no mechanism

Prefer:

- causal mechanisms
- concrete business variables
- profit and power analysis
- industry structure
- falsifiable hypotheses
- practical next questions

## Default Example Pattern

For a question like "很多 AI 初创公司第一年有好数据，为什么平台期死掉？", the core answer should distinguish early false PMF from durable commercial PMF, then analyze retention, workflow embedding, model cost, CAC, platform copying, pricing power, and organizational scaling. The upgrade should move from "why startups die" to "which AI companies control durable value-chain positions such as data, workflow, budget, distribution, and switching cost."
