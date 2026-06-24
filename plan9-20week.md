# 下学期计划：Stable Domain and Powerdomain

## 学习与科研训练模板

这份计划不是单纯的阅读列表。每个小节都要训练一种基本科研能力：从教材和论文中提取定义、识别关键例子、检查证明依赖、发现不清楚的问题，并把问题整理成可以继续查文献或尝试证明的形式。

### 课前怎么读

- 先快速通读本小节材料，标出所有定义、定理、例子和看不懂的术语。
- 第二遍只读定义和例子。每个定义都要回答三个问题：它比前一个概念多了什么条件？这个条件用来排除什么坏例子？这个条件在后面的哪个定理中被使用？
- 不要只抄定义。每个定义至少配一个小例子和一个非例子；如果找不到非例子，说明还没有理解这个定义的边界。
- 读证明时先找结构，不要一行一行硬啃。先写出证明依赖了哪些引理、用了哪些假设、结论最关键的一步在哪里。
- 遇到不懂的背景，不要跳过。先查教材、survey 或原论文，也可以问 AI 辅助梳理；但最后要回到可靠资料核对，把术语的最小可用版本补上。实在不懂就记录成问题。

### 课上怎么听和讨论

- 听汇报时不要只记结论，要追问“为什么要这样定义”和“这个假设如果去掉会怎样”。
- 每次讨论至少保留三个层次的问题：概念问题、证明问题、研究问题。
- 概念问题例子：stable order 和 extensional order 到底差在哪里？
- 证明问题例子：某个函数空间构造为什么仍然落在 stable domain 范畴中？
- 研究问题例子：某个 powerdomain 构造是否保持 stable universal domain 需要的闭性？

### 课后怎么自测

每次课后用下面的清单检查自己是否真的掌握：

- 我能不用书写出本节 3 个核心定义吗？
- 我能给每个定义举出一个例子和一个非例子吗？
- 我能解释本节最重要定理的证明思路，而不是只复述结论吗？
- 我知道每个关键假设在哪里被使用吗？
- 我能说清楚这个小节和 PCF、sequentiality、full abstraction 或 powerdomain 的关系吗？
- 我能提出至少一个具体、可查文献或可尝试证明的问题吗？

如果以上问题答不上来，就不要把本节标记为“已经学完”。应把缺口写进小节总结，下一次讨论优先处理。

### 怎么发现问题

发现问题不是随便问“这个方向还能做什么”。先查阅教材、survey、原论文和最新论文，也可以问 AI 帮助梳理背景，但不能停留在 AI 的回答上。需要自己整理清楚：这个问题现在已经做到什么程度，最新相关文献有哪些，哪些结论已经证明，哪些条件还不清楚，哪些遗留问题仍然没有解决。完成这一步后，再从下面几种缺口中找具体问题：

- 定义缺口：两个定义看起来相似，但不知道是否等价。
- 例子缺口：教材给了正例，但没有给反例或边界例子。
- 假设缺口：定理用了某个条件，但不清楚去掉后是否仍成立。
- 构造缺口：某个对象能构造出来，但不知道是否保持闭性、连续性、稳定性或 universal property。
- 对照缺口：Scott semantics、stable semantics、game semantics 或 powerdomain semantics 中同一个现象的表达方式不一致。
- 文献缺口：不同论文使用不同术语或不同范畴，需要整理翻译表。

### 每小节固定产出

每个小节不强制拆成多个文件，但必须留下可追踪的记录。可以手写，也可以做成文件。记录至少包含：

- 核心定义、例子、非例子。
- 主要定理的证明路线和依赖关系。
- 概念问题、证明问题、研究问题。
- 本小节涉及的教材、论文、survey，以及每篇材料解决了什么。
- 哪些问题已经解决，哪些问题仍然开放，哪些只是因为资料没查够。

另外，每个小节主讲人需要提前一周给出简短预告，说明下一次大概讲什么、准备怎么讲、希望大家提前看哪些材料、有哪些问题需要大家一起讨论。

## 总体目标

本计划覆盖下学期 6 个小节，每小节两次课。前 3 个小节先围绕 stable domain 展开，目标是从 PCF、sequentiality 和 full abstraction 的问题出发，理解 stable domains/stable functions 的动机、正式定义、解决了什么，以及为什么仍需走向 game semantics。后 3 个小节再转向 powerdomain，目标是理解非确定性计算效应为什么需要幂域，以及这些幂域如何通过 monad、free algebra 和 stable powerdomain 等视角组织起来。

