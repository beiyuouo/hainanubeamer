<!-- Author : Bingjie Yan -->
<!-- Program Email: bj.yan.pa@qq.com -->

# hainanubeamer: A Beamer Theme for Hainan University (HaiNanU)

# hainanubeamer：海南大学 Beamer 模板

![CTAN Version](https://img.shields.io/ctan/v/hainanubeamer.svg)
![GitHub Version](https://img.shields.io/github/release/beiyuouo/hainanubeamer.svg)
![Repo Size](https://img.shields.io/github/repo-size/beiyuouo/hainanubeamer.svg)
![License](https://img.shields.io/ctan/l/hainanubeamer.svg)

[GitHub](https://github.com/beiyuouo/hainanubeamer) | [Download](https://github.com/beiyuouo/hainanubeamer/releases) | [Wiki](https://github.com/beiyuouo/hainanubeamer/wiki) | [CTAN](https://www.ctan.org/pkg/hainanubeamer)

# Introduction to hainanubeamer

![](https://raw.githubusercontent.com/beiyuouo/hainanubeamer/main/img/overview.jpg)

**hainanubeamer** is a **beamer theme** designed for Hainan University (HaiNanU). Current version is 0.0.1, updated on 2021/11/18.

```latex
  |- figures
    |- hainanulogo.pdf
  |- macros.tex
  |- main-en.tex
  |- main-en.pdf
  |- main.tex
  |- main.pdf
  |- makebeamer-en.bat
  |- makebeamer.bat
  |- makeclean.bat
  |- makecleanall.bat
  |- makedoc.bat
  |- Makefile
  |- README.md
  |- reference.bib
  |- hainanu-beamer.bst
  |- hainanu-beamer.dtx
  |- hainanu-beamer.pdf
  |- beamercolorthemehainanubeamer.sty
  |- beamerinnerthemehainanubeamer.sty
  |- beamerouterthemehainanubeamer.sty
  |- beamerthemeshainanubeamer.sty
  |- dtx-styles.sty
```

# hainanubeamer 简介

hainanubeamer 是海南大学风格 Beamer 模板，当前版本0.0.1，更新于2021年11月18日。

# Documentation

Download and unzip the template. Specific usage documentation and examples can be found in the files below:

* Template usage (hainanubeamer.pdf, in Chinese)
* Template example (main.pdf, in Chinese)
* Brief Introduction (README.md, both in Chinese and English)

# 说明文档

下载并解压本模板，文件夹中包含以下说明文档：

* 模板开发文档（hainanubeamer.pdf，中文版）
* 模板撰写示例（main.pdf，中文版）
* 模板简介（README.md，中英双语）

# Downloads

* Published version: [CTAN](https://www.ctan.org/pkg/hainanubeamer)
* Developer version: [GitHub](https://github.com/beiyuouo/hainanubeamer)

# 下载

* 发布版本：[CTAN](https://www.ctan.org/pkg/hainanubeamer)
* 开发版本：[GitHub](https://github.com/beiyuouo/hainanubeamer)

# Reporting Issues

Please follow the procedure below:

* [GitHub Issues](https://github.com/beiyuouo/hainanubeamer/issues)
* [Email](mailto:bj.yan.pa@qq.com)

# 模板问题反馈

请按照以下顺序反馈问题：

* [GitHub 问题反馈](https://github.com/beiyuouo/hainanubeamer/issues)
* [邮件](mailto:bj.yan.pa@qq.com)

# Makefile Usage

To use Makefile, you should have GNU `make` tool installed.

```bash
make doc       # compile documentation (required before compiling the beamer)
make beamer    # compile beamer
make beamer-en # compile beamer prepared in English
make clean     # clean auxiliary files
make cleanall  # clean auxiliary files and style files
```

# 使用 Makefile

使用Makefile之前请确保已安装GNU `make`工具。

```bash
make doc       # 编译说明文档（在编译 beamer之前必须编译说明文档）
make beamer    # 编译 beamer
make beamer-en # 编译英文 beamer
make clean     # 清除辅助文件
make cleanall  # 清除辅助文件与样式文件
```

# batch Usage

`makedoc.bat`, `makebeamer.bat`, `makeclean.bat` and `makecleanall` are designed for windows platform. Double click these files, then they will echo corresponding functions automatically.

```bash
makedoc       # compile documentation (required before compiling the beamer)
makebeamer    # compile beamer
makebeamer-en # compile beamer prepared in English
makeclean     # clean auxiliary files
makecleanall  # clean auxiliary files and style files
```

# 使用编译脚本

`makedoc.bat`、`makebeamer.bat`、`makeclean.bat`与`makecleanall`为windows编译脚本，双击即可执行相应的功能。

```bash
makedoc       # 编译说明文档（在编译 beamer之前必须编译说明文档）
makebeamer    # 编译 beamer
makebeamer-en # 编译英文 beamer
makeclean     # 清除辅助文件
makecleanall  # 清除辅助文件与样式文件
```

# License

This material is subject to the [LATEX Project Public License 1.3c](https://ctan.org/license/lppl1.3) or any later version.

# 协议

本模板的发布遵照 [LATEX Project Public License 1.3c](https://ctan.org/license/lppl1.3) 协议或其后版本。

# Acknowledgements（致谢）

* [XDUstyle](https://github.com/StickCui/XDUstyle-Beamer-Theme)
* [thubeamer](https://github.com/tl3shi/thubeamer)
* [thubeamer](https://github.com/YangLaTeX/thubeamer)