# Andrew Ng 机器学习课程代码与笔记

这个仓库整理 Andrew Ng 经典机器学习课程的练习代码、Notebook、原始课程材料和个人笔记。内容按“先读笔记，再运行 Notebook，最后回查原始作业”的顺序组织。

## 快速入口

- [完整课程笔记](docs/course-notes.md)
- [原始 PDF 转写笔记](docs/source-notes/original-machine-learning-notes.md)
- [个人练习 Notebook](notebooks/)
- [课程原始代码与数据归档](archive/original-course-materials/)
- [章节作业 PDF](references/assignment-pdfs/)
- [博客版笔记](https://wangyujie.space/ML-DL-Course-Notes/)

## 目录结构

```text
.
├─ notebooks/                    # 按章节整理的个人 Jupyter Notebook
├─ docs/                         # 完整笔记与原始转写材料
├─ archive/original-course-materials/
│  ├─ coursera_ml_ipynb/         # Python Notebook 版本及配套数据
│  └─ machine-learning-ex*/      # Octave/MATLAB 原始练习
└─ references/                   # 章节 PDF 与历史参考资料
```

`archive/` 保留课程资料的原始目录关系，便于旧代码继续使用相对路径。新的学习记录优先放入 `notebooks/` 和 `docs/`。

## 环境

推荐使用 Python 3.10 或更新版本创建独立环境：

```powershell
python -m venv .venv
.\.venv\Scripts\Activate.ps1
python -m pip install -r requirements.txt
jupyter lab
```

部分早期 Notebook 使用旧版库或固定相对路径。运行时请从 Notebook 所在目录启动，并按实际数据位置调整路径。

## 学习顺序

| 阶段 | 主题 |
|---|---|
| 1 | 线性回归、梯度下降、特征缩放 |
| 2 | 逻辑回归、正则化、多分类 |
| 3 | 神经网络、反向传播、梯度检验 |
| 4 | 偏差与方差、学习曲线、误差分析 |
| 5 | SVM、聚类、PCA、异常检测 |
| 6 | 推荐系统与大规模机器学习 |

## 资料说明

仓库包含个人练习以及历史课程材料。引用、转载或再发布课程原文、题目与 PDF 前，请确认其原始许可；新增内容应注明来源。大型数据集和模型文件不应继续直接提交到 Git。
