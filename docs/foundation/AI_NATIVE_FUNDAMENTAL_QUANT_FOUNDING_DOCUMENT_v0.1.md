# AI-Native Fundamental Quant｜Alpha Research Operating System Founding Document

**版本：** v0.1  
**日期：** 2026-08-20  
**性质：** Founding / Living Document  
**用途：** 作为未来 Alpha Research Operating System、AI-Native Fundamental Quant 研究路线、个人学习系统、作品集与职业发展的上位约束文件。

---

## 0. 文档定位：这不是“项目需求文档”，而是系统宪法

本文件用于统一五件长期容易被割裂的事情：

1. **投资世界观**：价值、信息、价格、Alpha 与财富究竟是什么，以及它们之间如何传导；
2. **研究范式**：价值投资与基本面量化本质上在解决什么问题；
3. **系统范式**：如何把结构化基本面、非结构化现实信息、统计模型、AI Agents、组合与执行连接成一台可持续迭代的研究机器；
4. **个人能力战略**：会计/金融、CS/Systems、AI-Native Engineering、Quantitative Research Science 四块能力如何形成乘法关系；
5. **学习范式**：如何在 AI 时代同时最大化真实产出速度与长期独立能力，而不落入“全部手写”或“完全黑盒外包给 AI”的两个极端。

本文件不是一套不可修改的教条。它刻意区分：

- **Principles（原则）**：除非出现根本性反证，否则长期稳定；
- **Hypotheses（假设）**：需要用数据、项目和职业市场不断验证；
- **Architecture（架构）**：服务原则，可以迭代；
- **Roadmap（路线图）**：最容易变化，只代表当前最优判断。

最终目标不是“把一个 GitHub 项目做大”，而是同时完成两个产品：

> **Product A：一台 AI-Native Fundamental Quant Alpha Research Operating System。**
>
> **Product B：一个真正具备独立研究、工程判断、资本配置思维和 AI 杠杆能力的人。**

---

# Part I｜Operating Constitution：先读这部分就能对齐整个项目

## 1. 十二条核心宪法

### 1.1 价值

> **价值，是使某个主体的状态变得更好的能力。**

价值并不天然等于价格、收入或财富。社会价值、使用价值、交换价值、可货币化价值与最终被个人捕获的价值可能完全不同。

### 1.2 信息

> **信息，是能够使一个系统更新其内部世界模型的“可区分差异”；信息价值，是这种更新提高决策期望质量的能力。**

一个实用近似：

```text
Information Value
≈ Decision Quality Improvement
× Controlled Resources
× Actionability
× Timeliness
```

### 1.3 能力

> **能力，本质上是价值转换器。**

观察、筛选、理解、建模、判断、执行、组织和价值捕获，分别决定信息如何一步步变成现实结果。

### 1.4 价格

> **价格是一种社会信息系统：它把分散的知识、预期、偏好、约束、资本与供需压缩成公共信号，并通过激励反向协调资源。**

价格不是价值本身，而是一个带噪声、动态更新的社会估计器。

### 1.5 Alpha

> **Alpha 不是“知道正确的事情”，而是拥有尚未被价格完全、正确、及时兑付，并且自己能够行动的增量认知。**

一条信息如果已被市场正确吸收，其作为交易信号的边际价值趋近于零。

### 1.6 价值投资

> **价值投资的本质，不是寻找低 PE，而是寻找“价格所隐含的未来世界”与“自己认为最可能发生的未来世界”之间足够大、足够可验证、可利用的差异。**

研究对象始终有两个：企业真实的价值生成机制，以及当前价格隐含的市场世界模型。

### 1.7 基本面量化

> **基本面量化不是几个财务因子的自动排序，而是把企业基本面理解、预测、估值和决策逐步系统化、可计算化、可验证化。**

Quant 的核心区别首先是**决策方式的系统化**，而非是否程序化下单。

### 1.8 AI 的位置

> **AI handles ambiguity; deterministic systems handle money.**

AI 优先处理非结构化、语义密集、搜索空间巨大、需要假设生成的环节；资金、会计计算、组合约束、风险、回测记账与交易执行的关键链条应尽可能 deterministic、reproducible、testable。

### 1.9 研究系统

> **我们首先建设的不是“交易系统”，而是一台持续生产、验证、淘汰、组合投资认知的机器。**

总链条：

```text
Reality
→ Evidence
→ Data
→ Features
→ Hypotheses
→ Forecasts
→ Portfolio
→ Execution
→ Outcome
→ Learning
```

### 1.10 学习

> **AI 的目的不是让人少思考，而是把人从低价值实现摩擦中解放出来，使其更早、更频繁地进入高价值复杂问题。**

生产时最大化 AI 杠杆；学习时刻意制造认知摩擦；验证时尽量剥离 AI；思考时把 AI 当老师、同事与反方，而不是权威。

### 1.11 代码所有权

> **Code Ownership ≠ Code Authorship。**

一个人不需要亲手输入每一行生产代码，但必须能够解释核心设计、识别错误、定义 invariant、制定验收、定位失败并对最终结果负责。

### 1.12 职业战略

> **不要找“最符合当前技能”的工作；要找“既愿意为当前能力付钱，又让每天工作更接近未来稀缺能力”的平台。**

近期就业身份以 **Quant Developer / Research Engineer** 为最自然入口，学习第一优先却应是 **Quantitative Research Science**；长期向 **Systematic Equity / Fundamental Quant / Financial AI** 收敛。

---

# Part II｜统一理论：价值、信息、价格、Alpha 与财富

## 2. 价值：从“有用”到“被兑付”

### 2.1 价值不是一个孤立属性

价值总是隐含一个关系：

```text
某个对象 / 能力
→ 对某个主体
→ 在某个情境
→ 改善某种状态
```

因此更精确地说：

> **Value = State-improvement capability relative to a subject and context.**

同一事物对于不同主体、不同时间、不同约束可以拥有完全不同的价值。

### 2.2 创造价值与捕获价值是两件事

个人收入不是社会对其全部真实贡献的精确“兑付”。工资更接近劳动力市场在制度、稀缺性、可替代性、议价权与支付能力约束下形成的价格。

一个近似框架：

```text
Realized Economic Reward
≈ Monetizable Value
× Attributability
× Scarcity
× Bargaining Power
× Scale
× Ownership / Claim Rights
```

于是产生两个必须始终区分的概念：

- **Value Creation**：创造了多少增量状态改善；
- **Value Capture**：其中多少最终归属于自己。

