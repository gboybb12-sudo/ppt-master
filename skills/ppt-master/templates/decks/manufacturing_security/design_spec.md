---
deck_id: manufacturing_security
kind: deck
summary: "制造业数字化转型与信息安全解决方案的经典工业蓝配色模板。包含高可用架构、边界防护、终端防泄密与安全案例等多套复用板式。"
canvas_format: ppt169
canvas_width: 1280
canvas_height: 720
canvas_viewbox: "0 0 1280 720"
source_canvas_width: 1707
source_canvas_height: 960
source_viewbox: "0 0 1706.67 960"
page_count: 10
primary_color: "#0B5395"
accent_color: "#00B0F0"
category: scenario
scenarios: ["制造业信息化", "网络安全架构", "IT/OT融合系统集成"]
keywords: ["制造行业", "网络安全", "IT基础设施", "安全防护"]
---

# design_spec - manufacturing_security

## I. Template Overview

本模板源自《制造行业IT基础设施与网络安全解决方案》的经典工业蓝风格。整体基调专业、稳健而富有科技感，特别针对大中型制造企业的 IT 基础架构建设、数字化转型痛点、信息安全合规、终端安全管理（EDR/DLP/NAC）以及实战攻防案例汇报而设计。

---

## II. Color Scheme

本模板严格贯彻以“安全感、工业集成、高可靠”为主轴的调色规范：

| 角色 | HEX 颜色 | 视觉用途 |
|---|---|---|
| **Primary** | `#0B5395` | 主题深蓝：用于大面积背景、标题字、重点框架与主装饰矩形块 |
| **Accent** | `#00B0F0` | 科技亮蓝：用于高亮标签、修饰侧边粗线、进度圆环与核心字强调 |
| **Light Blue** | `#B3DDF2` | 浅蓝底色：用于深蓝色带上的次要文本高亮和标注背景 |
| **Dark Text** | `#333333` | 经典黑灰：正文主体字，保证长时间阅读不产生视觉疲劳 |
| **Light Card** | `#F2F2F2` | 极浅灰卡板：用于内容页并列或网格化卡片的边框与填充色 |
| **Background** | `#FFFFFF` | 主页面白色背景：保持留白和版面开阔感 |

---

## III. Signature Design Elements

1. **封面深蓝色带 (Footer Accent Band)**：封面底部占据约 25% 高度的深蓝色巨幅色块，承载方案主线、厂商标志与项目基本属性，赋予极高稳健感。
2. **科技蓝边线 (V-Bar Accent)**：内容页主标题左侧的亮蓝色竖线（8px 宽度），锁定读者的视觉起始线。
3. **圆弧环扣 (Circular Accents)**：在各页面的次要分类或页眉角落装饰精致的白色/蓝色细线圆圈，打破网格排版的生硬感。
4. **水印大字背景 (Huge Backdrop Watermark)**：页面边角放置浅灰色或微透明白色的 “SOLUTION” 等超大水印字，营造精致的排版设计层级。

---

## IV. Page Roster

| 文件名 | 页面类型 | 建议用途 | 核心占位符 (Canonical Placeholders) |
|---|---|---|---|
| `01_cover.svg` | cover | 幻灯片主封面，右侧带工业插图，左侧为主标题块 | `{{TITLE}}`, `{{SUBTITLE}}`, `{{ORGANIZATION}}`, `{{DATE}}` |
| `02_toc.svg` | toc | 目录结构页，分栏双列展示汇报大纲 | `{{TITLE}}`, `{{TOC_ITEMS}}` |
| `03_chapter.svg` | chapter | 章节分隔页，数字重点放大并带分隔标志插图 | `{{CHAPTER_NUM}}`, `{{CHAPTER_TITLE}}`, `{{CHAPTER_SUBTITLE}}` |
| `04a_content_intro.svg` | content | 图文混排页，左文右图，适合介绍现状、背景与大事件 | `{{PAGE_TITLE}}`, `{{SECTION_TITLE}}`, `{{BODY}}`, `{{IMAGE}}` |
| `04b_content_cards.svg` | content | 多列并列卡片页（2-3列），适合列举痛点挑战与解决方案 | `{{PAGE_TITLE}}`, `{{SECTION_TITLE}}`, `{{CARD_TITLE_1}}`, `{{CARD_BODY_1}}` |
| `04c_content_table.svg` | content | 网格/矩阵表格页，展示业务场景需求矩阵与对比 | `{{PAGE_TITLE}}`, `{{SECTION_TITLE}}`, `{{MATRIX_DATA}}` |
| `04d_content_columns.svg` | content | 四列垂直支柱卡片，适合展示平级特征、产品能力体系 | `{{PAGE_TITLE}}`, `{{SECTION_TITLE}}`, `{{COLUMN_TITLE_1}}`, `{{COLUMN_BODY_1}}` |
| `04e_content_grid.svg` | content | 六宫格网格架构，展示分支结构和体系方案细节 | `{{PAGE_TITLE}}`, `{{SECTION_TITLE}}`, `{{GRID_ITEMS}}` |
| `04f_content_timeline.svg` | content | 水平时间轴/技术路线图，展示发展规划或演进路线 | `{{PAGE_TITLE}}`, `{{SECTION_TITLE}}`, `{{TIMELINE_NODES}}` |
| `05_ending.svg` | ending | 总结与问答结束页，居中对称排版，简练有力 | `{{SLOGAN}}`, `{{THANK_YOU}}` |
