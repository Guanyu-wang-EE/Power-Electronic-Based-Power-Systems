# HW01 文献导引整合与核验

日期：2026-09-08。用途：支持阅读选材与证据判断，不是作业正文，也不代表用户已接受任何中心观点。

## 整合结论

外部导引带来了有价值的补充，尤其是风机利用转子动能的早期工作、不同能量载体、支撑后的恢复过程和变流器的资源限制。但其中有 3 个 DOI 错误、1 篇作者整体错配，部分“论文证明了什么”的表述与原文不符。因此保留它的文献发现成果，重写其证据解释，不能直接照着导引引用或写作。

原清单 8 篇与外部导引 10 篇有 2 篇重复，合计 16 篇。推荐 8 篇主线加 2 篇可选，剩余 6 篇仅作储备。完整书目、作者、卷页、来源和阅读状态统一保存在[现有文献清单](../../assignments/HW01_Inertia/LITERATURE.md)，避免另立一套编号。

## 来源与本次实际核验范围

- 用户提供的[外部导引原件](../../source/HW01_Inertia/电力系统惯量文献调研导引.docx)已复制进项目，Downloads 原件保留，未改写原文。
- [可检索提取文本](../../notes/source_extracts/HW01_inertia_external_guide.txt)包含段落、表格文字及超链接；数学内容经 OOXML 文本化，不保留全部版式与数学重音。原始公式若涉及点号等细节仍应回看 Word，不能将提取缺字直接算作原文错误。
- 8 篇新增文献通过 Crossref DOI 记录与作者机构、出版社或论文首页交叉核验；以正式卷期年为书目年份。引用量采用同日 Crossref 总引用，未剔除自引，不冒充 Google Scholar 或独立他引数。
- 本次通读核对 Morren 两页正文；对其他可得全文按争议定位检查关键段落，不声称完成全部精读。外部导引的“已读全文”与 `[cite: 30]` 等占位符，不构成本项目可复查的阅读证据。
- 当前 9 篇本地 PDF、4 篇在线全文、3 篇仅摘要/片段。L03、L09、L16 的未核验正文内容不进入已确认论据。

## 外部条目的接入与取舍

| 外部编号 | 项目编号 | 接入决定 | 对原主线的贡献 |
|---|---|---|---|
| P1 Tielens 2016 | L01，原有 | 合并，仍为入口 | 定义、能量、频率动态 |
| P2 Ratnam 2020 | L09，新增 | 备用，当前仅摘要 | 运行要求与措施；与已有综述重叠 |
| P3 Fang 2019 | L10，新增 | 主线选读 | 将动能、电容与储能联系到控制实现 |
| P4 Morren 2006 | L11，新增 | 主线精读 | 风机动能支撑的早期控制及恢复代价 |
| P5 Zhong 2011 | L04，原有 | 合并，修正导引解释 | 模拟同步机动态的代表性方案 |
| P6 D’Arco 2014 | L12，新增 | 可选补充 | 下垂与虚拟同步机的条件等价 |
| P7 Tayyebi 2020 | L13，新增 | 主线关键章节 | 区分直流源、交流限流与控制交互 |
| P8 Marković 2021 | L14，新增 | 进阶备用 | 小信号模态与系统结构，入门负担较大 |
| P9 实为 Liu 2018 | L15，新增 | 主线精读 | 转速恢复与二次频率跌落的控制 |
| P10 Teng 2016 | L16，新增 | 调度方向备用，当前仅摘要 | 将频率响应需求纳入运行决策 |

## 必须更正的书目信息

