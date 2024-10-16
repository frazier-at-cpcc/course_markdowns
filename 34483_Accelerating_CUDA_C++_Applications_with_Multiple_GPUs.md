# Accelerating CUDA C++ Applications with Multiple GPUs

**Product ID**: 34483
**Category ID**: nan
**Modality**: 6
**Active**: True
**Language**: en
**Product Code**: ACCAMG
**Vendor Code**: NV
**Vendor Name**: Nvidia
**URL**: [Course Link](https://www.fastlaneus.com/course/nv-accamg)

## Objective
- Use concurrent CUDA streams to overlap memory transfers with GPU computation
- Utilize all available GPUs on a single node to scale workloads across all available GPUs
- Combine the use of copy/compute overlap with multiple GPUs
- Rely on the NVIDIA Nsight™ Systems Visual Profiler timeline to observe improvement opportunities and the impact of the techniques covered in the workshop

## Essentials
- Professional experience programming CUDA C/C++ applications, including the use of the nvcc compiler, kernel launches, grid-stride loops, host-to-device and device-to-host memory transfers, and CUDA error handling
- Familiarity with the Linux command line
- Experience using makefiles to compile C/C++ code
Suggested resources to satisfy prerequisites: Fundamentals of Accelerated Computing with CUDA C/C++, Ubuntu Command Line for Beginners (sections 1 through 5), Makefile Tutorial (through the Simple Examples section)

## Audience
nan

## Outline
Introduction	



- Meet the instructor.
- Create an account at courses.nvidia.com/join
Using JupyterLab	



- Get familiar with your GPU-accelerated interactive JupyterLab environment.
Application Overview	



- Orient yourself with a single GPU CUDA C++ application that will be the starting point for the course.
- Observe the current performance of the single GPU CUDA C++ application using Nsight Systems.
Introduction to CUDA Streams	



- Learn the rules that govern concurrent CUDA stream behavior.
- Use multiple CUDA streams to perform concurrent host-to-device and device-to-host memory transfers.
- Utilize multiple CUDA streams for launching GPU kernels.
- Observe multiple streams in the Nsight Systems Visual Profiler timeline view.
Copy/Compute Overlap with CUDA Streams



- Learn the key concepts for effectively performing copy/compute overlap.
- Explore robust indexing strategies for the flexible use of copy/compute overlap in applications.
- Refactor the single-GPU CUDA C++ application to perform copy/compute overlap.
- See copy/compute overlap in the Nsight Systems visual profiler timeline.
Multiple GPUs with CUDA C++	



- Learn the key concepts for effectively using multiple GPUs on a single node with CUDA C++.
- Explore robust indexing strategies for the flexible use of multiple GPUs in applications.
- Refactor the single-GPU CUDA C++ application to utilize multiple GPUs.
- See multiple-GPU utilization in the Nsight Systems Visual Profiler timeline.
Copy/Compute Overlap with Multiple GPUs



- Learn the key concepts for effectively performing copy/compute overlap on multiple GPUs.
- Explore robust indexing strategies for the flexible use of copy/compute overlap on multiple GPUs.
- Refactor the single-GPU CUDA C++ application to perform copy/compute overlap on multiple GPUs.
- Observe performance benefits for copy/compute overlap on multiple GPUs.
- See copy/compute overlap on multiple GPUs in the Nsight Systems visual profiler timeline.
Course Assessment 

Final Review	



- Review key learnings.
- Learn to build your own training environment from the DLI base environment container.
- Complete the workshop survey.

## Summary
Computationally intensive CUDA C++ applications in high-performance computing, data science, bioinformatics, and deep learning can be accelerated by using multiple GPUs, which can increase throughput and/or decrease your total runtime. When combined with the concurrent overlap of computation and memory transfers, computation can be scaled across multiple GPUs without increasing the cost of memory transfers. For organizations with multi-GPU servers, whether in the cloud or on NVIDIA DGX systems, these techniques enable you to achieve peak performance from GPU-accelerated applications. And it's important to implement these single-node, multi-GPU techniques before scaling your applications across multiple nodes.

Please note that once a booking has been confirmed, it is non-refundable. This means that after you have confirmed your seat for an event, it cannot be cancelled and no refund will be issued, regardless of attendance.

## Course Duration
1 day

## Last Changed
2024-10-03T12:42:11.000Z