所有权的本质，是对未来价值流拥有索取权。财富长期积累从纯 income 走向 ownership，是从“出售价值创造能力”走向“拥有价值生产系统”的迁移。

---

## 3. 信息：对可能世界的排除

### 3.1 从差异到世界模型更新

信息可按三层理解：

1. **物理/符号层**：存在可区分状态；
2. **统计层**：减少不确定性；
3. **语义层**：使接收者的内部模型发生有意义更新。

Shannon 信息量强调低概率事件携带更多统计信息，但**高信息量不等于高价值**。随机字符串可能不可预测，却对决策毫无用途。

### 3.2 信息价值

真正重要的不是“我知道了更多”，而是：

> **这条信息是否改变了我的概率分布，从而改善决策的期望结果？**

所以：

```text
Information Value
≈ ΔDecision Quality
× Resource Scale
× Actionability
× Timeliness
```

其中：

- `ΔDecision Quality`：相对于无此信息，决策质量提升多少；
- `Resource Scale`：决策可以影响多少资本、时间、组织能力或其他资源；
- `Actionability`：是否真的能够采取行动；
- `Timeliness`：在别人之前、在机会消失之前是否可用。

真信息不一定有交易价值；已经公开且被正确吸收的真信息，其边际 Alpha 可以接近零。

### 3.3 信息传导链

```text
World
→ Observation
→ Data
→ Information
→ Cognition / Model
→ Forecast
→ Decision
→ Action
→ Outcome
→ Value
```

每两个节点之间都存在转换能力：

- 世界 → 数据：观察能力；
- 数据 → 信息：筛选能力；
- 信息 → 认知：理解能力；
- 认知 → 预测：建模能力；
- 预测 → 决策：判断能力；
- 决策 → 行动：执行能力；
- 行动 → 结果：资源与组织能力；
- 结果 → 财富：价值捕获/所有权能力。

因此个人综合能力更像一个**串联系统的转换效率乘积**。某一环节接近零，会大幅削弱最终 realized value。

---

## 4. 价格：信息进入资源配置的接口

### 4.1 价格是压缩后的集体信息

一个资产的价格看起来只是一个数字，但它可能压缩了：

- 未来现金流预期；
- 利率与折现率；
- 风险偏好；
- 行业结构；
- 私人信息；
- 流动性；
- 仓位、杠杆和监管约束；
- 对其他参与者行为的预期。

可抽象为：

```text
Price_t = F(Information, Expectations, Preferences,
            Constraints, Capital, Supply/Demand)
```

价格使分散在不同主体手中的知识可以无需中央大脑而被部分聚合。

### 4.2 价格不仅反映信息，也制造新的信息和激励

价格变化本身又成为新的公共信息，并直接改变行动成本：

```text
Original Information
→ Trading
→ Price
→ New Incentives
→ Resource Reallocation
→ New Reality
```

因此：

> **Price = Information Aggregator + Incentive Signal + Coordination Protocol.**

### 4.3 价格不是“真理”

```text
Price ≠ Value
```

价格是市场在当前信息、认知、约束和资本结构下形成的估计。它可以错误，因为参与者可能：

- 信息不完整；
- 模型错误；
- 过度反应/反应不足；
- 被迫买卖；
- 有期限、杠杆和职业约束；
- 对同一事实存在不同解释。

因此市场是一台**带噪声、会反馈、自适应的分布式估计器**。

### 4.4 价格是机会成本的公共编码

相对价格编码了社会对资源稀缺性的动态评价：获得 A 意味着放弃多少其他资源。企业家、投资者和资本配置者都在这张机会成本地图上寻找：

```text
Value of Output > Opportunity Cost of Inputs
```

这也使利润成为一种重要反馈：某种资源组合可能创造了高于市场当前机会成本的可捕获价值。

---

## 5. Alpha：尚未完成的“信息兑付”

### 5.1 “信息已公开”不等于“信息已反映”

完整的信息兑付至少需要：

```text
Information becomes available
→ Is noticed
→ Is interpreted correctly
→ Cash-flow impact is estimated correctly
→ Risk/time value is discounted correctly
→ Capital acts on it
→ Price incorporates it
```

任何环节的不完全都可能留下 edge。

### 5.2 Alpha 的更底层定义

> **Alpha = 可行动的、相对于价格隐含世界模型具有增量准确度的认知优势，在资本配置后形成的风险调整超额结果。**

因此：

```text
Being right is not enough.
You must be more right than what is already priced in.
```

一个研究者可以对某家公司所有事实判断都正确，却因为市场早已正确反映而没有 Alpha。

---

# Part III｜价值投资：研究“现实”和“价格隐含现实”之间的差

## 6. 价值投资的本质

### 6.1 两个世界模型

价值投资不是只研究企业，也不是只计算“内在价值”。它同时研究：

```text
Model A: How the business actually creates value
Model B: What future the current price implies
```

真正的投资问题是：

```text
My Distribution of Future Reality
vs.
Market-implied Distribution of Future Reality
```

如果两者不存在足够大的差异，就没有必要下注。

### 6.2 估值是反问题，不只是正问题

传统 DCF：

```text
Fundamentals → Price / Value
```

成熟价值研究还会做：

```text
Price → Implied Expectations
```

即 reverse DCF / expectations analysis：

> 当前价格需要什么收入增速、利润率、ROIC、竞争优势持续期和风险假设才能成立？这些隐含假设合理吗？

因此“PE 低不低”只是极低维的投影；真正的问题是**市场在押什么未来**。

### 6.3 价值投资不是 Value Factor

- **Value Investing**：`Intrinsic Value > Price`，核心是未来价值生成机制与赔率；
- **Quant Value Factor**：用 E/P、B/P、FCF/P、EBIT/EV 等 observable ratios 近似“便宜”。

高估值企业也可能是价值投资；低 PE 企业也可能是 value trap。

### 6.4 Alpha 的六种来源

1. **Information Edge**：获得更好的合法信息或数据；
2. **Analytical Edge**：同样的信息，解释模型更好；
3. **Expectation Edge**：更准确理解价格到底隐含了什么；
4. **Time-Horizon Edge**：别人无法等待，而自己能够等待；
5. **Behavioral Edge**：别人系统性受到认知偏差影响，而自己能够控制；
6. **Structural Edge**：其他资金因 mandate、benchmark、赎回、杠杆、流动性等原因“不能做正确的事”。

更简洁地：

