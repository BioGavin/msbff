# MASS Bioactive Fractions Filtering

## Install

MS-BFF package has been uploaded to PyPI, so you can install it by pip conveniently.

```bash
pip install msbff
```





## Main Function

### Module 1



### Module 2



### Module 3



## Usage







### Example





# Problems

## 参数设置问题

- PCC_threshold 取值范围在[-1,1]，默认值为0，即代表>0，所以大于号是固定吗？
- FDR _threshold (默认<=0.05) 是否有误
- 若RT_range / RT_binning 不等于整数，则舍弃余数部分的RT行？区间都是从0开始吗？
- Signal Intensity Per Block：填入p （变量p：统计特定范围内的Average Mz的平均值）与excel里面说明不一致。
- 原始数据表的表头固定吗？以及生物活性部分数据一定是5列吗？





## 代码完善问题

- 暂未设置阈值取值范围