<h1 align="center">Hi, I'm Ritesh Doijode 👋</h1>

<div align="center">
  <img src="https://readme-typing-svg.herokuapp.com/?lines=Robotics+%26+Physical+AI+Engineer;Autonomous+Systems+Researcher;Robot+Perception+%26+Sensor+Fusion;Embedded+Intelligence&font=Fira%20Code&center=true&width=560&height=45&color=f75c7e&vCenter=true&size=22" alt="Robotics and Physical AI Engineer">
</div>

<p align="center">
  <a href="https://sites.google.com/view/riteshdoijode/home"><img src="https://img.shields.io/badge/Portfolio-4285F4?style=for-the-badge&logo=googlechrome&logoColor=white" alt="Portfolio"></a>
  <a href="https://www.linkedin.com/in/riteshdoijode"><img src="https://img.shields.io/badge/LinkedIn-0077B5?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn"></a>
  <a href="mailto:riteshdoijode@nyu.edu"><img src="https://img.shields.io/badge/Email-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email"></a>
  <a href="https://github.com/riteshdoijode"><img src="https://img.shields.io/badge/GitHub-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub"></a>
</p>

## 🚀 About Me

```javascript
const ritesh = {
  location: "New York, USA",
  education: {
    masters: "MS in Mechatronics and Robotics - New York University",
    bachelors: "B.E. in Mechatronics Engineering (Minor: AI) - AIT"
  },
  workExperience: [
    "Graduate Research Assistant @ NYU Center for Robotics and Embodied Intelligence (Prema Lab)",
    "Graduate Research Assistant @ NYU Langone Health (Lin Lab)",
    "Physical AI Data and RL Intern @ Telemety AI",
    "Computer Vision Research Engineer @ NYU Robomaster Ultraviolet"
  ],
  interests: ["Physical AI", "Autonomous Systems", "Robot Perception", "Sensor Fusion", "Embedded Intelligence", "Multi-Agent Robotics"],
  currentFocus: "Building intelligent robotic systems that combine perception, localization, embedded hardware, and agentic AI."
};
```

## 🎓 Education

<div align="center">
  <table>
    <tr>
      <td align="center"><img src="https://img.shields.io/badge/NYU-5B2C6F?style=for-the-badge" alt="NYU"></td>
      <td><b>Master of Science, Mechatronics and Robotics</b><br>New York University, New York, USA<br><i>Recipient of Merit-based Scholarship</i> • Sept 2025 - Present<br><i>Relevant Coursework: Robot Perception, Advanced Mechatronics, Robot Gait and Manipulation, Robot Localization &amp; Navigation, Mathematics for Robotics, Reinforcement Learning &amp; Optimal Control for Autonomous Systems</i></td>
    </tr>
    <tr>
      <td align="center"><img src="https://img.shields.io/badge/AIT-E74C3C?style=for-the-badge" alt="AIT"></td>
      <td><b>Bachelor of Engineering, Mechatronics Engineering</b><br>Acharya Institute of Technology, Bangalore, India<br><i>Minor: Artificial Intelligence</i> • Jan 2022 - May 2024</td>
    </tr>
  </table>
</div>

## 🔄 Current Focus

I'm currently building robots that see, localize, and reason on their own:

- 🦾 **Robot Manipulation & Agentic AI**: Automating a UR5e fin test cycle with stereo-camera SLAM, V-JEPA, and Whisper voice control, plus offline LLM agents that monitor experiments and a retrieval-indexed shared memory for multi-agent systems.
- 🧠 **Computer Vision for Lab Automation**: Building a CV pipeline for automated behavioral experiments on YOLO26n, chosen after testing VideoMAE, DINOv3, and V-JEPA, and training it on custom CVAT datasets.
- ⚡ **Embedded Firmware**: Writing nRF52840 firmware for a wireless photometry device that runs a 200 Hz BMI270 IMU and streams IMU and optical data over Bluetooth to a live web dashboard.
- 🛰️ **Spacecraft Control & Space Robotics**: Designing gain-scheduled LQR and constrained MPC controllers for asteroid proximity operations, and simulating a robotic boulder capture in MuJoCo.