```text
Investment Alpha
≈ Cognitive Difference
× Probability of Being Right
× Payoff / Odds
× Capital Allocation
× Ability to Hold
```

### 6.5 价值投资的两台收益发动机

长期收益至少可以拆成：

```text
Return
≈ Intrinsic Value Compounding
+ Mispricing Convergence
+ Cash Distribution
- Permanent Capital Loss
```

优秀企业并不一定要求市场迅速“发现错误”。如果企业能长期以高 ROIC 再投资，内在价值本身就在复利增长。

### 6.6 安全边际的现代解释

企业价值不是一个精确点，而更像一个概率分布：

```text
V ~ P(V)
```

安全边际不是机械地“估值 100、80 买”，而是承认：

> **模型必然有误差，买入价格必须为自己的认知错误和左尾风险留出容错空间。**

---

## 7. 行为金融学：价值投资体系里的“误差理论”

行为金融学有两个对称角色：

### 7.1 解释市场为什么可能错

常见系统偏差包括：

- Anchoring；
- Recency Bias；
- Extrapolation；
- Loss Aversion；
- Herding；
- Overconfidence；
- Confirmation Bias。

这提供了“价格为什么可能暂时偏离价值”的微观机制之一。

### 7.2 解释投资者自己为什么也可能错

价值投资最危险的错觉之一是：

> “别人有行为偏差，我是理性的套利者。”

实际上自己同样会锚定买入价、爱上 thesis、只搜支持证据、上涨后提高长期预测、下跌后不断修改逻辑。

所以真正的四个问题是：

1. 现实是什么？
2. 市场认为现实是什么？
3. 为什么二者可能存在差异？
4. **为什么不是我错？**

行为金融因此不是装饰性心理学，而是投资体系中的**认知误差模型**。

---

# Part IV｜基本面量化：把企业研究变成系统化决策科学

## 8. 量化的核心区别：决策系统化，而非程序化下单

梁文锋在《一名程序员眼里中国量化投资的未来》的历史性演讲中提出一个重要定义：量化与非量化的关键区别不在交易是否程序化，也不在研究是否使用数学，而在**最终投资决策由人还是数量化系统完成**。

这一判断应保留为本项目的核心定义之一：

> **Quantitative Investing = Systematic / Quantitative Decision Making.**

需要同时保留历史边界：该演讲描述的是其当时（文中明确为 2019 年）的中国量化行业状态，其中关于规模、收益与未来年份的数字不应直接当作 2026 年事实；真正有价值的是其方法论判断——市场效率提升会不断压缩已有 Alpha，竞争会推动多策略与更精细的基本面量化。

## 9. 基本面量化与量价策略不是“投资 vs 投机”的二分

市场信息传播可写成：

```text
Real Economy
→ Business Operations
→ Fundamental Data / Text
→ Investor Models
→ Trading Decisions
→ Price / Volume
→ Order Flow
```

不同策略只是从不同位置观测：

- **Fundamental Quant**：上游，研究企业状态与价值生成；
- **Price/Volume Quant**：下游，研究市场对信息处理后的输出；
- **Momentum**：可能利用反应不足和信息逐步扩散；
- **Microstructure/HFT**：更靠近订单流和极短期价格形成。

它们共同的问题都是：

> **哪里存在尚未被价格完全、正确、及时吸收的信号？**

因此数据来源不等于投资周期，也不等于“投资/投机”的道德分类。

## 10. Fundamental Quant 的真正目标

它不应停留于：

```text
PE + PB + ROE + few factors → rank → buy
```

更有野心的定义是：

```text
Enterprise Reality
→ Accounting / Economic Semantics
→ Point-in-time Fundamental State
→ Features
→ Future Fundamentals / Return Distribution
→ Portfolio Decision
```

核心研究对象包括：

- Value；
- Quality；
- Profitability；
- Investment；
- Earnings Quality / Accruals；
- Revisions；
- Fundamental Momentum；
- Capital Allocation；
- Competitive Advantage；
- Balance-sheet strength；
- Cash-flow quality；
- Working-capital dynamics；
- 行业特异的 unit economics。

会计知识在这里不是传统背景包袱，而是**从财务数字返回经济现实的语义优势**。

---

# Part V｜AI-Native Fundamental Quant：为什么现在值得重新设计这台机器

## 11. AI 最大的基本面机会：降低“现实 → 可计算状态”的成本

传统 Quant 最舒服的是整洁矩阵：

```text
X[N, K]
```

而真实企业世界的大量重要信息存在于：

- 年报、季报与脚注；
- Earnings Call；
- 公司公告；
- 管理层措辞变化；
- 会计政策；
- 监管文本；
- 产品与客户反馈；
- 招聘与组织变化；
- 产业链关系；
- 合同、法律与另类数据。

过去很多信息“难以量化”，很大程度上不是原则上不可计算，而是**结构化成本过高**。

LLM/Agent 的关键机会因此不是“让聊天机器人直接买股票”，而是：

```text
Unstructured Reality
→ Evidence-backed Structured State
→ Computable Features
```

Two Sigma 在 2026 年关于 feature research 的公开讨论中也强调，随着 raw data 更商品化，edge 越来越依赖如何把世界事实塑造成特征；LLM 显著降低了文本和非结构化数据的 feature exploration 成本。这是本项目“AI Fundamental Engine”方向的重要外部验证，但仍须以实证研究而非叙事决定是否存在 Alpha。

## 12. 第一代 AI 原则：AI 做研究智能，不做不可审计的最终权威

第一代系统优先采取：

```text
AI for ambiguity / search / semantic extraction / hypothesis generation
+
Deterministic systems for accounting / statistics / portfolio / risk / execution
```

AI 可以承担：

- 文档解析；
- 事实与证据抽取；
- 语义归一化候选；
- 研究检索；
- 假设生成；
- 反证生成；
- 特征候选生成；
- 研究报告与诊断；
- 测试脚手架与工程实现。

但以下内容初期必须保持强确定性与可复现：

- point-in-time 时间语义；
- 财务计算；
- 特征数值生成的最终实现；
- backtest accounting；
- transaction cost；
- portfolio constraints；
- risk；
- order lifecycle；
- capital authorization。

## 13. Evidence-first Quant

Audit AI Workbench 中形成的 Evidence Authority、state、validation boundary、human explicit PASS 等思想应迁移到量化研究。

一个候选结构：

```text
EvidencePacket {
    entity
    source_id
    publication_time
    effective_period
    concept
    extracted_fact
    evidence_span
    confidence
    extractor_version
}
```

核心原则：

