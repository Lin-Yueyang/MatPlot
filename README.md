# 台阶图 · Step Plot

反应自由能台阶图编辑器，支持多体系、反应分支、可选过渡态及文字样式调整。

当前版本：[v0.17](./stepplot.html)。

[在线使用](https://lin-yueyang.github.io/step_plot/) · [更新记录](./更新.md)

可收藏上方的“在线使用”。离线使用时，下载 [stepplot.html](./stepplot.html)，用 Chrome 或 Edge 打开后加入收藏。以后将新版文件放回同一位置，即可沿用收藏。历史版本见 [archive](./archive/)。

输入 E、Gcorr 与小分子参考项即可绘图。工程通过“保存工程”导出 JSON，下次用“打开”该JSON可继续编辑。

保存图形支持 SVG、PNG、CSV。



## 输入示例

体系的 E、Gcorr 表格（eV）：

![体系能量表格示例](./images/states.png)

小分子的 E、Gcorr 表格（eV）：

![小分子能量表格示例](./images/molecules.png)

在 Excel 等表格软件中复制对应单元格，再粘贴到“体系与状态”或“小分子参考”。

中间态之间原子数量需要守恒，需要手动调整**小分子参考项**和其**系数**。默认以第一个非星号体系作为基准（如*NH3）

