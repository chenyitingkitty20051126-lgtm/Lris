# Lris_Data_Classification_and_Visualization

# 🌸 Project 3: 鸢尾花数据分类与可视化 (Iris Data Classification and Visualization)

使用 **Python + scikit-learn + Plotly 交互式可视化** 开发的机器学习分类演示项目。

-----

## 功能 Features

本项目通过四个核心任务，系统地展示了机器学习模型从 2D 到 3D 的决策过程和概率分布。

| 功能模块 | 描述 |
|----------|------|
| **Task 0: 数据探索 (EDA)** | 使用 **Seaborn** 分析特征分布（箱线图），**Plotly** 绘制交互式散点图。 |
| **Task 1: 2D 边界与概率** | 对比多种分类器，绘制 2D 决策边界和**各类别概率热力图**。 |
| **Task 2: 3D 线性超平面** | 在 3D 特征空间中，可视化 LogReg 模型的**线性决策超平面**。 |
| **Task 3: 3D 概率曲面** | 绘制 GPC 非线性**概率曲面**，并将其**完全投影**至 XOY/YOZ/ZOX 边界。 |
| **Task 4: 3D 决策区域** | 利用 **Plotly Volume** 迹线，渲染 GPC 模型在 3D 空间中的**实体决策区域块**。 |
| **技术栈核心 (附加)** | 使用 **Logistic Regression** 和 **Gaussian Process Classifier (GPC)** 进行建模。 |
| **交互性支持 (附加)** | 所有 3D 图表均支持鼠标拖动、旋转和缩放操作。 |

-----

## 程序架构（Illustration 图示）

<img src="illustration/illustration.png" width="550">
Task0:
<img src="result_image/data_preview.png" width="550">
<img src="result_image/classifier2d_initial.png" width="550">
Task1 result:
<img src="result_image/classifier2d.png" width="550">
Task2 result:
<img src="result_image/Figure_3d.png" width="550">
Task3 result:
<img src="result_image/classifier3d_probability.png" width="550">
Task4 result:
<img src="result_image/classifier3d_volume.png" width="550">

## 运行方法（Run）

首先，确保安装了所有必要的依赖库：

```bash
pip install numpy pandas scikit-learn matplotlib seaborn plotly scikit-image
```

运行主程序（例如运行任务四，查看最终 3D 决策区域效果）：

```bash
python classifier3d_volume.py
```