> **任何由 AI 从非结构化材料提取出来并进入研究/特征链的事实，都应尽可能携带 source、时间、版本和证据链。**

这既服务于 hallucination 控制，也服务于最关键的 point-in-time / leakage 审计。

## 14. Alpha Factory，而不是 AI Stock Picker

AI-Native 系统的目标不是输出一句：

> “BUY NVIDIA”。

而是构建：

```text
Evidence
→ Feature Candidate
→ Economic Hypothesis
→ Statistical Test
→ Falsification
→ OOS Validation
→ Cost / Capacity
→ Portfolio Integration
→ Monitoring
→ Decay / Kill
```

因此 AI 应服务于科学研究循环，而不是替代它。

---

# Part VI｜Alpha Research Operating System：北极星系统架构

## 15. 总体认知链

```text
REALITY
  ↓
Evidence Layer
  ↓
Point-in-Time Data Layer
  ↓
Feature / Representation Layer
  ↓
Hypothesis & Research Layer
  ↓
Forecast Layer
  ↓
Portfolio & Risk Layer
  ↓
Execution Layer
  ↓
Outcome / Attribution
  ↓
Learning / Model Update
```

这是一条闭环，而不是一次性 pipeline。

## 16. 建议的长期模块边界

```text
alpha-research-os/

    data/
        market/
        fundamentals/
        corporate_actions/
        universe/
        point_in_time/
        lineage/

    fundamental/
        accounting/
        valuation/
        quality/
        profitability/
        investment/
        revisions/

    research/
        features/
        factor_lab/
        statistics/
        validation/
        backtest/
        experiment_registry/

    ai_research/
        filings/
        announcements/
        extraction/
        evidence/
        agents/
        evals/
        feature_generation/

    portfolio/
        forecasts/
        risk/
        optimizer/
        constraints/
        transaction_costs/

    execution/
        cpp/
        event_engine/
        oms/
        exchange_sim/
        adapters/

    strategies/
        fundamental/
        momentum/
        event/
        combined/

    platform/
        config/
        artifact_store/
        observability/
        reproducibility/

    tests/
    research_notes/
    docs/
```

**重要：这只是北极星架构，不是第一年待办清单。**

系统欲本身是风险：如果先花一年打造漂亮基础设施、最后没有任何经过严谨验证的 signal，项目失败。

## 17. Multi-Strategy 的正确起点：统一“预测协议”，而不是同时造很多策略

第一阶段不追求 Value + Momentum + Event + HFT 全部实现，而先定义统一输出：

```text
Forecast {
    asset
    as_of
    horizon
    expected_return
    uncertainty / confidence
    strategy_id
    metadata
}
```

然后：

```text
Fundamental Model → Forecast
Momentum Model    → Forecast
Event Model       → Forecast
AI Feature Model  → Forecast

Forecasts → Portfolio / Risk / Capital Allocation
```

因此 Multi-Strategy 的本质是：

> **多个认知模型共享同一套资本配置、风险与评价系统。**

---

## 18. 系统不可违反的研究 Invariants

### 18.1 Point-in-time first

任何研究都必须先回答：

> 在历史时点 T，系统当时真实可获得的是什么？

重点防范：

- look-ahead bias；
- restatement leakage；
- survivorship bias；
- universe leakage；
- corporate action timing error；
- identifier mapping error。

### 18.2 Reproducibility first

一个研究结果必须能够从：

```text
Code Version
+ Data Version
+ Config
+ Feature Definition
+ Universe
+ Time Range
```

重新产生。

### 18.3 No Alpha Claim Without Falsification

不能只问“为什么有效”，还必须主动问：

- 换 universe 呢？
- 行业/规模中性以后呢？
- 换时期呢？
- OOS 呢？
- 成本以后呢？
- 容量以后呢？
- 是独立 signal 还是已有因子的重包装？
- 有没有合理的 risk-premium 解释而不是 mispricing？

### 18.4 No Backtest Without Leakage Audit

漂亮 Sharpe 是最危险的工程输出之一，因为错误系统可以完全正常运行。

### 18.5 Capital Requires Deterministic Gates

任何会真正改变资金暴露的动作必须经过明确的：

- risk constraint；
- position limit；
- capital authorization；
- reproducible portfolio logic；
- observable order lifecycle。

### 18.6 Survival before optimization

```text
Edge × Capital × Time
```

只有在没有爆仓、被迫平仓、数据错误和系统故障的前提下才有意义。

---

# Part VII｜当前个人能力基线：四块拼图

## 19. 第一块：Accounting / Finance Domain Model

既有优势：

- 一流会计学本科训练；
- 能理解财务报表背后的业务语义；
- 对证据、期间、口径、权威来源等天然敏感；
- Audit AI Workbench 提供了真实专业服务 workflow 的现场体验。

未来需要把它从“会计知识”升级为：

```text
Accounting Semantics
→ Economic Reality
→ Quantitative Feature
→ Valuation / Forecast
```

重点方向：盈利质量、accruals、working capital、ROIC、资本配置、现金流、资产负债表质量、行业 unit economics。

## 20. 第二块：CS / Systems / C++ Engineering

历史路径从 C、Linux、网络、线程、底层中间件一路进入 C++。

当前作品证据：

- `C_Journey`：count words、contacts、lock、thread pool、MySQL、DNS、HTTP、TCP、epoll 等早期底层学习项目；AI 参与近乎为零，体现真实手工学习轨迹；
- `quant_trade`：Order、OrderManager、OrderBook、Exchange、Feed、StrategyRunner、PreTradeRisk、OrderFactory 等分层，使用 CMake、GTest、Sanitizer 思维；当前核心代码可在严格 warning 配置下独立编译。

定位：

> **已经形成可靠的 QD / systems learning foundation，但尚不是 production low-latency trading infrastructure。**

未来 C++ 的边际学习应更多围绕真实需要：event-driven system、concurrency、market-data/execution adapter、benchmark、latency、recovery，而不再为了“继续学语法”扩展。

## 21. 第三块：AI-Native Engineering

`AuditAI-Workbench` 已经明显跨过纯 demo：

- workflow state；
- evidence；
- authority；
- validation boundary；
- INIT / ITERATE / PASS；
- review checkpoint；
- source delta；
- human explicit PASS；
- regression / real-machine verification；
- 较完整的协议、schema、测试与文档体系。

其真正价值不是 AI 写了多少代码，而是形成了：

```text
Domain
→ Computational Abstraction
→ Agent Workflow
→ Evaluation
→ Production Discipline
```