## 💼 Work Experience

<details open>
  <summary><b>Graduate Research Assistant - NYU Center for Robotics and Embodied Intelligence (Prema Lab)</b> [Sept 2026 - Present]</summary>
  <ul>
    <li>Programmed a UR5e 6-axis industrial robot arm for an automated fin test cycle, fusing stereo-camera SLAM with the V-JEPA video foundation model and a Whisper speech-recognition layer for voice automation at 50 ms latency.</li>
    <li>Developed an offline LLM monitoring agent using OpenClaw that watches experiment telemetry without cloud dependency and flags failed or invalid trials with 94% accuracy over 100 runs.</li>
    <li>Prototyping a retrieval-indexed shared memory layer for multi-agent selection that reduces per-query token usage by 40% compared with markdown or JSONL files.</li>
  </ul>
</details>

<details open>
  <summary><b>Graduate Research Assistant - NYU Langone Health (Lin Lab)</b> [Feb 2026 - Present]</summary>
  <ul>
    <li>Developed embedded firmware for a wireless photometry device on a custom PCB, synchronizing IMU odometry and optical sensor data over Bluetooth to a USB-CDC receiver that broadcasts live on a web dashboard.</li>
    <li>Programmed a Nordic nRF52840 MCU to drive a BMI270 6-DOF IMU at 200 Hz with a Madgwick filter, restored individual control of 16 channels across 4 daisy-chained DACs without a PCB redesign, and implemented a 96-bit SPI driver.</li>
    <li>Building a CV pipeline for automated lab experiments on YOLO26n, selected after testing the VideoMAE, DINOv3, and V-JEPA video foundation models, and labeling custom datasets on CVAT to train it.</li>
  </ul>
</details>

<details>
  <summary><b>Physical AI Data and RL Intern - Telemety AI</b> [Jun 2026 - Aug 2026]</summary>
  <ul>
    <li>Engineered a real-time visual-inertial SLAM backbone on an NVIDIA Jetson AGX Orin using dual stereo cameras and cuVSLAM, achieving 10 cm loop-closure accuracy indoors and 100 cm outdoors across 4 city blocks of field testing in Manhattan.</li>
    <li>Designed a multi-sensor localization architecture fusing visual-inertial odometry, LiDAR-inertial odometry, and PPS-disciplined GNSS-RTK as an outdoor anchor, enabling drift-free indoor/outdoor transitions for an in-house wearable motion-capture suit; improved odometry with Allan-variance IMU calibration and camera intrinsic/extrinsic calibration.</li>
    <li>Built a monocular traversability-estimation pipeline for pedestrian path prediction, deriving heading and pose from action-camera footage and its IMU metadata with ORB-SLAM3.</li>
  </ul>
</details>

<details>
  <summary><b>Computer Vision Research Engineer - Robomaster Ultraviolet (NYU)</b> [Apr 2025 - Aug 2026]</summary>
  <ul>
    <li>Developed a Linear Kalman Filter-based prediction model for real-time target tracking, contributing to localization and sensor-fusion accuracy within a ROS2 robotics pipeline.</li>
    <li>Consolidated two ROS2 node launch configurations into a single parameterized launch file, eliminating manual orchestration and reducing onboarding time for new developers by 50%.</li>
    <li>Improved deployment infrastructure by composing a multi-stage Docker container for NVIDIA Jetson and developing a custom CLI for streamlined project deployment.</li>
  </ul>
</details>

<details>
  <summary><b>Operations Manager - Eventsliner</b> [Jun 2024 - Dec 2024]</summary>
  <ul>
    <li>Led the deployment of a machine-learning-based content-recommendation algorithm.</li>
    <li>Implemented automated onboarding and user-management workflows using n8n and Zapier, and built structured data catalogs of user interests and activity patterns.</li>
  </ul>
