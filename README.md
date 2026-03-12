# Hi there, I'm Marco W. Santoro! 🤖

I am a **Robotics Engineer** currently pursuing a Master's degree in **Intelligent and Unmanned Systems** at Poznań University of Technology. My work focuses on the intersection of custom hardware design, real-time embedded systems, and autonomous robotics.

---

### ⚙️ Technical Arsenal

<p align="left">
  <img src="https://img.shields.io/badge/C++-%2300599C.svg?style=for-the-badge&logo=c%2B%2B&logoColor=white" />
  <img src="https://img.shields.io/badge/Python-3670A0?style=for-the-badge&logo=python&logoColor=ffdd54" />
  <img src="https://img.shields.io/badge/PyTorch-%23EE4C2C.svg?style=for-the-badge&logo=PyTorch&logoColor=white" />
  <img src="https://img.shields.io/badge/STM32-03234B?style=for-the-badge&logo=stmicroelectronics&logoColor=white" />
  <img src="https://img.shields.io/badge/ROS-%230A0FF9.svg?style=for-the-badge&logo=ros&logoColor=white" />
  <img src="https://img.shields.io/badge/KiCad-314EAB?style=for-the-badge&logo=kicad&logoColor=white" />
  <img src="https://img.shields.io/badge/NVIDIA%20Isaac%20Sim-76B900?style=for-the-badge&logo=nvidia&logoColor=white" />
</p>

* **Hardware Design:** Custom multi-layer PCB development (KiCad), signal integrity, and EMI compliance.
* **Embedded Systems:** Real-time firmware (STM32/ESP32) utilizing **DMA**, hardware interrupts, and **FreeRTOS**.
* **Sensors & Protocols:** MEMS integration (IMUs, I2S Mics) via **SPI/I2S** with low-latency **TCP/IP** streaming.
* **ML/AI & Signal Processing:** Time-frequency analysis (FFT, STFT) and CNN-based autonomous fault detection.

---

### 📊 GitHub Activity
<p align="left">
  <img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Wik19&layout=compact&hide_border=true&theme=vision-friendly-dark&langs_count=6" alt="Top Languages" />
</p>

---

### 🚀 Engineering Projects

#### **[project-WAVe (B.Sc. Thesis)](https://github.com/Wik19/project-WAVe)**
*A custom wireless vibroacoustic measurement system designed for the **Flapper Nimble+** ornithopter.*

<p align="center">
  <img src="assets/WAVe_PCB.png" width="45%" alt="KiCad 3D Render" />
  <img src="assets/pcb_coin.jpg" width="45%" alt="Physical PCB with Coin for Scale" />
</p>

* **The Hardware:** Engineered a custom 4-layer PCB powered by an **ESP32-C3** to capture high-res 24-bit acoustic (I2S) and 6-DOF inertial (SPI) data.
* **Real-time Pipeline:** Optimized data throughput using **Direct Memory Access (DMA)** and dual-buffering to achieve minimal-latency TCP streaming.
* **Signal Analysis:** Built a Python client for real-time parsing and **STFT** analysis to extract flapping wing frequency signatures and harmonics.

#### **[project-AI-WAVe](https://github.com/Wik19/project-AI-WAVe)**
*End-to-end framework for UAV health monitoring using deep learning.*

* **Deep Learning Pipeline:** Implemented a **2D CNN** that achieved **~97% accuracy** in real-time propulsion system fault detection.
* **Ablation Study:** Demonstrated high model robustness by maintaining **~95% accuracy** even after a **50% reduction** in input spectral features.
* **Acoustic Fingerprinting:** Automated extraction of **MFCCs** to transform raw audio into 2D spectral feature maps.

#### **[project-pup](https://github.com/Wik19/project-pup)**
*Development of a quadruped robot dog, from CAD to NN-driven locomotion.*

<p align="center">
  <img src="assets/dog_training.gif" width="90%" alt="Isaac Sim Simulation" />
</p>

* **Mechatronics:** Fully custom mechanical design optimized for high weight-to-torque ratios using **CAD** and **3D printing**.
* **Simulation & Autonomy:** Integrating **NVIDIA Isaac Sim** and **ROS** for reinforcement learning-based locomotion training.
* **Roadmap:**
    - [x] CAD design and assembly.
    - [x] Inverse Kinematics calculation and gait patterns.
    - [ ] Implementation in Isaac Sim.
    - [ ] NN-driven joint control.
    - [ ] Partial autonomy.

---

### 🎓 Education

* **B.Eng. in Automatic Control and Robotics** | Poznań University of Technology
* **M.Sc. in Intelligent and Unmanned Systems** | Poznań University of Technology (In Progress)

---

### 📫 Connect with me

<p align="left">
  <a href="https://www.linkedin.com/in/marco-wiktor-santoro-997391252/">
    <img src="https://img.shields.io/badge/LinkedIn-%230077B5.svg?style=for-the-badge&logo=linkedin&logoColor=white" />
  </a>
  <a href="https://github.com/Wik19/Wik19/blob/main/Thesis.pdf">
    <img src="https://img.shields.io/badge/Full_Thesis-PDF-red?style=for-the-badge&logo=adobe-acrobat-reader&logoColor=white" />
  </a>
</p>