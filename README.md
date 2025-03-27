# RobotMaker01
A project to try make robot

# 🤖 Robot Project Overview

This project aims to build an intelligent robot equipped with vision, hearing, and motion capabilities. It will integrate both hardware and software components for perception, interaction, and movement, leveraging modern AI models and microcontrollers.

---

## 🔍 Capabilities & Features

### 👁️ Vision System

**Software:**
- **Face Recognition**  
  - Identifies individuals (name, age, gender, emotion)  
  - Stores profiles for future recognition
- **Object Detection**  
  - Detects and avoids obstacles in real-time

**Hardware:**
- Camera (USB or CSI, depending on setup)

---

### 👂 Hearing System

**Software:**
- **STT (Speech-to-Text)**  
  - Converts human speech into text
- **TTS (Text-to-Speech)** *(Optional)*  
  - Converts text responses into spoken words

**Hardware:**
- Microphone Array (for clear voice input and direction detection)
- Speaker (for audio output)

---

### 🧠 Understanding & Interaction

**Software:**
- **Text Emotion Inference (BERT)**  
  - Understands sentiment or emotion behind spoken/written commands

---

### 🦾 Motion & Control System

**Hardware:**
- Motors & Wheels
- Motor Driver (L298N)
- Arduino Board (for motor control)
- Proximity Sensors (for obstacle avoidance)
- Touch Sensors (for interaction)
- IMU (Inertial Measurement Unit) (for orientation and movement tracking)

---

### 📺 Output & Display

**Hardware:**
- OLED or LCD screen (for displaying status, emotion, or messages)

---

### 🔋 Power System

- Power Supply (battery pack + power management system)

---

## 🧰 Development Tools & Platform

- **Main Controller:** Raspberry Pi 5  
- **Operating System:** Ubuntu 22.04 / 24.04  
- **Framework:** ROS2 (Robot Operating System 2)  
- **Programming Languages:** Python, C++

---

## 🧪 Research & Implementation Tasks

- [ ] Set up face recognition with data storage
- [ ] Implement object detection and real-time obstacle avoidance
- [ ] Integrate STT and optional TTS systems
- [ ] Train or integrate a BERT-based model for emotion analysis
- [ ] Program Arduino for motor control (forward, backward, turning)
- [ ] Integrate sensors (proximity, touch, IMU)
- [ ] Design robot communication with ROS2
- [ ] Build UI for OLED/LCD display
- [ ] Power system design and safety check
