@def title = "Resources"
@def tags = ["syntax", "code"]

# Course Resources
\toc

## Lecture Notes

The lecture notes are available [here](/assets/book_v1.2.pdf). They are a work in progress and may change.

### Changelog:
**Current Version: v1.1 (23/01/2023)**

- Updated to v1.1: Improved Chapters 5 and 6: Measuring Performance and Optimisation.


## GitHub Classroom

The assessment and submission will be done via GitHub Classroom, which allows for automated marking and feedback. The assignment for each week will be emailed to everyone enrolled in the class. You will need a GitHub account (it's free!) to sign up.

**Git/GitHub Refresher**

For this course, you do **not** need to be an expert with Git, but its use is encouraged. The video below gives an overview of Git for researchers, but any Git video/tutorial should be enough. Basic usage needed for the course will be covered during the first workshop.

[![Git and GitHub refresher](https://img.youtube.com/vi/CuOmaUS1FnM/0.jpg)](https://youtu.be/CuOmaUS1FnM)

## Assignments

1. Week 1 - Getting Started with Julia: Workflow and Setup - [click here](https://classroom.github.com/a/3bYk2x83)
2. Week 2 - Profiling and Optimisation - [click here](https://classroom.github.com/a/HFbbhcO1) 
3. Week 3 - Multithreading
4. Week 4 - Multiprocessing
5. Week 5 - GPU Programming


## Computing Resources

During this course, you should be able to do everything on your own personal machine. I would advise trying to run some code on your local cluster as well if you have access. However, not everybody has access to a GPU, and specifically during part of the course, you will need access to a modern NVIDIA GPU. If you have access to your local institution's HPC already, but do not have GPU access, you can ask your local admin to give you a small number of GPU hours (around 20 should be more than enough).

Another option is to use Google Colab which has free access to GPU resources for testing. There is also a cheap paid option for better access. The [notebook linked here](https://colab.research.google.com/github/ageron/julia_notebooks/blob/master/Julia_Colab_Notebook_Template.ipynb) has instructions for how to setup Julia and CUDA. This is the easiest way to get started.

If you are from UoN and are struggling to access GPUs, contact [myself](mailto:jamie.mair@nottingham.ac.uk) to see if we can arrange temporary access to our in-house Physics cluster. Access to this cluster **cannot** be guaranteed, and we advise students to use this as a last resort.

## Lecture Slides & Recordings (2023)

### (1/10) Hardware & Software Basics
[Lecture Slides](/assets/slides/session_1.pdf)
[![HPC in Julia (1/10) Lecture Video](https://img.youtube.com/vi/Y1W-PrIaPJ4/0.jpg)](https://youtu.be/Y1W-PrIaPJ4)

### (2/10) SIMD & The Stack and the Heap
[Lecture Slides](/assets/slides/session_2.pdf)
[![HPC in Julia (2/10) Lecture Video](https://img.youtube.com/vi/YQ6fnFCVa9E/0.jpg)](https://youtu.be/YQ6fnFCVa9E)

#### Errata
- Final operator in the stack example should evaluate as a `-` instead of a `+`.

### (3/10) Measuring Performance & Optimisation
[Lecture Slides](/assets/slides/session_3.pdf)
[![HPC in Julia (3/10) Lecture Video](https://img.youtube.com/vi/EbI49BPcOEs/0.jpg)](https://youtu.be/EbI49BPcOEs)

### (4/10) Optimisation & Type Safety
**Code Repository:**

[https://github.com/JamieMair/MPAGS\_Slides\_Examples](https://github.com/JamieMair/MPAGS_Slides_Examples)

[Lecture Slides](/assets/slides/session_4.pdf)
[![HPC in Julia (4/10) Lecture Video](https://img.youtube.com/vi/wrrmWpZLAS4/0.jpg)](https://youtu.be/wrrmWpZLAS4)