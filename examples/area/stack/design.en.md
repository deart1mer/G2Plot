---
title: 设计规范
---

## 何时使用

面积图可用来展示连续性数据，可很好地表示趋势、累积、减少以及变化。
堆叠面积图更擅于展示部分和整体之间的关系或趋势，而不是传达特定的值。

## 数据类型

| 图表类型 | 面积图 |
| --- | --- |
| 适合的数据 | 两个连续字段数据 |
| 功能 | 观察数据变化`趋势` |
| 数据与图形的映射 | 两个连续字段分别映射到横轴和纵轴 |
| 适合的数据条数 | 大于两条 |

## 用法建议

<img src="https://gw.alipayobjects.com/mdn/rms_d314dd/afts/img/A*BKTZSZq9p0gAAAAAAAAAAABkARQnAQ" width="600">

## 元素

<img src="https://gw.alipayobjects.com/mdn/rms_d314dd/afts/img/A*ENU-Q78K3w8AAAAAAAAAAABkARQnAQ" width="600">

* X 轴：通常对应连续数据，值为时间，调用连续数据 X 轴。
* Y 轴：通常对应连续数据，值为数字，调用连续数据 Y 轴。
* 图例：通常出现在多条折线图中，用来区分不同折线代表的数据含义。
* 标签：用来解释数据点的值。
* 辅助元素：用来解释某个特殊的数据点的值，或标记出某个特殊含义的区域。