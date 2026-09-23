# HW01 英文文献清单与来源核验

核验日期：2026-09-08。原有 8 篇与外部导引 10 篇按 DOI 去重为 16 篇，再按用户要求补入 2025 年 TPEL 方法论文 L17，当前候选库共 17 篇，作业主线共 9 篇。保留 L01–L16 的原编号；不要求读完候选库，尚未替用户确定个人立场。外部导引的逐项取舍见[整合核验报告](../../outputs/HW01_Inertia/LITERATURE_INTEGRATION_REVIEW.md)，该报告保留首次整合时的范围与结果。

**采用状态更新：**2026-09-08 用户接受原八篇，并要求为“1.2 惯量支撑的代表性方法”补一篇 2024 年 12 月之后的 JCR Q1 论文；选入 L17 后共九篇。[IEEE 参考文献章节](../../outputs/HW01_Inertia/REFERENCES_IEEE.md)只列正式期刊版。选择采用不等于已经完成阅读，也不表示已确定个人观点；L17 当前仅核对书目与摘要，未取得全文。

## HW01 已采用文献与 IEEE 编号

编号按当前提纲的预期首次引用顺序：引言与 1.1 为 [1]、[2]；1.2 为 [3]–[5]；1.3 为 [6]、[7]；1.4 为 [8]、[9]。新增 [5]=L17 后，旧 [5]–[8] 顺延为 [6]–[9]。实际正文若改变首次出现顺序，正文和参考文献应一起调整。L 编号继续用于本项目阅读资料定位。

2026-09-08 原八篇已重新请求 Crossref DOI 接口，并与作者机构记录或论文首页交叉比对；新增 L17 另经 Crossref 与 IEEE 出版社条目核对。九篇均确认已有正式期刊卷页；核对字段包括题名、完整作者及顺序、期刊、正式年份、卷期、页码，差异的取舍见下。

