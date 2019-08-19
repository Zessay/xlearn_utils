# 说明

&emsp;主要**用于生成`xlearn`库中`FM`和`FFM`两种算法需要的格式文件**。主要接口函数和类在`xlearn_utils.py`文件中，`data`中包含了测试数据，`xlearn_test.ipynb`是测试不同情况下的效果。



- `FMFormat`：为生成`FM`所需格式文件准备类，相当于对原始文件进行统计。
- `convert_to_fm`：生成`FM`文件的接口函数。
- `FFMFormat`：为生成`FFM`所需格式文件准备类。
- `convert_to_ffm`：生成`FFM`文件的接口函数。
- `preprocess`：对连续型特征进行归一化处理。
- `cut_bins`：对跨度较大的连续型特征，可以选择分箱处理。