</details>

## 🛠️ Skills & Competencies

<div align="center">
  <h3>Programming & Hardware Integration</h3>
  <img src="https://img.shields.io/badge/C++-00599C?style=for-the-badge&logo=cplusplus&logoColor=white" alt="C++">
  <img src="https://img.shields.io/badge/Python-3776AB?style=for-the-badge&logo=python&logoColor=white" alt="Python">
  <img src="https://img.shields.io/badge/C%23-239120?style=for-the-badge" alt="C#">
  <img src="https://img.shields.io/badge/CUDA-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="CUDA">
  <img src="https://img.shields.io/badge/Bash-121011?style=for-the-badge&logo=gnubash&logoColor=white" alt="Bash">
  <img src="https://img.shields.io/badge/Arduino-00979D?style=for-the-badge&logo=arduino&logoColor=white" alt="Arduino">
  <img src="https://img.shields.io/badge/ESP32-E7352C?style=for-the-badge&logo=espressif&logoColor=white" alt="ESP32">
  <img src="https://img.shields.io/badge/nRF52840-00A9CE?style=for-the-badge&logo=nordicsemiconductor&logoColor=white" alt="nRF52840">
  <img src="https://img.shields.io/badge/Raspberry_Pi-A22846?style=for-the-badge&logo=raspberrypi&logoColor=white" alt="Raspberry Pi">

  <h3>AI, Machine Learning & Computer Vision</h3>
  <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=for-the-badge&logo=pytorch&logoColor=white" alt="PyTorch">
  <img src="https://img.shields.io/badge/TensorFlow-FF6F00?style=for-the-badge&logo=tensorflow&logoColor=white" alt="TensorFlow">
  <img src="https://img.shields.io/badge/Keras-D00000?style=for-the-badge&logo=keras&logoColor=white" alt="Keras">
  <img src="https://img.shields.io/badge/OpenCV-5C3EE8?style=for-the-badge&logo=opencv&logoColor=white" alt="OpenCV">
  <img src="https://img.shields.io/badge/NumPy-013243?style=for-the-badge&logo=numpy&logoColor=white" alt="NumPy">
  <img src="https://img.shields.io/badge/Pandas-150458?style=for-the-badge&logo=pandas&logoColor=white" alt="Pandas">
  <img src="https://img.shields.io/badge/SciPy-8CAAE6?style=for-the-badge&logo=scipy&logoColor=white" alt="SciPy">
  <img src="https://img.shields.io/badge/YOLO-111F68?style=for-the-badge" alt="YOLO">
  <img src="https://img.shields.io/badge/Hugging_Face-FFD21E?style=for-the-badge&logo=huggingface&logoColor=black" alt="Hugging Face">
  <img src="https://img.shields.io/badge/LangChain-1C3C3C?style=for-the-badge&logo=langchain&logoColor=white" alt="LangChain">
  <img src="https://img.shields.io/badge/Ollama-000000?style=for-the-badge&logo=ollama&logoColor=white" alt="Ollama">

  <h3>Robotics, Simulation & DevOps</h3>
  <img src="https://img.shields.io/badge/ROS2-22314E?style=for-the-badge&logo=ros&logoColor=white" alt="ROS2">
  <img src="https://img.shields.io/badge/SLAM-4B0082?style=for-the-badge" alt="SLAM">
  <img src="https://img.shields.io/badge/MuJoCo-000000?style=for-the-badge" alt="MuJoCo">
  <img src="https://img.shields.io/badge/Isaac_Lab-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="Isaac Lab">
  <img src="https://img.shields.io/badge/MATLAB%2FSimulink-0076A8?style=for-the-badge" alt="MATLAB/Simulink">
  <img src="https://img.shields.io/badge/SolidWorks-E32224?style=for-the-badge&logo=dassaultsystemes&logoColor=white" alt="SolidWorks">
  <img src="https://img.shields.io/badge/Docker-2496ED?style=for-the-badge&logo=docker&logoColor=white" alt="Docker">
  <img src="https://img.shields.io/badge/NVIDIA_Jetson-76B900?style=for-the-badge&logo=nvidia&logoColor=white" alt="NVIDIA Jetson">
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" alt="Git">
  <img src="https://img.shields.io/badge/Linux-FCC624?style=for-the-badge&logo=linux&logoColor=black" alt="Linux">
