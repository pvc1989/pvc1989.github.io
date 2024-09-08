---
layout: page
title: Resume
---

# [PEI Weicheng](https://pvc1989.github.io/resume/english) [裴为诚](https://pvc1989.github.io/resume/chinese)

----

> <i class="fa-solid fa-envelope"></i> <weicheng.pei@icloud.com> •
> <i class="fas fa-mobile-alt"></i> +86-188-1143-5549 •
> <i class="fa-brands fa-github"></i> [My Home Page](https://pvc1989.github.io)

----

## Education Background

2008---2012
:   [Zhejiang University](https://www.zju.edu.cn) (Hangzhou, China)
:   Undergraduate, **BSc**, Engineering Mechanics

2012---2022
:   [Beihang University](https://www.buaa.edu.cn) (Beijing, China)
:   Graduate, **MSc & PhD**, Aircraft Design

2016---2017
:   [Texas Tech University](https://www.ttu.edu) (Lubbock, United States)
:   **Joint PhD Student**, sponsored by [China Scholarship Council](https://www.csc.edu.cn/), supervised by Prof. [Satya N. Atluri](https://en.wikipedia.org/wiki/Satya_N._Atluri) (member of US National Academy of Engineering)

----

## Work Experience

2022---2024
:   [Tsinghua University](https://www.tsinghua.edu.cn) (Beijing, China)
:   **Postdoctoral Researcher**, Prof. [Yu-Xin Ren](https://scholar.google.com/citations?user=iuhAibwAAAAJ)'s group, responsible for developing high-order CFD solvers.

----

## Publications

### <i class="fa-solid fa-graduation-cap"></i> PhD Thesis

Title
:   [Study on Computational Method for Aerodynamic Interference of Shipborne Helicopters](https://pvc1989.github.io/phdthesis/presentation)

Keywords
:   shipborne helicopter, aerodynamic interference, rotor aerodynamics, discontinuous Galerkin (DG) finite element method, weighted essentially non-oscillatory (WENO) reconstruction, unsteady momentum source (UMS) model

### Journal Articles

- Yang M, Li S and **Pei W** (corresponding). [Combination of Advanced Actuator Line/Disk Model and High-Order Unstructured Finite Volume Solver for Helicopter Rotors](https://doi.org/10.3390/aerospace11040296). *Aerospace*, 2024, 11(4): 296.

- **Pei W**, Jiang Y and Li S. [High-Order CFD Solvers on Three-Dimensional Unstructured Meshes: Parallel Implementation of RKDG Method with WENO Limiter and Momentum Sources](https://doi.org/10.3390/app12094228). *Aerospace*, 2022, 9(7): 372.

- **Pei W**, Jiang Y and Li S. [An Efficient Parallel Implementation of the Runge–Kutta Discontinuous Galerkin Method with Weighted Essentially Non-Oscillatory Limiters on Three-Dimensional Unstructured Meshes](https://doi.org/10.3390/app12094228). *Applied Sciences*, 2022, 12(9): 4228.

- Wang X, **Pei W** and S Atluri. [Bifurcation & chaos in nonlinear structural dynamics: Novel & highly efficient optimal-feedback accelerated Picard iteration algorithms](https://doi.org/10.1016/j.cnsns.2018.05.008). *Communications in Nonlinear Science and Numerical Simulation*, 2018, 65: 54-69.

### Conference Presentations

- **Pei W** and Ren Y. [A Novel Energy-based Artificial Viscosity for Suppressing Numerical Oscillations in Discontinuous Galerkin and Flux Reconstruction Schemes](https://pvc1989.github.io/ICCFD12/presentation). [*12th International Conference on Computational Fluid Dynamics (ICCFD12)*](https://confit.atlas.jp/guide/event/iccfd12/subject/5-C-01/), July 15-19, 2024, Kobe, Japan.

- **Pei W** and Li S. Computational Method for the Aeromechanical Behaviors of a Rotorcraft in Vortex Ring State. [*International Conference on Computational & Experimental Engineering and Sciences 2015 (ICCES2015)*](https://www.iccesconf.org/), July 20-24, 2015, Reno, USA.

----

## Programming Experience

### <i class="fa-brands fa-github"></i> Personal Code Repositories

[miniCFD](https://github.com/pvc1989/miniCFD)
: This repo maintains [Python3 prototypes](https://github.com/pvc1989/miniCFD/tree/develop/python) and [C++20 implementations](https://github.com/pvc1989/miniCFD/tree/develop/include) of the CFD algorithms studied in my PhD and postdoc period.
: Main features:
  - Spatial discretization: [DG](https://pvc1989.github.io/phdthesis/presentation), [FR](https://pvc1989.github.io/ICCFD12/presentation)
  - Shock capturing: [limiter](https://pvc1989.github.io/phdthesis/presentation), [artificial viscosity](https://pvc1989.github.io/ICCFD12/presentation)
  - Polymorphism: [`virtual`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/class/inheritance.html), [`template`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/generic.html), [`concept`/`requires`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#类型限制)
  - Parallelism: [pvc1989/METIS](https://github.com/pvc1989/METIS), [MPI](https://pvc1989.github.io/miniWiki/programming/mpi.html)
  - I/O: [CGNS](https://pvc1989.github.io/miniWiki/programming/mesh/cgns.html), [VTK](https://pvc1989.github.io/miniWiki/programming/mesh/vtk.html)
  - Build: [CMake](https://pvc1989.github.io/miniWiki/programming/languages/cpp/make.html#cmake)、[Github Actions](https://github.com/pvc1989/miniCFD/actions)
  - Test: [Google Test](https://pvc1989.github.io/miniWiki/programming/languages/cpp/unittest.html#google-test), [CTest](https://pvc1989.github.io/miniWiki/programming/languages/cpp/unittest.html#ctest)
  - C++20: [`concept`/`requires`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#类型限制), [`<concepts>`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#concepts), [`<ranges>`](https://pvc1989.github.io/miniWiki/programming/languages/cpp/template/concept.html#ranges)

[miniWiki](https://github.com/pvc1989/miniWiki)
: This repo maintains tutorials for self-study and cheatsheets for daily work.
: Main topics:
  - Mathematics (real/complex/functional/tensor analysis, ODEs and PDEs)
  - Physics ([analytical mechanics](https://pvc1989.github.io/miniWiki/physics/analytical_mechanics.html), [quantum mechanics](https://pvc1989.github.io/miniWiki/physics/quantum_mechanics.html), [fluid mechanics](https://pvc1989.github.io/miniWiki/physics/continuum/))
  - Algorithms ([data structures](https://pvc1989.github.io/miniWiki/algorithms/data_structures/))
  - Programming ([CSAPP](https://pvc1989.github.io/miniWiki/programming/csapp.html), [Linux](https://pvc1989.github.io/miniWiki/programming/linux.html), [C++](https://pvc1989.github.io/miniWiki/programming/languages/cpp.html), [Python](https://pvc1989.github.io/miniWiki/programming/languages/python.html), [MPI](https://pvc1989.github.io/miniWiki/programming/mpi.html), [UML](https://pvc1989.github.io/miniWiki/programming/design/uml.html), [design patterns](https://pvc1989.github.io/miniWiki/programming/design/patterns.html))
  - Documenting ([LaTeX](https://pvc1989.github.io/miniWiki/documenting/latex/), [Markdown](https://pvc1989.github.io/miniWiki/documenting/markdown.html), [HTML/CSS/JS](https://pvc1989.github.io/miniWiki/documenting/web/))

### <i class="fa-solid fa-arrow-up-a-z"></i> Data Structure and Algorithms

- [LeetCode](https://leetcode.com/u/pvc1989/) daily challenges (mainly in C++)
  - ![LeetCode Stats](https://leetcard.jacoblin.cool/pvc1989?theme=light&ext=heatmap)
- [Programming assignments](https://github.com/pvc1989/assignments-algorithms-princeton) in Princeton's [*Algorithms*, Part 1](https://www.coursera.org/learn/algorithms-part1) and [Part 2](https://www.coursera.org/learn/algorithms-part2) (mainly in Java)
  - `percolation` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/percolation/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_b0ea575d0c5b8bf763650c6747a7cdc4.html)) finds the value of the **percolation threshold** via **Monte Carlo simulation** based on the **union-find** data structure.
  - `queues` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/queues/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_1216876c582b2d8bc8af271d600ae31a.html)) implements the **double-ended queue** and **randomized queue** data structures.
  - `collinear` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/collinear/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_027a30c366c586e6898ee55071a8fb6e.html)) finds collinear points in a point set using **comparison-based sorting** algorithms.
  - `8puzzle` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/8puzzle/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_ef6e82a25a617010ce5f079a2b75227b.html)) solves the generalized 8-puzzle problem using the **A* search** algorithm based on the **priority queue** data structure.
  - `kdtree` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/kdtree/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_a52ca6093bf653b3f327f6154fdf935b.html)) implements the **2d tree** data structure to support efficient **range search** and **nearest-neighbor search**.
  - `wordnet` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/wordnet/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_3f71ad797cfe718c22ccdb1b06ec9938.html)) builds a rooted **directed acyclic graph (DAG)** data structure and looks for the **shortest common ancestor** of any two vertices.
  - `seam` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/seam/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_89346fbae99106396c15a3f1abf88bd2.html)) implements content-aware image resizing algorithm based on algothms for finding the **single-source shortest path** in a **sparse graph**.
  - `baseball` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/baseball/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_7ae337e67fc61319ed2ae7abe6dec3ea.html)) solves the baseball elimination problem using the **Ford--Fulkerson** algorithm for the **maxflow** problem.
  - `boggle` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/boggle/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_2f5a60232d789ad5a886f7da2c383c9f.html)) plays the word game Boggle using the **R-way trie** data structure.
  - `burrows` ([spec](https://coursera.cs.princeton.edu/algs4/assignments/burrows/specification.php), [ans](https://pvc1989.github.io/assignments-algorithms-princeton/dir_4c05c4b10993e593b29578503fdeb137.html)) implement a **data compression** algorithm based on the **Burrows--Wheeler transform** and the **Huffman compression** algorithm.

### <i class="fa-brands fa-linux"></i> Linux System Programming

- [Lab assignments](https://csapp.cs.cmu.edu/3e/labs.html) in CMU's [15-213/18-213: *Introduction to Computer Systems*](https://www.cs.cmu.edu/~213/) (mainly in C and x86-64 assembly)
  - `data` ([spec](http://csapp.cs.cmu.edu/3e/datalab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/data.html)) implements logical, integral and floating-point operations using **bit manipulations** only.
  - `bomb` ([spec](http://csapp.cs.cmu.edu/3e/bomblab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/bomb.html)) deciphers passwords hidden in an **x86-64** executable file via `gdb`/`lldb` and `objdump`.
  - `attack` ([spec](http://csapp.cs.cmu.edu/3e/attacklab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/attack.html)) alters the behaviors of two **x86-64** executable files by **code injection** and **return-oriented programming**.
  - `cache` ([spec](http://csapp.cs.cmu.edu/3e/cachelab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/cache.html)) implements a simulator of CPU cache, which takes the statistics of **cache-hit** and **cache-miss**; minimize the number of **cache-miss**es in matrix transpose operations.
  - `shell` ([spec](http://csapp.cs.cmu.edu/3e/shlab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/shell.html)) implements a tiny Unix shell, which supports **job management** (`fg`/`bg`, `jobs`) and **signal handling** (`ctrl-c`, `ctrl-z`).
  - `malloc` ([spec](http://csapp.cs.cmu.edu/3e/malloclab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/malloc.html)) implements `malloc()` and `free()` via system calls, which manage the **virtual memory**.
  - `proxy` ([spec](http://csapp.cs.cmu.edu/3e/proxylab.pdf), [ans](https://pvc1989.github.io/miniWiki/programming/csapp/labs/proxy.html)) implements a tiny proxy server, which supports caching **HTTP responses** and **multi-thread concurrency**.

### <i class="fa-solid fa-server"></i> Concurrent and Parallel Programming

[Platform](https://pvc1989.github.io/miniWiki/programming/mpi.html#平台搭建)
: Build a **LAN** (Ethernet segment) and a **CPU cluster** (100 cores / 5 nodes) based on [SSH](https://pvc1989.github.io/miniWiki/programming/linux/ssh.html) and **network file system (NFS)**.

[MPI](https://pvc1989.github.io/miniWiki/programming/mpi)
: In [miniCFD](https://github.com/pvc1989/miniCFD/),
  - partitions unstructured grids by [pvc1989/METIS](https://github.com/pvc1989/METIS), each process takes charge of one part.
  - overlaps computation with communication via the **non-blocking communication** interface including `MPI_[Isend|Irecv|Waitall]`.

POSIX
: In the [`proxy`](https://pvc1989.github.io/miniWiki/programming/csapp/labs/proxy.html) lab,
  - listens and accepts requests by a single supervisor thread and responses by a number of pre-created worker threads.
  - ensures **thread-safe** I/O on shared resources via **synchronization** mechanisms including [`sem_t`](https://pvc1989.github.io/miniWiki/programming/csapp/12_concurrent_programming.html#semaphore), [`pthread_mutex_t`](https://pvc1989.github.io/miniWiki/programming/csapp/12_concurrent_programming.html#pthread_mutex_t) and [`pthread_rwlock_t`](https://pvc1989.github.io/miniWiki/programming/csapp/12_concurrent_programming.html#pthread_rwlock_t).

[CUDA](http://pvc1989.github.io/miniWiki/programming/cuda)
: In [miniCFD](https://github.com/pvc1989/miniCFD/),
  - utilize **scalar-level** concurrency for post-processing output files in batch.
  - overlaps computation with communication via the  `cudaStream_t` and `cudaEvent_t` for speeding up the generation of high-quality unstructured meshes.
