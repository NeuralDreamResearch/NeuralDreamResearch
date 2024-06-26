# Neural Dream Research

![Image](https://github.com/NeuralDreamResearch/NeuralDream/blob/main/NeuralDream%20-%20logo.png?raw=true)

Neural Dream Research is a private research organization dedicated to the exploration of computational systems and intelligence. Our mission is to design novel hardware accelerators and efficiently utilize them to create the next generation of AI. We are at the forefront of technological advancements, pushing the boundaries of what is possible in the realm of computation and artificial intelligence.


## Milestones
### 1-) [Image Upsampling](https://github.com/NeuralDreamResearch/ImageUpsampling)
📅 13 July 2023

Image upsampling model upsample images from 1080p to 4K resolution. The model was trained on only 1 image and can deliver substantial performance.

### 2-) [Digital Soul - Cuda-backend Pre-Release](https://github.com/NeuralDreamResearch/DigitalSoulCuda)
📅 11 November 2023

Unified platform for CPU, GPU, FPGA and Quantum Computation. First pre-release includes basic utilities for LookUp Table computation and basic quantum simulation utilities

### 3-) [Starknet Airdrop Received](https://www.starknet.io/en/content/starknet-provisions-program)
📅 20 February 2024

Starknet Foundation distributed 700 M STRK. Neural Dream Research's founder and owner of Ali Hakim Taşkıran received 111.1 STRK by contributing at least 3 times to non-crypto top 5000 open source projects. We are especially thankful to Starknet Foundation. This also incentivized us to develop web3 enhanced HPC and AI applications on top of Starknet blockchain.

### 4-) [Digital Soul - Python Edition Pre-Release](https://github.com/NeuralDreamResearch/DigitalSoul)
📅 12 March 2024

<img src="https://github.com/NeuralDreamResearch/DigitalSoulPy/blob/main/Logo.jpeg?raw=true" height=100>
Digital Soul is now migrated into Python. New version of Digital Soul uses numpy, cupy and tensorflow as backend; implements vhdl transpiler and quantum simulator in itself. Pre-release includes generic computational graph and implementation of logical functions. The library is able to expand by defining computational functions on nodes.

<hr>

## Compute Infrastructure
   Neural Dream Research requires immense computational power for rapid development and testing. This is our current infrastructure handles tasks.
### Main Workstation:
- This computer includes Ryzen 5 5600 + 64 GB DDR4 3333 MT/s OC + **2xRTX 3070 + RTX 2080**
- Triple GPU provides less memory usage on compute-dedicated GPUs. RTX 2080 is allocated for display tasks and 2xRTX 3070s is for computational workloads
### Nvidia Jetson Nano
- This computer is for deploying inference engines on the line.
- Tegra model provides unified memory for both CPU and GPU
### FPGAs & SoC
- FPGA's are the most recently adopted compute units of our infrastructure. They provide very low latency computation on some tasks.
- FPGA's provides test&development environment model for new algorithms and architectures

