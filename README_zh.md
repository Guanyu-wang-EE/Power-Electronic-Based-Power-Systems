# 电力电子化电力系统 — EE6005

<p align="right">
  <a href="README.md">English</a> | <strong>中文</strong>
</p>

王冠羽的课程学习资料库，保存课程资料、文献笔记、作业草稿、交付 PDF 和审核记录。本项目用于学习与写作，目前没有可执行仿真或训练实验。

## 从这里开始

| 入口 | 用途 |
| --- | --- |
| [当前状态](notes/CURRENT_STATE.md) | 最新进展及带日期的审核历史；优先于较早的规划记录 |
| [课程概览](notes/COURSE_OVERVIEW.md) | 大纲的 11 个模块、32 学时及尚未明确的课程要求 |
| [项目简介](PROJECT_BRIEF.md) | 原始资料、作业的详细导航和历史背景 |
| [协作规则](AGENTS.md) | 项目边界、资料处理、写作约定与仓库维护 |

## 仓库结构

| 目录 | 内容 |
| --- | --- |
| [原始资料](source/) | 课程 Word 原件、文献 PDF 和外部研究导引 |
| [学习笔记](notes/) | 课程概览、当前状态和可检索的[原文提取文本](notes/source_extracts/) |
| [作业工作区](assignments/) | 作业题目、文献清单、阅读笔记及 HW01 可编辑稿 |
| [交付与审核](outputs/) | 报告、Word/PDF 成果、原稿备份和历史版式校验文件 |

## 作业与证据入口

| 主题 | 阅读与证据 | 交付文件 |
| --- | --- | --- |
| HW01：电力电子化电力系统惯量问题 | [作业要求](assignments/HW01_Inertia/ASSIGNMENT.md)、[文献清单](assignments/HW01_Inertia/LITERATURE.md)、[阅读笔记](assignments/HW01_Inertia/READING_NOTES.md)、[文献原件](source/HW01_Inertia/) | [可编辑 Word](assignments/HW01_Inertia/电力电子化电力系统惯量问题解读.docx)、[交付 PDF](outputs/HW01_Inertia/第一次作业_电力电子化电力系统惯量问题解读_王冠羽.pdf) |
| HW02：柔性高压直流输电（Flexible High-Voltage Direct Current Transmission，柔性直流）的中国发展与领跑 | [作业要求](assignments/HW02_SoftTx/ASSIGNMENT.md)、[文献清单](assignments/HW02_SoftTx/LITERATURE.md)、[阅读笔记](assignments/HW02_SoftTx/READING_NOTES.md)、[原始资料](source/HW02_SoftTx/) | [可编辑 Word](outputs/HW02_SoftTx/柔性直流输电技术在我国的发展和领跑.docx)、[当前 PDF](outputs/HW02_SoftTx/柔性直流输电技术在我国的发展和领跑.pdf) |

HW01 已有交付 PDF，并保留维持原结构的最小修改记录。HW02 已有 Word 稿和五页 PDF，2026-09-15 的审阅反馈见当前状态。文件存在不代表已向教师提交或获得认可。

其他报告：[HW01 审核与修订记录](outputs/HW01_Inertia/DRAFT01_REVIEW.md)、[文献整合核验](outputs/HW01_Inertia/LITERATURE_INTEGRATION_REVIEW.md)、[个人解读指导](outputs/HW01_Inertia/PERSONAL_INTERPRETATION_GUIDE.md)、[IEEE 格式参考文献](outputs/HW01_Inertia/REFERENCES_IEEE.md)。

## 资料依据与结论边界

[课程简介](<source/EE6005_ 电力电子化电力系统 内容简介 202305.doc>)和[教学大纲](source/EE6005_+电力电子化电力系统+教学大纲+202305.docx)的版本标记为 202305。文件记载本课程为 32 学时、2 学分的博士课程，考核方式为考试；这些信息不等于已确认当前学期的安排、成绩比例、作业期限或考试范围。

文献清单区分书目核验、摘要获取和全文获取。下载论文不代表学生已阅读。外部导引及提取文本用于辅助检索，以原始来源为核对依据。工程领跑表述必须保留相应日期、指标与适用范围。本资料库不证明新的实验结果，也不代表已核验当前世界纪录。

## 文档、图片与核验

作业正文以所链接的 Word 和 PDF 为入口。[.qa_revision 历史校验目录](outputs/HW01_Inertia/.qa_revision/)保留 HW01 各轮页面渲染 PNG、中间 PDF、一个 Word 修订文件和文字替换记录。它们来自不同修订阶段，含已被替代的版本，仅用于版式诊断，不是独立科研图或当前提交稿。制作展示摘录时使用当前 PDF，不应只凭图片文件名挑选旧页面。目前没有独立 SVG 图包或可执行绘图流程。

[审核记录](outputs/HW01_Inertia/DRAFT01_REVIEW.md)与[当前状态](notes/CURRENT_STATE.md)保存此前文字和版式检查的说明。仓库维护核验包括双语 README 一致性、本地导航链接、空白格式、完整文件纳入及远端同步；不表示重新科学审核了全部归档资料。

## 获取与维护

使用 Git 获取完整资料库：

```sh
git clone git@github.com:Guanyu-wang-EE/Power-Electronic-Based-Power-Systems.git
cd Power-Electronic-Based-Power-Systems
git status --short
git ls-files
git diff --check
git fetch origin
git rev-list --left-right --count origin/main...main
```

最后一条命令输出 `0 0` 表示本地与远端主分支一致。阅读仅需 Markdown 阅读器、兼容的 Word 阅读器和 PDF 阅读器。目前没有必需的 Python 环境、求解器、固定种子实验或数值复现命令。

项目文件全部纳入，包括课程原件、文献 PDF、草稿、备份、提取文本及隐藏的版式校验文件。不新增项目忽略规则。Git 自身的内部元数据不属于课程内容，Git 不记录空目录。本次发布不清理或删除历史文件。

## 后续工作与待补信息

围绕用户当前课程问题或明确指定的稿件继续。保留课程原件与历史草稿，只修改用户要求的作业内容。当前学期课件、确认的截止时间、成绩细则及考试范围仍待补充；资料库发布不代表启动新实验或自动提交作业。