| 文献 | 外部导引记录 | 核验后的 DOI |
|---|---|---|
| Fang 2019 | 10.1109/JESTPE.2018.2878521 | [10.1109/JESTPE.2018.2877766](https://doi.org/10.1109/JESTPE.2018.2877766) |
| Marković 2021 | 10.1109/TPWRS.2021.3060641 | [10.1109/TPWRS.2021.3061434](https://doi.org/10.1109/TPWRS.2021.3061434) |
| Avoiding Frequency Second Dip… | 10.1109/TPWRS.2017.2758158 | [10.1109/TPWRS.2017.2761897](https://doi.org/10.1109/TPWRS.2017.2761897) |

三个原 DOI 本次 Crossref 精确查询均未返回记录；更正项对应所列题名。P9 正确作者为 **Kangcheng Liu、Yanbin Qu、Hak-Man Kim、Huihui Song**，不是导引所列的 Kang、Yao、Muljadi、Maksimovic、Kang。[第一作者主页](https://kangchengliu.github.io/)与[作者上传全文](https://www.researchgate.net/publication/320341815_Avoiding_Frequency_Second_Dip_in_Power_Unreserved_Control_During_Wind_Power_Rotational_Speed_Recovery)可交叉核对。

分区方面，沿用本项目可追溯的 [IEEE 官方 2025-08 清单](https://open.ieee.org/wp-content/uploads/IEEE-Title-List-August-2025.pdf)：它采用 2024 JCR 数据、2025 年 6 月发布，相关六种 IEEE 期刊列为 Q1。外部导引的 2023 JIF 和精确类别名次未取得对应原记录，不并入“已核验”字段。RSER 的原始 JCR 分区证据仍待取得；不因此丢弃主题高度相关的 L01，也不把中科院一区、JCR Q1 和高被引认证混为一谈。

## 内容核验：保留贡献，纠正论据

### 1. Morren 2006：不是“忽视恢复的微分惯量仿真”

**导引的问题：**把图 2 说成微分惯量控制的验证，称算例为单机无穷大系统、扰动为负荷突增，并称作者完全回避了转速恢复。

**原文：**IV 节明确该算例只演示一次频率支撑，没有启用额外惯量模拟。算例含两台同步机及六台风机，扰动是 20 MW 同步机退出。第二页说明转速恢复时送网功率降低；V 节还讨论错开风机退出时间和渐变恢复。[原文 PDF，第 433–434 页，IV–V 节及图 2](../../source/HW01_Inertia/L11_Morren_2006_repository.pdf)。

**接入方式：**保留图 1 的两类附加控制思路和能量来源；把 L11 → L15 的发展关系写成“早期已认识恢复代价，后续进一步设计恢复控制”。不能人为制造“早期完全没看见、后来才推翻”的历史。

### 2. Zhong 2011：模拟某些动态不等于完整复制同步机

**导引的问题：**用该文支持“无需 PLL、真正无延时惯量、完整复制同步机全部特性”，并把未核验的黑启动描述作为已完成实验。

**原文：**仿真段落明确使用锁相环（Phase-Locked Loop, PLL）进行初始同步；直流母线部分强调需要能量储存。本文没有给出可供本作业采用的“所有过程都无 PLL、无延时”的证明。[作者 PDF，仿真初始同步段落及直流储能说明](../../source/HW01_Inertia/L04_Zhong_2011_author.pdf)；[定位文本](../../notes/source_extracts/L04_Zhong_2011_author.txt)。

**接入方式：**保留同步逆变器的模型到控制映射这一奠基价值；不把内电势自主生成等同于无限能源、无限过载能力或全部同步机特性，也不把后续自同步方案的结果提前归给 2011 年论文。

### 3. D’Arco 2014：等价有条件，导引的滤波方向写反

**原文：**有功功率测量先经过一阶低通滤波，再进入下垂控制；IV 节讨论恒定参考值与参数映射，图 3 确实给出了相应阶跃响应对比。[论文第 395 页，图 2、图 3、式 (3)–(6)](https://www.researchgate.net/profile/Jon-Suul/publication/260058589_Equivalence_of_Virtual_Synchronous_Machines_and_Frequency-Droops_for_Converter-Based_MicroGrids/links/0c96052f52c68ecacf000000/Equivalence-of-Virtual-Synchronous-Machines-and-Frequency-Droops-for-Converter-Based-MicroGrids.pdf)。

**辅导推导，使用统一简化记号，不冒充原文逐式转录：**设参考值恒定，采用一致单位或标幺基准，忽略初值项；下垂增益为正数 m_p，功率测量滤波时间常数为 tau。则

$$
\Delta\omega(s)=-\frac{m_p}{1+s\tau}\Delta P(s).
$$

等价改写为

$$
\Delta P(s)=-\frac{1+s\tau}{m_p}\Delta\omega(s),
$$

$$
\frac{\tau}{m_p}\frac{d\Delta\omega}{dt}=-\Delta P-\frac{1}{m_p}\Delta\omega.
$$

因此这里的惯性项系数为 tau/m_p，阻尼项系数为 1/m_p。导引把功率写成频率的函数时仍保留分母中的低通环节，无法从该式推出它后面给出的映射。上述惯性系数也不能不经容量、频率基准换算就直接叫 H。此结果不证明所有下垂与所有 VSM 在参考值变化、内环、限流和故障下都相同。

### 4. Tayyebi 2020：直流限制与交流限流必须分清

**导引的问题：**把证据说成详细开关管仿真与李雅普诺夫证明，将案例描述为严重短路下“限流即失稳”，并把 1.1–1.4 p.u. 当作普遍物理阈值。

**原文：**II 节采用平均变换器模型。IV-D 中直流源饱和可以发生在尚未达到交流电流上限时；IV-E 的简单电流限幅不能稳定相关案例，但后续修改有功设定值的方案可改善并稳定部分案例。matching control 在文中测试的直流饱和条件下有不同表现。VI 节将形式化稳定分析和更完整的故障限流设计列为后续工作。[预印本，II、IV-D、IV-E、VI 节](../../source/HW01_Inertia/L13_Tayyebi_2020_preprint.pdf)。

**接入方式：**保留“控制参数必须服从实际资源与动态”的启发，但证据要具体到直流源、限流方法、扰动和控制方案。不能推导出所有构网型变流器一触碰限流就必然失稳，也不能反向声称某控制在所有故障下稳定。

### 5. Liu 2018：恢复能量不等于严重二次跌落不可避免

**导引的问题：**将恢复过程说成必然引发严重第二次频率下降，甚至暗示通常必须从电网反向吸收电能。

**原文：**研究无功率预留的风机在恢复转速时可能引起的二次频率跌落，提出修改控制以在所研究孤岛微网中缓解这一问题。[作者全文，摘要及恢复控制相关正文](https://www.researchgate.net/publication/320341815_Avoiding_Frequency_Second_Dip_in_Power_Unreserved_Control_During_Wind_Power_Rotational_Speed_Recovery)。

**辅导解释：**恢复转速需要净机械功率用于增加动能；风机可以把部分持续输入的风能留给转子，使送网功率减少，未必出现反向购电。能量收支不可绕过，但恢复速度、退出方式和其他机组支撑会影响系统频率轨迹。L15 的贡献恰恰是改进控制，不能引用它证明后果无法避免。

### 6. 其余条目：降低断言强度，保留合适用途

- **Fang / L10：**保留风机、电容、超级电容和电池的能量载体比较；文章综述了多项已有技术，不能把所引实验统一算作该文自己的硬件在环实验。具体公式需逐式核对后采用。[作者机构记录](https://vbn.aau.dk/en/publications/on-the-inertia-of-future-more-electronics-power-systems/)、[作者上传全文](https://www.researchgate.net/publication/328513288_On_the_Inertia_of_Future_More-Electronics_Power_Systems)。
- **Marković / L14：**保留小信号模型、模态与控制相互作用的价值；具体算例的渗透率临界点不是所有电网通用的比例要求，也不能从小信号模型直接推出大故障暂态稳定。[作者公开稿](../../source/HW01_Inertia/L14_Markovic_2021_author.pdf)。
- **Ratnam / L09 与 Teng / L16：**只有摘要和书目，导引指定的图表、公式与实验细节暂不采纳。Teng 的未来系统场景不能写成已观测的 2030 年运行数据；未核对全文前，不使用导引的“直接反比”“毫秒级替代”作结论。[DTU 条目](https://orbit.dtu.dk/en/publications/future-low-inertia-power-systems-requirements-issues-and-solution/)、[Imperial 条目](https://www.imperial.ac.uk/electrical-engineering/research/control-and-power/publications/?id=747352&noscript=noscript&respub-t4-action=citation.html)。

## 跨文献解释应保持的边界

以下是结合现有文献与能量平衡形成的辅导解释，不是用户个人判断，也不是十篇论文逐字一致的“领域共识”。

1. **定义、能量与响应分开。**转动惯量 J、惯量常数 H 和动能 E_k 不同；dE_k/dt 的量纲是功率，不能称为惯量的定义。H 采用额定转速动能与额定容量之比，也不代表全部动能都能在允许频率范围内用掉。[L01 原文](../../source/HW01_Inertia/L01_Tielens_2016_repository.pdf)。
2. **控制类别与服务分开。**构网型控制（Grid-Forming, GFM）、跟网型控制（Grid-Following, GFL）描述控制结构；虚拟/合成惯量（Virtual/Synthetic Inertia, VI/SI）的用词在文献间存在重叠；快速频率响应（Fast Frequency Response, FFR）描述响应服务。不能强行建立“SI 只属于风机 GFL、VI 只属于电池 GFM、FFR 只能阶跃注入”的一一对应。[L06](../../source/HW01_Inertia/L06_Poolla_2019_preprint.pdf)、[L07](../../source/HW01_Inertia/L07_Rosso_2021_repository.pdf)。
3. **频率过程会重叠。**惯量、负荷阻尼及控制共同进入动态模型。频率变化率（Rate of Change of Frequency, RoCoF）与惯量的简单反比关系，要说明功率失衡、系统聚合及其他响应的假设；频率最低点和准稳态偏差也不是各由一个参数独占决定。不能把“前 500 ms”当作所有系统普适的分界。[L01](../../source/HW01_Inertia/L01_Tielens_2016_repository.pdf)、[L08 出版社全文](https://www.annualreviews.org/content/journals/10.1146/annurev-control-052622-032657)。
4. **能量约束和限流案例不直接证明“惯量越大越差”。**它们说明某种实现和资源条件下，不能任意增大参数；是否改善系统，还要固定扰动、阻尼、控制、网络及评价指标。它们也没有证明虚拟惯量在所有系统中都无法或都能够完全替代同步机物理惯量。

## 收敛后的阅读用途

建议主线 8 篇：L01 → L11 → L10 → L04 → L07 → L06 → L15 → L13。对应“物理定义 → 风机动能 → 能量载体 → 控制实现 → 控制分类 → 系统比较 → 能量恢复 → 资源与动态限制”。L12 与 L08 是按需要加入的两篇补充。这样保留外部检索带来的历史与工程细节，同时用原清单避免把不同控制和服务混为一谈。

用户已要求停止 grill-me，本轮不布置问题、不要求答题，也不替用户生成中心观点或四页提纲。待用户实际阅读、写下自己的理解或原稿后，再对相应内容做证据核查与表达反馈。
