## 图片目录说明

用于存放键位图、分层说明与示意截图。建议使用中文文件名标签，便于国内用户快速理解与检索。

### 命名建议

- `整体布局预览.png`
- `层1_基础输入.png`、`层2_导航与编辑.png`、`层3_媒体控制.png`
- `蓝牙配对步骤.png`、`固件升级流程.png`

### 中文显示（matplotlib/seaborn）

若使用 Python 生成图片，请设置中文字体，避免中文显示为方块：

```python
import matplotlib.pyplot as plt
import seaborn as sns
plt.rcParams['font.sans-serif'] = ['SimHei', 'Noto Sans CJK SC', 'Arial Unicode MS']
plt.rcParams['axes.unicode_minus'] = False
# 在此处绘图...
plt.savefig('层1_基础输入.png', dpi=200, bbox_inches='tight')
```

参考链接：
- `https://woodskb.com/config/#/WOODS40_BASE/LAYOUT_45`
- `https://woodskb.com/wiki/`


