<img src="./marvin-terminal-banner.svg" alt="Hi, I'm Marvin" width="100%">

## What I'm working on

### Voice-Controlled, AI-Assisted Robotic Arm with Uncertainty-Aware Control and Adaptive Grasp Recovery

**Goal:** Develop a voice-controlled robotic arm capable of identifying and sorting previously unseen objects into freely positioned containers. The system aims to autonomously verify grasp success, recover from failures, and make reliable manipulation decisions under uncertainty.

**Planned Development:** The system will combine workspace calibration using ArUco markers, camera-based object localization, inverse kinematics, and closed-loop visual servoing. Depth-sensing approaches, including stereo vision and dedicated depth cameras, will be evaluated to improve spatial perception and grasp accuracy.

A key focus will be **adaptive grasp recovery**, combining visual feedback with servo telemetry to detect unsuccessful grasps, identify potential failure causes, and execute bounded corrective actions rather than repeatedly attempting the same movement.

**Uncertainty-Aware Control & Hard Gate:** A central objective is to develop an uncertainty-aware validation framework that evaluates positional uncertainty, sensor reliability, and motion constraints before executing AI-generated actions. An independent **hard gate** will authorize, reject, or request revalidation of proposed actions based on predefined safety constraints and uncertainty thresholds. The system will explore risk-adaptive decision-making while ensuring that uncertain or invalid commands cannot directly control the robot's actuators.

**AI Integration:** OpenAI Whisper is planned for speech recognition, while the Gemini API will support visual understanding, natural-language task interpretation, and clarification of ambiguous commands. A local web interface will provide manual control, live camera feedback, and execution monitoring.

**Software Architecture:** The software will follow a modular architecture separating perception, task planning, motion control, uncertainty assessment, and failure recovery. Hugging Face LeRobot will be evaluated for hardware integration, with ROS 2 and MoveIt considered for advanced motion planning and collision avoidance.

**Experimental Evaluation:** A central research objective is to investigate how different feedback and uncertainty-management strategies influence the reliability of autonomous robotic manipulation. Controlled experiments will compare **open-loop grasping, vision-based grasp verification, multimodal feedback with adaptive recovery, and uncertainty-aware execution gating**.

Performance will be evaluated using grasp success rates, recovery effectiveness, task completion times, positioning accuracy, and the frequency of unsafe or unsuccessful execution attempts across different objects and workspace configurations.

**Status:** Planning and hardware evaluation, with the SO-101 and SO-ARM102 under consideration.

### Magnetic bottles & auroras

**Planned approach:** Simulate charged-particle trajectories under the Lorentz force using a Boris integrator and compare selected results with a fourth-order Runge–Kutta method (RK4).

I plan to validate the simulations against analytical trajectories in a uniform magnetic field, investigate time-step convergence, and measure energy drift over long integration times. For magnetic-bottle configurations, I will vary initial speed and pitch angle and compare confinement and escape with predictions from magnetic-mirror theory.

**Focus:** Connecting physical explanations with numerical simulations, quantified numerical errors, and clear visualizations.

**Status:** Planning and simulation design.

## Experimental work - 1st place in Germany’s national Jugend testet competition 

Together with a teammate, I won first place nationally in **Jugend testet 2025**, a competition organized by **Stiftung Warentest**, Germany’s well-known independent consumer testing organization, for our investigation of kitchen paper towels.

We programmed an ESP32 microcontroller to control a motorized test arm and transmit experimental data over Wi-Fi to a Python-based system for automated data processing, statistical analysis, and visualization. This experience strengthened my interest in reproducible experiments, measurement, and the connection between hardware and data.

https://www.suedkurier.de/region/hochrhein/bad-saeckingen/ganz-schoen-pfiffig-saeckinger-schueler-holen-ersten-preis-beim-bundeswettbewerb-jugend-testet;art372588,12430724

https://www.test.de/Jugend-testet-2025-Ausgezeichnete-Talente-6223403-0/

**Code and visualizations coming soon.**

## Languages and Tools

<p>
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/python/python-original.svg" alt="Python" title="Python" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/java/java-original.svg" alt="Java" title="Java" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/cplusplus/cplusplus-original.svg" alt="C++" title="C++" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/numpy/numpy-original.svg" alt="NumPy" title="NumPy" width="40" height="40" />
  <img src="https://scipy.org/images/logo.svg" alt="SciPy" title="SciPy" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pandas/pandas-original.svg" alt="Pandas" title="Pandas" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/matplotlib/matplotlib-original.svg" alt="Matplotlib" title="Matplotlib" width="40" height="40" />
  <img src="https://seaborn.pydata.org/_static/logo-mark-lightbg.svg" alt="Seaborn" title="Seaborn" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/pytorch/pytorch-original.svg" alt="PyTorch" title="PyTorch" width="40" height="40" />
  <img src="https://huggingface.co/front/assets/huggingface_logo-noborder.svg" alt="Hugging Face Transformers" title="Hugging Face Transformers" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/arduino/arduino-original.svg" alt="Arduino" title="Arduino" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/raspberrypi/raspberrypi-original.svg" alt="Raspberry Pi" title="Raspberry Pi" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/linux/linux-original.svg" alt="Linux" title="Linux" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/ubuntu/ubuntu-original.svg" alt="Ubuntu" title="Ubuntu" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/git/git-original.svg" alt="Git" title="Git" width="40" height="40" />
  <img src="https://cdn.jsdelivr.net/gh/devicons/devicon@latest/icons/docker/docker-original.svg" alt="Docker" title="Docker" width="40" height="40" />
</p>

## How I work

I focus on substantial projects, combining theoretical understanding with implementation and testing. I aim to make my work reproducible, explain design decisions, and document both successful results and limitations.
