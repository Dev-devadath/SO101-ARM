# 🤖 SO-101: Vision-Language-Action Robot (LeRobot-Based Build)

SO-101 is a **Vision-Language-Action (VLA)** based humanoid robot prototype inspired by **[Hugging Face’s LeRobot](https://huggingface.co/lerobot)** framework.  
This project aims to explore how **language models can control real-world robots** through visual perception and natural language understanding — starting with teleoperation and gradually evolving into **autonomous VLM-driven motion**.

---

## 🎯 Project Overview

The SO-101 serves as an entry point to understand and experiment with **robot action models**, **visual grounding**, and **end-to-end VLA learning**.  
It bridges software intelligence (AI) with physical embodiment through ESP32 microcontrollers, servo-driven motion, and camera-based perception.

### 🧠 Goals
- Learn and implement **Vision-Language-Action (VLA)** concepts.
- Train and test **action models** using the **LeRobot framework**.
- Develop a **teleoperation interface** for manual data collection.
- Integrate **visual grounding** using a **camera + VLM** (like Gemini or CLIP).
- Transition from teleoperation to **semi-autonomous motion control**.

---

## 🕹️ Features

- **🧍 Humanoid Motion Simulation:**  
  Dynamic servo movement (arms, head) with human-like gestures.

- **🎥 Visual Perception:**  
  Camera feed processed via **VLMs (Vision-Language Models)** for object/scene understanding.

- **🎤 Interactive Control:**  
  Commands like “What am I holding?” or “Look at that object” trigger perception-based responses.

- **🌐 Wireless Teleoperation:**  
  Control robot actions and record motion data via Python–ESP32 Wi-Fi link.

- **📊 Dataset Recording:**  
  Log video, action, and language data for model fine-tuning and analysis.


