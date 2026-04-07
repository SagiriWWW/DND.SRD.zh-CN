# D&D 5E SRD 中文本地版

> 说明：本项目是面向个人本地使用的 D&D 5E SRD 中文 Markdown 整理版。
>
> 来源：内容基于 [OldManUmby/DND.SRD.Wiki](https://github.com/OldManUmby/DND.SRD.Wiki) 的 Markdown 版本整理；原始 SRD 5.1 内容来自 Wizards of the Coast LLC，并依据 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode) 发布。
>
> 翻译状态：中文内容主要由机器翻译生成，并经过批量术语统一与格式清理；未经过完整人工逐条校对。用于跑团或引用规则前，建议对照英文 SRD 原文确认。

详细出处与声明见 [NOTICE.md](NOTICE.md) 和 [Legal.md](Legal.md)。

---

![D&D Logo](RE&.logo.png)

---

查看 [更新日志](https://github.com/OldManUmby/DND.SRD.Wiki/blob/master/Changelog.md)

# RE重新组织。RE重新发布。RE重新精制！

### 什么是 D&D 5E SRD REmastered？

这是一个将 D&D 5E SRD 重新格式化为 Markdown（.MD）的改编版本，便于导出到其他出版格式。若材料本身存在任何问题或不一致之处，请进行反馈；详见下方“讨论与问题”。

**系统参考文档（SRD）** 包含依据 [Creative Commons Attribution 4.0 International License](https://creativecommons.org/licenses/by/4.0/legalcode)（“CC-BY-4.0”）发布内容的相关指南。[Dungeon Masters Guild](http://dungeonmastersguild.com/) 也为个人和团体提供自助出版机会。OGL 与 Dungeon Masters Guild 提供的是不同类型的出版途径。若要概览这些方案，请访问官方的 [Wizards SRD 页面](http://dnd.wizards.com/articles/features/systems-reference-document-srd) 进行比较。

本文档中的内容已逐行重新精制为 Markdown 格式，以便你用于自己的 5E 项目。我花费了大量心力将原始 Wizard's SRD v5.1 PDF 转换为 Markdown，并纳入 _2018 年 11 月更新_中的全部勘误。更多信息请访问 [SRD Wiki](https://srd.wiki)。

<details>
 <summary>为什么使用 Markdown 格式？</summary>

Markdown 是由 [John Gruber](https://daringfireball.net) 创建的一种轻量级标记语言，采用纯文本格式语法。正因为它本质上是纯文本文件，所以能在保留基础文本与表格格式能力的同时，为一组文档提供更好的长期可用性。此外，Markdown 可以借助多种 Markdown 编辑器导出为 HTML 及许多其他格式。Markdown 常用于格式化 readme 文件、撰写书籍、博客和消息，或仅仅是在 Markdown 编辑器中用纯文本创建富文本内容。

</details>

<details>
 <summary>导出选项</summary>

我推荐使用以下 Markdown 应用来编辑这些内容：

* [Typora](https://typora.io): $15（一次付费）
* [Visual Studio Code](https://code.visualstudio.com/Download): 免费

若要将 Markdown 导出为多种出版格式，我推荐使用上面列出的 Typora，因为它提供了许多优秀的导出选项，足以满足大多数用户需求。大多数优秀的 Markdown 编辑器都能提供基础导出功能。不过，如果你需要更多选项，[PanWriter](https://panwriter.com) 是更好的方案。要让 PanWriter 正常工作并最大化导出选项，还需要安装以下应用：

* [下载 PanDoc](https://github.com/jgm/pandoc/releases/download/2.19.2/pandoc-2.19.2-macOS.pkg)

或者，你也可以通过 Homebrew 安装 pandoc：

`brew install pandoc`

Homebrew 还可以安装其他与 Pandoc 集成的软件。例如，安装 librsvg（其 `rsvg-convert` 可处理不支持 SVG 的格式）、Python（用于 Pandoc 过滤器）以及 BasicTeX（用 LaTeX 排版 PDF）：

`brew install librsvg python homebrew/cask/basictex`

注意：在不受支持的 macOS 版本上（落后超过三个大版本），Homebrew 会从源码安装，这会额外消耗时间和磁盘空间来构建 ghc 编译器及其依赖的 Haskell 库。

对于不想使用安装器的用户，也提供一个包含二进制文件和 man 手册页的 zip 文件。只需解压后将二进制文件和 man 手册页移动到你喜欢的目录即可。

默认情况下，Pandoc 使用 LaTeX 生成 PDF。由于完整的 MacTeX 安装会占用约四 GB 磁盘空间，我们推荐使用 BasicTeX 或 TinyTeX，并在需要时通过 `tlmgr` 工具安装额外包。如果你收到找不到字体的错误警告：

`tlmgr install collection-fontsrecommended`

</details>

<details>
 <summary>对 Obsidian 友好</summary>

这个 D&D 5E SRD 改编版本包含了专为 Obsidian 这类 PKM 应用设计的可选内容。[Obsidian.md](https://obsidian.md) 是一个建立在本地纯文本 Markdown 文件夹之上的强大知识库工具。这个定义听起来很简单，但 Obsidian 远不止如此。想进一步了解如何将 Obsidian 用于你的桌面角色扮演战役管理，请访问 [Josh Plunket 的 YouTube 频道](https://www.youtube.com/c/JoshPlunkett/videos)。

</details>

<details>
 <summary>讨论与问题</summary>

欢迎访问我们的 [discussion](https://github.com/OldManUmby/DND.SRD.Wiki/discussions) 论坛，交流有关 D&D SRD 出版方面的想法。如果你发现任何问题，请通过 GitHub 提交 [issues](https://github.com/OldManUmby/DND.SRD.Wiki/issues) 进行 **REport**。或者，你也可以通过 GitHub [pull request](https://github.com/OldManUmby/DND.SRD.Wiki/pulls) 来 **REfork & REuse** 本项目。

</details>

<details>
 <summary>获取下载内容</summary>

* 下载最新的 [Release](https://github.com/OldManUmby/DND.SRD.Wiki/releases)。
* 下载 Wizards 官方的 [PDF 格式 SRD v5.1](https://www.dndbeyond.com/attachments/39j2li89/SRD5.1-CCBY4.0_License_live%20links.pdf)。
* 下载 Wizards 官方的 [Errata and Basic Rules](http://dnd.wizards.com/articles/features/basicrules)。
* 下载 Wizards 官方的 [Characters Sheets](http://dnd.wizards.com/articles/features/character_sheets)。

</details>

---

© 2015 Wizards. All Rights Reserved. Dungeons & Dragons® 是 Wizards of the Coast 的商标。有关 Wizards of the Coast 及其商标或其他知识产权的更多信息，请访问其网站 [www.wizards.com](http://www.wizards.com)。

网站、Markdown 转换与扩展格式由 [Old Man Umby](http://www.oldmanumby.com) 制作。经许可，本网站使用了来自 [Wizard's Fan Site Kit](http://dnd.wizards.com/articles/features/fan-site-kit) 的官方素材与图像。Wizards of the Coast、Dungeons & Dragons 及其标志是 Wizards of the Coast LLC 在美国及其他国家的商标。
