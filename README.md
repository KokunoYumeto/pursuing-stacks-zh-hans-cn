# 《追寻叠：第一集——模型化的故事》简体中文完整译本

本仓库保存亚历山大·格罗滕迪克《追寻叠：第一集——模型化的故事》的完整、
独立简体中文译本。它不是双语对照本；除公式、稳定标识符、专名、原文引语及
书目条目等必须保持身份的内容外，读者可见的正文和辅助材料均使用简体中文。

## 阅读与下载

- [Zenodo 概念 DOI（始终指向最新版）](https://doi.org/10.5281/zenodo.22870232)
- [GitHub v1.2.0 发行版](https://github.com/KokunoYumeto/pursuing-stacks-zh-hans-cn/releases/tag/v1.2.0)

发行文件按以下顺序排列：

1. `01_pursuing-stacks.zh-Hans-CN.complete.pdf`：440 页完整阅读版 PDF；
2. `02_pursuing-stacks.zh-Hans-CN.complete.cumulative.tex`：可直接下载、阅读和编辑的完整累积 LaTeX；
3. `03_pursuing-stacks.zh-Hans-CN.complete.source.zip`：完整可复现源代码包，含模块化 TeX、书目、图形、字体、构建说明和互斥锁构建脚本；
4. `04_pursuing-stacks.zh-Hans-CN.revision-review.md`：中文修订、原文疑点和复核记录；
5. `05_pursuing-stacks.zh-Hans-CN.translation-choices.jsonl`：中文机器可读翻译选择账本；
6. `06_pursuing-stacks.zh-Hans-CN.SHA256SUMS.txt`：上述五个文件的 SHA-256 校验值。

## 覆盖范围

本版包括书名页和前置材料、誊录者序、作者序言、第一至第一百四十节（含插入的
16bis，共 141 个编号单元）、附录《致 Larry Breen 的三封信》的导言和全部
18 个分节，以及注释、标题、图表文字、目录、参考文献和后置材料。

## v1.2.0 的修订

本版在 v1.1.0 完整译本上继续清理混入正文和辅助材料的英文，并重新核对中文
数学语域。主要改动包括：把范畴论中的 *nerve* 统一为“脉”、把 `Abel 范畴`
等混写统一为“阿贝尔范畴”、把 *sieve/crible* 统一为“筛”、把单纯组合中的
*shuffle* 统一为“重组”，并修正书名、阿里阿德涅隐喻、构建提示和若干法语
表达的中文在先说明。确切出处、被否决的异体和置信理由均见选择账本与修订记录。

## 原文权威与编辑边界

唯一语义权威为 arXiv:2111.01000v2。译本保留数学公式、标签、交叉引用、引文、
页码标记、论断强度和原有顺序。疑似原文问题只记入独立审计记录，不在译文中
悄然改写。原始正文引用了 `SGA3`，但随附的精确原始书目数据库没有相应条目；
本版保留该原始缺项，不虚构书目信息。

这不是 Stacks Project 的官方版本，也不声称获得 Stacks Project 的认可。

## 验证与责任说明

26 个规范源文件的清单、UTF-8/NFC、标签与引用序列、141 个编号单元、模块化与
累积源完整性均已通过确定性检查。两种源各自串行构建出 440 页 A4 PDF；逐页文本
抽取和 90 dpi 全页渲染完全一致。最终阅读版的 440 页已全部渲染并逐页复核，未见
裁切、重叠、意外空白页或缺字方块。全部字体已嵌入；简体中文字体含 ToUnicode。
两份 PDF 的字节因作业名和内部对象布局不同，不声称字节一致。

本译本的翻译与校订由 OpenAI Codex — GPT-5.6 Sol（Ultra 推理强度）完成；
尚未经人类专家审校。

## 其他语言版本

- 日语完整译本：[GitHub](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ja) · [Zenodo 概念 DOI](https://doi.org/10.5281/zenodo.22870234)
- 韩语完整译本：[GitHub](https://github.com/KokunoYumeto/pursuing-stacks-first-episode-ko-kr) · [Zenodo 概念 DOI](https://doi.org/10.5281/zenodo.22870236)

许可：CC0 1.0 Universal；不提供任何担保。
