# 版权声明与生成责任 / Copyright & Generation Responsibility

## 成果属性

本投稿包（`submissions/cxgreat2014/jingzhang-ai-meridian/`）为 AI 智能体生成的**开源共创概念方案**，提交账号为 GitHub 用户 `cxgreat2014`。全部空间落地建议均为“概念建议 / 参考方案 / 可供专业团队深化研究”，不替代正式规划，不构成政府审定结论、投资承诺或工程可行性结论。本方案不代表任何官方立场。

## 生成方式披露

- **生成主体**：Anthropic Claude（Fable 5，`claude-fable-5[1m]`），经 Claude Code CLI 运行。
- **生成流程**：并行网络调研（WebSearch/WebFetch，来源全部登记于 `sources.json`）→ 程序化几何引擎（Python + shapely + pyproj，EPSG:4548 复算）→ 指标与图件派生（matplotlib）→ 四门自检（scripts/self_check_submission.py）修复循环。
- **图件与图纸**：`assets/figures/*.png`、`drawings/*.pdf`、`visual/index.html` 均由本包 GeoJSON 与 metrics 程序化绘制，为数据驱动的概念示意图，不是现场照片、实测图或官方规划图。
- **字体**：图件与 PDF 使用本机已安装的开源字体（思源系列 / 国标系列），遵循其开源许可证（SIL OFL 等）。
- **未使用素材**：未使用新闻图片、商业地图截图、未授权字体/商标/人物肖像、非公开规划图件、个人隐私数据。智能体未冒称官方批准。

## 外部资料与引用责任

- 外部事实（遗产史实、公园建设进展、产业数据、全球案例）均来自公开来源，逐条登记于 `sources.json`（发布者、URL、获取日期、用途边界）。
- 存在口径差异的公开事实（遗址公园总面积两口径、“学北园/众智园”名称差异、京张里程原点两说）在 `assumptions.json`（A-EXTDATA-001）登记，正文按口径标注年份表述。
- 参考资料的著作权归原发布者所有；本包以引用与分析为目的使用其公开事实与观点，未复制其版式、图片或长篇原文。

## 授权与展示

- 本包 `license: COMMUNITY-DISPLAY-ONLY`：授权征集方在征集、评审、公示与成果展示场景中使用本方案内容；任何正式采纳须另行约定。
- 方案中所有命名（零公里 KM0、智能公里桩、时间桩等）为概念品牌建议，未经商标注册核查程序确认可用性；Logo 仅为方向描述，未产出受保护的最终商标图样。

## 责任声明

AI 生成内容可能存在错误。作者（提交账号持有人）对事实引用、版权边界与最终表达负责；评审者与后续使用方应以 `sources.json` 登记的原始来源与官方文件为准进行复核。
