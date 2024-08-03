# PintOS Projects - CS301 Operating Systems Course at IITGN

This repository contains the implementation of the first four core projects of the PintOS operating system framework as part of the CS301 Operating Systems course at IIT Gandhinagar. The projects covered include Threads, User Programs, Virtual Memory Paging, and Virtual Memory MMap.

## Project Descriptions

### 1. Threads
Implemented thread management, including basic synchronization primitives such as semaphores, locks, and condition variables. The implementation includes priority scheduling and thread synchronization.

### 2. User Programs
Extended the PintOS to support running user programs. Tasks included implementing system calls, program loading, and handling user-level exceptions.

### 3. Virtual Memory Paging
Implemented a virtual memory system with paging, including handling page faults and managing memory resources efficiently.

### 4. Virtual Memory MMap
Extended the virtual memory system to support memory-mapped files, allowing efficient file I/O through memory mapping.

## Getting Started

### Prerequisites

- Linux environment
- QEMU for emulating the x86 architecture
- GCC (GNU Compiler Collection)
- GDB (GNU Debugger)

## Reports
Detailed reports for each project can be found in the Reports folder:

- P1-Threads.pdf: Documentation and analysis for the Threads project.
- P2-User_Program.txt: Documentation for the User Program project.
- P3-VM_Paging.txt: Documentation for the Virtual Memory Paging project.
- P4-VM_Map.txt: Documentation for the Virtual Memory Mapped project.


## Project Structure

```text
.
├── Reports
│ ├── P1-Threads.pdf
│ ├── P2-User_Program.txt
│ ├── P3-VM_Paging.txt
│ └── P4-VM_Map.txt
├── src
│ ├── devices
│ ├── examples
│ ├── filesys
│ ├── lib
│ ├── misc
│ ├── tests
│ ├── threads
│ ├── userprog
│ ├── utils
│ └── vm
├── .gitignore
├── LICENSE
├── Make.config
├── Makefile
├── Makefile.build
├── Makefile.kernel
├── Makefile.userprog
└── Readme.md
