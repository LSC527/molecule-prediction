# 智源小分子化合物性质预测挑战赛
https://www.biendata.com/competition/molecule/

# preprocess.ipynb:  
删除train表和test表中无用的一值特征，将label加入train表，然后使用reduce_mem_usage函数降低表格内存消耗，最后将表格保存为feather格式进一步加快读取速度（也可以继续使用csv格式）。
