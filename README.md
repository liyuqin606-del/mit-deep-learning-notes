# 计算机视觉论文阅读：中文学习笔记

根据当前课程材料整理的非官方笔记，目标是掌握阅读 CV 与 3D 视觉论文的基础。包含两份可编辑的 LaTeX 源码和编译好的 PDF。

| 笔记 | PDF | LaTeX |
| --- | --- | --- |
| MIT 6.S191：深度学习入门 | [阅读](main.pdf) | [源码](main.tex) |
| CS231n：CNN、训练、Transformer、检测与分割；CS231A：相机模型 | [阅读](cv_core_notes.pdf) | [源码](cv_core_notes.tex) |

第二份笔记覆盖 CS231n 的 L5、L6、L8、L9 与 CS231A Camera Models；包含卷积尺寸和参数量、注意力维度、视觉任务与指标、投影与相机位姿等算例和练习。指标与 3D 应用有为论文阅读而补充的解释。两份笔记都附有来源和课件页码。

## 编译

使用含 `ctex` 和 Fandol 中文字体的 TeX Live（macOS 上会优先使用系统宋体和黑体）：

```sh
xelatex main.tex
xelatex main.tex
xelatex cv_core_notes.tex
xelatex cv_core_notes.tex
```

也可使用 Tectonic，例如 `tectonic cv_core_notes.tex`。PDF 使用 Tectonic 与 macOS 系统字体生成。

## 来源

- [MIT 6.S191 课程](https://introtodeeplearning.com/) · [Lecture 1](https://introtodeeplearning.com/slides/6S191_MIT_DeepLearning_L1.pdf)
- [Stanford CS231n](https://cs231n.stanford.edu/schedule.html)：[L5](https://cs231n.stanford.edu/slides/2026/lecture_5.pdf)、[L6](https://cs231n.stanford.edu/slides/2026/lecture_6.pdf)、[L8](https://cs231n.stanford.edu/slides/2026/lecture_8.pdf)、[L9](https://cs231n.stanford.edu/slides/2026/lecture_9.pdf)
- [CS231A Camera Models](https://web.stanford.edu/class/cs231a/course_notes/01-camera-models.pdf)

CS231n L5 的官方课件页脚仍为 2025；CS231A 相机讲义未标年份。这里是独立整理和解释，并非官方译本；仓库不包含原始课件。
