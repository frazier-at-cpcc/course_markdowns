# Scaling CUDA C++ Applications to Multiple Nodes

**Product ID**: 34487
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: SCCAMN
**Vendor Code**: NV
**Vendor Name**: Nvidia
**URL**: [Course Link](https://www.fastlaneus.com/course/nv-sccamn)

## Objective
By participating in this workshop, you’ll:



- Learn several methods for writing multi-GPU CUDA C++ applications
- Use a variety of multi-GPU communication patterns and understand their tradeoffs
- Write portable, scalable CUDA code with the single-program multiple-data (SPMD) paradigm using CUDA-aware MPI and NVSHMEM
- Improve multi-GPU SPMD code with NVSHMEM’s symmetric memory model and its ability to perform GPU-initiated data transfers
- Get practice with common multi-GPU coding paradigms like domain decomposition and halo exchanges

## Essentials
Intermediate experience writing CUDA C/C++ applications.

Suggested materials to satisfy the prerequisites:



- Fundamentals of Accelerated Computing with CUDA C/C++
- Accelerating CUDA C++ Applications with Multiple GPUs
- Accelerating CUDA C++ Applications with Concurrent Streams
- Scaling Workloads Across Multiple GPUs with CUDA C++

## Audience
nan

## Outline
Introduction	



- Meet the instructor.
- Create an account at courses.nvidia.com/join
Multi-GPU Programming Paradigms	



- Survey multiple techniques for programming CUDA C++ applications for multiple GPUs using a Monte-Carlo approximation of pi CUDA C++ program.
- Use CUDA to utilize multiple GPUs.
- Learn how to enable and use direct peer-to-peer memory communication.
- Write an SPMD version with CUDA-aware MPI.
Introduction to NVSHMEM	



- Learn how to write code with NVSHMEM and understand its symmetric memory model.
- Use NVSHMEM to write SPMD code for multiple GPUs.
- Utilize symmetric memory to let all GPUs access data on other GPUs.
- Make GPU-initiated memory transfers.
Halo Exchanges with NVSHMEM	



- Practice common coding motifs like halo exchanges and domain decomposition using NVSHMEM, and work on the assessment.
- Write an NVSHMEM implementation of a Laplace equation Jacobi solver.
- Refactor a single GPU 1D wave equation solver with NVSHMEM.
- Complete the assessment and earn a certificate.
Final Review	



- Learn about application tradeoffs on GPU clusters.
- Review key learnings and answer questions.
- Complete the workshop survey.

## Summary
Present-day high-performance computing (HPC) and deep learning applications benefit from, and even require, cluster-scale GPU compute power. Writing CUDA applications that can correctly and efficiently utilize GPUs across a cluster requires a distinct set of skills. In this workshop, you’ll learn the tools and techniques needed to write CUDA C++ applications that can scale efficiently to clusters of NVIDIA GPUs.

Please note that once a booking has been confirmed, it is non-refundable. This means that after you have confirmed your seat for an event, it cannot be cancelled and no refund will be issued, regardless of attendance.

## Course Duration
1 day

## Last Changed
2024-10-03T12:43:51.000Z
