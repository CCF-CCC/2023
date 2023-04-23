---
layout: page
toc: false
title: Submission Instructions
short_title: Submission
sidebar: true
icon: fas fa-upload
order: 5
---

## Preliminary Submissions
You can optionally submit your design for the preliminary submissions (see [schedule]({% link _pages/schedule.md %})). This allows you to check that your solutions is working on our evaluation platform. 


## Requirements:

Every problem of this competition has two requirement level: basic and advanced. 
In the basic flow, a successful AIE emulation run is the only requirement. In the advanced flow, the connection with PL and host must be considered to ensure a successful hardware run on VCK5000. Following are critical components in making a kernel work on VCK5000 platform using Vitis™ Tool 2022.2:

### Basic Flow

- Development Steps
    - Prepare the AIE Kernels
    - Data Flow Graph construction
    - Setting up platform ports
    - Makefile to compile the kernel for aie simulation

The Versal® ACAP AI Engine SystemC simulator (aiesimulator) includes the modeling of the global memory (DDR memory) and the network on chip (NoC) in addition to the AI Engine array. When the application is compiled using the SystemC simulation target.

- Submission File Tree
```
├── data
│   └── input.txt
├── Makefile
└── src
    ├── aie_kernels
    │   └── fir_asym_8t_16int_vectorized.cpp
    ├── aie_kernels.h
    ├── graph.cpp
    └── graph.h
```

### Advanced Flow

- Development Steps

    - Prepare the AIE Kernels
    - Data Flow Graph construction
    - Setting up platform ports
    - Makefile to compile the kernel for aie simulation
    - Prepare the PL Kernels
    - Host code integration
    - Makefile to compile the system for hw-emulation / hw runs

- Submission File Tree

```
├── aie
│   ├── data
│   │   ├── inputa_float.txt
│   │   ├── ref_outputc_float.txt
│   ├── Makefile
│   └── src
│       ├── aie_kernels
│       ├── aie_kernels.h
│       ├── graph.cpp
│       ├── graph.h
│       └── system_settings.h
├── host
│   ├── host.cpp
│   ├── Makefile
│   └── matmult.py
├── hw_link
│   └── config.cfg
├── Makefile
└── pl
    ├── Makefile
    └── src
        ├── config.hpp
        ├── mm2s.cpp
        └── s2mm.cpp
```

### Submission Requirements

1. Prepare the files according to the submission file tree.
1. Add appropriate code comments to increase code readability.
1. Do not hardcode any file paths. 
1. Place all of your files in a single zip archive and submit it.

## Final Submission
For the final submission, follow the instructions above. In addition:

1. Submit all source files for your design, in a zip archive.
1. Your design must be available, open-source, and in working condition in order to be considered for an award. You are permitted to use publicly available closed source library, tools and IP; however, all of your work (any modifications and configurations to commercial, closed-source tools), must be accessible.

## Submission Links
TBD