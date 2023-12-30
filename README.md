# Neural Dream Research

![Image](https://github.com/NeuralDreamResearch/NeuralDream/blob/main/NeuralDream%20-%20logo.png?raw=true)

Neural Dream Research is a private research organization dedicated to the exploration of computational systems and artificial intelligence. Our mission is to design novel hardware accelerators and efficiently utilize them to create the next generation of AI. We are at the forefront of technological advancements, pushing the boundaries of what is possible in the realm of computation and artificial intelligence.

### Compute Infrastructure
   Neural Dream Research requires immense computational power for rapid development and testing. This is our current infrastructure handles tasks.
#### Main Workstation:
- This computer includes Ryzen 5 5600 + 48 GB DDR4 3333 MT/s OC + **RTX 3070 + RTX 2080** + HD 4650
- Triple GPU provides less memory usage on compute-dedicated GPUs. HD 4650 is allocated for display tasks and RTX 3070 is for computational workloads
#### Nvidia Jetson Nano
- This computer is for deploying inference engines on the line.
- Tegra model provides unified memory for both CPU and GPU
#### FPGAs & SoC
- FPGA's are the most recently adopted compute units of our infrastructure. They provide very low latency computation on some tasks.
- FPGA's provides test&development environment model for new algorithms and architectures

## Milestones
### 1-) [Image Upsampling](https://github.com/NeuralDreamResearch/ImageUpsampling)
📅 13 July 2023

Image upsampling model upsample images from 1080p to 4K resolution. The model was trained on only 1 image and can deliver substantial performance.

### 2-) [Digital Soul - Core Pre-Release](https://github.com/NeuralDreamResearch/DigitalSoul)
📅 11 November 2023

Unified platform for CPU, GPU, FPGA and Quantum Computation. First pre-release includes basic utilities for LookUp Table computation and basic quantum simulation utilities
