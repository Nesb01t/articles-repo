---
tag: 'markdown'
date: 2024/7/7
---

# 利用cv找到特征走出固定迷宫

场景：电子游戏中分析怪物的位置 计算怪物出现在某个位置的频率 或是训练ai帮助人物走出特定的迷宫

可以用的模型例如:
1. YOLO 系列
2. Faster R-CNN 精度高，速度慢
3. SSD 速度和精度适中

还有 SORT 算法可以提高追踪效果

## 标注

1. 创建数据集: 收集地标, 比如说是形状, 颜色或者灯光
2. 数据增强: 通过旋转缩放裁剪增强模型