讨论班仍采用原来的方式：

- 第一次课：主讲人汇报主要定义、例子和定理。
- 第二次课：围绕遗留问题深入讨论，补充证明、例子和反例。
- 每个小节结束后整理一页小结：核心定义、典型例子、仍未解决的问题。

## 时间安排

默认从 2026-09-07 开始，每周一下午 2:30。2026-10-05 为国庆周，建议暂停一次；若实际不停课，则第 3 小节及后续内容可整体提前一周。

| 小节 | 日期 | 主题 | 主材料 |
| :--- | :--- | :--- | :--- |
| 1 | 09/07, 09/14 | Stable domain / stable function 入门与研究现状；coherence space 和 stable universal domain 讨论 | Amadio-Curien；寇老师相关论文；补充文献 |
| 2 | 09/21, 09/28 | 带着问题精读 Curien stable domain 相关章节 | Amadio-Curien, *Domains and Lambda-Calculi* |
| 休 | 10/05 | 国庆周暂停 | 整理前两节问题 |
| 3 | 10/12, 10/19 | Stable semantics 到 game semantics | Amadio-Curien；Abramsky-McCusker / Hyland-Ong 概览 |
| 4 | 10/26, 11/02 | Monad 与 Powerdomain 数学；PCF-like 非确定性例子 | Moggi；`Semantic_Domains_and_Denotational_Semantics.pdf` |
| 5 | 11/09, 11/16 | Hoare / Smyth / Plotkin 三种幂 domain | `Semantic_Domains_and_Denotational_Semantics.pdf` 1.5 |
| 6 | 11/23, 11/30 | Stable powerdomain | Stable powerdomain 相关材料；Hoare/Smyth/Plotkin 回顾 |

## 小节 1：Stable Domain / Stable Function 入门与研究现状

### 核心问题

- stable domain、stable order、stable function 的基本概念是什么？
- 为什么 stable function 可以表达“输出依赖于输入的最小信息”？
- stable domain 与 Scott domain、coherence space、sequentiality、full abstraction 的关系是什么？
- 这条线目前有哪些仍在被讨论的问题？
- 寇老师关于 coherence space、stable universal domain 的论文与 Amadio-Curien 教材中的框架如何对应？

### 阅读重点

主参考为 Roberto Amadio and Pierre-Louis Curien, *Domains and Lambda-Calculi* 中 stable domains / stable functions 的相关章节。第一次课不要求立即进入所有技术证明，但要先把概念网络搭起来：

- stable function 的定义、直觉和基本例子；
- stable order 与 extensional order 的区别；
- trace 如何记录最小输入依赖；
- coherence spaces 与 stable functions 的关系；
- stable universal domain 的问题意识：是否存在足够大的、闭合性良好的稳定语义宇宙，可以统一解释函数空间、递归类型或相关构造。

同时主讲人需要主动搜集文献，把不熟悉的背景先补清楚。初始文献清单包括：

- Berry, *Stable Models of Typed Lambda-Calculi*。
- Fritz Mueller, *On Berry's conjectures about the stable order in PCF*。
- Abramsky, Jagadeesan, Malacaria, *Full Abstraction for PCF*。
- Koutavas, Lin, Tzevelekos, *Fully Abstract Normal Form Bisimulation for Call-by-Value PCF*。
- 寇老师关于 coherence space、stable universal domain 的论文或讲义，由主讲人在课前补充准确题名、版本和链接。

### 两次课安排

- 第一次课：先讲 stable domain、stable order、stable function、trace 等概念；讲解时顺带回顾 PCF、sequentiality、full abstraction 的背景，并梳理这条线的研究现状和可读文献。
- 第二次课：集中讨论寇老师关于 coherence space、stable universal domain 的论文相关内容，对照 Amadio-Curien 的定义体系，分析还有哪些问题可以继续做。

### 本节产出

整理三份材料：

- 一页概念图：stable domain、stable function、trace、coherence space、stable universal domain。
- 一页研究现状表：经典文献、近年相关工作、每篇文章解决的问题。
- 一页问题清单：寇老师论文中可继续推进的定义、构造、闭性、反例或应用问题。

## 小节 2：带着问题精读 Curien Stable Domain 相关章节

