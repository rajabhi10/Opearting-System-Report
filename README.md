# Processes Scheduling Algorithms

## Abstract
CPU scheduling plays a crucial role in managing system resources efficiently by allocating CPU time to different processes. The effectiveness of an operating system heavily relies on the quality of its CPU scheduling algorithms. This project serves as a simulator for process scheduling, exploring the behavior of five different scheduling algorithms.

## Table of Contents
1. [Introduction](#1-introduction)
2. [Design Philosophy](#2-design-philosophy)
3. [Theoretical Overview](#3-theoretical-overview)
4. [Conclusion & Summary](#4-conclusion--summary)
5. [References](#5-references)

## 1. Introduction
Process scheduling involves the allocation of CPU time to various processes based on specific scheduling algorithms. This project examines five scheduling algorithms:
- First-Come, First-Served (FCFS) Scheduling
- Shortest-Job-First (SJF) Scheduling
- Shortest Remaining Time
- Priority Scheduling
- Round Robin (RR) Scheduling

These algorithms vary in their pre-emptive or non-pre-emptive nature and their strategies for selecting the next process to execute. Understanding these algorithms is essential for optimizing CPU utilization and enhancing system performance.

## 2. Design Philosophy
Java programming language was employed to implement the simulation of these scheduling algorithms. The program utilizes a main loop to continuously calculate and modify process values generated randomly based on user preferences. Processes are characterized by properties such as arrival time, priority, and an array of bursts (representing CPU or IO operations). The simulation involves three main queues: Jobs Queue, Ready Queue, and a list of devices for Input/Output operations. The scheduling process involves sorting the Ready queue based on the chosen algorithm and calculating parameters such as CPU utilization, throughput, turnaround time, and CPU waiting time.

## 3. Theoretical Overview
### 3.1 Choosing a Scheduling Algorithm
There is no universally "best" scheduling algorithm, and operating systems often use combinations of algorithms to suit their specific requirements. For instance, Windows XP/Vista utilizes a multilevel feedback queue, incorporating various scheduling strategies to optimize system performance and response time.

### 3.2 OS Scheduler Implementations
Operating systems employ diverse scheduling algorithms, ranging from simple round-robin to more sophisticated approaches considering process priority and processor affinity. These algorithms aim to balance resource utilization and system responsiveness.

### 3.3 Simulating Before Real Work
Simulation serves as a valuable tool for evaluating scheduling algorithms before real-world implementation. By creating virtual environments and modeling system behaviors, simulations provide insights into algorithm performance and aid in decision-making for system design and optimization.

## 4. Conclusion & Summary
Optimal CPU scheduling is critical for efficient system operation. While no single scheduling algorithm is perfect, understanding their strengths and weaknesses enables system designers to make informed decisions. Simulations play a crucial role in evaluating and comparing scheduling algorithms, facilitating the development of robust operating systems.

## 5. References
1. Operating Systems Concepts (9th edition) by Greg Gagne.
2. Operating systems lecture notes, Haldia Institute of Technology.
3. Wikipedia.
4. YouTube.
