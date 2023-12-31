# Markdown 入门基础

本文来自[https://markdown.com.cn/](https://markdown.com.cn/). (更多内容请看这里)

## 什么是Mrakdown？

**Markdown** 是一种轻量级的标记语言，可用于在纯文本文档中添加格式化元素。Markdown 由 John Gruber 于 2004 年创建，如今已成为世界上最受欢迎的标记语言之一。

1. 专注于文字内容；
2. 纯文本，易读易写，可以方便地纳入版本控制；
3. 语法简单，没有什么学习成本，能轻松在码字的同时做出美观大方的排版。

使用 Markdown 与使用 Word 类编辑器不同。在 Word 之类的应用程序中，单击按钮以设置单词和短语的格式，并且，更改立即可见。而 Markdown 与此不同，当你创建 Markdown 格式的文件时，可以在文本中添加 Markdown 语法，以指示哪些单词和短语看起来应该有所不同。

## 为什么要使用 Markdown？

当你可以通过按下界面中的按钮来设置文本格式时，为什么还要使用 Markdown 来书写呢？使用 Markdown 而不是 word 类编辑器的原因有：

* Markdown 无处不在。StackOverflow、CSDN、掘金、简书、GitBook、有道云笔记、V2EX、光谷社区等。主流的代码托管平台，如 GitHub、GitLab、BitBucket、Coding、Gitee 等等，都支持 Markdown 语法，很多开源项目的 README、开发文档、帮助文档、Wiki 等都用 Markdown 写作。
* Markdown 是纯文本可移植的。几乎可以使用任何应用程序打开包含 Markdown 格式的文本文件。如果你不喜欢当前使用的 Markdown 应用程序了，则可以将 Markdown 文件导入另一个 Markdown 应用程序中。这与 Microsoft Word 等文字处理应用程序形成了鲜明的对比，Microsoft Word 将你的内容锁定在专有文件格式中。
* Markdown 是独立于平台的。你可以在运行任何操作系统的任何设备上创建 Markdown 格式的文本。
* Markdown 能适应未来的变化。即使你正在使用的应用程序将来会在某个时候不能使用了，你仍然可以使用文本编辑器读取 Markdown 格式的文本。当涉及需要无限期保存的书籍、大学论文和其他里程碑式的文件时，这是一个重要的考虑因素。

## 工欲善其事，必先利其器

Markdown 入门的最佳方式就是多使用它。由于有大量免费[工具](https://markdown.com.cn/tools.html)的存在，上手 Markdown 是很方便的。比较遗憾的一点是各平台可能采用不同语言实现的 Markdown 解析引擎，或采用同一解析引擎的不同版本，而且可能有不同程度的定制与扩展，这导致在不同平台上使用 Markdown 写作时体验并不完全一致。不过幸好对于大家公认的一些标准语法，各家都是支持的。

你甚至都不需要下载任何程序，就可以使用[在线 Markdown 编辑器](https://markdown.com.cn/editor/) 来编写 Markdown。进入其站点就可以开始在左侧窗格中书写了。渲染后的文档在右侧窗格预览。

阅读本指南时，你可以打开 [在线 Markdown 编辑器](https://markdown.com.cn/editor/) 。这样，你就可以一边学习 Markdown 语法一边练习了。熟悉 Markdown 之后，再选择一个顺手的 Markdown 的应用程序。

## Markdown 的工作原理

在使用 Markdown 格式书写时，文本内容存储在带有 `.md` 或 `.markdown` 扩展名的纯文本文件中。那然后呢？你的 Markdown 格式的文件如何转换为 HTML 或可打印的文档呢？

简单来说，你需要一个能够处理 Markdown 文件的  *Markdown 应用程序* 。有许多应用程序可供选择，从简单的脚本到类似于 Microsoft Word 的桌面应用程序。尽管它们在视觉上有所不同，但所有应用程序都执行相同的操作。像 [在线 Markdown 编辑器](https://markdown.com.cn/editor/) 一样，它们都是将 Markdown 格式的文本转换为 HTML，以便可以在 Web 浏览器中显示。

Markdown 应用程序使用一种称为  *Markdown 处理器* （也通常称为“解析器”或“实现”）的东西将获取到的 Markdown 格式的文本输出为 HTML 格式。此时，可以在 Web 浏览器中查看你的文档，或者将其与样式表组合并打印。

**注意：** Markdown 应用程序和处理器是两个单独的组件。为了简洁起见，在下图中，我将它们组合为一个元素（即 “Markdown应用程序”）。

总而言之，这是一个四步的过程：

1. 使用文本编辑器或 Markdown 专用的应用程序创建 Markdown 文件。该文件应带有 `.md` 或 `.markdown` 扩展名。
2. 在 Markdown 应用程序中打开 Markdown 文件。
3. 使用 Markdown 应用程序将 Markdown 文件转换为 HTML 文档。
4. 在 web 浏览器中查看 HTML 文件，或使用 Markdown 应用程序将其转换为其他文件格式，例如 PDF。

从你的角度来看，该过程将根据你使用的应用程序的不同而有所不同。例如，[在线 Markdown 编辑器](https://markdown.com.cn/editor/) 本质上将第 1-3 步组合到一个单一、无缝的界面中，你要做的就是在左窗格中键入内容，然后转换结果就在右窗格中就神奇地出现了。但是，如果你使用的是其他工具（例如带有静态网站生成器的文本编辑器），则会发现该过程更为明显。

## Markdown 有什么用？

Markdown 是做笔记、为网站创建内容以及生成可打印文档的快速、简便的方法。

学习 Markdown 语法并不需要很长时间，一旦你知道如何使用它，你就可以在几乎所有地方使用 Markdown 进行书写了。大多数人使用 Markdown 来为网站创建内容，但是 Markdown 也可以很好地格式化从电子邮件到购物清单的所有内容。

下面是一些你可以使用 Markdown 的场景。

### 网站

Markdown 是为 web 而设计的，因此，市面上有很多专门用于创建网站内容的应用程序就不足为奇了。

如果您熟悉 HTML、CSS和版本管理工具，请试试 [Jekyll]，这是一个广受欢迎的静态网站生成器，它能将 Markdown 文件并构建为 HTML 网站。这种方法的优势之一是 [GitHub Pages] 为 Jekyll 生成的网站提供免费托管服务。如果 Jekyll 不是你的理想之选。

如果你是 WordPress 博主，你可以使用 [Jetpack 插件](https://jetpack.com/support/markdown/)实现对 Markdown 的支持。

### 文件资料

Markdown 并不具备像 Microsoft Word 这样的文字处理程序的所有功能，但是对于创建基本文件（例如作业和信件）来说已经足够了。你可以使用 Markdown 文档创作工具来创建 Markdown 格式的文档并将其导出为 PDF 或 HTML 格式。PDF 格式是关键，因为一旦有了 PDF 文档，您就可以使用它进行任何操作：打印、通过电子邮件发送或将其上传到网站。

这是我推荐的一些Markdown文档创作工具：

* 现代编辑器
  VSCode / Atom
* 传统编辑器
  Vim / Emacs / Sublime Text / Notepad++
* IDE 自带编辑器
  IntelliJ IDEA / Android Studio / WebStorm
* 专用编辑器
  Ulysses / Mou / Typora / Markpad
* 在线编辑器
  各种支持 Markdown 的网站都提供了[在线 Markdown 编辑器](https://markdown.com.cn/editor/)

### 笔记

在几乎所有方面，Markdown 都是记笔记的理想语法。不幸的是，两个最受欢迎的笔记应用程序 [Evernote](https://evernote.com/) 和 [OneNote](https://www.onenote.com/) 目前都不支持 Markdown。好消息是，其他一些笔记应用程序 *是* 支持 Markdown 的：

* [Simplenote] 是适用于所有平台的免费、简单的笔记应用程序。
* [Notable] 是可以在各种平台上运行的笔记应用程序。
* [Bear] 是适用于 Mac 和 iOS 设备的类似 Evernote 的应用程序。默认情况下，它并不专门针对 Markdown 的，但是你可以启用 Markdown 兼容模式。
* [Boostnote] 自称是“专为程序员设计的开源笔记应用程序”。

如果你无法放弃 Evernote，可以试试 [Marxico](https://marxi.co/)，一个专门针对 Evernote 的基于订阅付费的 Markdown编辑器，或在 Evernote 网站上使用 [Markdown Here] 插件。

### 书籍

想要自行出版小说？请试试 [Leanpub](https://leanpub.com/)，该服务可将你的 Markdown 格式的文件转换为电子书。Leanpub 以 PDF、EPUB 和 MOBI 文件格式输出你的图书。如果你要创建纸版书籍，可以将 PDF 文件上传到类似 [Kindle Direct Publishing](https://kdp.amazon.com/) 之类的服务提供商处。要了解有关使用 Markdown 编写和自行出版书籍的更多信息，请阅读 [此博文](https://medium.com/techspiration-ideas-making-it-happen/how-i-wrote-and-published-my-novel-using-only-open-source-tools-5cdfbd7c00ca)。

### 演示文稿

信不信由你，你可以将 Markdown 格式的文件转换成演示文稿。在 Markdown 中创建演示文稿需要一点时间来适应，但是一旦你掌握了它，你就能体会到比使用 PowerPoint 或 Keynote 之类的应用程序更快、更容易。[Remark](https://remarkjs.com/)（[GitHub 仓库](https://github.com/gnab/remark)）和 [Cleaver](https://jdan.github.io/cleaver/)（[GitHub 仓库](https://github.com/jdan/cleaver)）一样，是一种基于浏览器的、流行的 Markdown 幻灯片工具。如果你使用的是 Mac，并且希望安装一个应用程序来使用的话，请试试 [Deckset](https://www.decksetapp.com/) 或 [Marked](https://marked2app.com/)。

### 邮件

如果你需要发送大量电子邮件，并且对大多数电子邮件提供商网站上可用的格式设置控件感到厌倦，那么你将很高兴地发现有一种使用 Markdown 编写电子邮件的简便方法：[Markdown Here] 是一个免费、开源的浏览器扩展程序，可将 Markdown 格式的文本转换为可用于发送的 HTML。

### 文档

Markdown 非常适合技术文档。像 GitHub 这样的公司越来越多地转向使用 Markdown 来创建其文档了，请查看此 [博文](https://github.com/blog/1939-how-github-uses-github-to-document-github) 以了解如何将 Markdown 格式的文档迁移到 [Jekyll]。如果你是为产品或服务编写文档，请试试以下的便捷工具：

* [Read the Docs](https://readthedocs.org/) 可以将你所开源的 Markdown 文件生成文档网站。只需将你的 GitHub 仓库连接到他们的服务，然后你就可以将内容推送到该仓库中，Read the Docs 会完成其余的工作。他们还为 [商业实体提供服务](https://readthedocs.com/)。
* [MkDocs] 是一个快速、简单的静态站点生成器，专门用于构建项目文档。文档源文件使用 Markdown 编写，并使用一个 YAML 配置文件进行配置。MkDocs 有多个 [内置主题](https://www.mkdocs.org/user-guide/styling-your-docs/)，包括移植自 [Read the Docs](https://readthedocs.org/) 的文档主题。最新的一个主题是 [MkDocs Material](https://squidfunk.github.io/mkdocs-material/)。
* [Docusaurus] 是一个静态网站生成器，专门用于创建文档网站。它支持翻译、搜索和版本控制。
* [VuePress](https://vuepress.vuejs.org/) 是基于 [Vue](https://vuejs.org/) 构建的静态站点生成器，并针对编写技术文档进行了优化。
* [Jekyll] 前面已经提到过它了，但它也是将 Markdown 文件生成文档网站的一个不错的选择。如果你选择 Jekyll，请务必试试 [Jekyll 文档主题](https://idratherbewriting.com/documentation-theme-jekyll/)。