</div>

## 🚀 Featured Projects

### Autonomous Robot Navigation and Localization
A distributed multi-robot control system for real-time offline robot localization and cooperative formation control (NYU, guided by Prof. Vikram Kapila).
- **Tech Highlights:** Extended Kalman Filter state estimation fusing Ultra-Wide-Band transceivers, IMU odometry, and wheel odometry, with inter-robot sharing of heading, velocity, and position over ESP32 MCUs.
- **Impact:** Achieved 5 cm positioning and loop-closure precision, improved pose-estimation accuracy by 40%, and reached the desired robot formation 25% faster during cooperative motion.

### [Enhanced Gravity Tractor: LQR-MPC Spacecraft Control and Robotic Boulder Capture](https://github.com/riteshdoijode/enhanced_gravity_tractor)
An autonomous spacecraft that descends to asteroid Bennu, captures a 20-tonne boulder with a robotic arm, and uses the added mass as a gravity tractor to steer Bennu's orbit, all in a physics simulator built from first principles (NYU Autonomous Space Robotics, guided by Prof. Benjamin Riviere).
- **Tech Highlights:** Gain-scheduled LQR and constrained MPC (cvxpy, 30-step horizon, ~5 ms per solve), a 10-state EKF fusing LIDAR range and camera bearings, computed-torque arm control in MuJoCo, and N-body plus polyhedron gravity models compiled with numba.
- **Impact:** The MPC settled 2× faster than LQR (1.8 h vs 3.7 h) with 2.6× lower cost and 7% less Δv; the descent ended within 0.13 m of the grasp point, the arm lifted the 20 t boulder 4.6 m with 4 cm grip slip, and the simulator propagates Bennu within JPL's 3σ uncertainty over 110 years, checked by a 130-test validation suite.

### Self-Balancing Robot (Inverted Pendulum)
An autonomous single-stage self-balancing inverted pendulum with a custom control algorithm designed from scratch (NYU, guided by Prof. Nicolas Chbat).
- **Tech Highlights:** Mechatronic system modeling, 3D CAD design, and MATLAB/Simulink real-time tuning on Arduino for hardware-software integration.
- **Impact:** Improved balance accuracy and response time through iterative controller optimization.

## 🏆 Publications & Achievements

- **Publication:** [*Design and Development of Sign-Language Glove*](https://drive.google.com/file/d/16Bfoa6cpV9FWMf4V2fjE3EGkHYfQtn-E/view?usp=drive_link), a prototype of an AI-integrated sign-language glove - IEEE International Conference on Advanced Intelligent Mechatronics (AIM 2023)
- **Award:** Recipient of the Merit-based Scholarship at New York University.

## 🤝 Let's Connect

<div align="center">
  <a href="https://www.linkedin.com/in/riteshdoijode">
    <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn">
  </a>
  <a href="mailto:riteshdoijode@nyu.edu">
    <img src="https://img.shields.io/badge/Email-Contact-D14836?style=for-the-badge&logo=gmail&logoColor=white" alt="Email">
  </a>
  <a href="https://github.com/riteshdoijode">
    <img src="https://img.shields.io/badge/GitHub-Follow-181717?style=for-the-badge&logo=github&logoColor=white" alt="GitHub">
  </a>
</div>

<div align="center">
  <p>I'm always eager to collaborate on robotics, physical AI, computer vision, autonomous systems, and embedded-intelligence projects. Feel free to reach out!</p>
</div>
