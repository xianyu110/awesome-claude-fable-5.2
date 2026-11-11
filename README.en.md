# Awesome Claude Fable 5.2

A community catalog of real, sourced [Claude Fable 5.2](https://www.anthropic.com/claude/fable) use cases and public results. This is not an official Anthropic list.

Claude Fable 5.2 is Anthropic’s most capable generally available model for ambitious technical work (coding, long-running agents, science, finance, 3D and hardware). It shares an underlying model with the restricted Claude Mythos 5.2, but Fable ships with stronger cybersecurity and biology safeguards. **This repo only lists work that a source clearly attributes to Fable 5.2 (or to an earlier version of Fable 5.2). Mythos-only results are excluded.**

There are currently **58** entries. Every entry has a source URL we actually opened. Quotes, figures, and dates are restated from those pages; treat the originals as authoritative.

## Official links

- Product page: [Claude Fable](https://www.anthropic.com/claude/fable)
- Launch post (9 Nov 2026): [Introducing Claude Fable 5.2 and Claude Mythos 5.2](https://www.anthropic.com/claude-fable-and-mythos-5-2)
- Platform docs: [Fable 5.2 overview](https://platform.claude.com/docs/en/models/fable-5-2/overview)
- AWS: [Introducing Claude Fable 5.2 on AWS](https://aws.amazon.com/blogs/machine-learning/introducing-claude-fable-5-2-on-aws/)
- Hardware write-up: [Claude can design electronic prototypes from start to finish](https://www.anthropic.com/research/claude-electronics-design)

中文版：[README.md](./README.md). Structured data: [cases.json](./cases.json).

Browse the [GitHub Pages catalog](https://xianyu110.github.io/awesome-claude-fable-5.2/).

## Categories

| Category | Count |
|---|---:|
| Coding and agents | 9 |
| Science and mathematics | 6 |
| Finance and quantitative research | 7 |
| Legal, compliance, and knowledge work | 1 |
| 3D, hardware, and robotics | 6 |
| Community demos | 15 |
| Evaluations and benchmarks | 14 |
| **Total** | **58** |

## Cases

### Coding and agents

#### 1. Anthropic production service migrated from Python to Rust (~26× faster startup)

Anthropic 在 2026-11-09 的发布文中写道：一组运行「较早版本 Fable 5.2」的智能体，把一项关键生产服务从 Python 迁到了 Rust；该服务现在更高效、更可靠，启动大约快 26 倍。原文明确写的是 earlier version of Fable 5.2，不是公开发布的最终版。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 2. Prototype OS from an empty folder, built over eight days

Anthropic 称，一名工程师让 Fable 5.2 从空文件夹开始设计原型操作系统。模型协调了 1000 多个子智能体，昼夜工作八天，编写、测试并审查代码，产出可在笔记本启动的系统，含内核、磁盘/键盘/网络驱动、持久存储、窗口、登录界面、安装程序和内置 Claude 功能。此为公司内部实验，发布文称附有视频。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 3. Vercel: projects stuck for weeks were finished and approved in a few days

Vercel 技术成员 Joe Haddad 在 Anthropic 产品页/发布文中表示：Fable 5.2「懂我每次提示背后的意图」，他一次都不必说「不，我的意思是……」；团队用其他模型推进了数周的项目，在几天内完成并得到同事批准，而且评审其代码的人意见更少。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Joe Haddad（Vercel，Member of Technical Staff）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 4. Datadog: figured out how to work inside unseen, ambiguous systems

Datadog 高级主任工程师 Matt Lee 说，可以把 Claude Fable 5.2「扔到它从未见过的、模糊的新系统里」，它会弄清如何真正在其中工作；「几乎像一名事故指挥官，能派出更快的模型去拿信号并做协调」，从而减轻操作者负担。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Matt Lee（Datadog，Senior Staff Engineer）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 5. Cognition: admitted a prior estimate was wrong and refused to give a number until it measured

Cognition 技术成员 Adhyyan Sekhsaria 说，Claude Fable 5.2 会承认不知道的事情而不是幻觉；有一次它告诉他上次估计是错的，「在测量到变化之前不会再给数字」。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Adhyyan Sekhsaria（Cognition，Member of Technical Staff）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 6. Shopify: refine a loose idea, then trust it to finish with little intervention

Shopify 主任工程师 Tom Pritchard 说，Claude Fable 5.2 善于把松散想法 refinement，答案考虑得很周全；几轮之后他几乎总能说「好，去做吧」，并相信它会在很少干预下完成。「感觉像在和另一位 staff-level 工程师共事。」姓名与职务来自 Anthropic 产品页/发布文。这是选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Tom Pritchard（Shopify，Staff Engineer）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 7. Snowflake: strongest model measured on 103-task data-eng-bench; passed every interactive coding task

Snowflake AI 与开发者体验副总裁 Bala Kasiviswanathan 说，Claude Fable 5.2 是他们在开源基准 data-eng-bench（103 项数据工程任务）上测到的最强模型；它在重复运行中稳定解题，并通过了他们给出的每一项交互式编码任务。证言未公布具体分数。该基准的仓库与 2026-08 介绍博文存在，但八月那篇测试的是更早的模型，Fable 5.2 结果以这条官方证言为准。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Bala Kasiviswanathan（Snowflake，VP of AI and Developer Experience）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 8. iGent: built a hypervisor in one session with 3,500+ machine-checked proofs

iGent 联合创始人兼 CEO Sean Ward 说，Claude Fable 5.2 在单次会话中构建了 hypervisor（在同一台机器上隔离虚拟计算机的软件），其核心经数学证明可保持隔离；超过 3500 条机器检查证明覆盖了每一种情形，而不只是抽测到的那些。他认为这是自己见过的第一个能把如此大规模问题拆成可证明片段、再拼起来并继续做更难工作的模型，相对 Fable 5.1 是明显升级。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Sean Ward（iGent，Co-Founder and CEO）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 9. Uber: 10–12 hour security audit with ~170 reviewer agents, fix PRs, and a policy proposal

Uber 智能体系统主任工程师 Andrew Mager 说，他让 Claude Fable 5.2 跑了一次 10–12 小时的安全审计：派出约 170 个审查智能体，回来时带上报告、修复 pull request 和政策建议。它会一直做到任务真正完成，而不是停在「看起来像样」的检查点；自我纠正和对缺口的坦诚给他留下印象。他表示在高 effort 下，会把它用于长时间无人值守审计和重文档工作。来源明确写的是 Fable 5.2（而非 Mythos）。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Andrew Mager（Uber，Staff Engineer, Agentic Systems）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

### Science and mathematics

#### 1. About 1,000 Fable 5.2 agents formalized Fermat’s Last Theorem in 30 hours

Anthropic 称，一个由约 1000 个 Fable 5.2 智能体组成的团队，在最少人工干预下于 30 小时内用 Lean 完整形式化了费马大定理。模型从极简提示出发、自建协作方式，只用中间定理清单衡量进度；行动 token 约为该公司首次形式化的三分之一，证明长度约为七分之一。同期相同设置下，Opus 5.5 在 18 小时完成约 26%，30 小时后几乎不再推进。注意：Anthropic 2026-09-04 那次 11 天的首次形式化用的是未发布研究模型，不能算作 Fable 5.2 案例。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 2. Completed the weak-coupling Hawking–Page calculation (first-order transition)

Anthropic 发布文将两个黑洞相关开放问题归功于 Fable 5.2。其一：1983 年结果只适用于足够大的宇宙；2003 年已写出在极小宇宙中检验同样跃迁是否突变的计算，但过于繁琐。发布文称 Fable 5.2 大体自主完成了该计算，并发现跃迁同样是突变的。对应预印本 Hexagon 2611.00175v1（2026-11-07）给出 b = −1.48×10⁻³ λ²，并判定跃迁为一阶。预印本出处声明写的是「内部 Claude 研究模型在物理学家提示下得到结果」，并未在文中写出 Fable 5.2 字样；本条以发布文的归属为主，并同时给出预印本。该文尚未经同行评审。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 3. Exact large-c slope of the spinless modular bootstrap ≈ 9.1266

Anthropic 发布文称，Fable 5.2 找到了物理学家使用逾 15 年的一种方法（用于在简化宇宙中排除候选量子引力理论）的精确极限。对应预印本 Hexagon 2611.00174v1（2026-11-07）给出 Λ_V = 12π²/(π² + 4 arcsinh² 1) ≈ 9.1266，此前该斜率只知介于 8.503 与 12 之间。预印本出处声明写的是：主要结果先由「内部 Claude 研究模型」自主得到，公开的 Claude Opus 5.5 后来独立得到同一结果；文中未出现 Fable 5.2 字样。本条以发布文的归属为主，并同时给出预印本。该文尚未经同行评审。

- Source: [https://hexagonmath.org/2611.00174v1](https://hexagonmath.org/2611.00174v1)  
- Author / org: Anthropic  
- Date: 2026-11-07  
- Source type: `preprint`

#### 4. Discovered Materials: Quantum ESPRESSO DFPT phonon code ~36× faster on the same GPU

Discovered Materials 联合创始人 Akash Ramdas 在 Anthropic 产品页被引用，公司自己的研究博文给出了完整基准表：在 13 个案例上，相对库存 GPU 版的几何平均加速约为 36 倍，整套基准墙钟从 3.3 小时降到 4 分钟以内，并说明这比 Fable 5.1 的加速高 3–4 倍。加速来自混合精度、对称性、更好的预条件以及 GPU 常驻准备步骤。公司称用测试套件做了正确性检查，数值偏差在实验表征误差范围内，并表示开源了通过核对的补丁。

- Source: [https://discoveredmaterials.com/research/accelerating-quantum-espresso/](https://discoveredmaterials.com/research/accelerating-quantum-espresso/)  
- Author / org: Akash Ramdas（Discovered Materials，Co-Founder）  
- Date: 2026-11-09  
- Source type: `company-post`

#### 5. Discovered Materials: ~9× hybrid-functional DFT speedup plus unsolicited multi-GPU support

同一篇 Discovered Materials 博文报告了第二项独立结果：Fable 5.2 将 Quantum ESPRESSO 的杂化泛函代码加速约 9 倍（几何平均），并且在未被要求的情况下实现了该算法的多 GPU 版本。文中给出了 10 个案例的分项时间，并解释加速来自 GPU 常驻轨道、批处理交换算符等改动。

- Source: [https://discoveredmaterials.com/research/accelerating-quantum-espresso/](https://discoveredmaterials.com/research/accelerating-quantum-espresso/)  
- Author / org: Akash Ramdas / Discovered Materials  
- Date: 2026-11-09  
- Source type: `company-post`

#### 6. Discovered Materials: combined both speedups on an NV-center-in-diamond workflow

Discovered Materials 将上述声子与杂化泛函加速合在一起，用于金刚石中带负电氮空位（NV）色心：63 原子超胞的声子计算从库存 GPU 版的 77 秒降到 6 秒（约 13 倍）；文中称借助多 GPU 杂化泛函实现，可在四张 H100 上以杂化精度处理同一体系，并表示这把原先可能需要数天的工作流变成数小时量级。这是同一篇文章中的第三项应用结果。

- Source: [https://discoveredmaterials.com/research/accelerating-quantum-espresso/](https://discoveredmaterials.com/research/accelerating-quantum-espresso/)  
- Author / org: Discovered Materials  
- Date: 2026-11-09  
- Source type: `company-post`

### Finance and quantitative research

#### 1. Balyasny: traced investment-research evidence and flagged a misleading question framing

Balyasny Asset Management 的 AI 研究员 Ashish Malik 说，他们让 Claude Fable 5.2 调查某组织如何在核心技术系统中测试一项新集成。它追到了正确来源，没有夸大证据所能支持的结论，并指出该问题的提问方式可能具有误导性。他认为这种克制能分清未知之处，以及市场可能错误定价风险或机会的地方。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Ashish Malik（Balyasny Asset Management，AI Researcher）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 2. Box: flagged that loan-file salary deposits did not match the bank-statement balance

Box AI 产品副总裁 Yashodha Bhavnani 说，在测试中 Claude Fable 5.2 能识别不一致、利用整套文档的上下文，并根据相关证据调整建议。例如在审阅贷款申请附件时，它指出工资入账与银行对账单余额不匹配，从而让审批人聚焦该核对的内容。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Yashodha Bhavnani（Box，VP of AI Products）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 3. IMC: new best scores on three of four finished quant-research problems

IMC 首席 AI 工程师 Marquis Wong 说，Fable 5.1 已出现真正创新研究想法的苗头；Fable 5.2 延续了这一趋势：既有他们欣赏的 5.1 洞察，又提出了第二个全新角度，并在已完成的四个量化研究问题中的三个上取得新的最好成绩。他们希望把它用于高影响、长时间运行的研究，或协调其他模型团队。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Marquis Wong（IMC，Principal AI Engineer）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 4. Jump Trading: 10% lower error on an internal research-automation benchmark; played every major role

Anthropic 发布文称，Jump Trading 在类似其自身研究工具链的 harness 上，用接近量化研究任务的代理评测测试了 Fable 5.2；有一次运行中，它同时扮演代码编写、协调、规划和提交任务等角色，而以往模型需要大量人工重新分配角色。Jump Trading 的 LLM 研发负责人 Lucas Baker 说，它在定义问题、解释、协调以及找到并实现关键想法方面都很强，是他们见过的品位和判断力最强的模型之一；在内部研究自动化基准上，误差比次优模型低整整 10%。这是 Anthropic 选登的客户证言与发布说明。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Lucas Baker（Jump Trading，Head of LLM R&D）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 5. XTX Markets: strong quant-research gains vs Fable 5.1, especially with coordinating agents

XTX Markets 创始人兼 CEO Alex Gerko 说，在他们的量化研究工作中，Claude Fable 5.2 相对 Fable 5.1 带来非常强的提升，尤其是在多个智能体相互协调的设置里；其数学研究能力也是又一次有意义的进步。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Alex Gerko（XTX Markets，Founder and CEO）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 6. Oracle: generated correct debt-summary SQL; two other models over-summed by 5–8×

Oracle 机器学习高级经理 Liyu Gong 在 Anthropic 发布文中说，在一项结合各国债务摘要、还款历史和地区基准的测试里，Claude Fable 5.2 生成的 SQL 返回了预期结果；另外两个模型生成的 SQL 也能跑通，但错误地汇总了国家级摘要金额，得到的值是预期的 5–8 倍。他认为把这类业务计算做对比，是他们看重用 Fable 5.2 做企业 SQL 生成的原因。这是 Anthropic 选登的客户证言（产品页 HTML 与发布文）。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Liyu Gong（Oracle，Senior Manager of Machine Learning）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

#### 7. Fundamental Research Labs: 10-K-to-forecasting-model task; 91% vs 86% for the next-best model

Fundamental Research Labs 技术成员 Jeffrey Liu 说，有一项任务要求把公司财务数据从 10-K 抽到预测模型中，模板并未说明某项指标该用报表数字还是计算值。Fable 5.2 从单元格格式推断作者意图，发现地区数字加总与报表合计不符，并且每个单元格都填对了。他说，这类更好的判断是它在他们的评测上得到 91%、次优模型 86% 的主要原因。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Jeffrey Liu（Fundamental Research Labs，Member of Technical Staff）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

### Legal, compliance, and knowledge work

#### 1. Harvey: clearer I-9 compliance guidance than Fable 5.1

Harvey AI 研究负责人 Niko Grupen 说，在一次 I-9 合规审查中，Claude Fable 5.2 给客户的方向比 Fable 5.1 更清晰：标出需要立即关注的员工，并说明如何纠正每项问题、应由谁行动。他认为这是模型给出可操作法律指引能力的明显进步。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Niko Grupen（Harvey，Head of AI Research）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

### 3D, hardware, and robotics

#### 1. Home voice-assistant hub prototype designed with Diode

Anthropic 与电路板公司 Diode Computers 合作，用一段简短提示让 Fable 5.2 设计三台带四层电路板、3D 打印外壳和固件的电子设备。其中之一是家用语音助手集线器。研究博文称，Claude 写规格、选件、布线、用 CAD 建模外壳并编写固件；每块板在一天内可交付制造，人为干预很少。Diode 按设计文件制板后，Claude 指导工程师测试组装。三台设备均无需电路修改即可工作。文中说明它们仍是原型，尚未做电气验证、天线调谐、热测试或认证。Anthropic 披露与 Diode 有商业关系。

- Source: [https://www.anthropic.com/research/claude-electronics-design](https://www.anthropic.com/research/claude-electronics-design)  
- Author / org: Anthropic；Diode Computers（Craig Chen 等）  
- Date: 2026-11-09  
- Source type: `official`

#### 2. USB speakerphone puck prototype, including touch-wheel routing

三台设备中的第二件是 USB 会议扬声器。提示要求「通过 USB-C 插入电脑、带麦克风和扬声器、支持带 PCB 天线的蓝牙的 puck」。研究博文详细写了四层板触控环下方的走线约束、芯片引脚重分配，以及外壳装配时静音开关需倾斜约 25° 才能装入。Anthropic 称该扬声器原型在数周使用后仍能工作。

- Source: [https://www.anthropic.com/research/claude-electronics-design](https://www.anthropic.com/research/claude-electronics-design)  
- Author / org: Anthropic；Diode Computers  
- Date: 2026-11-09  
- Source type: `official`

#### 3. Handheld battery virtual-pet prototype, including a datasheet-based no-battery check

三台设备中的第三件是手持虚拟宠物。研究博文记载，当被问到没有电池能否工作（文中注明这是少数几次由 Diode 团队主动提问的情况之一）时，Claude 阅读充电器数据手册后回答：可用 USB 供电，但预计充电指示灯会闪烁，因为充电器会反复给电池位置上的小电容充电。Anthropic 称该原型仍处于良好工作状态。

- Source: [https://www.anthropic.com/research/claude-electronics-design](https://www.anthropic.com/research/claude-electronics-design)  
- Author / org: Anthropic；Diode Computers  
- Date: 2026-11-09  
- Source type: `official`

#### 4. Wrote its own PCB router for the voice-assistant hub in about half an hour

在语音助手集线器布线时，Fable 5.2 先使用 Diode 提供的、调用 KiCad 内置路由器的软件，一次只画一条线。面对 100 针连接器上的长走线，它判断逐步引导成本过高，于是自己写了一个把板子划成网格、搜索每条走线通路的路由器。Anthropic 称约半小时后，该路由器大约一秒就能铺好一条长走线；发现音频时钟线过于靠近以太网走线后，它还调整了算法以给敏感走线留出空间。

- Source: [https://www.anthropic.com/research/claude-electronics-design](https://www.anthropic.com/research/claude-electronics-design)  
- Author / org: Anthropic；Diode Computers  
- Date: 2026-11-09  
- Source type: `official`

#### 5. Controlled physical robots: puzzle cube, bottle cap, and a robot drawing

Anthropic 发布文称，与更早的 Claude 模型相比，Fable 5.2 在控制实体机器人方面有明显进步，即使是从未专门训练过的任务。文中视频展示其完成解谜题魔方、拧开瓶盖、画一幅机器人等任务。这是公司自己的演示，不是第三方复现。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 6. Unity: higher-quality 3D scenes from scratch and rebuilds from a visual reference

Unity 创意技术专家 Sam Zhang 说，Fable 5.2 能完成以往模型吃力的任务，最清楚的例子是从零构建更高质量的 3D 场景，以及根据视觉参考重建体验；在更难的游戏开发任务上，它会持续迭代改进而不是卡住。姓名与职务来自 Anthropic 产品页 HTML（Creative Technologist, Unity）。这是 Anthropic 选登的客户证言。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Sam Zhang（Unity，Creative Technologist）  
- Date: 2026-11-09  
- Source type: `customer-testimonial`

### Community demos

#### 1. Ethan Mollick: one-shot an embeddable launch video in code

沃顿教授 Ethan Mollick 在 One Useful Thing 文章中写道，他请 Fable 5.2 为发布做「能嵌入文章、有冲击力、展示能力范围」的作品。模型请他先把视频看到结尾再公开；他称这是一次完成（one shot）、除该提示外没有反馈，并认为达到了「只用代码做电影的人类专家」水准。视频在原文中展示。

- Source: [https://www.oneusefulthing.org/p/fable-52-and-jagged-agi](https://www.oneusefulthing.org/p/fable-52-and-jagged-agi)  
- Author / org: Ethan Mollick  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 2. Ethan Mollick: turned a Codex Micro USB keyboard into a game console with six games

Mollick 请 Fable 把桌上的 Codex Micro（带少量发光按键的迷你 USB 键盘，原本为 ChatGPT 设计）改成游戏机。他写道，公开说明似乎不存在，于是模型阅读了控制该键盘的两个应用的代码，弄清如何设置每个键的颜色并读取旋钮和摇杆，并写出包括 Simon 和用旋钮玩的开锁游戏在内的六款游戏；第一次尝试即完成，且无需帮助。

- Source: [https://www.oneusefulthing.org/p/fable-52-and-jagged-agi](https://www.oneusefulthing.org/p/fable-52-and-jagged-agi)  
- Author / org: Ethan Mollick  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 3. Ethan Mollick: screened 22 ideas and prototyped the Prebid Brief business

Mollick 要求「一年至少赚 2 万美元、每月占用他不超过 20 分钟、其余由模型完成」。Fable 筛选了 22 个想法，提出 Prebid Brief：向设备销售代表提供公园和水利项目在正式招标前的资金与设计动态，并读取了 201 个市县政府的公开议程来做第一期内容，还建立了城市既有资产、年限与采购价格的档案。它开始安排定时任务并询问能否向地方政府发出信息公开请求；Mollick 在真正上线前改令其只做演示。他自己估计成功概率为 20%–40%，并作为创业教授称若这是学期末 MBA 团队作业会让他印象深刻。

- Source: [https://www.oneusefulthing.org/p/fable-52-and-jagged-agi](https://www.oneusefulthing.org/p/fable-52-and-jagged-agi)  
- Author / org: Ethan Mollick  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 4. Ethan Mollick: reconstructed Auden’s 1941 Fate and the Individual course

Mollick 请 Claude 以有趣、可教诗歌而非折磨人的方式，复原 W. H. Auden 1941 年在密歇根大学开设的「Fate and the Individual in European Literature」。站点为教学大纲上 35 部主要作品各做一页，并收录黑板内容、播放的唱片和作业；还阅读了奥登已发表的学术文字，用他在其他地方对诗的评论作注解。Claude 做了研究、设计、写作和代码，并安排批评智能体审阅字句、事实核查对照来源。开源代码在 GitHub（emollick/auden-class）。Mollick 写明第一版准确但无趣，经他反馈后才改得更美观；他与其他先进模型交叉核对未发现重大错误。

- Source: [https://www.oneusefulthing.org/p/fable-52-and-jagged-agi](https://www.oneusefulthing.org/p/fable-52-and-jagged-agi)  
- Author / org: Ethan Mollick  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 5. Ethan Mollick: The One-Dollar Company, a 182-page research-paper draft

Mollick 请 Fable 找一个创业研究中未解决的实证问题，找数据、预注册假说与方法、写论文并由其他智能体批评。结果是《The One-Dollar Company》：估计科罗拉多将 LLC 注册费从 50 美元降到 1 美元后新注册约增 17%，英国将费用从 12 英镑提高到 50 英镑后约降 17%，且注册变化并未伴随后续商业活动记录的相应变化。他写明研究计划实际并未做预注册，有些计划写于已有结果之后；全文 182 页，因为每条批评都变成新分析且几乎不删。他认为初读水平高于对二年级博士生的预期，但尚不可发表，且包括他自己在内还没有人完整核对结果。

- Source: [https://www.oneusefulthing.org/p/fable-52-and-jagged-agi](https://www.oneusefulthing.org/p/fable-52-and-jagged-agi)  
- Author / org: Ethan Mollick  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 6. Ethan Mollick: analyzed 1,186 stories on whether plots share a universal shape

Mollick 的第二个研究项目更顺利：他请 Fable 复现「故事遵循几种基本情感弧线」的研究，并追问情节是否有普遍性。模型阅读了来自世界各地的 1186 个故事，并做一个站点，结论是故事「并不共享同一种形状或情节，但大多数由相同的少数部件构成，最典型的故事是一则关于拿着魔法香蕉的巫师的夏威夷民间传说」。他写到主要问题仍是套话，经几次提醒后修好。

- Source: [https://www.oneusefulthing.org/p/fable-52-and-jagged-agi](https://www.oneusefulthing.org/p/fable-52-and-jagged-agi)  
- Author / org: Ethan Mollick  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 7. Ethan Mollick: Portals, 450+ procedural 3D worlds drawn entirely in code

Mollick 用一段关于「由传送门连接的、无需动手的 3D 世界之旅」的描述，要求「做出来并让它令人敬畏」。20 小时后线上有 204 个世界，后来超过 450 个，全部由代码实时绘制，没有现成 3D 模型或图片文件。他估计项目涉及约 25000 次智能体运行（绝大多数只做单次任务，如评判一张图）。第 10 天时有一个主导智能体和 28 个并行团队。他请模型「打磨」后，智能体自建了最长达 204 节、约 87500 字的规则书，产出明显变慢；他另组顾问团队后，速度回到每天约 30 个以上世界。开源代码：github.com/emollick/ai-portals；站点 portals-endless-worlds.netlify.app。

- Source: [https://www.oneusefulthing.org/p/fable-52-and-jagged-agi](https://www.oneusefulthing.org/p/fable-52-and-jagged-agi)  
- Author / org: Ethan Mollick  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 8. Matt Shumer: a from-scratch voxel engine with real destruction physics

投资者兼早期测试者 Matt Shumer 在 2026-11-09 的评测中写道，Fable 5.2 做成了他用几乎每个模型尝试一年的体素引擎：真实破坏物理、从零构建，且能在他的 MacBook 上运行；演示在浏览器标签页中，文章提供了在 Spawn 上试玩的入口。他估计自己在测试窗口中向该模型投入了近 4000 亿 token。这是作者自述，未见独立复现报告。

- Source: [https://somethingbig.ai/fable-5-2-everyday](https://somethingbig.ai/fable-5-2-everyday)  
- Author / org: Matt Shumer  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 9. Matt Shumer: a Hogwarts-meets-Fortnite battle-royale game

Shumer 写他让模型做「霍格沃茨遇见 Fortnite」的游戏。起初让多个副本组成团队，结果平庸；改由单个实例独自完成后才有起色。他称模型在大约两周、几乎没有他指引的情况下做成，并在文中给出 Spawn 试玩链接。他写「并不完美，但已经接近」。该作品使用第三方特许故事世界，存在版权风险，收录仅作能力记录，不鼓励商业仿作。同为作者自述。

- Source: [https://somethingbig.ai/fable-5-2-everyday](https://somethingbig.ai/fable-5-2-everyday)  
- Author / org: Matt Shumer  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 10. Matt Shumer: in-progress Mirror Earth with live weather and NYC subway schedules

Shumer 写下一步是建造地球本身：可去任何地方，所见镜像真实地点，包括当时天气；在纽约市，它正在加入按真实列车时刻运行的地铁。他称项目仍在进行中，文中有预览视频，并强调在如此长的任务上初始提示决定一切。作者自述，且明确未完成。

- Source: [https://somethingbig.ai/fable-5-2-everyday](https://somethingbig.ai/fable-5-2-everyday)  
- Author / org: Matt Shumer  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 11. Matt Shumer: multiple homepage design options for his newsletter site

Shumer 写 Fable 5.2 具有设计品味，但需要先给大量他所喜欢的例子。他请它为通讯站点做新的首页设计，并在文中展示了若干方案，自评「真的很好」。他还建议先把风格定下来再生成完整成品，以免为不想要的结果付费。

- Source: [https://somethingbig.ai/fable-5-2-everyday](https://somethingbig.ai/fable-5-2-everyday)  
- Author / org: Matt Shumer  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 12. Matt Shumer: Fable 5.2 video, which he says looks more professional by default

Shumer 在同一篇评测中写道，Fable 5.2 也擅长视频：默认看起来比更早模型的作品更专业，并且可以推向任意风格。文中配有视频示例。这是作者对设计/视频能力的展示，而非第三方测评。

- Source: [https://somethingbig.ai/fable-5-2-everyday](https://somethingbig.ai/fable-5-2-everyday)  
- Author / org: Matt Shumer  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 13. Matt Shumer: overnight review of his company’s business AI agent

Shumer 称其公司出售面向企业的 AI agent（有独立邮箱、短信/电话号码和计算机）。他把整条业务交给 Fable 5.2 询问「我们哪里做错了」。它通宵工作后，在产品（含他认为用其他办法找不到的改进，以及让助手更好同时降低单客成本的改动）、成本（漏掉的节省和从未计入的成本）和业务（注册与付费问题，并围绕真正驱动付费的因素重做商业模式，过程中证伪了他们最有把握的一些猜测）三个方面给出答案，此外还有数十项更小改动。这是作者对其本公司产品的自述。

- Source: [https://somethingbig.ai/fable-5-2-everyday](https://somethingbig.ai/fable-5-2-everyday)  
- Author / org: Matt Shumer  
- Date: 2026-11-09  
- Source type: `personal-blog`

#### 14. Every / Kieran Klaassen: built the internal video editor Everycut

Every 的 Katie Parrott 在《Vibe Check: Fable 5.2》一文开头（免费可读部分）写道：Kieran Klaassen 在某月一个休息日让 Fable 5.2 去做视频编辑器；第二天下午，他向团队展示了一个结合 Adobe Premiere 剪辑能力、After Effects 标题与视觉效果、以及 Ableton 音乐混音的应用，并带有可运行这一切的 AI 智能体。开始三天后 Everycut 上线，一周后他们开了全公司演示。文章说明 Every 作为早期访问的一部分免费使用 Fable 5.2，文中金额为按标价估算。全文其余部分需订阅，本条仅依据已抓取到的开头所述事实。

- Source: [https://every.to/vibe-check/fable-5-2](https://every.to/vibe-check/fable-5-2)  
- Author / org: Katie Parrott 报道；Kieran Klaassen 构建（Every）  
- Date: date not stated on the source page  
- Source type: `news`

#### 15. How I AI: a one-prompt 3D virtual typewriter at typed.page

YouTube 频道 How I AI 在 2026-11-09 发布短视频，标题与简介写明用 Claude Fable 5.2 做出带有按键声、写作计时器和唱机的虚拟打字机，并指向 https://typed.page。该站点目前可打开。第三方转写还提到多种场景（火车、油灯、笔记本、复古电脑等），本条以创作者视频标题/简介和可访问的演示站点为准，不把转写里未在原视频页面出现的细节当成已核验事实。创作者个人姓名未在已抓取的视频页上出现。

- Source: [https://www.youtube.com/watch?v=sONvKt39t8k](https://www.youtube.com/watch?v=sONvKt39t8k)  
- Author / org: How I AI（YouTube 频道）  
- Date: 2026-11-09  
- Source type: `video`

### Evaluations and benchmarks

#### 1. Artificial Analysis Intelligence Index: Fable 5.2 (Max) scored 65; AA said it debuted at #1

评测机构 Artificial Analysis 官方账号 @ArtificialAnlys 在 2026-11-09 发帖称，Claude Fable 5.2 在 Artificial Analysis Intelligence Index v5 上以 65 分暂列第一（Max effort），领先 Gemini 4 Carbon（high，60）5 分、Claude Opus 5.5（max，59）6 分。AA changelog 同日记录：Fable 5.2（Max, Default Fallback）Intelligence Index 为 65；Xhigh/High 为 62，Medium 为 56，Low 为 54。这是独立评测，不是 Anthropic 自评。名次以当时公告为准，后续可能变化。

- Source: [https://x.com/ArtificialAnlys/status/2119878995386982508](https://x.com/ArtificialAnlys/status/2119878995386982508)  
- Author / org: Artificial Analysis  
- Date: 2026-11-09  
- Source type: `independent-eval`

#### 2. Artificial Analysis AA-3D: 1271 Elo, first on the interactive 3D benchmark

AA-3D v1.0 由 Artificial Analysis 开发，包含 55 个任务：模型在离线沙箱中把文字brief做成 three.js 场景，Elo 来自人类评审的盲测成对投票。AA 页面写明 Claude Fable 5.2（Max, Default Fallback）以 1271 分最高，随后是 Claude Sonnet 5.5（1204）和 Claude Opus 5.5（1202）。这是独立评测。

- Source: [https://artificialanalysis.ai/evaluations/aa-3d](https://artificialanalysis.ai/evaluations/aa-3d)  
- Author / org: Artificial Analysis  
- Date: date not stated on the source page  
- Source type: `independent-eval`

#### 3. FrontierCode 2.0: 49.1% at Xhigh effort, highest released-model score Anthropic reported

Anthropic 发布文与产品页给出：Fable 5.2 在代理编程基准 FrontierCode 2.0 上，Xhigh effort 为 49.1%（Fable 5.1 同设置为 32.4%；Opus 5.5 为 45.5%；GPT-6 Astra 为 42.8%；Gemini 4 Carbon Medium effort 为 41.1%）。文中还称 High effort 下 Fable 5.2 约 45.3%，与 Opus 5.5 最佳成绩接近，而每任务成本大约为一半。FrontierCode 衡量的是模型代码改动是否会被开源仓库维护者合并。这是厂商公布的评测，方法详见系统卡。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 4. FrontierSWE v2: 69.9% agentic coding

Anthropic 产品页/发布文表格：Fable 5.2 在 FrontierSWE v2 上为 69.9%，对比 Fable 5.1 的 56.3%、Opus 5.5 的 62.3%、GPT-6 Astra 的 65.5%、Gemini 4 Carbon 的 61.2%。厂商公布成绩，默认展示各模型最高可用 effort。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 5. RoboDojo Sim: 64.9% at Max effort on a simulated two-arm robot (internal runs)

Anthropic 称，在公开基准 RoboDojo（根据相机图像控制模拟双臂机器人）上，Fable 5.2 在相同 harness 下超过其他前沿模型，也超过多数专为机器人控制构建的系统。表格与脚注写明：RoboDojo Sim 展示最高可用 effort，且为内部运行；Max effort 下 Fable 5.2 为 64.9%，对比 GPT-6 Astra 29.8%、Fable 5.1 27.6%、Opus 5.5 39.4%。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 6. BenchCAD 2.1: 83.5 at Max effort on hardware-engineering designs

Anthropic 称 BenchCAD 2.1 衡量硬件工程，看设计与参考几何和电路的接近程度，0–100 分并可部分给分。发布文图表：Max effort 下 Fable 5.2 为 83.5，高于 Opus 5.5 的 65.3 和 Fable 5.1 的 44.4。硬件研究博文再次引用该分数。厂商公布成绩。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 7. Diode PCB Gym: 69% on place-and-route, vs 25% for Fable 5

Anthropic 硬件研究博文称，为展示布线能力进步，请 Diode 运行其内部基准 PCB Gym：在去掉原布局的板子上放置元件并重新布线。Fable 5.2 得分为 69%，Fable 5 为 25%。这是合作方内部基准，不是公开排行榜。

- Source: [https://www.anthropic.com/research/claude-electronics-design](https://www.anthropic.com/research/claude-electronics-design)  
- Author / org: Anthropic；Diode Computers  
- Date: 2026-11-09  
- Source type: `official`

#### 8. Terminal-Bench-Science 0.1: Fable 5.2 scored 74.6% (Mythos 5.2’s 75.3% listed separately)

Anthropic 表格将代理科学研究基准 Terminal-Bench-Science 0.1 上的 Fable 5.2 列为 74.6%，并另行列出 Mythos 5.2 的 75.3%。对比 Fable 5.1 的 52.6%、Opus 5.5 的 58.7%、GPT-6 Astra 的 68.1%、Gemini 4 Carbon 的 64.8%。本条只收录 Fable 的 74.6%，不把 Mythos 分数算作 Fable 案例。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 9. Perplexity WANDR: 82.1% relaxed score; Medium-effort cost about 40% of Opus 5.5’s top score

Anthropic 称 Perplexity 的 WANDR 衡量智能体在大规模数据收集任务上的表现。Fable 5.2 宽松分为 82.1%，对比 Fable 5.1 的 68.7% 和 Opus 5.5 的 72.3%。发布文还称，Medium effort 下 Fable 5.2 达到与 Opus 5.5 最高分相当的水平，而每任务成本约为 40%。厂商公布成绩。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 10. OSWorld 2.1 (offline set, partial): 89.3% computer use

Anthropic 表格：Fable 5.2 在 OSWorld 2.1（offline set, partial）上为 89.3%，对比 Fable 5.1 的 83.5%、Opus 5.5 的 87.2%、GPT-6 Astra 的 79.5%、Gemini 4 Carbon 的 81.5%。厂商公布成绩，标注为部分离线集。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 11. Humanity’s Last Exam (with tools): 74.2%; Low-effort cost under one-tenth of Opus 5.5’s top score

Anthropic 将 HLE 称为专家级学术知识与推理测试。Fable 5.2（含工具）为 74.2%，对比 Fable 5.1 的 65.6%、Opus 5.5 的 67.7%、GPT-6 Astra 的 57.2%。发布文图表称，Low effort 下 Fable 5.2 达到与 Opus 5.5 最高分相当的水平，而每任务成本不到十分之一。厂商公布成绩。

- Source: [https://www.anthropic.com/claude-fable-and-mythos-5-2](https://www.anthropic.com/claude-fable-and-mythos-5-2)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 12. Chartography (no tools): 73.4% visual chart recognition

Anthropic 称 Chartography 测试模型读图表的准确性。Fable 5.2（无工具）为 73.4%，对比 Fable 5.1 的 44.8%、Opus 5.5 的 64.4%、GPT-6 Astra 的 71.0%、Gemini 4 Carbon 的 72.5%。发布文还称 Medium effort 下为 66.4%，高于 Opus 5.5 在 Max effort 的 64.4%，而每任务成本不到十分之一。厂商公布成绩。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 13. Remote Labor Index: 41.3% at High effort

Anthropic 将 RLI 列为知识工作基准。Fable 5.2 在 High effort 下为 41.3%，对比 Fable 5.1 的 17.9%、Opus 5.5 的 21.3%、GPT-6 Astra 的 20.8%。相对前代跳变较大，但是厂商公布成绩。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

#### 14. AA-Briefcase v1.1: 66.1% rubric (1785 Elo)

Anthropic 表格列出知识工作基准 AA-Briefcase v1.1：Fable 5.2 量规分 66.1%、Elo 1785；Fable 5.1 为 61.5% / 1669 Elo；Opus 5.5 为 61.2% / 1800 Elo；GPT-6 Astra 为 52.0% / 1569 Elo；Gemini 4 Carbon 为 61.8% / 1611 Elo。注意这里 Fable 的 Elo（1785）低于 Opus 5.5 的 1800，尽管量规分更高。厂商公布成绩。

- Source: [https://www.anthropic.com/claude/fable](https://www.anthropic.com/claude/fable)  
- Author / org: Anthropic  
- Date: 2026-11-09  
- Source type: `official`

## Inclusion notes

- Entries must have a public primary source that names **Claude Fable 5.2**. Vendor scores, selected customer quotes, and first-person write-ups are labeled as such; we do not treat them as independently verified.
- **Excluded:** work a source attributes to Claude Mythos 5.2 (for example AAV capsid structure prediction, most cybersecurity vulnerability-discovery evals, and de novo binder design), even though Fable and Mythos share an underlying model.
- Anthropic’s 11-day Fermat formalization from September 2026 used an unreleased research model and is not listed. The Python-to-Rust migration is listed, with the launch post’s wording that it used an earlier version of Fable 5.2.
- The two black-hole physics preprints say an “internal Claude research model” produced the results; the Fable 5.2 credit comes from Anthropic’s 9 Nov 2026 announcement. Both wordings appear in those entries.
- Distinct results in one source (the three devices, the two Quantum ESPRESSO speedups, Mollick’s separate projects) are listed separately.
- Contributions welcome: see [CONTRIBUTING.md](./CONTRIBUTING.md). Licensed under MIT; original case text remains with its authors, see [NOTICE.md](./NOTICE.md).

This project is not affiliated with Anthropic.
