# OptiQubo UI Design

本仓库保存 OptiQubo 上位机的界面预览图与交互设计文档。

## 页面索引

- [全局界面与导航规范](./00_全局界面与导航规范.md)
- [首页](./home/01_首页界面设计.md)
- [QUBO 求解](./qubo/02_QUBO求解界面设计.md)
- [经典求解](./clssic/01_OptiQubo_经典求解界面设计.md)
- [结果分析：光学结果](./analyse/02_OptiQubo_结果分析_光学结果.md)
- [结果分析：经典结果](./analyse/03_OptiQubo_结果分析_经典结果.md)
- [结果分析：对比模式](./analyse/04_OptiQubo_结果分析_对比模式.md)
- [设置容器与二级导航](./setting/04_设置容器与二级导航.md)
- [设置：标定](./setting/car/05_设置_标定界面设计.md)
- [设置：对齐](./setting/align/07_设置_对齐界面设计.md)

对齐页面预览图：`setting/align/align.svg`
- [设置：设备与系统](./setting/dev/06_设置_设备与系统界面设计.md)

## 当前结果分析预览图

- 光学结果：`analyse/optic-two-row.svg`
- 经典结果：`analyse/computer-two-row.svg`
- 对比模式：`analyse/conmtrast.png`

非对比模式的 Sigma 向量预览统一为两行，每行 20 个元素，共预览前 40 个元素。

## 统一约束

- 一级菜单：首页、QUBO 求解、经典求解、结果分析、设置。
- 标定、对齐与设备与系统均归入“设置”。
- Sigma 始终是一维向量。
- 结果分析不显示“是否达到最优解”。
- 经典求解运行完成前只显示“当前最优能量”。
- USB 原始帧以固件协议 `FD ... FE` 为准。
