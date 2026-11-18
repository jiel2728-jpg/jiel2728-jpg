**English** | [简体中文](README.zh-CN.md)

### Hi, I'm Peijie Sun 👋

Currently a student at the University of Electronic Science and Technology of China (UESTC).
My focus is **putting neural networks and algorithms into hardware** — getting models and
algorithms all the way down to RTL, where compute, bandwidth and timing are the constraints
you can't design around.

---

### 🎯 What I'm thinking about

`Neural network accelerators` · `Algorithm-to-hardware` · `Digital front-end design` · `RTL microarchitecture`

The main thread is one question: what does a well-behaved software algorithm have to pay
once it moves onto silicon — and which of those costs can be designed away?

### 🔧 What I'm building

**[voq-buffer](https://github.com/jiel2728-jpg/voq-buffer)** — a 16-queue Virtual Output Queue buffer

An exercise in switch-chip datapath design: shared storage managed by linked lists, so that
512 physical slots are shared fully and dynamically across 16 queues, eliminating the
head-of-line blocking of a FIFO architecture. Three memory banks, three phases
(init / PUSH / POP), with a cycle-by-cycle address walkthrough in the README.

`Verilog-2001` · `UVM 1.2` · `TSMC 65LP synthesis: 15,742 cells / ~330 MHz`

### 🛠 Toolchain

`Verilog / SystemVerilog` · `UVM` · `VCS + Verdi` · `ModelSim / Questa` · `Design Compiler` · `SVA`

### 📝 Writing

- [How would you design an efficient Virtual Output Queue (VOQ) mechanism?](https://zhuanlan.zhihu.com/p/2063218113894684196) — from head-of-line blocking to a linked-list implementation *(in Chinese)*