的 mental model。

## 22. 第四块：Quantitative Research Science——当前最重要的缺口

`quant_start` 已具备：

- pandas 数据处理；
- MA cross；
- position state；
- 基本回测与手续费；
- 对 look-ahead 的初步意识；
- 简单 metrics。

但仍属于学习型 demo。关键缺口：

```text
Python research fluency
+ Probability / Statistics
+ Econometrics
+ Asset Pricing
+ Cross-sectional Research
+ Time-series Thinking
+ ML
+ Portfolio Construction
+ Research Methodology
```

目前数据源与研究核心仍较强耦合（例如模块 import 即绑定具体数据供应商），这正好是“demo → research platform”的第一批工程训练点。

结论：

> **未来 12–24 个月最需要新增的能力资本，不是继续证明自己会 C++，而是补出 Quantitative Research Science。**

---

# Part VIII｜职业战略：让就业成为长期目标的训练场

## 23. 就业与学习的双重排序

个人偏好排序：

```text
QD
> QR
> Financial-AI
> Applied AI
> Vertical-AI
```

建议进一步解释为：

- **就业第一身份：Quant Developer / Research Engineer**——最容易兑现现有 systems/C++/engineering；
- **学习第一优先：Quantitative Research Science**——是未来 Fundamental Quant 必须补出的第四块；
- **长期迁移方向：Systematic Equity / Fundamental Quant / Financial AI**；
- **安全垫：Applied AI / Vertical AI**，尤其是有真实 domain、data、evaluation、production 的场景。

## 24. 为什么技术栈不能丢，但不能再成为终点

中国量化招聘长期偏 STEM、数学、计算机与强编程，这使 C++、系统与算法仍然是现实就业“门票”。但门票与长期稀缺性必须分开：

```text
C++ / Python / LLM / Framework
= Capability Components
≠ Identity
```

职业身份应逐渐收敛为：

> **Quant / ML Research Engineer with strong systems background, accounting/finance domain knowledge and AI-native engineering capability.**

## 25. 平台优先于过早创业

当前最重要的不是决定未来是否创办量化公司，而是获得：

- 真实金融数据；
- 真实资本与 risk constraints；
- 严谨研究者；
- production research infra；
- 大规模实验反馈；
- 市场微观结构与执行经验；
- 组织化 research taste。

未来是否创业，应建立在已经拥有可复用研究机器、团队互补能力、合法合规基础与真实 edge 之上。

## 26. GitHub：从“学习仓库”升级为 Proof-of-Work Portfolio

长期建议 pinned portfolio：

1. `AlphaResearchOS`：旗舰；
2. `AuditAI-Workbench`：Vertical AI / AI Engineering；
3. `quant_trade` 或其升级版：C++ / QD；
4. 一个从主系统真实抽离的 OSS 高质量组件；
5. Fundamental Quant Research reports / lab；
6. 其他可选。

`C_Journey` 保留为历史学习轨迹即可；`quant_start` 应逐渐被新研究系统吸收。

开源原则：

```text
Solve real problem internally
→ Reuse
→ Discover stable abstraction
→ Open source infrastructure/component
```

优先开源基础设施、评估、数据抽象、性能组件；未来真正持续有效的 Alpha 配方不需要为了证明能力而公开。

---

# Part IX｜AI-Native Learning System：如何在 AI 时代真正学会

## 27. 学习的定义

学习不是“能看懂”，也不是“把原项目逐行默写一次”。

> **学习 = 内部模型发生持久变化，使人在面对相似但不完全相同的问题时，能够更好地解释、预测、判断、行动。**

能力层级：

```text
Recognition
→ Explanation
→ Reconstruction
→ Transfer
→ Judgment
```

真正高价值的终点是 Judgment，而不是 surface recall。

## 28. AI 学习的核心悖论

AI 使外部产出能力迅速增长：

```text
Augmented Performance ↑↑
```

但内部能力并不会自动同速增长：

```text
Internalized Competence ?
```

2026 年 Anthropic 的随机对照实验发现，在其特定实验中，使用 AI 的开发者后续知识测试平均明显较低；但“用 AI 追问解释、概念、为什么，同时仍主动编码”的参与者掌握更好。这支持一个关键结论：

> **问题不是用不用 AI，而是 AI 交互方式是否包含主动理解与认知回收。**

## 29. 项目驱动 + 即时学习 + 周期性补骨架

主学习范式：

```text
Problem-Driven
+ Just-in-Time
+ AI-Scaffolded
+ Periodic Systematic Consolidation
```

项目负责告诉自己“为什么要学”；系统学习负责防止知识变成 Swiss Cheese。

不再把 1000 小时课程当必须顺序播放的 Netflix，而把课程/书/文档当：

> **Knowledge Index + Dependency Map。**

先识别不可跳过的 trunk，再由真实问题触发 branches。

## 30. AI-Native Learning Loop

```text
Problem
→ Scaffold
→ Understand
→ Build
→ Break
→ Retrieve
→ Transfer
→ Reflect
```

解释：

- **Problem**：从真实问题开始；
- **Scaffold**：AI 给最小知识地图、方案与示例；
- **Understand**：先问 why、inputs/outputs、invariant、failure mode；
- **Build**：允许大量 AI 实现；
- **Break**：主动构造边界、错误和 counterexample；
- **Retrieve**：关 AI，自行讲述/实现核心；
- **Transfer**：换一个新问题验证是否能迁移；
- **Reflect**：压缩为 mental model 和下一步问题。

## 31. 三种工作模式

### 31.1 Build Mode

目标：最大化真实项目进展。

AI 高度参与：boilerplate、adapter、tests scaffold、docs、refactor、integration、重复工程实现。

人负责：problem selection、architecture、spec、acceptance、review、integration、risk、trade-off。

### 31.2 Learn Mode

目标：最大化 internalization。

AI 改为 Socratic tutor：先解释、提问、给 hint、review，不直接交关键答案。

### 31.3 Exam Mode

目标：测量“到底什么已经是自己的”。

AI 尽量关闭，只测：

- 核心概念；
- 核心算法；
- 核心架构；
- debugging；
- 新变体。

失败不是挫败，而是高价值 Learning Signal。

## 32. Selective Reconstruction，而不是默写整个项目

建议启发式：

```text
Critical Core → self reconstruction
Boilerplate / repeated implementation → AI
```

例如 OrderBook：应能独立重建 matching core、状态转换、风险边界，并解释复杂度；不必手抄全部 CMake、logging、factory boilerplate。

