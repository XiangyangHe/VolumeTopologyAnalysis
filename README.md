# VolumeTopologyAnalysis

## 1. 利用ttk生成体数据对应的轮廓树(contour_tree_extraction.py)

    -- 输入：体数据， persistence参数
    -- 输出：体数据对应的obj
    需要利用ttk工具包的pvpython.exe编译运行，计算量大，比较耗内存

调用命令如下:
```python
pvpython contour_tree_extraction.py --configure_file ../configure/topology_analysis_combustion_chi_uint8_p_0.01.json
```

 -----------
 2. 将obj转为networkx图文件。
    