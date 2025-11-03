# <img src="https://raw.githubusercontent.com/ABSphreak/ABSphreak/master/gifs/Hi.gif" width="30px"> Hey, I'm Aaron Mano Cherian

## 🎯 About Me

I'm a hardware-software engineer obsessed with making AI faster, smaller, and smarter. My work lives at the intersection of **custom silicon design**, **neural network optimization**, and **edge computing**—basically, I'm trying to put datacenter-level intelligence into devices that fit in your pocket.

Currently designing **SoC architectures for language model acceleration** and building **GPU-accelerated decoders for 6G wireless systems** at Columbia. Previously published research at IEEE conferences on self-healing sensor networks and AI-powered chess engines.

```python
current_focus = {
    "hardware": "Synthesizable accelerators for BERT-Tiny in SystemC",
    "wireless": "LDPC decoders optimized for low-SNR 6G systems",
    "research": "Pushing the boundaries of TinyML and edge intelligence"
}
```

**Quick Facts:**
- 🔬 Published 2 papers at IEEE conferences (ESCI, CONECCT)
- 🏆 Chancellor's Special Achiever Award recipient
- 🎓 9.31/10 GPA from VIT with IoT specialization
- 🗽 Graduate student @ Columbia representing 6000+ students
- 🎤 Former President of 1800-member Model UN Society

---

## 🛠️ Tech Stack