量化研究中，以下属于 **Low Delegation / High Internalization**：

- probability；
- expectation / variance；
- inference；
- regression；
- bias/variance；
- cross-validation；
- look-ahead / survivorship；
- factor exposure / neutralization；
- IC；
- portfolio risk；
- transaction cost。

而以下可 **High Delegation**：

- adapters；
- schema / serialization；
- plotting；
- CLI；
- config；
- CI；
- report generation；
- test scaffolding；
- repetitive data plumbing。

## 33. 判断“该不该让 AI 做”的三个问题

每次只问：

1. **这件事本身是不是我要获得的能力？**
2. **AI 做完以后，我有没有能力验证它？**
3. **AI 省下的时间，我是否真的投入了更高层的问题？**

典型判断：

```text
No / Yes / Yes → 大胆委托 AI
Yes / No / No  → 必须自己做
```

## 34. Anti-Illusion Mechanism：防止“看懂了”的幻觉

### 34.1 Prediction before Generation

AI 输出前先预测 30–120 秒：

- 我会怎么设计？
- 哪些 class/interface？
- 最大风险？
- 结果大概是什么？

再看 AI 输出，利用 prediction error 更新模型。

### 34.2 Teacher → Adversary → Reality

```text
AI Teacher
→ Human Model
→ AI Adversary
→ Reality / Test / Data / Docs
```

必须让 AI 主动反驳、构造 counterexample、寻找漏洞；最终由测试、数据、论文、官方文档和真实运行裁决。

### 34.3 Coherence ≠ Truth

AI 会显著提高表达的自洽性，但逻辑漂亮不等于世界真实。Quant 项目应成为最严格的 epistemic gym：

```text
Beautiful story
→ OOS test
→ Costs
→ Reality decides
```

## 35. Code Ownership ≠ Code Authorship

前沿 agentic engineering 正在把人的注意力从逐行 implementation 上移到 specification、architecture、evaluation 与 feedback loops。OpenAI 公开的 agent-first 工程实验甚至展示了由 Codex 生成全部应用代码、测试、CI、文档和 observability 的内部产品实验；Anthropic 的 Claude Code 使用研究也显示，典型交互中人更多决定“做什么”，Agent 更多决定“怎么实现”，而领域专家往往能让 Agent 每条指令完成更多有效工作。

这不意味着基础知识不重要。恰恰相反：AI 生成越多，能否审查、调试、定义 invariant 与识别错误越重要。

长期目标可以是：

```text
AI Authorship → very high
Human Understanding / Judgment → must remain high
```

---

# Part X｜未来一年研发与学习路线（2026.09–2027.08）

## 36. 总原则

未来一年不新开五个互相分离的学习项目，而采用：

```text
One Core System
→ Multiple Capability Proofs
```

Alpha Research OS 同时作为：

- Python 学习载体；
- Statistics / Quant 学习载体；
- Fundamental Finance 学习载体；
- AI Agent 学习载体；
- C++ QD 升级载体；
- GitHub 旗舰作品；
- 面试故事与职业迁移载体。

## 37. Phase 1｜Research Foundation（2026.09–10）

**System Objective**：把 `quant_start` 的教育型 demo 重构成独立于具体数据源的 research kernel。

重点：

- Python 深化；
- NumPy / pandas / Polars；
- SQL / DuckDB；
- package / pytest / type hints；
- data source interface；
- normalized dataset；
- reproducible config；
- 基础统计。

**Human Objective**：真正具备 Python research fluency，而不是“能看懂 AI 写的 pandas”。

**Exam Mode 示例**：独立写一个无 look-ahead 的 single-factor backtest，并解释时间语义。

## 38. Phase 2｜Point-in-Time Fundamental Data Plane（2026.11–12）

重点：

- financial statement schema；
- publication/effective time；
- restatement；
- corporate action；
- universe history；
- identifier mapping；
- data lineage。

**Human Objective**：把会计语义、数据工程与 research leakage 真正串起来。

## 39. Phase 3｜Fundamental Alpha Lab（2027.01–02）

目标：完成 2–3 个完整而不是“漂亮”的 empirical research case。

首选从 domain advantage 出发：

- accruals / earnings quality；
- ROIC / capital efficiency；
- cash-flow quality；
- working capital / revenue quality；
- fundamental momentum。

每项必须包含：

```text
Economic Hypothesis
→ Data Definition
→ Feature
→ Cross-sectional Test
→ Neutralization
→ IC / Portfolio
→ OOS
→ Costs
→ Failure Analysis
→ Research Report
```

## 40. Phase 4｜AI Fundamental Engine（2027.03–04）

目标：将 Audit Workbench 的 evidence-first 思想迁移至金融文本。

候选 vertical slice：

```text
10-K / Annual Report / Announcement
→ Evidence Extraction
→ Structured Assertion
→ Deterministic Validation
→ Feature Candidate
→ Empirical Test
```

AI 不直接输出交易建议，而输出**可审计研究对象**。

## 41. Phase 5｜Portfolio + C++ Execution Bridge（2027.05–06）

重点：

- forecast standardization；
- position sizing；
- risk；
- transaction cost；
- optimizer；
- event-driven simulator；
- Python research → C++ execution bridge。

将已有 `quant_trade` 的教育成果逐步升级为系统末端，而不是重新造一套孤立项目。

## 42. Phase 6｜Multi-Strategy + Hardening + OSS（2027.07–08）

重点：

- signal combination；
- common forecast protocol；
- experiment registry；
- benchmark / profiling；
- monitoring；
- one reusable high-quality OSS component；
- Alpha Research OS v0.1 release / technical report。

成功标准不是“目录都实现”，而是存在至少一个从 evidence/data 到 portfolio 的**完整、严格、可复现 vertical slice**。

---

# Part XI｜并行系统：不要让主项目吞掉所有人生

## 43. Audit AI Workbench

继续线上推进，但定位明确：

> **真实 Vertical AI / workflow / evaluation 的长期实验场。**

它提供 Alpha Research OS 暂时无法提供的：真实用户、真实业务、真实 failure、deployment 与组织信任。

## 44. LeetCode

定位：

> **Interview Infrastructure + Independent Problem-Solving Gym。**

继续独立手写。大致可保持 C++ 为主、Python 为辅；不让其吞噬主项目时间，但在当前招聘制度仍有效时不提前放弃门票训练。

## 45. 专业英语：把兴趣输入变成职业能力

每周只精读/精听 2 个内容：

