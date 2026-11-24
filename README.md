# MatPlot · 材料绘图台

当前稳定版：[v1.0.0](./archive/matplot-v1.0.0.html)。

[在线使用](https://lin-yueyang.github.io/MatPlot/) · [更新记录](./更新.md) · [历史版本](./archive/)

在浏览器中读取本地计算文件、调整图形并导出 PNG、SVG 或 CSV。可打开多个绘图标签，分别编辑不同体系。

| 工具 | 功能 |
| --- | --- |
| [台阶图](https://lin-yueyang.github.io/MatPlot/#steps) | 输入 E、Gcorr 与小分子参考项，比较多体系、分支和过渡态，保存可编辑的 JSON 工程。 |
| [Slow Growth](https://lin-yueyang.github.io/MatPlot/#barrier) | 读取 VASP REPORT，拼接分段并积分，显示自由能、导数和最高点。 |
| [COHP](https://lin-yueyang.github.io/MatPlot/#cohp) | 读取 LOBSTER 输出，比较不同键的 COHP、ICOHP 和自旋分量。 |
| [DOS](https://lin-yueyang.github.io/MatPlot/#dos) | 读取 DOSCAR 或投影表格，按元素、轨道和自旋绘制态密度。 |

离线使用可下载根目录的 `index.html`，用 Chrome 或 Edge 打开，点击工具卡片开始绘图。

## 输入示例

体系的 E、Gcorr 表格（eV）：

![体系能量表格示例](./images/states.png)

小分子的 E、Gcorr 表格（eV）：

![小分子能量表格示例](./images/molecules.png)

在 Excel 等表格软件中复制对应单元格，再粘贴到“体系与状态”或“小分子参考”。

中间态之间原子数量需要守恒，需要手动调整**小分子参考项**和其**系数**。默认以第一个非星号体系作为基准（如*NH3）