| 正文编号 | 项目编号 | 正式期刊卷期、页码及出版时间 | 第二来源 |
|---|---|---|---|
| [1] | L01 | RSER 55:999–1009，2016-03 | [KU Leuven 作者稿封面及首页](../../source/HW01_Inertia/L01_Tielens_2016_repository.pdf)明列正式版书目与 DOI |
| [2] | L10 | JESTPE 7(4):2130–2146，2019-12 | [Aalborg 机构记录](https://vbn.aau.dk/en/publications/on-the-inertia-of-future-more-electronics-power-systems/)给出四位作者、DOI、正式卷页和 2019-12 出版状态 |
| [3] | L11 | TPWRS 21(1):433–434，2006-02 | [TU Delft 机构记录](https://research.tudelft.nl/en/publications/wind-turbines-emulating-inertia-and-supporting-primary-frequency-/)及[期刊排版 PDF](../../source/HW01_Inertia/L11_Morren_2006_repository.pdf) |
| [4] | L04 | TIE 58(4):1259–1267，2011-04 | [作者高校来源的期刊排版 PDF](../../source/HW01_Inertia/L04_Zhong_2011_author.pdf)首页及刊内页码 |
| [5] | L17 | TPEL 40(10):15450–15465，2025-10 | [IEEE 出版社条目](https://ieeexplore.ieee.org/document/11003428/)与 [Crossref DOI 记录](https://api.crossref.org/works/10.1109/TPEL.2025.3569931)；六位作者、题名、DOI 和正式卷页一致 |
| [6] | L06 | TPWRS 34(4):3035–3046，2019-07 | [ETH 作者书目](https://people.ee.ethz.ch/~floriand/bib/Year/2019.complete.html)核对作者拼写、题名、DOI 与卷页；该页月份与正式卷期日期的差异见下 |
| [7] | L07 | OJIA 2:93–109，2021 | [Aalborg 机构记录](https://vbn.aau.dk/da/publications/grid-forming-converters-control-approaches-grid-synchronization-a/)及正式出版版 PDF |
| [8] | L15 | TPWRS 33(3):3097–3106，2018-05 | [作者上传的期刊全文](https://www.researchgate.net/publication/320341815_Avoiding_Frequency_Second_Dip_in_Power_Unreserved_Control_During_Wind_Power_Rotational_Speed_Recovery)，正文首页标明 May 2018，含四位作者 |
| [9] | L13 | JESTPE 8(2):1004–1018，2020-06 | [ETH 正式发表记录](https://www.research-collection.ethz.ch/handle/20.500.11850/416456?show=full)的检索记录及[作者代码库中的期刊引用](https://github.com/ATayebi/GridFormingConverters/blob/master/README.md) |

**交叉核验中处理的差异：**

- Crossref 在 [6] 将 Groß 转成 `Gros`、Dörfler 转成 `Dorfler`；在 [9] 使用 `Gross`、`Dorfler`。按作者书目中的 `Gro{\\ss}`、`Dörfler` 和作者代码库保留 **Groß、Dörfler**，作者数量及顺序不变。
- [6] ETH 作者书目月份写 January，但 Crossref 正式卷期出版日期为 **2019-07**；采用 34(4) 的 **Jul. 2019**，不混入提前上线日期，也不引用同题会议条目。
- [8] 作者上传页面顶部写 October 2017，但该页面内期刊全文首页及 Crossref 正式卷期均为 **May 2018**，故采用 2018。其作者确为 Liu、Qu、Kim、Song，正确 DOI 为 10.1109/TPWRS.2017.2761897。
- [1]、[2]、[3]、[4] 的 DOI 字符串含年号与正式卷期年份不同，不据此改动 DOI 或卷期年。最终分别采用 2016、2019、2006、2011 年的正式版。
- [7] OJIA 对应记录没有期号，按 vol. 2、pp. 93–109、2021 输出，不编造 no. 1，也不将上线月份充作期号日期。
- [5] IEEE 条目提前上线日期为 2025-05-13，正式卷期为 2025-10；引用采用 **Oct. 2025**、40(10)、15450–15465。两种日期均晚于用户指定的 2024 年 12 月界线。
- [2] 机构库列有 IEEE Xplore 文档号 8506338；该文已有连续页码，参考文献使用 pp. 2130–2146，不把文档号误写成替代页码的文章号。

**版本与访问说明：**参考文献九条均引用正式期刊版 DOI、正式卷页和日期，没有 arXiv 条目，也没有 early access 或 to be published 占位。部分本地阅读材料仍是作者稿或预印本，这不改变已核实的正式发表信息；正文若引用仅预印本存在的细节，仍需核对正式版。Elsevier DOI 页面、Zhong 高校 PDF 网址及 ETH [9] 全页直接打开有失败，已分别用本地作者稿封面、既存期刊 PDF、ETH 检索记录及作者代码库交叉核对；[5] 仅取得出版社摘要和书目，未取得 PDF。没有声称全部出版社全文均可在线直读。

**IEEE 格式：**按 [IEEE Author Center 引用指南入口](https://journals.ieeeauthorcenter.ieee.org/create-your-ieee-journal-article/create-the-text-of-your-article/ieee-editorial-style-manual/)采用方括号编号、姓名首字母、题名句首大写、期刊缩写、卷期页、正式出版日期和 DOI。九篇均不超过六位作者，全部列出，不使用 et al.。DOI 大小写与题名大小写的规范化不改变所指文献。

## 核验口径

17 篇的题名、作者、发表年份、刊物、卷页与 DOI 均经 Crossref DOI 接口核验，并用出版社、作者高校页面或论文首页交叉检查。外部导引中的 3 个错误 DOI 和 P9 作者归属已纠正。作者姓名的变音符号优先按作者论文/高校页面保留。年份采用正式卷期年，不把预印本年或 DOI 中的年份误作正式发表年。

表中被引数为 2026-09-08 实时查询 Crossref 的 `is-referenced-by-count`，仅代表该数据库覆盖的总引用，未排除自引，不能称为 ESI 高被引论文认证。可通过 `https://api.crossref.org/works/` 后接相应 DOI 复查。排序优先考虑问题关联和教学价值，不按引用数机械排名。

全文状态分为本地 PDF、在线全文和仅摘要/片段。本轮是候选筛选、书目核验与关键段落检查；L11 两页正文已通读核对，其他论文未完成逐节精读。用户尚未反馈论文阅读；外部导引声称的“已读全文”不转记为本项目的阅读记录。

## 文献质量与分区依据

- 新增 L17 的分区依据：[IEEE 官方期刊清单，December 2025](https://open.ieee.org/wp-content/uploads/IEEE-Title-List-December-2025.pdf)，第 3 页 T-PEL 行明确列出 IEEE Transactions on Power Electronics 为 SCIE、JIF 6.5、JIF Quartile Q1；第 4 页脚注说明采用 **2024 JCR 数据、2025 年 6 月发布版**。据此确认该版本 Q1；不称已核验最新 2026 发布版，也不将 Q1 等同于中科院 Top 标签。
- [IEEE 官方刊物清单，2025-08-01 数据](https://open.ieee.org/wp-content/uploads/IEEE-Title-List-August-2025.pdf)：说明采用 2024 数据、2025 年 6 月发布的 JCR。TIE、TAC、TPWRS、OJIA、JESTPE、TSG 的 JIF Quartile 均标为 Q1；OJIA 为 ESCI，其余为 SCIE。该清单没有逐类别列出排名，类别明细尚待 JCR 原记录核验，也不代表已核验这些期刊的最新 2026 发布版。
- [Annual Reviews 官方排名](https://www.annualreviews.org/about/impact-factors)：2026 发布版、2025 数据，Annual Review of Control, Robotics, and Autonomous Systems 在 Automation & Control Systems 为 2/88，在 Robotics 为 3/48；依据两类排名可判定处于 Q1，JIF 14.6。
- Renewable and Sustainable Energy Reviews 的 JCR 年份及类别原记录尚未取得，因此 L01、L09 暂不标“Q1 已核验”。外部导引所写的 2023 数据、JIF 16.3 和类别名次没有可追溯的原始证明，不直接沿用。
- L02、L03 是会议文献，不适用 JCR 分区。为理解发展历程而保留；JCR Q1、SCIE 收录和中科院一区/Top 不是同一个标签。

## 快速选读地图

| ID | 作用 | 建议 | Crossref 被引 | 全文状态 |
|---|---|---|---|---|
| L01 | 惯量定义、能量与系统影响的入口 | 第一篇分段精读 | 727 | 已取得高校公开作者稿 |
| L02 | 低转动惯量如何改变频率动态 | 选读公式、曲线与假设 | 623 | 已取得 arXiv 预印本 |
| L03 | 低惯量问题全景与研究脉络 | 选读；与 L08 有交叠 | 851 | 未取得全文，仅摘要与检索片段 |
| L04 | 让逆变器模拟同步机的经典思路 | 精读核心原理，暂跳实现细节 | 2866 | 已取得作者高校 PDF |
| L05 | 同样的惯量放在哪里是否一样 | 进阶选读，理解基础后再决定 | 256 | 已取得 arXiv 预印本 |
| L06 | 构网、跟网、虚拟惯量及快速频响的连接 | 重点精读模型比较与结果边界 | 364 | 已取得 arXiv 预印本 |
| L07 | 构网与跟网的控制结构及限制 | 精读概念比较，选读细节 | 1130 | 已取得高校库公开 PDF |
| L08 | 从设备到系统，检查“补回惯量即可” | 后期选读关键章节 | 77 | 出版社 HTML 全文已确认可读，未保存本地 |
| L09 | 低惯量要求、问题与控制措施综述 | 备用；与 L01、L10 重叠 | 439 | 仅摘要与书目 |
| L10 | 风机、电容与储能怎样提供惯量支撑 | 选读能量载体与控制框图 | 605 | 作者上传的在线全文可读，无本地 PDF |
| L11 | 风机利用转子动能参与频率支撑的早期方案 | 精读，两页 | 1091 | 已取得 TU Delft 公开 PDF |
| L12 | 带功率滤波的下垂与 VSM 的条件等价 | 可选精读，两页；有一定推导门槛 | 599 | 在线全文 PDF 可读，本地下载失败 |
| L13 | 直流源、限流和快慢动态对支撑的影响 | 精读关键案例，选读模型细节 | 412 | 已取得 arXiv 预印本 |
| L14 | 低惯量系统的小信号模态与控制交互 | 进阶备用 | 339 | 已取得作者公开 PDF |
| L15 | 风机动能支撑结束后的转速恢复与二次跌落 | 精读机制与控制对比 | 109 | 作者上传的在线全文可读，无本地 PDF |
| L16 | 惯量和频率响应需求如何进入调度 | 调度方向备用 | 351 | 仅摘要与书目 |
| L17 | 将惯量响应、超级电容能量管理、阻尼与限流纳入同一构网方案 | 纳入 1.2；取得全文后重点读原理与验证边界 | 6 | 仅出版社摘要与书目，未取得全文 |

当前建议阅读路线：L01 → L11 → L10 → L04 → L17 → L07 → L06 → L15 → L13，共 9 篇；阅读路线不等于正文首次引用顺序。新增 L17 将近期储能与约束设计接到经典支撑方法之后。L12（数学等价）与 L08（系统综述）仍为可选：保留九篇时最多再加一篇，或替换现有文献，合计不超过 10 篇。并非要求九篇全部通篇精读，正式引用应对应用户实际读过的内容，未读全文的部分须明确标注。

## L01：定义与能量入口

**The relevance of inertia in power systems**

Pieter Tielens; Dirk Van Hertem. 2016. *Renewable and Sustainable Energy Reviews*, 55, 999–1009. DOI：[10.1016/j.rser.2015.11.016](https://doi.org/10.1016/j.rser.2015.11.016)。

- 回答的问题：惯量来自哪里？惯量常数怎样定义？变流器接口为何改变原有的转速—频率联系？
- 值得读：题目和作业直接对应，适合建立术语与物理图景；是本组的入门综述。
- 读法：先精读第 2 节与图 2，再进入量化和系统影响。当前已核对作者稿封面、摘要及第 2 节相关公式，尚未精读全篇。
- 边界：文中系统聚合公式有同步连接、容量基准和忽略部分负荷惯量等假设；惯量常数不能直接理解为允许全功率支撑的持续时间。历史背景数据属于当时，不当作 2026 年事实。
- 全文：[KU Leuven 作者稿](https://lirias.kuleuven.be/retrieve/f9638e33-7272-4a93-a99c-1bf1930cb263)；[本地 PDF](../../source/HW01_Inertia/L01_Tielens_2016_repository.pdf)。21 页含封面，封面说明为接受发表的作者版本；正式期刊版为 11 页。OpenAlex 的 submittedVersion 标签与稿件封面不同，此处以实际封面为据。

## L02：低惯量的动态后果

**Impact of Low Rotational Inertia on Power System Stability and Operation**

Andreas Ulbig; Theodor S. Borsche; Göran Andersson. 2014. *IFAC Proceedings Volumes*, 47(3), 7290–7297，19th IFAC World Congress. DOI：[10.3182/20140824-6-ZA-1003.02615](https://doi.org/10.3182/20140824-6-ZA-1003.02615)。

- 回答的问题：相同功率扰动下，较低转动惯量如何影响频率变化和运行？
- 值得读：较早、被广泛引用的低惯量系统分析，有助于把“问题出现”与后来的控制补偿研究连接起来。
- 读法：选读频率动态的模型、参数对比和曲线，不要求初学阶段通读所有稳定性分析。
- 边界：对比必须说明扰动大小、阻尼和控制设置；不能从局部曲线推导所有系统都存在相同惯量门槛。
- 全文：[arXiv 页面](https://arxiv.org/abs/1312.6435)；[本地 PDF](../../source/HW01_Inertia/L02_Ulbig_2014_preprint.pdf)。预印本初始年份为 2013，正式出版为 2014；版本分页不同，不混用页码。

## L03：基础与挑战全景

**Foundations and Challenges of Low-Inertia Systems (Invited Paper)**

Federico Milano; Florian Dörfler; Gabriela Hug; David J. Hill; Gregor Verbič. 2018. *2018 Power Systems Computation Conference (PSCC)*, 1–25. DOI：[10.23919/PSCC.2018.8450880](https://doi.org/10.23919/PSCC.2018.8450880)。

- 回答的问题：低惯量系统的困难是否仅是频率下降更快？建模、同步、控制之间怎样关联？
- 值得读：受邀综述，提供跨电力系统与控制领域的基础路线，也可用于追溯参考文献。
- 读法：选读频率、惯量和变流器控制部分；与 L08 重叠，不必两篇都全篇精读。
- 边界：当前推荐基于作者摘要和目录/检索片段，不使用尚未核对的正文细节作论据。
- 全文状态：作者的 [UCD PDF 地址](https://faraday1.ucd.ie/archive/papers/lowinertia.pdf) 已定位，但本次网页打开失败、本地获取遇到 TLS 连接错误，未保存全文。[ETH 作者条目](https://old.control.ee.ethz.ch/publications/2018/6009.html) 与 [HKU 条目](https://hub.hku.hk/handle/10722/263530) 可核验书目。HKU 列表作者排序有差异，采用 Crossref 及论文首页检索展示的顺序。

## L04：同步逆变器的经典方案

**Synchronverters: Inverters That Mimic Synchronous Generators**

Qing-Chang Zhong; George Weiss. 2011. *IEEE Transactions on Industrial Electronics*, 58(4), 1259–1267. DOI：[10.1109/TIE.2010.2048839](https://doi.org/10.1109/TIE.2010.2048839)。

- 回答的问题：没有机械转子的逆变器，能否通过控制呈现某些同步机动态？实际交换的能量来自哪里？
- 值得读：同步逆变器（Synchronverter）的代表性奠基论文，提供从物理模型到控制实现的直观桥梁；本轮 Crossref 被引 2866 次。并非声称它是所有虚拟同步机思想的最早出处。
- 读法：精读同步机模型、直流侧与交流侧功率关系和控制思路，暂跳硬件实现细节。已核对首页、直流储能说明与仿真初始同步段落，未逐节精读。
- 边界：模拟同步机的动态方程不等于自动拥有其能量、过载能力或全部稳定特性；实验装置结论不能直接推广为全系统替代结论。本文仿真明确使用锁相环（Phase-Locked Loop, PLL）进行初始同步，不能以该文证明“全流程无 PLL、完全无延时”。
- 全文：[作者高校 PDF](https://www.eng.tau.ac.il/~gweiss/art97_IEEE.pdf)；[本地 PDF](../../source/HW01_Inertia/L04_Zhong_2011_author.pdf)，9 页期刊排版。2010 为在线发表/DOI 年，正式卷期为 2011。

## L05：系统中的位置与指标

**Optimal Placement of Virtual Inertia in Power Grids**

Bala Kameshwar Poolla; Saverio Bolognani; Florian Dörfler. 2017. *IEEE Transactions on Automatic Control*, 62(12), 6209–6220. DOI：[10.1109/TAC.2017.2703302](https://doi.org/10.1109/TAC.2017.2703302)。

- 回答的问题：系统惯量总量相同，空间配置是否仍会改变效果？优化到底改善哪个指标？
- 值得读：把装置惯量讨论推进到网络位置与性能指标，防止只看单个惯量常数。
- 读法：进阶选读问题设定和算例，当前不要求推导优化算法。
- 作者模型假设：线性化、网络降阶模型及 H2 性能指标；局部最优与特殊情形全局结论有区别。不能当作所有非线性暂态与限流情况下的最优方案。
- 全文：[arXiv](https://arxiv.org/abs/1510.01497)；[ETH 作者记录](https://old.control.ee.ethz.ch/publications/2017/5362.html)；[本地预印本](../../source/HW01_Inertia/L05_Poolla_2017_preprint.pdf)。

## L06：把控制类型与频率服务分开

**Placement and Implementation of Grid-Forming and Grid-Following Virtual Inertia and Fast Frequency Response**

Bala Kameshwar Poolla; Dominic Groß; Florian Dörfler. 2019. *IEEE Transactions on Power Systems*, 34(4), 3035–3046. DOI：[10.1109/TPWRS.2019.2892290](https://doi.org/10.1109/TPWRS.2019.2892290)。

- 回答的问题：构网型、跟网型实现虚拟惯量及快速频率响应时，有哪些不同的动态环节和系统效果？
- 值得读：直接连接本作业容易混淆的几类概念，有明确装置建模、配置问题和系统案例。
- 读法：在理解 L04、L07 后，精读模型比较、频率指标和案例边界；优化求解细节选读。
- 边界：作者基于其控制实现和东南澳系统模型开展案例，不能改写成“所有构网控制始终优于所有跟网控制”。
- 全文：[arXiv](https://arxiv.org/abs/1807.01942)；[本地预印本](../../source/HW01_Inertia/L06_Poolla_2019_preprint.pdf)。本清单采用 2019 TPWRS 正式论文；检索中有 2020 PESGM 同题条目，不重复计为第二篇。

## L07：构网与跟网的控制地图

**Grid-Forming Converters: Control Approaches, Grid-Synchronization, and Future Trends—A Review**

Roberto Rosso; Xiongfei Wang; Marco Liserre; Xiaonan Lu; Soenke Engelken. 2021. *IEEE Open Journal of Industry Applications*, 2, 93–109. DOI：[10.1109/OJIA.2021.3074028](https://doi.org/10.1109/OJIA.2021.3074028)。

- 回答的问题：构网型控制（Grid-Forming, GFM）与跟网型控制（Grid-Following, GFL）到底怎样区别？同步和限流为何影响支撑能力？
- 值得读：概念对比、统一控制结构及开放问题集中在一篇综述里，便于建立装置控制地图。
- 读法：精读第 II 节和图 1–3，选读第 IV 节中的同步稳定及故障穿越限制。
- 边界：GFM 是控制类别，不自动等于虚拟同步机，也不保证具有无限能量和电流支撑能力。
- 全文：[Aalborg 机构记录](https://vbn.aau.dk/da/publications/grid-forming-converters-control-approaches-grid-synchronization-a/)；[公开 PDF](https://vbn.aau.dk/ws/files/437615274/Grid_Forming_Converters_Control_Approaches_Grid_Synchronization_and_Future_TrendsA_Review.pdf)；[本地 PDF](../../source/HW01_Inertia/L07_Rosso_2021_repository.pdf)。机构库文件含封面共 18 页，正文 93–109 页。

## L08：回到系统层判断

**Control of Low-Inertia Power Systems**

Florian Dörfler; Dominic Groß. 2023. *Annual Review of Control, Robotics, and Autonomous Systems*, 6, 415–445. DOI：[10.1146/annurev-control-052622-032657](https://doi.org/10.1146/annurev-control-052622-032657)。

- 回答的问题：为什么“补回惯量”未必解决所有低惯量系统问题？装置模型、同步和系统服务怎样连接？
- 值得读：较新的高水平控制综述，适合在基础建立后检查概念和过度推广，而非零基础第一篇。
- 读法：选读第 2 节模型概念、第 4 节频率动态，以及结论；不要求一次读完控制理论。
- 边界：作者明确说明综述带有自身研究视角；“低惯量”不能替代对控制相互作用的具体分析。
- 全文：[出版社 HTML 全文](https://www.annualreviews.org/content/journals/10.1146/annurev-control-052622-032657) 已确认含各节正文及参考文献，尚未保存本地，也未精读全篇。在线提前发表为 2022-10-06，正式卷年为 2023。

## 检索记录与剩余事项

本轮检索主题：`inertia power systems review`、`low rotational inertia power system stability`、`synchronverters`、`grid-forming grid-following virtual inertia fast frequency response`、`optimal placement virtual inertia`。按 DOI 去重，以 2011–2023 的基础发展路线为目的；不是截至 2026 年的系统性穷尽综述。

学术检索 MCP 未挂载，采用网页发现 → Crossref DOI 核验 → 作者/出版社全文确认，并以 OpenAlex 辅助定位公开版本。本次融合后的状态：9 份本地 PDF（L01、L02、L04、L05、L06、L07、L11、L13、L14）；4 篇在线全文（L08、L10、L12、L15）；3 篇仅摘要/片段（L03、L09、L16）。作者上传版本与正式刊物版分页可能不同，引用书目采用正式版，阅读定位注明版本。

## L09：运行要求与解决途径综述（外部 P2）

**Future low-inertia power systems: Requirements, issues, and solutions - A review**

Kamala Sarojini Ratnam; K. Palanisamy; Guangya Yang. 2020. *Renewable and Sustainable Energy Reviews*, 124, 109773. DOI：[10.1016/j.rser.2020.109773](https://doi.org/10.1016/j.rser.2020.109773)。

- 回答的问题：低惯量带来哪些要求与问题，可以采用哪些控制措施？
- 值得读与读法：覆盖运行要求和风、光、微网控制，作为综述备用；与现有综述重叠，当前不增加必读负担。
- 证据边界：仅核对摘要，不能沿用外部导引声称的特定事故、表 1、图 1 或逐节结论。
- 全文：未取得。[DTU 作者机构条目及摘要](https://orbit.dtu.dk/en/publications/future-low-inertia-power-systems-requirements-issues-and-solution/)。

## L10：惯量支撑的实际能量载体（外部 P3）

**On the Inertia of Future More-Electronics Power Systems**

Jingyang Fang; Hongchang Li; Yi Tang; Frede Blaabjerg. 2019. *IEEE Journal of Emerging and Selected Topics in Power Electronics*, 7(4), 2130–2146. DOI：[10.1109/JESTPE.2018.2877766](https://doi.org/10.1109/JESTPE.2018.2877766)。

- 回答的问题：风机、直流电容、超级电容和电池怎样通过变流器参与惯量支撑？
- 值得读与读法：连接 L01 的能量定义与 L04 的控制思路，选读不同能量载体和相应控制结构；暂跳详细设计。
- 边界：这是一篇广泛梳理相关技术的文章，图表包含被综述工作的结果；不能把所有实验波形称为作者自己完成的硬件在环实验。能量可用范围需结合电压、转速和功率限制。
- 全文：[Aalborg 作者机构书目](https://vbn.aau.dk/en/publications/on-the-inertia-of-future-more-electronics-power-systems/)；[作者上传的在线全文](https://www.researchgate.net/publication/328513288_On_the_Inertia_of_Future_More-Electronics_Power_Systems)。在线正文已确认，检查了相关段落；IEEE PDF 获取失败，未保存本地。2018 是在线发表年，正式卷期为 2019。

## L11：风机利用“已有但未自然耦合”的动能（外部 P4）

**Wind Turbines Emulating Inertia and Supporting Primary Frequency Control**

Johan Morren; Sjoerd W. H. de Haan; Wil L. Kling; J. A. Ferreira. 2006. *IEEE Transactions on Power Systems*, 21(1), 433–434. DOI：[10.1109/TPWRS.2005.861956](https://doi.org/10.1109/TPWRS.2005.861956)。

- 回答的问题：变速风机仍有转子动能，为何需要附加控制才能用于频率支撑？支撑结束后怎样恢复？
- 值得读与读法：高引用的早期代表性研究，两页精读，尤其图 1、IV 节与 V 节。未核验“领域绝对首次”的优先权，不使用这一说法。
- 作者证据：控制框图含惯量模拟和频率支撑两支路；IV 节明确此处仿真只演示一次频率支撑，没有启用额外惯量模拟。算例是两台同步机和六台风机的小电网，扰动为 20 MW 同步机退出。
- 边界：不能把图 2 称为微分惯量支路的验证。V 节已经讨论恢复导致的输出下降以及错开退出、渐变恢复，不能说早期作者完全忽视恢复代价。
- 全文：[TU Delft 官方记录](https://research.tudelft.nl/en/publications/wind-turbines-emulating-inertia-and-supporting-primary-frequency-/)；[本地 PDF](../../source/HW01_Inertia/L11_Morren_2006_repository.pdf)，2 页；[检索正文](../../notes/source_extracts/L11_Morren_2006_repository.txt)。本轮已通读核对两页。

## L12：下垂与虚拟同步机的条件等价（外部 P6）

**Equivalence of Virtual Synchronous Machines and Frequency-Droops for Converter-Based MicroGrids**

Salvatore D’Arco; Jon Are Suul. 2014. *IEEE Transactions on Smart Grid*, 5(1), 394–395. DOI：[10.1109/TSG.2013.2288000](https://doi.org/10.1109/TSG.2013.2288000)。

- 回答的问题：带有功率测量滤波的下垂控制，何时与基于摆动方程的虚拟同步机（Virtual Synchronous Machine, VSM）有相同动态表达？
- 值得读与读法：两页短文，适合已有控制基础后精读图 1–3、式 (1)–(6)；当前作为可选补充。
- 边界：限定文中的模型、恒定参考值和参数映射。作者图 3 确有阶跃响应比较，但不是所有 VSM 与所有下垂控制的全工况等价证明。外部导引把功率测量低通滤波的传递方向写反，修正见整合报告。
- 全文：[IEEE 原始条目](https://ieeexplore.ieee.org/document/6683080/)；[作者上传的在线 PDF](https://www.researchgate.net/profile/Jon-Suul/publication/260058589_Equivalence_of_Virtual_Synchronous_Machines_and_Frequency-Droops_for_Converter-Based_MicroGrids/links/0c96052f52c68ecacf000000/Equivalence-of-Virtual-Synchronous-Machines-and-Frequency-Droops-for-Converter-Based-MicroGrids.pdf)。在线两页正文已核对关键段落；直接下载返回 403，无本地文件。

## L13：直流侧、限流与系统动态的共同约束（外部 P7）

**Frequency Stability of Synchronous Machines and Grid-Forming Power Converters**

Ali Tayyebi; Dominic Groß; Adolfo Anta; Friederich Kupzog; Florian Dörfler. 2020. *IEEE Journal of Emerging and Selected Topics in Power Electronics*, 8(2), 1004–1018. DOI：[10.1109/JESTPE.2020.2966524](https://doi.org/10.1109/JESTPE.2020.2966524)。

- 回答的问题：控制器的良好频率表现，如何受到直流源响应、直交流限流以及与同步机动态相互作用的影响？
- 值得读与读法：主线末篇，精读 IV-D、IV-E 和结论；复杂模型暂选读。已核对建模、限流案例和结论。
- 作者证据：采用平均变换器模型及 IEEE 9 节点案例；直流源饱和可能发生在尚未达到交流电流限值时。简单电流限幅仍可能不稳定；修改有功设定值的限流方案能稳定文中部分案例，matching control 在所测直流饱和案例表现不同。
- 边界：不能归结成“一触碰半导体限流就必然失稳”，也不能把案例当作已完成所有短路故障验证和形式化稳定性证明。
- 全文：[arXiv](https://arxiv.org/abs/2003.04715)；[本地预印本](../../source/HW01_Inertia/L13_Tayyebi_2020_preprint.pdf)，15 页；[检索正文](../../notes/source_extracts/L13_Tayyebi_2020_preprint.txt)。

## L14：系统稳定性不止一个惯量数值（外部 P8）

**Understanding Small-Signal Stability of Low-Inertia Systems**

Uroš Marković; Ognjen Stanojev; Petros Aristidou; Evangelos Vrettos; Duncan Callaway; Gabriela Hug. 2021. *IEEE Transactions on Power Systems*, 36(5), 3997–4017. DOI：[10.1109/TPWRS.2021.3061434](https://doi.org/10.1109/TPWRS.2021.3061434)。

- 回答的问题：同步机、跟网型与构网型变流器混合后，哪些动态及参数主导小信号稳定性？
- 值得读与读法：将系统层讨论推进到模态分析；当前门槛较高，作为进阶备用，选读摘要、结论和模型范围。
- 边界：工作点附近的线性化模型与参数敏感性结果，不能直接证明大故障暂态稳定，也不能提炼出所有电网通用的构网比例门槛。
- 全文：[IEEE 条目](https://ieeexplore.ieee.org/document/9361257)；[作者公开稿](https://sps-lab.org/publication/2021jmarkovicb/2021JMarkovicb.pdf)；[本地 PDF](../../source/HW01_Inertia/L14_Markovic_2021_author.pdf)，19 页作者稿，分页区别于正式版；[检索正文](../../notes/source_extracts/L14_Markovic_2021_author.txt)。

## L15：风机支撑后的转速恢复（外部 P9）

**Avoiding Frequency Second Dip in Power Unreserved Control During Wind Power Rotational Speed Recovery**

Kangcheng Liu; Yanbin Qu; Hak-Man Kim; Huihui Song. 2018. *IEEE Transactions on Power Systems*, 33(3), 3097–3106. DOI：[10.1109/TPWRS.2017.2761897](https://doi.org/10.1109/TPWRS.2017.2761897)。

- 回答的问题：未预留功率的风机释放动能后，恢复转速为何可能造成第二次频率下降，控制如何缓解？
- 值得读与读法：与 L11 构成清晰的历史衔接；精读恢复机理和控制前后比较，不必先掌握所有风机设计细节。
- 边界：作者提出的修改控制在所研究孤岛微网案例中缓解二次跌落；恢复动能的需要不等于必然出现严重二次跌落。风能输入继续存在，转子加速通常来自减少送网功率，不能一概写成风机从电网反向购电。
- 全文：[第一作者主页](https://kangchengliu.github.io/)列有此文及代码；[作者上传的在线全文](https://www.researchgate.net/publication/320341815_Avoiding_Frequency_Second_Dip_in_Power_Unreserved_Control_During_Wind_Power_Rotational_Speed_Recovery)可读，已核对作者、摘要与相关正文，未保存本地 PDF、未逐节精读。外部导引的 Kang 等五人不是这篇文章的作者。

## L16：把频率要求放进调度（外部 P10）

**Stochastic Scheduling With Inertia-Dependent Fast Frequency Response Requirements**

Fei Teng; Vincenzo Trovato; Goran Strbac. 2016. *IEEE Transactions on Power Systems*, 31(2), 1557–1566. DOI：[10.1109/TPWRS.2015.2434837](https://doi.org/10.1109/TPWRS.2015.2434837)。

- 回答的问题：怎样在随机调度中让频率响应需求随在线惯量而改变？
- 值得读与读法：从动态模型连接到运行决策，适合作业最终选择调度观点时替换进主线；当前作为备用。
- 边界：现仅核对摘要与书目；外部导引中的特定公式、毫秒数和“直接反比替代”均不作为已核实论据。未来 GB 2030 场景不应称为已观测的 2030 实际运行数据。
- 全文：尚未取得。[Imperial 作者机构记录](https://www.imperial.ac.uk/electrical-engineering/research/control-and-power/publications/?id=747352&noscript=noscript&respub-t4-action=citation.html)；[IEEE 条目](https://ieeexplore.ieee.org/document/7115982)。同题 2016 PESGM 条目不另算一篇。

## L17：近期代表性方法——能量管理、阻尼与限流协同

**Improved Grid Forming Control for Energy-Type STATCOM to Enhance Damping and Limit Multiple Currents**

Xianqiang Shi; Rui Li; Xiqi Wu; Dangsheng Zhou; Yirun Cheng; Xu Cai. 2025. *IEEE Transactions on Power Electronics*, 40(10), 15450–15465, October. DOI：[10.1109/TPEL.2025.3569931](https://doi.org/10.1109/TPEL.2025.3569931)。

- **来源与版本核验：**[IEEE 出版社条目](https://ieeexplore.ieee.org/document/11003428/)与 [Crossref DOI 元数据](https://api.crossref.org/works/10.1109/TPEL.2025.3569931)核对题名、六位作者及顺序、期刊、卷期和页码。IEEE 提前上线日期为 2025-05-13，正式卷期为 2025-10，均符合 2024 年 12 月之后的要求；引用正式期刊版，不引用预印本或 early access 占位。
- **质量依据：**TPEL 是电力电子领域主流权威期刊，IEEE 官方 December 2025 清单列为 SCIE、JCR Q1、JIF 6.5（2024 数据、2025 年 6 月发布版）；出处见上方分区说明。新论文不以高引用或奠基地位作为选入理由。
- **回答的问题：**实际储能装置怎样在提供惯量响应时，同时照顾能量状态、振荡阻尼与电流上限？
- **作者在摘要中报告的方案：**在储能型静止同步补偿器（Energy-Type Static Synchronous Compensator, ET-STATCOM）中嵌入超级电容，提供有功惯量响应及无功电压支撑。方案结合基于匹配控制的能量同步环节、有功直接反馈增强阻尼和多电流限制，目标包括自主能量管理、自同步，以及总电流和有功/无功电流分别限制。摘要报告仿真与实际样机验证；尚未核验正文中的实验设置和结果曲线。
- **辅导解释与选入理由：**接在 L11 的转子动能调用、L04 的同步机动态模拟之后，能将 1.2 的比较扩展到“如何把实际能量资源与装置约束纳入支撑方法”。这是一条为本作业组织的比较线索，不是作者提出的全领域历史分期。比仅新增一般综述更适合用户指定的“代表性方法”小节。
- **阅读建议：**选读方法结构，重点读能量来源、同步机制、限流与阻尼设计，以及验证条件；暂跳过复杂电路推导。取得全文前只作摘要层面的介绍，不能据此写实验优越性、参数公式或适用范围的强结论。
- **边界：**特定 ET-STATCOM 控制和验证不能直接推广为全系统频率安全，也不能据此认定虚拟惯量可完全替代同步机物理惯量。近年存在这一研究可说明该问题仍有新方法发表，不能凭单篇判断全领域研究热度。
- **全文状态：**尚未取得。IEEE 公开条目提供摘要和正式书目；OpenAlex 未提供 OA 全文，ResearchGate 条目标为 Request PDF。IEEE PDF 端点本次请求返回 HTTP 418，未保存 PDF，也未生成本地全文链接。可由用户通过 IEEE 机构订阅入口阅读正式版；不记为代理或用户已阅读全文。