### Hardware & RTL Design
![Verilog](https://img.shields.io/badge/-Verilog-8B4513?style=flat-square&logo=v&logoColor=white)
![SystemC](https://img.shields.io/badge/-SystemC-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![SystemVerilog](https://img.shields.io/badge/-SystemVerilog-1E88E5?style=flat-square&logo=v&logoColor=white)
![FPGA](https://img.shields.io/badge/-FPGA-E60000?style=flat-square)

### Parallel Computing
![CUDA](https://img.shields.io/badge/-CUDA-76B900?style=flat-square&logo=nvidia&logoColor=white)
![OpenCL](https://img.shields.io/badge/-OpenCL-FF6F00?style=flat-square)
![PyCUDA](https://img.shields.io/badge/-PyCUDA-79B900?style=flat-square)

### Languages
![C](https://img.shields.io/badge/-C-A8B9CC?style=flat-square&logo=c&logoColor=black)
![C++](https://img.shields.io/badge/-C++-00599C?style=flat-square&logo=c%2B%2B&logoColor=white)
![Python](https://img.shields.io/badge/-Python-3776AB?style=flat-square&logo=python&logoColor=white)
![Java](https://img.shields.io/badge/-Java-007396?style=flat-square&logo=java&logoColor=white)
![MATLAB](https://img.shields.io/badge/-MATLAB-0076A8?style=flat-square&logo=mathworks&logoColor=white)

### AI/ML Frameworks
![PyTorch](https://img.shields.io/badge/-PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white)
![TensorFlow](https://img.shields.io/badge/-TensorFlow-FF6F00?style=flat-square&logo=tensorflow&logoColor=white)
![TinyML](https://img.shields.io/badge/-TinyML-00979D?style=flat-square)

### Embedded & IoT
![Arduino](https://img.shields.io/badge/-Arduino-00979D?style=flat-square&logo=arduino&logoColor=white)
![RTOS](https://img.shields.io/badge/-RTOS-009639?style=flat-square)
![LoRa](https://img.shields.io/badge/-LoRa-00A8E1?style=flat-square)
![BLE](https://img.shields.io/badge/-BLE-0082FC?style=flat-square&logo=bluetooth&logoColor=white)

### Cloud & DevOps
![AWS](https://img.shields.io/badge/-AWS-232F3E?style=flat-square&logo=amazon-aws&logoColor=white)
![GCP](https://img.shields.io/badge/-GCP-4285F4?style=flat-square&logo=google-cloud&logoColor=white)
![Docker](https://img.shields.io/badge/-Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Kubernetes](https://img.shields.io/badge/-Kubernetes-326CE5?style=flat-square&logo=kubernetes&logoColor=white)

---



```verilog
module passionate_engineer (
    input  wire clk,
    input  wire [7:0] curiosity,
    output reg  innovation,
    output reg  impact
);

always @(posedge clk) begin
    if (curiosity > 0) begin
        innovation <= 1'b1;
        impact <= innovation & curiosity[7];
    end
end

endmodule // Where hardware meets intelligence
```

<div align="center">

[![LinkedIn](https://img.shields.io/badge/-LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](your-linkedin)
[![Email](https://img.shields.io/badge/-Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white)](mailto:aaron.cherian@columbia.edu)
[![Portfolio](https://img.shields.io/badge/-Portfolio-000000?style=for-the-badge&logo=safari&logoColor=white)](your-website)

**MS Computer Engineering @ Columbia University**

*Architecting the future of hardware-accelerated AI*

![Profile Views](https://komarev.com/ghpvc/?username=YOUR_USERNAME&color=blueviolet&style=flat-square)

</div>

---


## 🔥 What I'm Working On

### 🔬 Current Research

**BERT-Tiny Hardware Accelerator** • *SystemC*
> Designing a fully synthesizable SoC for transformer inference. Building custom silicon for all 11 layers including multi-head attention, feed-forward networks, and GELU activation. Making language models fast enough for edge deployment.

**GPU-Accelerated LDPC Decoder** • *PyCUDA*
> Leveraging massive parallelism for real-time signal processing in 6G wireless systems. Optimizing bit error rates in low-SNR scenarios where traditional decoders struggle.

---

## 📚 Research Highlights

### Self-Healing IoT Sensor Networks
*IEEE ESCI Conference • Led team of 4*

Developed a re-tasking algorithm that enables autonomous fault recovery in structural health monitoring systems. Achieved 85-95% detection accuracy with response times under 400ms—comparable to FTMR and reinforcement learning approaches but with significantly lower overhead.

### Neural Chess Engine with NNUE
*IEEE CONECCT @ IISc*

Built an AI-powered chess engine using Efficiently Updatable Neural Networks and Nega-Max search that performs comparably to StockFish v16. Optimized evaluation function achieves near-perfect move selection with minimal computational cost.

---

## 💡 Featured Projects

**Cross-Modal Knowledge Distillation** → 92.3% accuracy, 83% memory reduction, 9.3ms inference
- Compressed teacher models to ultra-lightweight student networks deployable on edge devices
- Dynamic resource allocation and modality-specific compression techniques

**Hospital-Acquired Infection Prevention** → Joint project with Christian Medical College
- Intelligent positioning system using Bowyer-Watson triangulation and BLE wearables
- Ensemble boosted decision trees for predictive infection risk analysis

**EEG Emotion Recognition** → 89% valence-arousal prediction accuracy
- Hybrid deep learning: Stacked autoencoders + LSTM for temporal sequence learning
- Outperformed baseline SVM and standalone LSTM models on DEAP dataset

---

## 🎯 Areas of Expertise

<table>
<tr>
<td valign="top" width="33%">

### ⚡ Hardware Design
- SoC Architecture
- ASIC/FPGA Development
- Hardware Accelerators
- Formal Verification
- RTL Design

</td>
<td valign="top" width="33%">

### 🤖 AI/ML on Edge
- TinyML & Model Compression
- Neural Architecture Search
- Knowledge Distillation
- Quantization & Pruning
- ML on FPGA

</td>
<td valign="top" width="33%">

### 🔌 Embedded Systems
- RTOS Development
- IoT Protocol Design
- Sensor Networks
- Wearable Computing
- Edge Computing

</td>
</tr>
</table>

---

## 📊 GitHub Stats

<div align="center">

![GitHub Stats](https://github-readme-stats.vercel.app/api?username=YOUR_USERNAME&show_icons=true&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&icon_color=1F6FEB&text_color=C9D1D9)

![Top Languages](https://github-readme-stats.vercel.app/api/top-langs/?username=YOUR_USERNAME&layout=compact&theme=tokyonight&hide_border=true&bg_color=0D1117&title_color=58A6FF&text_color=C9D1D9)

</div>

---

## 🌟 Leadership & Impact

**Engineering Graduate Student Council** → Department Representative at Columbia
- Representing Electrical Engineering department for 6000+ graduate students
- Contributing to academic policy and curriculum development

**VIT Model United Nations** → President (2023-2025)
- Led 1800-member organization with 800% participation growth
- Coordinated multiple conferences with 40+ Under Secretary Generals

**IEEE ic-ETITE 2024** → Chief Coordinator
- Managed team of 117 coordinators across 3-day international conference
- Oversaw 367 paper presentations, 15 keynote speakers, and Bolt2.0 Hackathon

---

## 📫 Let's Connect!

I'm always excited to collaborate on projects involving hardware acceleration, edge AI, or IoT systems. Whether you're building custom silicon, optimizing neural networks, or just want to geek out about computer architecture—let's talk!

<div align="center">

**aaron.cherian@columbia.edu** • **New York, NY**

[![LinkedIn](https://img.shields.io/badge/-Let's_Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white)](your-linkedin)
[![Portfolio](https://img.shields.io/badge/-View_Portfolio-000000?style=for-the-badge&logo=safari&logoColor=white)](your-website)

---

*"Making AI run at the speed of silicon"*

</div>