### 核心问题

- Amadio-Curien 中 stable domain 的正式定义是什么？
- stable order 与 extensional order 的区别是什么？
- stable function 与 Scott continuous function 的关系是什么？
- trace / coherence / stability 这些概念如何表达“输入信息的依赖关系”？
- function space、cartesian closedness、递归定义和 universal domain 在 stable 语义中分别需要哪些条件？
- 哪些定义只是形式上类似 Scott domain，哪些地方本质上更强？

### 阅读重点

主读 Roberto Amadio and Pierre-Louis Curien, *Domains and Lambda-Calculi* 中关于 stable domains、stable functions、sequentiality 的相关章节。具体页码根据实际使用版本再补充。

本节不做泛泛阅读，而是带着第 1 小节留下的问题逐条精读：

- 定义是否依赖 algebraicity、bounded completeness、coherence 或 event-structure 式结构？
- stable functions 是否对交、相容并、有限近似有额外保持条件？
- trace 表示是否能完全恢复 stable function？
- stable function space 的构造如何保证范畴闭性？
- stable universal domain 的构造如果失败，失败点可能在哪里？

### 两次课安排

- 第一次课：逐条讲 stable domain / stable function 的定义，明确所有 order、continuity、stability、trace 条件，并把不懂的术语当场记录。
- 第二次课：通过例子比较 Scott continuous function 与 stable function，整理 stable category 的基本性质，并回到第 1 小节的问题清单判断哪些问题已经解决、哪些还需要查文献。

### 本节产出

- 一张定义表：extensional order、stable order、stable function、trace、coherence condition。
- 一个具体函数例子：说明它是 Scott continuous 但不 stable，或说明 stable 条件如何限制依赖结构。
- 一张“问题-教材位置-是否解决”对照表。

## 小节 3：Stable Semantics 到 Game Semantics

### 核心问题

- stable semantics 为什么仍然不是 PCF full abstraction 的终点？
- game semantics 把程序看成什么样的交互对象？
- strategy 如何比 domain element / stable function 更细致地记录 sequential behavior？
- stable semantics 与 game semantics 的概念桥梁是什么？
- arena/game、move、justification/enabling、P/O polarity、legal play、strategy、innocence、visibility 等定义分别是什么？
- PCF full abstraction 的 game-semantics 证明思路是什么？

### 两次课安排

- 第一次课：从 stable semantics 的局限出发，讲清 game semantics 的基本定义：arena/game、moves、enabling relation、合法 play、strategy、composition，以及这些定义如何表达程序与环境的交互。
- 第二次课：概览 game semantics 如何处理 PCF full abstraction。虽然不进入完整证明技术细节，但必须弄清证明结构：soundness/adequacy、definability、innocent 或 history-free strategies、quotient 或 intrinsic preorder，以及为什么这些步骤导向 full abstraction。

### 本节产出

整理一张模型比较表：

| 模型 | 函数空间中的 morphism | 优点 | 局限 |
| :--- | :--- | :--- | :--- |
| Scott domains | Scott continuous functions | 适合递归和不动点 | 允许非顺序函数 |
| Stable domains | stable functions | 捕捉部分 sequential dependence | 仍不够细致 |
| Game semantics | strategies | 记录交互过程和调用顺序 | 技术体系更复杂 |

另整理一页 game semantics 证明路线图：

```text
syntax of PCF
-> games/arenas for types
-> strategies for terms
-> adequacy/soundness
-> definability of compact strategies or relevant finite behaviours
-> quotient/order-extensional collapse if needed
-> full abstraction
```

## 小节 4：Monad 与 Powerdomain 数学

### 核心问题

- 为什么普通 domain $D$ 只描述确定性计算，而非确定性计算需要某种 $P(D)$？
- Monad 的 `unit`、`bind`、Kleisli composition 在程序语义中分别对应什么？
- 为什么 powerset monad 在 Set 中很自然，但在 Domain 中需要 powerdomain？
- 如何用类似 PCF 的语言展示 powerdomain 的必要性？

### 建议例子

使用一个 PCF-like 语言，在 PCF 基础上加入有限非确定性选择：

```text
M, N ::= x | lambda x. M | M N | fix M | 0 | succ M | ifz M then N else L | M op N
```

其中 `M op N` 表示非确定性选择。类型解释从普通的

