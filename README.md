起始状态为手动输入如：123056478<br/>
程序默认的目标为123456780<br/>
如果需要改变目标将GOAL改变即可<br/>
输出为从起始状态到目标状态最少步数<br/>
A\*算法使用的是队列，因为我写了递归，发现在比较复杂的情况下由于递归太多次导致堆栈溢出，所以沿用了广度优先和深度优先的写法