- 1 个 Quant / systematic investing；
- 1 个 AI / Agent engineering。

推荐长期来源：

- Flirting with Models；
- Two Sigma Insights / feature research；
- BlackRock Systematic Investing；
- AQR Research；
- Man Group Insights；
- Latent Space；
- OpenAI Engineering / Podcast；
- Anthropic engineering/research。

固定 ritual：

```text
Blind Listening
→ Transcript Check
→ 5–10 Professional Expressions
→ 3-min English Summary
→ 1–2 min My View
→ Written Research Note
```

Research note 固定四段：

```text
What I heard
Key concepts
My interpretation
Connection to AlphaResearchOS
```

一年后形成 50+ 条专业研究笔记，同时训练 listening、technical vocabulary、synthesis、research taste 与面试表达。

---

# Part XII｜反模式：这些事情看起来努力，但应主动避免

## 46. 不造“终极系统”

系统架构是北极星，不是 feature checklist。优先完成纵向闭环，而不是横向铺满目录。

## 47. 不做 Factor Zoo

每增加一个因子都必须有：经济解释、数据定义、独立性、OOS、成本与失效条件。研究数量不是 KPI。

## 48. 不做“LLM 直接炒股 Demo”作为核心作品

LLM 的输出如果不可复现、不可审计、不可做 point-in-time validation，就不能承担高风险资本决策权。

## 49. 不为了“学扎实”逐行默写全部 AI 代码

采用 Selective Reconstruction。把有限人生投入最稳定、最基础、最关键的 mental models。

## 50. 不为了“高效”而永远不独立提取

任何重要能力都必须周期性进入 Exam Mode，否则 augmented performance 会掩盖内部能力空洞。

## 51. 不把课程完成率当学习成果

课程是索引，不是终点。目标是 mental model + transfer。

## 52. 不把技术栈变成身份

不因为“我是 C++”而拒绝 Python，也不因为“AI 很强”而放弃 systems fundamentals。

## 53. 不让宏大叙事压过 empirical evidence

长期气质：

```text
Big Theory
+
Brutal Empiricism
```

尤其在金融中，市场不奖励故事完整度，只奖励可执行、可持续的 edge。

---

# Part XIII｜项目治理：让研究和学习都可追踪

## 54. 每个研究都应成为 First-class Artifact

建议每个 experiment 至少拥有：

```text
experiment_id
hypothesis
economic_rationale
data_snapshot
universe
feature_definition
code_commit
parameters
results
oos_results
cost_assumptions
failure_modes
status: candidate / accepted / rejected / retired
```

研究失败也必须保留。Rejected ideas 是防止未来重复踩坑的知识资产。

## 55. Decision Journal

重大研究/架构/职业决策记录：

- 当时知道什么；
- 当时不知道什么；
- 核心假设；
- 概率判断；
- 为什么选择；
- 什么证据会使观点失效。

未来复盘应评价**决策质量**，而不只是结果好坏。

## 56. Human Learning Ledger

每个 milestone 同时记录：

```text
System Learning Objective
Human Learning Objective
AI Delegation Boundary
Exam-mode Check
Transfer Task
```

确保项目不是只有仓库在变强。

---

# Part XIV｜一年后的目标画像

## 57. 不以“做完系统”为 KPI，而以能力跃迁为 KPI

一年后的目标不是自称“优秀 Quant”，而是能够真实完成：

### 57.1 Research

```text
Research Question
→ Point-in-Time Dataset
→ Economic Hypothesis
→ Feature
→ Statistical Test
→ Neutralization
→ OOS
→ Costs
→ Portfolio
→ Research Report
```

### 57.2 Fundamental / AI

面对一份财报或公告，能够设计 evidence-backed workflow，把非结构化信息变成可验证的 feature candidate，而不是让 Agent 给主观买卖结论。

### 57.3 Engineering

能把 research-generated target positions 接入 event-driven execution simulation，理解系统性能、正确性、risk 与 recovery 边界。

### 57.4 Judgment

能审查 AI 生成的大型实现；知道哪些地方自己不懂；能提出反例和 failure mode；不把“能跑”当“正确”。

### 57.5 Career Signal

对于 QD / Research Engineer / Applied AI in Quant，应形成强而连续的作品证据；对于纯 QR，至少从“新手”进入可以严肃讨论 empirical research 的候选人状态。

---

# Part XV｜最终统一：这台机器到底是什么

## 58. 最终定义

所谓“新世纪量化交易系统”，不是传统意义上：

```text
Market Data → Strategy → Order
```

而是：

```text
World
→ Information
→ Evidence
→ Cognition
→ Forecast
→ Price Comparison
→ Edge
→ Capital Allocation
→ Execution
→ Market Feedback
→ Model Update
```

其中：

- **信息**告诉系统世界发生了什么；
- **认知/模型**解释它意味着什么；
- **价格**压缩市场已经知道和相信了什么；
- **Edge**是自己模型相对于价格隐含模型的可行动增量；
- **资本**把认知优势放大；
- **执行**把决策变成现实；
- **风险和生存**决定有没有机会等到价值兑现；
- **所有权**决定价值最终如何形成财富；
- **AI**降低认知生产和非结构化信息处理的成本；
- **Evaluation**防止模型、Agent 和人共同制造“漂亮但错误”的幻觉。

所以 Alpha Research Operating System 最深层的定义是：

> **一台把现实世界信息转化为可验证认知，再把认知差异通过纪律化资本配置货币化，并持续从现实反馈中更新自身的机器。**

而个人的长期目标也与之完全同构：

> **成为能够进入复杂专业领域，建立正确的世界模型，把隐性问题形式化为计算系统，利用 AI 放大实现和研究能力，并通过验证、工程、资本配置和现实反馈把认知真正变成价值的人。**

---

# Appendix A｜长期最重要的能力树

```text
Personal Moat
=
Domain Understanding
× Systems Thinking
× AI Leverage
× Quantitative Research Science
× Evaluation / Judgment
× Product / Problem Selection
× Deployment / Organizational Trust
× Learning Velocity
```

其中本阶段四大主拼图：

```text
Accounting / Finance
×
CS / Systems / C++
×
AI-Native Engineering
×
Quantitative Research Science
```

第四块是未来一年最大增量投资方向。

---

# Appendix B｜价值投资技能树（用于后续系统课程设计）