```text
[[sigma -> tau]] = [[sigma]] -> [[tau]]
```

变为带效应的 Kleisli 形式：

```text
[[sigma -> tau]] = [[sigma]] -> P([[tau]])
```

这里 $P$ 是某种 powerdomain monad。本小节不急于区分 Hoare/Smyth/Plotkin，而是先弄清楚为什么需要 $P$，以及为什么 `bind` 正是在组合带非确定性结果的程序。

### 两次课安排

- 第一次课：讲 monad 的基本定义，重点解释 `unit`、`bind`、Kleisli category 和 computational effect。
- 第二次课：用 PCF-like 非确定性选择例子重写指称语义，解释为什么 $D \to P(E)$ 比 $D \to E$ 更合适。

### 本节产出

- 一页 monad 速查表：`unit`、`bind`、Kleisli composition、monad laws 的程序含义。
- 一个 PCF-like 非确定性小语言的语义草图。

## 小节 5：Hoare / Smyth / Plotkin 三种幂 Domain

### 核心问题

- Hoare、Smyth、Plotkin 三种 powerdomain 分别捕捉哪种非确定性观察？
- lower / upper / convex powerdomain 与 may / must / erratic nondeterminism 的关系是什么？
- 为什么不能直接用普通子集 ordered by inclusion？
- Egli-Milner order 在 Plotkin powerdomain 中扮演什么角色？
- 三种 powerdomain 如何体现 free algebra / monad 的观点？

### 两次课安排

- 第一次课：讲 Hoare lower powerdomain 与 Smyth upper powerdomain，比较 partial correctness / total correctness 的直觉。
- 第二次课：讲 Plotkin convex powerdomain 和 Egli-Milner order，比较三种幂域的定义、序结构和程序解释。

### 本节产出

整理一张对照表：

| 幂域 | 常用名称 | 序的直觉 | 程序语义直觉 | 典型观察 |
| :--- | :--- | :--- | :--- | :--- |
| Hoare | lower powerdomain | may information 增加 | 可能终止结果 | partial correctness |
| Smyth | upper powerdomain | must information 增加 | 保证结果 / 必须性质 | total correctness |
| Plotkin | convex powerdomain | may 与 must 同时记录 | erratic nondeterminism | Egli-Milner |

## 小节 6：Stable Powerdomain

### 核心问题

- stable powerdomain 想把 powerdomain 构造放进什么样的 stable / sequential 语义背景中？
- 在 stable domains / stable functions 的范畴中，Hoare、Smyth、Plotkin 幂域分别还能保留哪些性质？
- powerdomain 构造是否保持 stable domain 的闭性、函数空间构造或 universal-domain 结构？
- 非确定性选择与 sequentiality / stability 条件之间有什么张力？
- coherence space 视角下的 stable powerdomain 可以提出哪些新问题？

### 阅读重点

- stable powerdomain 相关材料：重点先理解问题意识，即 powerdomain 构造能否与 stable domains / stable functions 的 sequentiality 约束兼容。
- 回顾 Hoare / Smyth / Plotkin powerdomain 的定义，检查哪些构造可以移植到 stable 语义背景。
- 对照第 1、2 小节中的 coherence space、stable universal domain 问题，分析 stable powerdomain 是否给出新的构造路线或反例来源。

### 两次课安排

- 第一次课：回顾普通 Hoare / Smyth / Plotkin powerdomain，逐条检查这些构造与 stable order、stable function、trace 的兼容性。
- 第二次课：集中讨论 stable powerdomain 的可做问题：闭性、universal domain、coherence space 表示、反例构造，以及与 PCF-like 非确定性语义的关系。

### 本节产出

- 一页 stable powerdomain 问题清单：需要保留的稳定性条件、可能失败的闭性性质、与 Hoare/Smyth/Plotkin 幂域的关系。
- 一个 PCF-like 非确定性例子：说明普通 powerdomain 语义与 stable powerdomain 语义希望区分的现象。
- 一张“构造-闭性-待验证问题”表。

## 总结产出

学期结束时建议形成三个文档：

- `stable_domain_summary.md`：PCF full abstraction 问题、stable domain 定义、stable function 例子。
- `powerdomain_summary.md`：Monad、Hoare/Smyth/Plotkin、stable powerdomain。
- `model_comparison.md`：Scott semantics、stable semantics、game semantics、powerdomain semantics 的比较。
