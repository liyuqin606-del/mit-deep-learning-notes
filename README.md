# 深度学习入门：面向论文阅读的中文笔记

根据 MIT 6.S191 2026 Lecture 1 整理的非官方学习笔记，覆盖神经元、激活函数、损失、梯度下降、反向传播、批次与泛化，并包含算例与自测答案。

- [阅读 PDF](main.pdf)
- [LaTeX 源码](main.tex)
- [MIT 6.S191 官方课程](https://introtodeeplearning.com/)
- [Lecture 1 官方课件](https://introtodeeplearning.com/slides/6S191_MIT_DeepLearning_L1.pdf)

## 编译

使用含 `ctex` 和 Fandol 中文字体的 TeX Live（macOS 上会优先使用系统宋体和黑体）：

```sh
xelatex main.tex
xelatex main.tex
```

也可使用 Tectonic 编译：`tectonic main.tex`。本次 PDF 使用 Tectonic 与 macOS 系统字体生成。

本笔记是独立整理和解释，并非 MIT 官方材料或逐页翻译；不包含原始课件。
