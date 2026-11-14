# Exercise_5
LIFO Scheduling Algorithm Implementation 1. Introduction 

This project focuses on implementing and analyzing the LIFO (Last In, First Out) scheduling algorithm using three synchronization approaches: Semaphore, Monitor, and a Combination of Semaphore and Monitor.

LIFO is a scheduling method in which the most recently arrived process is selected for execution first.

2. Project Objectives Implementing the LIFO scheduling algorithm. Managing process synchronization. Preventing race conditions and synchronization errors. Comparing different synchronization techniques. Analyzing scheduling performance. 3. Implementation Methods 3.1 LIFO Using Semaphore 

This implementation uses semaphores to control access to shared resources and ensure mutual exclusion between processes.

3.2 LIFO Using Monitor 

This implementation uses monitors to manage process synchronization through shared data, procedures, and condition variables.

3.3 LIFO Using Semaphore and Monitor 

This approach combines semaphore and monitor mechanisms to manage synchronization and coordinate process execution.

4. Performance Metrics 

The following performance metrics are considered:

Average Waiting Time (Avg WT): Average time processes spend waiting. Turnaround Time (TAT): Total time from process arrival to completion. Response Time (RT): Time between process arrival and first execution. Blocking Time: Time spent waiting for a resource or synchronization condition. Execution Time: Total time required to execute processes. 5. Project Components Source Code Pseudocode Algorithm Flowcharts Gantt Charts Performance Tables Execution Results Comparative Analysis 6. Comparison 

The three implementations are evaluated based on synchronization correctness, process coordination, execution behavior, waiting time, and overall performance.

7. Conclusion 

This project demonstrates how the LIFO scheduling algorithm can be implemented using different synchronization mechanisms. Comparing Semaphore, Monitor, and their combination helps illustrate their differences in process management and synchronization.

