# Objective-C ARC Memory Leak: Unbalanced Retain/Release

This repository demonstrates a common error in Objective-C related to memory management using ARC.  Improper handling of retain/release calls, especially when dealing with strong properties and complex object graphs, can lead to subtle memory leaks that are difficult to track down.

The `bug.m` file shows the flawed code, while `bugSolution.m` presents the corrected version, highlighting best practices for using ARC.  Read the code comments for a detailed explanation of the issue and solution.

This example focuses on the memory leak scenario, but the principle extends to other ARC-related problems such as retain cycles.