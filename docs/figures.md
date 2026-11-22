# 主要图件

[返回项目首页](../README.md)

## BDT 分类诊断

- [训练与测试样本的 BDT 分数对照](../figures/bdt-train-test.png)展示信号与背景分数的分布，以及不同数据划分的差异。
- [ROC 图](../figures/bdt-roc.png)的横轴为信号保留比例，纵轴为背景排斥比例。

## BDT 与 PID 阈值扫描

- [BDT 分数阈值对质子 PID](../figures/fom-bdt-proton-pid.png)
- [两组强子 PID 阈值](../figures/fom-hadron-pid.png)

这两张图是同一组四维扫描的二维切片，每张图固定另外两个阈值。

## 质量谱拟合

| 模型 | 质量谱 | pull |
| --- | --- | --- |
| 基准三分量模型 | [查看质量谱](../figures/data-fit-baseline.pdf) | [查看残差](../figures/data-pull-baseline.pdf) |
| 扩展背景模型 | [查看质量谱](../figures/data-fit-expanded.pdf) | [查看残差](../figures/data-pull-expanded.pdf) |

每行使用归档中同一模型输出的一组图。pull 按绘图数据误差对残差归一化，用于检查哪些质量区间持续偏离拟合。
