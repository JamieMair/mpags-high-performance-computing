@def title = "Topics"
@def tags = ["syntax", "code"]

# Topics

\toc

## Computing Foundations

This module will start with a description of modern hardware and software, as many students do not come from a Computer Science background. We aim to teach the student the basic architecture of a modern system, describing in detail parts such as the CPU, memory and co-processors like Graphics Processing Units (GPUs). We do this to ground future discussions of optimisations with a physical model of the computing system one is optimising for. Additionally, we will dive into the basics of software on a computing system, discussing what an operating system is, and how source code is transformed into machine code which can run on the system via the use of compilers. Using the knowledge of this section we will cover the taxonomy of the features of modern programming languages, and their relation to high performance code.

## Julia Crash Course

As we are not expecting any students taking this course to have experience with the Julia programming language, we will cover a quick crash course into the syntax of the language and give students a mental model of how the language functions so that they can understand the code examples throughout the module. This course is grounded in practical examples, given and assessed using Julia. While the concepts in this module are certainly applicable to other languages, Julia has been chosen for this course as it has the lowest barrier to entry for writing high performance, parallel code (including GPU programming).

## Measuring Performance

Optimisation is fairly useless without the ability to measure the impact of your changes. Benchmarking forms a core part of high performance computing, and this section will cover how to efficiently measure the run-time of your code, while we begin to understand what makes code run slowly. We will cover basic benchmarking techniques, such as timing, as well as more advanced techniques, such as profiling, to understand where to focus our time and effort when optimising. Additionally, we will touch on the theory of computational complexity to explain how the performance of an algorithm scales with the problem size.

## Optimising Serial Code

Here, we will focus on trying to get a given algorithm to execute as quickly, or efficiently, as possible on some given hardware. We will touch on lower-level optimisation details such as memory locality, stack vs heap memory and non-branching programming. The aim of this section is to write simple, yet fast, code to run as quickly as possible. We will also talk about Julia specific techniques to increase performance (or rather, avoid bad performance).

## Introduction to Parallel Programming
Here, we will introduce the theory of parallel computing and provide a framework to analyse the ability of an algorithm to be accelerated using parallel processing via the use of Directed Acyclical Graphs (DAGs). The theory introduced in this section will help frame the practical applications of parallel computing to any given task, while also giving theoretical devices to aid parallelising algorithms via the use of *maps* and *reductions*. On the practical side of things, we will talk about **race conditions** which are common pitfalls new students make when doing parallel computing.

## Multithreading & Multiprocessing

Multithreading is the easiest and most common paradigm one can use to parallelise one's code. We will start by discussing the advantages and disadvantages of using multithreading, as well as giving many practical examples of how to use multithreading in your code via the discussion of an *embarrassingly-parallel* problem. Next, we will discuss multiprocessing, which can be used to scale up parallel processing across an entire cluster. We will give examples of how multiprocessing can be achieved in Julia and set the scene for running code on a high performance supercomputing cluster.

## Cluster Computing

We will introduce a few ways of deploying code on a cluster, including basic multithreading, multiprocessing and even dive into the basics of MPI (Message Passing Interface) programs. For this, we will give examples of launching code on SLURM backed clusters.

## GPGPU Programming

The end of the module will centre around *General Purpose Graphics Processing Unit* (GPGPU) programming. GPUs are incredible devices with the ability to perform tens of thousands of operations in parallel. Programming for these devices has had a notoriously high barrier to entry until only recently. Julia provides users the ability to write native Julia code that can be executed directly on the GPU, increasing the flexibility and re-useability of the code for execution on many different devices. In this section, we will talk about the theory of GPU computing and give students an idea of what workloads can be accelerated by using a GPU, along with the limitations. Further, we will give students the opportunity to use the GPU via high-level abstractions and even write their own GPU kernels (programs that run on the GPU), all in Julia.