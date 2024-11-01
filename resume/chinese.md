---
layout: page
title: 个人简介
---

# [裴为诚](https://pvc1989.github.io/resume/chinese) [PEI Weicheng](https://pvc1989.github.io/resume/english)

----

> <i class="fa-solid fa-envelope"></i> <weicheng.pei@icloud.com> •
> <i class="fas fa-mobile-alt"></i> +86-188-1143-5549 •
> <i class="fa-brands fa-github"></i> [个人主页](https://pvc1989.github.io)

----

## 教育背景

2008---2012
:   [浙江大学](https://www.zju.edu.cn)
:   **本科**学历，**工学学士**学位，**工程力学**专业

2012---2022
:   [北京航空航天大学](https://www.buaa.edu.cn)
:   **研究生**学历，**工学博士**学位，**飞行器设计**专业

2016---2017
:   [得克萨斯理工大学](https://www.ttu.edu) (Lubbock, United States)
:   **联合培养博士生**，[国家留学基金委](https://www.csc.edu.cn/)资助，美国工程院院士 [Satya N. Atluri](https://en.wikipedia.org/wiki/Satya_N._Atluri) 教授指导

----

## 工作经历

2022---2024
:   [清华大学](https://www.tsinghua.edu.cn)
:   **博士后**，[任玉新](https://www.hy.tsinghua.edu.cn/info/1154/1826.htm)教授团队，负责开发高阶计算流体力学求解器

----

## 发表论文

2015
旋翼涡环
自由尾迹
简单并行
: **Pei W** and Li S. Computational Method for the Aeromechanical Behaviors of a Rotorcraft in Vortex Ring State. [*International Conference on Computational & Experimental Engineering and Sciences 2015 (ICCES2015)*](https://www.iccesconf.org/), July 20-24, 2015, Reno, USA.

  |:---:|:---:|:---:|
  | ![](../images/hover.svg) | ![](../images/forward.gif) | ![](../images/cpu40.png) |

----

2018
: Wang X, **Pei W** and S Atluri. [Bifurcation & chaos in nonlinear structural dynamics: Novel & highly efficient optimal-feedback accelerated Picard iteration algorithms](https://doi.org/10.1016/j.cnsns.2018.05.008). *Communications in Nonlinear Science and Numerical Simulation*, 2018, 65: 54-69.

----

2022a
有限元
间断伽辽金
WENO 限制器
MPI 并行
: **Pei W**, Jiang Y and Li S. [An Efficient Parallel Implementation of the Runge–Kutta Discontinuous Galerkin Method with Weighted Essentially Non-Oscillatory Limiters on Three-Dimensional Unstructured Meshes](https://doi.org/10.3390/app12094228). *Applied Sciences*, 2022, 12(9): 4228.
  ![](https://www.mdpi.com/applsci/applsci-12-04228/article_deploy/html/images/applsci-12-04228-g022.png)

----

2022b
有限元
间断伽辽金
WENO 限制器
MPI 并行
动量源模型
: **Pei W**, Jiang Y and Li S. [High-Order CFD Solvers on Three-Dimensional Unstructured Meshes: Parallel Implementation of RKDG Method with WENO Limiter and Momentum Sources](https://doi.org/10.3390/aerospace9070372). *Aerospace*, 2022, 9(7): 372.
  ![](https://www.mdpi.com/aerospace/aerospace-09-00372/article_deploy/html/images/aerospace-09-00372-g027.png)

----

2022c
有限元
间断伽辽金
WENO 限制器
MPI 并行
动量源模型
:   [舰载直升机气动干扰计算方法研究](https://pvc1989.github.io/phdthesis/presentation)
    ![](https://pvc1989.github.io/phdthesis/thesis/figures/ship/a=45_p=3/animation.gif)

----

2024a
有限体积
变分重构
WBAP 限制器
动量源模型
: Yang M, Li S and **Pei W** (corresponding). [Combination of Advanced Actuator Line/Disk Model and High-Order Unstructured Finite Volume Solver for Helicopter Rotors](https://doi.org/10.3390/aerospace11040296). *Aerospace*, 2024, 11(4): 296.
  ![](https://www.mdpi.com/aerospace/aerospace-11-00296/article_deploy/html/images/aerospace-11-00296-g029.png)

----

2024b
有限元/谱元
间断伽辽金
通量重构
人工黏性
: **Pei W** and Ren Y. [A Novel Energy-based Artificial Viscosity for Suppressing Numerical Oscillations in Discontinuous Galerkin and Flux Reconstruction Schemes](https://pvc1989.github.io/ICCFD12/presentation). [*12th International Conference on Computational Fluid Dynamics (ICCFD12)*](https://confit.atlas.jp/guide/event/iccfd12/subject/5-C-01/), July 15-19, 2024, Kobe, Japan.
  <a href id="riemann2d_planar"></a>

  |:---:|
  | [![](https://pvc1989.github.io/ICCFD12/riemann2d/h=1e-2_p=3/animation.gif)](#riemann2d_warpped) |

----

2024c（预计）
有限体积
变分重构
WBAP 限制器
动量源模型
: Yang M, **Pei W** and Li S. 基于高阶有限体积格式的 UH60A 直升机旋翼--机身气动干扰模拟（暂拟）
  ![](../images/UH60A.gif)

----

2024d（预计）
有限元/谱元
间断伽辽金
分裂形式
大涡模拟
: Gao M, **Pei W** and Ren Y. 基于 DESEM 的 LES 建模方法及其在非稳态湍流中的应用（暂拟）

  |:---:|:---:|
  | ![](../images/underbelly.jpg) | <video height="240" controls><source src="../images/underbelly.mp4" type="video/mp4">Your browser does not support the video tag.</video> |

----

## 编程经验

### <i class="fa-brands fa-github"></i> 个人代码仓库

[miniCFD](https://github.com/pvc1989/miniCFD)
: 该仓库维护本人博士、博士后阶段研究的计算流体力学算法的 [Python3 原型](https://github.com/pvc1989/miniCFD/tree/develop/python)及 [C++20 实现](https://github.com/pvc1989/miniCFD/tree/develop/include)。
: 主要特性：
  - 空间离散：[间断伽辽金 (DG)](https://pvc1989.github.io/phdthesis/presentation)、[通量重构 (FR)](https://pvc1989.github.io/ICCFD12/presentation)
  - 激波捕捉：[限制器](https://pvc1989.github.io/phdthesis/presentation)、[人工黏性](https://pvc1989.github.io/ICCFD12/presentation)
  - 多态：[`virtual`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/class/inheritance.html)、[`template`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/generic.html)、[`concept`/`requires`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#类型限制)
  - 并行：[pvc1989/METIS](https://github.com/pvc1989/METIS)、[MPI](https://pvc1989.github.io/miniWiki/programming/mpi.html)
  - 读写：[CGNS](https://pvc1989.github.io/miniWiki/programming/mesh/cgns.html), [VTK](https://pvc1989.github.io/miniWiki/programming/mesh/vtk.html)
  - 构建：[CMake](https://pvc1989.github.io/miniWiki/programming/languages/cpp/make.html#cmake)、[GitHub Actions](https://github.com/pvc1989/miniCFD/actions)
  - 测试：[Google Test](https://pvc1989.github.io/miniWiki/programming/languages/cpp/unittest.html#google-test)、[CTest](https://pvc1989.github.io/miniWiki/programming/languages/cpp/unittest.html#ctest)
  - C++20：[`concept`/`requires`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#类型限制)、[`<concepts>`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#concepts)、[`<ranges>`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#ranges)

----

[miniWiki](https://github.com/pvc1989/miniWiki)
: 该仓库维护自学教程及日常工作用到的速查表。
: 主要内容：
  - 数学：实分析、复分析、泛函分析、张量分析、微分方程
  - 物理：[分析力学](https://pvc1989.github.io/miniWiki/physics/analytical_mechanics.html)、[量子力学](https://pvc1989.github.io/miniWiki/physics/quantum_mechanics.html)、[流体力学](https://pvc1989.github.io/miniWiki/physics/continuum/)
  - 算法：[数据结构](https://pvc1989.github.io/miniWiki/algorithms/data_structures/)、数值方法、优化方法
  - 编程：[CSAPP](https://pvc1989.github.io/miniWiki/programming/csapp.html)、[Linux](https://pvc1989.github.io/miniWiki/programming/linux.html)、[C++](https://pvc1989.github.io/miniWiki/programming/languages/cpp.html)、[Python](https://pvc1989.github.io/miniWiki/programming/languages/python.html)、[MPI](https://pvc1989.github.io/miniWiki/programming/mpi.html)、[UML](https://pvc1989.github.io/miniWiki/programming/design/uml.html)、[设计模式](https://pvc1989.github.io/miniWiki/programming/design/patterns.html)
  - 文档：[LaTeX](https://pvc1989.github.io/miniWiki/documenting/latex/)、[Markdown](https://pvc1989.github.io/miniWiki/documenting/markdown.html)、[HTML/CSS/JS](https://pvc1989.github.io/miniWiki/documenting/web/)

----

### <i class="fa-solid fa-arrow-up-a-z"></i> 数据结构及算法

[![](../images/leetcode_coin.gif)](https://leetcode.com/u/pvc1989/)
: - ![LeetCode Stats](https://leetcard.jacoblin.cool/pvc1989?theme=light&ext=heatmap)

----

Princeton's
[![](https://algs4.cs.princeton.edu/cover.png)](https://github.com/pvc1989/assignments-algorithms-princeton)
: - [`percolation`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_b0ea575d0c5b8bf763650c6747a7cdc4.html) 基于**并查集**数据结构，通过**蒙特卡洛模拟**，寻找**渗透阈值**。
  - [`queues`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_1216876c582b2d8bc8af271d600ae31a.html) 实现**两端队列**及**随机队列**数据结构。
  - [`collinear`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_027a30c366c586e6898ee55071a8fb6e.html) 用**基于比较的排序**，在给定点集中寻找共线点。
  - [`8puzzle`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_ef6e82a25a617010ce5f079a2b75227b.html) 用基于**优先级队列**数据结构的 **A* 查找**算法，解决广义华容道问题。
  - [`kdtree`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_a52ca6093bf653b3f327f6154fdf935b.html) 实现**二维树**数据结构，支持高效的**范围查找**及**最近邻居查找**。
  - [`wordnet`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_3f71ad797cfe718c22ccdb1b06ec9938.html) 实现有根的**有向无环图**数据结构，寻找任意两点的**最近公共祖先**。
  - [`seam`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_89346fbae99106396c15a3f1abf88bd2.html) 基于**稀疏图**的**单元最短路径**算法，实现一种内容感知的图像裁剪算法。
  - [`baseball`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_7ae337e67fc61319ed2ae7abe6dec3ea.html) 用**最大流量**问题的 **Ford--Fulkerson** 算法，排除联赛中夺冠无望的球队。
  - [`boggle`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_2f5a60232d789ad5a886f7da2c383c9f.html) 用**多路字典树**数据结构，完成连词游戏。
  - [`burrows`](https://pvc1989.github.io/assignments-algorithms-princeton/dir_4c05c4b10993e593b29578503fdeb137.html) 用 **Burrows--Wheeler 变换**及**霍夫曼压缩**算法，实现一种**数据压缩**算法。

----

### <i class="fa-brands fa-linux"></i> Linux 系统编程

Carnegie Mellon's
[![](http://csapp.cs.cmu.edu/3e/images/csapp3e-cover.jpg)](https://csapp.cs.cmu.edu/)
: - [`data`](https://pvc1989.github.io/miniWiki/programming/csapp/labs/data.html) 用**位运算**实现逻辑、整型、浮点型运算。
  - [`bomb`](https://pvc1989.github.io/miniWiki/programming/csapp/labs/bomb.html) 用 `gdb`/`lldb` 及 `objdump` 破译给定 **x86-64** 可执行文件中的密码。
  - [`attack`](https://pvc1989.github.io/miniWiki/programming/csapp/labs/attack.html) 用**代码注入**及**面向返回编程**改变给定 **x86-64** 可执行文件的行为。
  - [`cache`](https://pvc1989.github.io/miniWiki/programming/csapp/labs/cache.html) 实现 CPU 缓存模拟器，统计**缓存命中**及**缓存丢失**次数；以*缓存丢失*次数最少为目标，优化矩阵转置运算。
  - [`shell`](https://pvc1989.github.io/miniWiki/programming/csapp/labs/shell.html) 实现简易 Unix shell，支持**作业管理** (`fg`/`bg`, `jobs`) 及**信号处置** (`ctrl-c`, `ctrl-z`)。
  - [`malloc`](https://pvc1989.github.io/miniWiki/programming/csapp/labs/malloc.html) 基于管理**虚拟存储**的系统调用，实现 `malloc()` 及 `free()`。
  - [`proxy`](https://pvc1989.github.io/miniWiki/programming/csapp/labs/proxy.html) 实现简易代理服务器，支持缓存 **HTTP 响应**及**多线程并发**。

----

### <i class="fa-solid fa-server"></i> 高性能计算实践

[平台搭建](https://pvc1989.github.io/miniWiki/programming/mpi.html#平台搭建)
: 基于 [SSH](https://pvc1989.github.io/miniWiki/programming/linux/ssh.html) 及**网络文件系统 (NFS)**，搭建**局域网**（以太网段）及 **CPU 机群**（100 核心 / 5 结点）。

  |:---:|:---:|:---:|
  | ![](../images/vbird_basics.jpg) | ![](../images/vbird_server.png) | ![](../images/d501_server.jpg) |

----

[MPI](https://pvc1989.github.io/miniWiki/programming/mpi)
: 在 [miniCFD](https://github.com/pvc1989/miniCFD/) 中
  - 利用 [pvc1989/METIS](https://github.com/pvc1989/METIS) 对非结构网格分区，每个 [MPI](https://pvc1989.github.io/miniWiki/programming/mpi) 进程分别负责一块。
  - 利用 `MPI_[Isend|Irecv|Waitall]` 等**非阻塞通信**接口，实现计算与通信重叠。

  |:---:|
  | ![](https://pvc1989.github.io/phdthesis/thesis/figures/double_mach/partition.png) |

  |:---:|:---:|:---:|
  | ![](https://pvc1989.github.io/phdthesis/thesis/figures/double_mach/balance.svg) | ![](https://pvc1989.github.io/phdthesis/thesis/figures/double_mach/speedup.svg) | ![](https://pvc1989.github.io/phdthesis/thesis/figures/double_mach/efficiency.svg) |

----

POSIX
: 在 [`proxy`](https://pvc1989.github.io/miniWiki/programming/csapp/labs/proxy.html) 实验中
  - 由单一主管线程监听并接收请求，由若干预先创建的工作线程负责响应。
  - 利用 [`sem_t`](https://pvc1989.github.io/miniWiki/programming/csapp/12_concurrent_programming.html#semaphore)、[`pthread_mutex_t`](https://pvc1989.github.io/miniWiki/programming/csapp/12_concurrent_programming.html#pthread_mutex_t)、[`pthread_rwlock_t`](https://pvc1989.github.io/miniWiki/programming/csapp/12_concurrent_programming.html#pthread_rwlock_t) 等**同步**机制，确保**线程安全**地读写共享资源。

  |:---:|
  | ![](https://pvc1989.github.io/miniWiki/programming/csapp/ics3/conc/prethreaded.svg) |

----

[CUDA](http://pvc1989.github.io/miniWiki/programming/cuda)
: 在 [miniCFD](https://github.com/pvc1989/miniCFD/) 中
  1. 利用**标量级**并发，批量后处理输出文件。
  2. 利用 `cudaStream_t`、`cudaEvent_t`，实现 GPU 计算与数据转移重叠，从而加速高质量非结构网格生成。

  |  1  |  2  |
  |:---:|:---:|
  | <a href id="riemann2d_warpped"></a>[![](../images/riemann2d_warpped.gif)](#riemann2d_planar) | ![](../images/distmesh_hole.gif) |
