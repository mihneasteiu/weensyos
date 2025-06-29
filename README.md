# WeensyOS: Virtual Memory and Process Management

This repository contains my implementation of **WeensyOS**, a small educational operating system project focused on virtual memory and process management. It was developed as part of the **[CSCI 0300 (Fundamentals of Computer Systems)](https://csci0300.github.io)** course at Brown University. The project covers virtual memory, kernel/user privilege separation, process isolation, and system calls like `fork` and `exit`. You can find more information about the project [here](https://csci0300.github.io/assign/projects/project4.html).

---

## Project Overview

WeensyOS runs on x86-64 architecture (emulated by QEMU) and supports:

- Virtual memory management with page tables.
- Kernel isolation from user processes.
- Independent process address spaces.
- Dynamic virtual page allocation.
- Process creation (`fork`) and termination (`exit`).

### Technical Highlights

- Implemented kernel vs. user privilege separation to protect kernel memory.
- Designed isolated page tables for each process to prevent interference.
- Enabled flexible virtual-to-physical memory mapping for efficient memory use.
- Developed system calls for process lifecycle management.
- Used QEMU for emulation and testing.

---

## Note
To comply with Brown’s academic code, this repository does not include the source code. If you are a potential employer and would like access to my implementation, please contact me at **mihnea_steiu@brown.edu**.
