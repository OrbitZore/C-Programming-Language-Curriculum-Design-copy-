# C-Programming-Language-Curriculum-Design

湖南科技大学C语言程序设计课程设计实验报告存档。

## 特点

- 利用pandoc软件，使用markdown语言现代化编写实验报告并转换成latex文档，优雅的渲染成pdf。

- 使用`xmake`构建工具

## 目录结构

```
.
├── build					课程设计报告构建位置
│   ├── all.md
│   ├── all.pdf
│   ├── final.pdf			最终生成的报告
│   └── makefile
├── doc						子文档存放
├── header					课程设计报告头信息存放位置
│   ├── header.md
│   ├── header.tex
│   ├── infoheader.docx
│   └── infoheader.pdf
├── img						报告使用的图像
│   ├── info.png
│   ├── r2.png
│   └── r.png
├── LICENSE
├── makefile
├── README.md
└── src						源代码分日期存放位置
    ├── headers				ATL库
    ├── T1					个人信息管理系统
    └── T2					电子印章程序
```
## 构建

本仓库已提供了构建完成后的实验报告`build/final.pdf`，也可用户自行构建。

请提供Linux环境，安装`make`,`pandoc`,`xelatex`,`ctex`软件包，安装Pandoc模板[Eisvogel](https://github.com/Wandmalfarbe/pandoc-latex-template)。

在根目录`make`，最终实验报告`final.pdf`即位于`build/final.pdf`

也可`make clean`清除构建文件