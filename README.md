# System Call for Semaphore - Chain Smoker Problem

## Project Details

- **University:** National University of Computer and Emerging Sciences (Karachi Campus)
- **School:** FAST School of Computing
- **Semester:** Fall 2023
- **Course:** System Call for Semaphore
- **Team Members:** 
  - Muhammad Tahir (21K-4503)
  - Insha Javed (21K-3279)
  - Sabika Shameel (21K-4606)
- **Department:** BSCS (4-E)

## Problem Statement

The project addresses the classic synchronization problem known as the Chain Smoker Problem using semaphores. It involves an agent and three smokers, each having an infinite supply of one smoking ingredient (matches, paper, or tobacco). The agent randomly provides two ingredients, and smokers must coordinate to make and smoke cigarettes without the agent knowing which smoker needs which ingredient.

## Objective

Implement a solution using semaphores to ensure that only one smoker can proceed to make a cigarette when the required ingredients are available, preventing deadlock and ensuring efficient resource allocation.

## Problem Complexity

The challenge lies in coordinating the actions of the agent and smokers using semaphores and condition variables to avoid race conditions and ensure mutual exclusion. Smokers must wait for both ingredients to be available before proceeding, while the agent must wait for a smoker to finish smoking before offering more ingredients.

## Methodology and Implementation

The solution involves using semaphores and condition variables in C programming language with pthreads. Smokers and the agent are implemented as separate threads, and synchronization mechanisms are employed to ensure proper sequencing of actions.

## Project Description

The project simulates a scenario where an agent continuously selects two random ingredients and offers them to smokers who possess the third ingredient required to make a cigarette. This demonstrates resource allocation and synchronization in operating system environments, akin to an OS managing resources for multiple processes.

## Conclusion

By implementing semaphores and proper synchronization techniques, the project aims to demonstrate effective management of shared resources among concurrent threads, illustrating key concepts in operating system design and synchronization.
