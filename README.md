### 你好，我是孙培杰 👋

电子科技大学在读。方向是**神经网络与算法的硬件化**——把模型和算法真正落到 RTL 上，
关心算力、带宽、时序这些绕不过去的约束。

---

### 🎯 现在关心什么

`神经网络加速器` · `算法硬件化` · `数字前端设计` · `RTL 微架构`

主线是想搞明白一件事：一个算法在软件里跑得好，搬到硅上要付出什么代价，
以及哪些代价是可以通过设计省掉的。

### 🔧 在做的项目

**[voq-buffer](https://github.com/jiel2728-jpg/voq-buffer)** — 16 队列虚拟输出队列缓存

交换芯片数据通路的练习：用链表管理共享存储，把 512 个物理槽位在 16 个队列之间
做完全动态的复用，消除 FIFO 架构的队头阻塞。三块存储体、三个阶段
（初始化 / PUSH / POP），README 里有逐拍的地址走查。

`Verilog-2001` · `UVM 1.2` · `TSMC 65LP 综合 15,742 cells / 约 330 MHz`

### 🛠 工具链

`Verilog / SystemVerilog` · `UVM` · `VCS + Verdi` · `ModelSim / Questa` · `Design Compiler` · `SVA`

### 📝 写的一点东西

- [如何设计一套高效的虚拟输出队列 (VOQ) 机制？](https://zhuanlan.zhihu.com/p/2063218113894684196) — 从队头阻塞讲到链表实现

### 📮 联系

邮箱：sunpeijie@std.uestc.edu.cn
