个人使用，小小小代码量，低低低coding水平

# 2024.03.07更新
对于文件夹内的转录组数据，使用fastp进行质检
质检后进行STAR比对
(需要提前修改文件中的基因组位置信息等内容)

# 2024.01.09更新
简化了一下筛选，直接根据FDR0.05和0.1进行筛选然后输出结果

# 11.21更新
分析筛选rMATS的结果，算是可以用吧，还需要进一步修正

# 下一步计划：

- 针对不同的sample数目可以进行识别和调整
- 补充后续R的代码

# 最终目标

实现fastq到可变剪切可视化的全自动代码流程（或者仅需微调一些参数）
💪
