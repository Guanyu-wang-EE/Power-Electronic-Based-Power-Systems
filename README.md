# Power-Electronic-Based Power Systems — EE6005

<p align="right">
  <strong>English</strong> | <a href="README_zh.md">Chinese</a>
</p>

Course study archive maintained by Guanyu Wang: course materials, literature notes, assignment drafts, delivered PDFs, and review records. This is a learning and writing repository; it does not currently contain executable simulations or training experiments.

## Start here

| Entry | Purpose |
| --- | --- |
| [Current state](notes/CURRENT_STATE.md) | Latest progress and dated review history; consult this before older planning notes |
| [Course overview](notes/COURSE_OVERVIEW.md) | Eleven syllabus modules, 32 contact hours, and unresolved course requirements |
| [Project brief](PROJECT_BRIEF.md) | Detailed source and assignment navigation with historical context |
| [Working instructions](AGENTS.md) | Scope, source handling, writing conventions, and repository maintenance |

## Repository map

| Directory | Contents |
| --- | --- |
| [source](source/) | Original course Word files, literature PDFs, and external research guides |
| [notes](notes/) | Course overview, current state, and searchable [source extracts](notes/source_extracts/) |
| [assignments](assignments/) | Assignment prompts, literature lists, reading notes, and the HW01 editable draft |
| [outputs](outputs/) | Reports, Word/PDF deliverables, original-draft backup, and historical layout checks |

## Assignments and evidence

| Topic | Reading and evidence | Deliverables |
| --- | --- | --- |
| HW01: inertia in power-electronic-based power systems | [Assignment](assignments/HW01_Inertia/ASSIGNMENT.md), [literature](assignments/HW01_Inertia/LITERATURE.md), [reading notes](assignments/HW01_Inertia/READING_NOTES.md), [source papers](source/HW01_Inertia/) | [Editable Word](assignments/HW01_Inertia/电力电子化电力系统惯量问题解读.docx), [delivered PDF](outputs/HW01_Inertia/第一次作业_电力电子化电力系统惯量问题解读_王冠羽.pdf) |
| HW02: development and leadership of flexible high-voltage direct current transmission in China | [Assignment](assignments/HW02_SoftTx/ASSIGNMENT.md), [literature](assignments/HW02_SoftTx/LITERATURE.md), [reading notes](assignments/HW02_SoftTx/READING_NOTES.md), [source material](source/HW02_SoftTx/) | [Editable Word](outputs/HW02_SoftTx/柔性直流输电技术在我国的发展和领跑.docx), [current PDF](outputs/HW02_SoftTx/柔性直流输电技术在我国的发展和领跑.pdf) |

HW01 has a delivered PDF and a minimal revision record preserving the original structure. HW02 has a Word draft and a five-page PDF reviewed on 2026-09-15; feedback is recorded in the current-state file. File availability does not establish assignment submission or teacher acceptance.

Additional reports: [HW01 review and revision record](outputs/HW01_Inertia/DRAFT01_REVIEW.md), [literature integration review](outputs/HW01_Inertia/LITERATURE_INTEGRATION_REVIEW.md), [personal interpretation guide](outputs/HW01_Inertia/PERSONAL_INTERPRETATION_GUIDE.md), and [IEEE references](outputs/HW01_Inertia/REFERENCES_IEEE.md).

## Sources and interpretation limits

The [course description](<source/EE6005_ 电力电子化电力系统 内容简介 202305.doc>) and [syllabus](source/EE6005_+电力电子化电力系统+教学大纲+202305.docx) carry the version marker 202305. They describe a 32-hour, two-credit doctoral course assessed by examination; they do not confirm the current semester schedule, grading weights, assignment deadlines, or examination scope.

Literature lists distinguish bibliographic verification, abstract access, and full-text availability. A downloaded paper does not mean it has been read by the student. External guides and extracted text support navigation; original sources remain authoritative. Engineering leadership claims must retain their stated dates, metrics, and scope. This archive does not demonstrate new experimental results or verified current world records.

## Documents, figures, and validation

Read the linked Word and PDF deliverables for assignment content. Historical HW01 page-render PNGs, intermediate PDFs, a Word revision, and a replacement record are retained in [.qa_revision](outputs/HW01_Inertia/.qa_revision/). These are layout diagnostics from different revision stages, including superseded stages, rather than independent scientific figures or the current submission. For presentation excerpts, use the current PDF; do not select an old page image solely by its filename. No standalone SVG figure package or executable figure-generation pipeline is present.

The [review record](outputs/HW01_Inertia/DRAFT01_REVIEW.md) and [current state](notes/CURRENT_STATE.md) describe prior text and layout checks. Repository maintenance checks cover bilingual README consistency, local navigation links, whitespace, complete file inclusion, and synchronization with the remote. They do not constitute a new scientific review of every archived source.

## Access and maintenance

Clone the complete archive with Git:

```sh
git clone git@github.com:Guanyu-wang-EE/Power-Electronic-Based-Power-Systems.git
cd Power-Electronic-Based-Power-Systems
git status --short
git ls-files
git diff --check
git fetch origin
git rev-list --left-right --count origin/main...main
```

The last command reports `0 0` when local and remote main branches agree. A Markdown viewer, a compatible Word reader, and a PDF viewer are sufficient for reading. There is no required Python environment, solver, fixed-seed experiment, or numerical reproduction command in the current project.

All project files are included, including source documents, literature PDFs, drafts, backups, extracted text, and hidden layout-check artifacts. No project ignore rules are introduced. Git's own internal metadata is not course content, and empty directories are not represented by Git. No cleanup or removal of historical files is part of this publication.

## Next work and missing information

Continue from the user's current course question or explicitly named draft. Preserve the original course documents and historical drafts; make only requested changes to assignment text. Current-semester teaching materials, confirmed deadlines, grading details, and examination scope remain pending. Do not infer a new experiment or automatic assignment submission from the archive's publication.
