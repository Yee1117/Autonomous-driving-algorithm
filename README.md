# 自动驾驶算法

## 坐标系变换算法

[](。。、)src/utilities/coordinate_transformation.py


```
    二维坐标系变换，平移+旋转 \n
    :param raw_matrix: 原始坐标矩阵
    :param rotation: 旋转角
    :param translation_x: x方向平移
    :param translation_y: y方向平移
    :return: 变换后的坐标
```

## 局部路径规划算法

[](。。、)src/LocalPathPlanning/FSAE_PathPlanning/FSAE_local_path_planning.py


```
    :param traffic_cone_l: 左侧锥桶坐标
    :param traffic_cone_r: 右侧锥桶坐标
    :param interpolation_num: 贝塞尔曲线插值点的数量（用于平滑曲线）
    :param translation_dis: 只有单侧锥桶时，向内平移的距离，[m]
    :return: 期望路径
```
