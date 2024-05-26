# VDR

### DownLoad Dataset：
 - https://github.com/QinYi-team/Variance-discrepancy-representation/tree/main/Dataset

### Official Materials
 - TF:  https://github.com/QinYi-team/Variance-discrepancy-representation/tree/main
 - Paper： 
   - [PUBLISHED PAPERS](https://doi.org/10.1016/j.ymssp.2024.111544)   
   

### Cited:
```html
@article{QIAN2024111544,
title = {Variance discrepancy representation: A vibration characteristic-guided distribution alignment metric for fault transfer diagnosis},
journal = {Mechanical Systems and Signal Processing},
volume = {217},
pages = {111544},
year = {2024},
doi = {10.1016/j.ymssp.2024.111544}
}
```
### Usage

建议大家将开源的MMSD域差异度量损失（即插即用）在赵老师的开源的代码中替换掉度量模块。(https://github.com/ZhaoZhibin/UDTL)

替换方式：

```python
from VDRD import VDR
criterion2 = VDR()
loss = criterion2(output1, output2)
```

# Contact

- **Chao He**
- **chaohe#bjtu.edu.cn   (please replace # by @)**
