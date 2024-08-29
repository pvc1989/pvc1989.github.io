---
layout: page
title: 简历
---

# 裴为诚 [PEI Weicheng](https://pvc1989.github.io/resume/english)

----

> <i class="fa-solid fa-envelope"></i> <weicheng.pei@icloud.com>\
> <i class="fas fa-mobile-alt"></i> +86-188-1143-5549\
> <i class="fa-brands fa-github"></i> [https://pvc1989.github.io](https://pvc1989.github.io)

----

## 教育背景

2012---2022
:   [北京航空航天大学](https://www.buaa.edu.cn)
:   **硕士、博士，飞行器设计**

2016---2017
:   [得克萨斯理工大学](https://www.ttu.edu) (Lubbock, United States)
:   **访问学者**，获[国家留学基金委](https://www.csc.edu.cn/)资助

2008---2012
:   [浙江大学](https://www.zju.edu.cn)
:   **学士，工程力学**

----

## 工作经历

2022---2024
:   [清华大学](https://www.tsinghua.edu.cn)
:   **博士后，流体力学**，负责开发高阶计算流体力学求解器

----

## 发表论文

### <i class="fa-solid fa-graduation-cap"></i> 博士学位论文

标题
:   [舰载直升机气动干扰计算方法研究](https://pvc1989.github.io/phdthesis/presentation)

关键词
:   舰载直升机，气动干扰，旋翼空气动力学，间断伽辽金有限元法，加权基本无振荡重构，非定常动量源模型

### 期刊论文

- Yang M, Li S and **Pei W** (corresponding). [Combination of Advanced Actuator Line/Disk Model and High-Order Unstructured Finite Volume Solver for Helicopter Rotors](https://doi.org/10.3390/aerospace11040296). *Aerospace*, 2024, 11(4): 296.

- **Pei W**, Jiang Y and Li S. [High-Order CFD Solvers on Three-Dimensional Unstructured Meshes: Parallel Implementation of RKDG Method with WENO Limiter and Momentum Sources](https://doi.org/10.3390/app12094228). *Aerospace*, 2022, 9(7): 372.

- **Pei W**, Jiang Y and Li S. [An Efficient Parallel Implementation of the Runge–Kutta Discontinuous Galerkin Method with Weighted Essentially Non-Oscillatory Limiters on Three-Dimensional Unstructured Meshes](https://doi.org/10.3390/app12094228). *Applied Sciences*, 2022, 12(9): 4228.

- Wang X, **Pei W** and S Atluri. [Bifurcation & chaos in nonlinear structural dynamics: Novel & highly efficient optimal-feedback accelerated Picard iteration algorithms](https://doi.org/10.1016/j.cnsns.2018.05.008). *Communications in Nonlinear Science and Numerical Simulation*, 2018, 65: 54-69.

### 会议报告

- **Pei W** and Ren Y. [A Novel Energy-based Artificial Viscosity for Suppressing Numerical Oscillations in Discontinuous Galerkin and Flux Reconstruction Schemes](https://pvc1989.github.io/ICCFD12/presentation). [*12th International Conference on Computational Fluid Dynamics (ICCFD12)*](https://confit.atlas.jp/guide/event/iccfd12/subject/5-C-01/), July 15-19, 2024, Kobe, Japan.

- **Pei W** and Li S. Computational Method for the Aeromechanical Behaviors of a Rotorcraft in Vortex Ring State. [*International Conference on Computational & Experimental Engineering and Sciences 2015 (ICCES2015)*](https://www.iccesconf.org/), July 20-24, 2015, Reno, USA.

----

## 编程经验

### <i class="fa-brands fa-github"></i> 个人代码仓库

[miniCFD](https://github.com/pvc1989/miniCFD)
: 该仓库维护本人博士、博士后阶段研究的计算流体力学算法的 [Python3 原型](https://github.com/pvc1989/miniCFD/tree/develop/python)及 [C++20 实现](https://github.com/pvc1989/miniCFD/tree/develop/include)。
: 主要特性：
  - 空间离散：[间断伽辽金 (DG)](https://pvc1989.github.io/phdthesis/presentation)、[通量重构 (FR)](https://pvc1989.github.io/ICCFD12/presentation)
  - 激波捕捉：[限制器](https://pvc1989.github.io/phdthesis/presentation)、[人工黏性](https://pvc1989.github.io/ICCFD12/presentation)
  - 多态：[虚函数](https://pvc1989.github.io/miniWiki/programming/languages/cpp/class/inheritance.html)、[模板](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/generic.html)
  - 并行：[METIS](https://github.com/pvc1989/METIS)、[MPI](https://pvc1989.github.io/miniWiki/programming/mpi.html)
  - 读写: [CGNS](https://pvc1989.github.io/miniWiki/programming/mesh/cgns.html), [VTK](https://pvc1989.github.io/miniWiki/programming/mesh/vtk.html)
  - 构建：[CMake](https://pvc1989.github.io/miniWiki/programming/languages/cpp/make.html#cmake)
  - 测试：[Google Test](https://pvc1989.github.io/miniWiki/programming/languages/cpp/unittest.html#google-test)、[CTest](https://pvc1989.github.io/miniWiki/programming/languages/cpp/unittest.html#ctest)
  - CI/CD：[Github Actions](https://github.com/pvc1989/miniCFD/actions)
  - C++20：[`concept`/`requires`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#类型限制)、[`<concepts>`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#concepts)、[`<ranges>`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#ranges)

[miniWiki](https://github.com/pvc1989/miniWiki)
: 该仓库维护自学教程及日常工作用到的速查表。
: 主要内容：
  - 数学
  - 物理（[分析力学](https://pvc1989.github.io/miniWiki/physics/analytical_mechanics.html)、[量子力学](https://pvc1989.github.io/miniWiki/physics/quantum_mechanics.html)、[流体力学](https://pvc1989.github.io/miniWiki/physics/continuum/)）
  - 算法（[数据结构](https://pvc1989.github.io/miniWiki/algorithms/data_structures/)）
  - 编程（[CSAPP](https://pvc1989.github.io/miniWiki/programming/csapp.html)、[Linux](https://pvc1989.github.io/miniWiki/programming/linux.html)、[C++](https://pvc1989.github.io/miniWiki/programming/languages/cpp.html)、[Python](https://pvc1989.github.io/miniWiki/programming/languages/python.html)、[MPI](https://pvc1989.github.io/miniWiki/programming/mpi.html)、[UML](https://pvc1989.github.io/miniWiki/programming/design/uml.html)、[设计模式](https://pvc1989.github.io/miniWiki/programming/design/patterns.html)）
  - 文档（[LaTeX](https://pvc1989.github.io/miniWiki/documenting/latex/)、[Markdown](https://pvc1989.github.io/miniWiki/documenting/markdown.html)、[HTML/CSS/JS](https://pvc1989.github.io/miniWiki/documenting/web/)）

### <i class="fa-solid fa-arrow-up-a-z"></i> 数据结构及算法

- [LeetCode](https://leetcode.com/u/pvc1989/) 每日一题（主要用 C++）
  - ![LeetCode Stats](https://leetcard.jacoblin.cool/pvc1989?theme=light&ext=heatmap)
- 普林斯顿大学[《算法》](https://www.coursera.org/learn/algorithms-part1)课程的[编程作业](https://github.com/pvc1989/assignments-algorithms-princeton)（主要用 Java）
  - `percolation` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/percolation/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_b0ea575d0c5b8bf763650c6747a7cdc4.html)) 基于**并查集**数据结构，通过**蒙特卡洛模拟**，寻找**渗透阈值**。
  - `queues` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/queues/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_1216876c582b2d8bc8af271d600ae31a.html)) 实现**两端队列**及**随机队列**数据结构。
  - `collinear` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/collinear/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_027a30c366c586e6898ee55071a8fb6e.html)) 用**基于比较的排序**，在给定点集中寻找共线点。
  - `8puzzle` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/8puzzle/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_ef6e82a25a617010ce5f079a2b75227b.html)) 用基于**优先级队列**数据结构的 **A* 查找**算法，解决广义华容道问题。
  - `kdtree` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/kdtree/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_a52ca6093bf653b3f327f6154fdf935b.html)) 实现**二维树**数据结构，支持高效的**范围查找**及**最近邻居查找**。
  - `wordnet` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/wordnet/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_3f71ad797cfe718c22ccdb1b06ec9938.html)) 实现有根的**有向无环图**数据结构，寻找任意两点的**最近公共祖先**。
  - `seam` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/seam/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_89346fbae99106396c15a3f1abf88bd2.html)) 基于**稀疏图**的**单元最短路径**算法，实现一种内容感知的图像裁剪算法。
  - `baseball` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/baseball/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_7ae337e67fc61319ed2ae7abe6dec3ea.html)) 用**最大流量**问题的 **Ford--Fulkerson** 算法，排除联赛中夺冠无望的球队。
  - `boggle` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/boggle/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_2f5a60232d789ad5a886f7da2c383c9f.html)) 用**多路字典树**数据结构，完成连词游戏。
  - `burrows` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/burrows/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_4c05c4b10993e593b29578503fdeb137.html)) 用 **Burrows--Wheeler 变换**及**霍夫曼压缩**算法，实现一种**数据压缩**算法。

### <i class="fa-brands fa-linux"></i> Linux 系统编程

- 卡耐基梅隆大学[《计算机系统导论》](https://www.cs.cmu.edu/~213/)课程的[实验作业](https://csapp.cs.cmu.edu/3e/labs.html)（主要用 C 及 x86-64 汇编）
  - `data` ([spec](http://csapp.cs.cmu.edu/3e/datalab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/data.html)) 用**位运算**实现逻辑、整型、浮点型运算。
  - `bomb` ([spec](http://csapp.cs.cmu.edu/3e/bomblab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/bomb.html)) 用 `gdb`/`lldb` 及 `objdump` 破译给定 **x86-64** 可执行文件中的密码。
  - `attack` ([spec](http://csapp.cs.cmu.edu/3e/attacklab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/attack.html)) 用**代码注入**及**面向返回编程**改变给定 **x86-64** 可执行文件的行为。
  - `cache` ([spec](http://csapp.cs.cmu.edu/3e/cachelab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/cache.html)) 实现 CPU 缓存模拟器，统计**缓存命中**及**缓存丢失**次数。
  - `shell` ([spec](http://csapp.cs.cmu.edu/3e/shlab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/shell.html)) 实现简易 Unix shell，支持**作业管理** (`fg`/`bg`, `jobs`) 及**信号处置** (`ctrl-c`, `ctrl-z`)。
  - `malloc` ([spec](http://csapp.cs.cmu.edu/3e/malloclab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/malloc.html)) 基于管理**虚拟存储**的系统调用，实现 `malloc()` 及 `free()`。
  - `proxy` ([spec](http://csapp.cs.cmu.edu/3e/proxylab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/proxy.html)) 实现简易代理服务器，支持缓存 **HTTP 响应**及**多线程并发**。

### <i class="fa-solid fa-server"></i> 并发与并行编程

- 基于 [SSH](https://pvc1989.github.io/miniWiki/programming/linux/ssh.html) 及**网络文件系统**，[搭建局域网及 CPU 机群](https://pvc1989.github.io/miniWiki/programming/mpi.html#平台搭建)。
- 在 [miniCFD](https://github.com/pvc1989/miniCFD/) 中，用 [METIS](https://github.com/pvc1989/METIS) 对非结构网格分区，基于 [MPI](https://pvc1989.github.io/miniWiki/programming/mpi.html) 的**非阻塞通信**将计算与通信重叠。
- 在 [`proxy` 实验](https://pvc1989.github.io/miniWiki/programming/csapp/labs/proxy.html) 中，利用 [POSIX threads](http://pvc1989.github.io/miniWiki/programming/csapp/12_concurrent_programming.html#32-pthread) 支持**多线程并发**。
