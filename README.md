# Neural Dream

![Image](https://github.com/NeuralDreamResearch/NeuralDream/blob/main/NeuralDream%20-%20logo.png?raw=true)

   We are standing at the precipice of a new frontier in artificial intelligence: one where computers not only perceive the world but also dream about it. Imagine an AI capable of replicating the stunning complexity of human dreams, generating vivid and novel scenarios without any external input. This is the vision of Neural Dream.

Our dream is as bold as it is intricate. The aim is to develop an advanced algorithm that mirrors the human brain's dreaming process, creating an AI that dreams in real-time, much like humans do. As humans, we weave together a tapestry of experiences, memories, and emotions into dreams. Neural Dream aims to emulate this in the realm of artificial intelligence, blending vast volumes of training data into unique and sometimes surreal visual narratives.

This vision of Neural Dream extends far beyond the traditional confines of generative models. Our ambition is to generate not just lifelike images, but to imbue them with a sense of emotion, narrative, and continuity. Imagine AI not only mirroring reality but also being able to simulate dreams that capture the essence of human imagination.

Neural Dream represents a paradigm shift in AI creativity, opening up unprecedented possibilities in fields such as entertainment, design, virtual reality, and even mental health. It’s not just about creating an algorithm that can mimic or remix existing visuals; it's about envisaging a future where technology can dream, abstract, and create in ways that rival human creativity.

Join us on our journey towards Neural Dream - a vision of transforming neural interactions into a captivating landscape of AI dreams. We invite you to explore the possibilities of what AI can truly achieve. Neural Dream is not a reality yet, but we believe in the potential of this vision to reshape the AI world. We're excited to share this dream with you.

### Compute Infrastructure
   Neural Dream Research requires immense computational power for rapid development and testing. This is our current infrastructure handles tasks.
#### Main Workstation:
- This computer includes Ryzen 5 5600 + 48 GB DDR4 3333 MT/s OC + **RTX 3070** + HD 4650
- Dual GPU provides less memory usage on RTX 3070. HD 4650 is allocated for display tasks and RTX 3070 is for computational workloads
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