1. 商业模式与价值驱动因素；
2. 财务报表、会计语义与 earnings quality；
3. Unit economics、ROIC 与资本回报；
4. 产业结构、竞争优势与 moat；
5. 管理层与 capital allocation；
6. DCF / multiples / SOTP 等估值；
7. Reverse valuation / implied expectations；
8. Probability / Bayesian thinking / scenarios；
9. Risk / permanent capital loss；
10. Behavioral finance；
11. Decision science；
12. Portfolio construction；
13. Research / data sourcing；
14. Falsification；
15. Time horizon / patience / thesis updating。

---

# Appendix C｜AI Delegation Matrix

| 任务类型 | 默认 AI 参与 | 人必须保留的能力 |
|---|---:|---|
| Boilerplate / Adapter / CLI / Config | 高 | API 边界、验收 |
| Test scaffolding / Docs | 高 | 测试意图、关键 case |
| Non-structured extraction | 高 | schema、evidence、validation |
| Architecture candidate | 中高 | trade-off、invariant、ownership |
| Core statistics / inference | 低到中 | 必须能独立解释与实现核心 |
| Backtest accounting | 中 | 时间语义、成本、leakage 必须掌握 |
| Portfolio / Risk | 中 | 假设、约束、失败模式必须掌握 |
| Execution critical path | 中 | state、risk、recovery、correctness |
| Final capital authorization | 低 | deterministic gate / human ownership |

---

# Appendix D｜当前项目基线快照（2026-08-20）

### D.1 `C_Journey`

性质：早期纯手工 CS / C 学习轨迹。  
长期作用：证明底层学习路径，不建议投入大量时间重构。

### D.2 `quant_trade`

性质：C++17 教育型交易系统 / QD foundation。  
已有：OMS/OrderBook/Exchange/Feed/Strategy/Risk/CMake/GTest/Sanitizer 思维。  
下一步：逐渐作为 AlphaResearchOS 的 execution 子系统，而不是孤立扩建。

### D.3 `quant_start`

性质：Python Quant learning demo。  
已有：data loader、MA signals、stateful position、简单 backtest/metrics。  
下一步：停止继续堆 feature，重构为 Phase 1 research kernel；首先解耦 data provider 与 research core。

### D.4 `AuditAI-Workbench`

性质：当前最具差异化的 AI-Native Engineering / Vertical Workflow 项目。  
下一步：继续真实用户与 field test；将 evidence/state/validation/eval 等稳定 primitive 迁移到金融研究。

---

# Appendix E｜外部行业与研究信号（仅作为当前证据，不作为不可变真理）

1. **OpenAI, “Harness engineering: leveraging Codex in an agent-first world”, 2026-02-11.**  
   公开展示 agent-first 工程实验：人更多负责环境、意图、反馈与验收，Agent 执行大规模实现。  
   https://openai.com/index/harness-engineering/

2. **OpenAI, “Unrolling the Codex agent loop”, 2026-01-23.**  
   将 agent/harness 明确拆解为 model、instructions、tools、context 与 execution loop。  
   https://openai.com/index/unrolling-the-codex-agent-loop/

3. **Anthropic, “How AI assistance impacts the formation of coding skills”, 2026-01-29.**  
   RCT 显示 AI 辅助与 skill formation 存在潜在 trade-off；主动追问解释和概念的使用方式表现更好。  
   https://www.anthropic.com/research/AI-assistance-coding-skills

4. **Anthropic, “Agentic coding and persistent returns to expertise”, 2026-06-16.**  
   对约 40 万 Claude Code session 的研究显示，典型协作中人更多做 planning、Agent 更多做 execution；领域 expertise 仍产生持续回报。  
   https://www.anthropic.com/research/claude-code-expertise

5. **Two Sigma, Ben Wellington, “Anything Can Be Language Now: My Thoughts on the Future of Features Research”, 2026-07-09.**  
   强调 Quant edge 从 raw data 向 feature shaping / representation 移动，LLM 降低非结构化特征探索成本。  
   https://www.twosigma.com/articles/anything-can-be-language-now-my-thoughts-on-the-future-of-features-research/

6. **G-Research, “Quantitative Researcher – Fundamental Equity Research”, current 2026 listing.**  
   证明 fundamental equity knowledge 与 quantitative research 的交叉岗位真实存在。  
   https://www.gresearch.com/vacancies/quantitative-researcher-fundamental-equity-research/

7. **G-Research, “Applied AI Engineer”, current 2026 listing.**  
   证明 Agent / AI engineering 与 Quant Research workflow 已出现明确职业交叉。  
   https://www.gresearch.com/vacancies/ai-engineer/

8. **BlackRock, “Quantitative Researcher – Systematic Active Equity”, current 2026 listing.**  
   职位强调 markets、ML/AI、data science、economics 与 systematic alpha research 的组合。  
   https://careers.blackrock.com/job/london/associate-quantitative-researcher-systematic-active-equity/45831/99017512480

---

# Appendix F｜内部来源与历史材料

1. 《一名程序员眼里中国量化投资的未来》（用户提供 Markdown 归档）。  
   采用内容：量化的决策方式定义、市场效率/Alpha 衰减、多策略、基本面量化方向。  
   注意：文中行业数字与时间预测属于其历史语境，不作为 2026 年当前事实。

2. `AI_NATIVE_ENGINEERING_PERSONAL_MOAT_2026-08-18.md`。  
   采用内容：AI-Native Systems / Agent Engineer + Vertical Workflow Architect 定位；Vibe Engineering；Domain → Computational Abstraction；Evaluation/Verification；Deployment/Trust；Personal Moat；长期学习与产品原则。

3. 四个项目源码快照：`C_Journey`、`quant_trade`、`quant_start`、`AuditAI-Workbench`。  
   采用内容：当前个人工程与研究能力 baseline，用于制定未来一年学习与研发依赖。

---

# Appendix G｜本文件的更新协议

未来修改此 Founding Document 时遵循：

1. **原则层**修改必须说明反证或重大新事实；
2. **假设层**允许随着 empirical evidence 更新；
3. **架构层**只要更好服务原则即可重构；
4. **路线图层**每 4–8 周根据实际进展调整；
5. 每次重大版本保留 `What changed / Why changed / Evidence`；
6. 不因新技术热度改变长期身份；只问：

```text
如果模型能力再提高 10 倍，
这项能力是升值还是贬值？
```

最终长期判断：

> **不要把稀缺性建立在“今天比别人更会使用 AI”上；要把稀缺性建立在“AI 越强，越能够利用它解决更复杂、更真实、更高价值的问题”上。**

---

**End of Founding Document v0.1**
