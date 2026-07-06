# Edge AI Engineering Roadmap

> A living document of my learning journey from Physics graduate → Data Scientist → Edge AI Engineer.  
> Built in public. Updated as I grow.

**GitHub:** [@MrBQuantized](https://github.com/MrBQuantized) · **Brand:** [OnohLabs](https://github.com/MrBQuantized) · **Location:** Aba, Nigeria  
**Background:** Electronic Physics · Solar PV Design · LED Display Systems

---

## Table of Contents

- [Why Edge AI](#why-edge-ai)
- [Engineering Principles](#engineering-principles)
- [Now](#now)
- [Current Stage](#current-stage)
- [Learning Milestones](#learning-milestones)
- [Learning Roadmap](#learning-roadmap)
- [Physics Applications](#physics-applications)
- [Computer Science Fundamentals](#computer-science-fundamentals)
- [Mathematics](#mathematics)
- [Programming](#programming)
- [Backend & APIs](#backend--apis)
- [Data Science & Analytics](#data-science--analytics)
- [Machine Learning](#machine-learning)
- [Deep Learning](#deep-learning)
- [Computer Vision](#computer-vision)
- [AI Agents & Automation](#ai-agents--automation)
- [MLOps](#mlops)
- [Embedded Systems](#embedded-systems)
- [Edge AI & Deployment](#edge-ai--deployment)
- [Tools & Frameworks](#tools--frameworks)
- [Projects](#projects)
- [Bookshelf](#bookshelf)
- [Active Learning Tracks](#active-learning-tracks)
- [Changelog](#changelog)
- [Resources](#resources)

---

## Why Edge AI

My background is in physics and practical electronics — LED display systems, solar PV design, power systems. That foundation made one thing clear: the most impactful AI is not always in the cloud. It is at the edge.

Edge AI means running intelligent models on constrained hardware — microcontrollers, embedded systems, mobile devices — where latency, power, and connectivity define what is possible. It sits at the intersection of hardware intuition and software intelligence. That is where I am headed.

---

## Engineering Principles

These principles guide how I learn, build, and document work across this roadmap.

- **Build projects over collecting certificates.** Understanding comes from shipping things, not from completing courses.
- **Learn first principles before frameworks.** A framework is a shortcut. First principles are the map.
- **Write clean, maintainable, documented code.** Code that only works on your laptop is not finished.
- **Learn in public.** Every repo, note, and commit is part of a longer record of growth.
- **Prefer depth over hype.** Go deep on fewer things rather than shallow on many.
- **Connect physics, mathematics, electronics, and software engineering.** The intersections are where rare capabilities live.
- **Build things that solve real problems.** Solar fault detection, smart energy metering, and predictive maintenance are not toy projects — they matter in the African context I build from.

---

## Now

> What I am actively studying today. Everything else is intentionally queued.

- Python (intermediate → advanced)
- Machine Learning fundamentals (Scikit-learn)
- Data Structures & Algorithms (CS50x, NeetCode)
- FastAPI & REST APIs
- LangChain & AI Agents

---

## Current Stage

> Last updated: July 2026

### Completed
- Python (fundamentals → intermediate)
- Git & GitHub
- SQL (basics → intermediate)
- Statistics & Probability
- Data Cleaning & EDA
- Pandas · NumPy · Matplotlib · Seaborn · Scikit-learn (basics)

### Currently Learning
- Python (intermediate → advanced)
- Machine Learning
- Data Structures & Algorithms
- FastAPI & REST APIs
- LangChain & AI Agents

### Queued
- Deep Learning (PyTorch)
- Computer Vision (OpenCV, CNNs)
- MLOps (Docker, MLflow)
- Embedded Systems (C/C++, ESP32, FreeRTOS)
- Model Optimization (TFLite, ONNX, TensorRT)
- Edge AI Deployment

---

## Learning Milestones

> A structured view of the full journey broken into progressive milestones. Checkboxes updated as milestones are completed.

### Milestone 1 — Foundations
- [x] Python fundamentals
- [x] Git & GitHub
- [x] SQL (basics → intermediate)
- [x] Statistics & Probability
- [x] Data cleaning & EDA
- [x] Pandas, NumPy, Matplotlib, Seaborn

### Milestone 2 — Data & Software Engineering
- [ ] Python (intermediate → advanced)
- [ ] Data Structures & Algorithms
- [ ] FastAPI & REST APIs
- [ ] Software engineering practices (testing, packaging, logging)
- [ ] Machine Learning fundamentals (Scikit-learn)
- [ ] End-to-end ML project with deployment

### Milestone 3 — Deep Learning & Vision
- [ ] PyTorch fundamentals
- [ ] Neural networks (CNNs, RNNs, Transformers)
- [ ] Transfer learning
- [ ] Computer Vision (OpenCV, YOLO)
- [ ] At least one deployed CV project

### Milestone 4 — MLOps & Production
- [ ] Docker
- [ ] MLflow & experiment tracking
- [ ] CI/CD for ML (GitHub Actions)
- [ ] Model serving and monitoring
- [ ] DVC for data versioning

### Milestone 5 — Embedded Systems
- [ ] Linux fundamentals
- [ ] C / C++ basics
- [ ] Microcontrollers (Arduino, ESP32)
- [ ] Communication protocols (UART, SPI, I2C)
- [ ] FreeRTOS fundamentals
- [ ] First working hardware project

### Milestone 6 — Edge AI Engineering
- [ ] Model optimization (quantization, pruning, distillation)
- [ ] TensorFlow Lite on-device inference
- [ ] Edge Impulse deployment pipeline
- [ ] TinyML project on constrained hardware
- [ ] Full Edge AI project from sensor input to inference output

---

## Learning Roadmap

```
Physics + Electronics
        ↓
CS Fundamentals + Math
        ↓
  Data Science & Analytics
        ↓
   Machine Learning
        ↓
    Deep Learning
        ↓
  Computer Vision
        ↓
   MLOps & Backend
        ↓
  Embedded Systems
        ↓
  Model Optimization
        ↓
  Edge AI Deployment  ← destination
```

AI Agents & Automation run as a parallel track throughout — not a prerequisite for the chain, but a compounding skill that reinforces systems thinking.

---

## Physics Applications

> My Electronic Physics background is not just context — it is a technical differentiator for Edge AI engineering. Engineers who understand hardware constraints at a physical level reason differently about deployment than those approaching from pure software.

**Signal Processing**  
Fourier transforms and filtering are used in audio and sensor preprocessing for on-device ML. Sampling theory and the Nyquist rate govern sensor data pipeline design.

**Sensors & Instrumentation**  
How physical sensors work (temperature, pressure, accelerometers, cameras), sensor calibration, noise, and drift — all affect model input quality. ADC/DAC fundamentals explain how analog signals become digital data.

**Control Systems**  
Feedback loops define how Edge AI models integrate with actuators and real-world systems. PID control is relevant to robotics and intelligent embedded systems.

**Power Electronics**  
A microcontroller running inference operates inside a fixed energy envelope. Solar PV design background maps directly to predictive maintenance and smart energy metering use cases.

**Computer Vision for Instrumentation**  
Using cameras as measurement instruments — dimension measurement, fault detection on solar panels — bridges traditional instrumentation with modern CV-based Edge AI.

---

## Computer Science Fundamentals

> These are computer science foundations that many data science and machine learning learning paths spend relatively little time on. For Edge AI, they become increasingly important because understanding hardware and systems directly influences deployment and performance. Work through these gradually alongside the main track.

### Computer Architecture

Understanding how CPUs, memory, and caches actually work influences inference performance on constrained hardware. ARM is the dominant architecture on edge devices — Raspberry Pi, mobile, microcontrollers.

- [Computer Organization and Architecture — Neso Academy](https://www.youtube.com/playlist?list=PLBlnK6fEyqRgLLlzdgiTUKULKJPYc0A4q)
- [Nand to Tetris — Build a Modern Computer from First Principles (Coursera)](https://www.coursera.org/learn/build-a-computer)
- [Computer Architecture — CMU 15-213](https://www.cs.cmu.edu/~213/)
- [Patterson & Hennessy — Computer Organization and Design, ARM Edition (Book)](https://www.elsevier.com/books/computer-organization-and-design-arm-edition/patterson/978-0-12-801733-3)

Key concepts: CPU architecture, memory hierarchy, cache, registers, instruction pipelines, ARM vs x86.

### Operating Systems

- [Operating Systems: Three Easy Pieces (free book)](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- [CS50's Introduction to Operating Systems](https://cs50.harvard.edu/)
- [Linux Kernel Programming — freeCodeCamp](https://www.youtube.com/watch?v=RZBcE2KLmLg)

Key concepts: processes, threads, memory management, scheduling, file systems.

### Computer Networks

- [Computer Networking: A Top-Down Approach — Kurose & Ross (Book)](https://gaia.cs.umass.edu/kurose_ross/index.php)
- [Computer Networking Full Course — freeCodeCamp](https://www.youtube.com/watch?v=qiQR5rTSshw)
- [Networking Fundamentals — Practical Networking](https://www.youtube.com/playlist?list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi)

Key concepts: TCP/IP, HTTP, REST, MQTT (IoT messaging protocol).

### Databases

- [CMU 15-445 — Database Systems](https://15445.courses.cs.cmu.edu/)
- [CS50's Introduction to Databases with SQL](https://cs50.harvard.edu/sql/)
- [Use The Index, Luke — SQL performance](https://use-the-index-luke.com/)

### Data Structures & Algorithms

Efficient algorithms become more consequential on constrained hardware where compute and memory are limited. DSA also underpins serious software engineering work.

- [CS50x — Harvard](https://cs50.harvard.edu/x/)
- [Algorithms — Abdul Bari (YouTube)](https://www.youtube.com/playlist?list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O)
- [Algorithms — William Fiset (YouTube)](https://www.youtube.com/playlist?list=PLDV1Zeh2NRsB6SWUrDFW2RmDotAfPbeHu)
- [NeetCode — DSA Roadmap](https://neetcode.io/roadmap)
- [LeetCode](https://leetcode.com/)
- [Introduction to Algorithms — CLRS (Book)](https://mitpress.mit.edu/9780262046305/introduction-to-algorithms/)

---

## Mathematics

### Linear Algebra

- [Linear Algebra at MIT — Gilbert Strang](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- [Essence of Linear Algebra — 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
- [Mathematics for Machine Learning — Linear Algebra (Coursera)](https://www.coursera.org/learn/linear-algebra-machine-learning)

### Statistics & Probability

- [Khan Academy — Statistics and Probability](https://www.khanacademy.org/math/statistics-probability)
- [Introduction to Statistics — Stanford (Coursera)](https://www.coursera.org/learn/stanford-statistics)
- [StatQuest with Josh Starmer (YouTube)](https://www.youtube.com/@statquest)

### Calculus & Optimization

- [Essence of Calculus — 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
- [Mathematics for Machine Learning — Multivariate Calculus (Coursera)](https://www.coursera.org/learn/multivariate-calculus-machine-learning)
- [Convex Optimization — Stanford](https://web.stanford.edu/class/ee364a/)

---

## Programming

### Python

- [Practical Python Programming — David Beazley](https://dabeaz-course.github.io/practical-python/)
- [100 Numpy Exercises](https://github.com/rougier/numpy-100)
- [Python Data Science Handbook — Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Real Python — Intermediate and Advanced Topics](https://realpython.com/)

**Planned repo:** `python-foundations`

### SQL

> SQL is the language of data. Every data science, analytics, and production ML role requires it. It is the primary tool for querying databases, exploring datasets, and building data pipelines.

- [CS50's Introduction to Databases with SQL](https://cs50.harvard.edu/sql/)
- [SQLZoo — Interactive SQL](https://sqlzoo.net/)
- [Mode SQL Tutorial](https://mode.com/sql-tutorial/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)

**Planned repo:** `sql-practice`

### Linux

> The operating environment for most edge devices — Raspberry Pi, Jetson, and embedded Linux boards all run Linux.

- [The Linux Command Line (Book — free)](https://linuxcommand.org/tlcl.php)
- [The Missing Semester — MIT](https://missing.csail.mit.edu/)
- [Linux Journey — Interactive](https://linuxjourney.com/)

### C / C++

> Required for embedded systems, microcontrollers, and writing on-device inference code. The language of constrained hardware.

- [C Programming for Beginners — freeCodeCamp](https://www.youtube.com/watch?v=KJgsSFOSQv0)
- [Learn C++ — learncpp.com](https://www.learncpp.com/)
- [TensorFlow Lite for Microcontrollers (C++ API)](https://www.tensorflow.org/lite/microcontrollers)

### Bash / Shell

- [The Missing Semester — Shell Tools](https://missing.csail.mit.edu/2020/shell-tools/)
- [Bash Scripting Full Course — freeCodeCamp](https://www.youtube.com/watch?v=e7BufAVwDiM)

### YAML · Docker · Rust · Go

- [YAML in 5 Minutes](https://www.youtube.com/watch?v=cdLNKUoMc6c)
- [Docker Getting Started — Official Docs](https://docs.docker.com/get-started/)
- [Docker for Beginners — TechWorld with Nana](https://www.youtube.com/watch?v=3c-iBn73dDE)
- [The Rust Programming Language (Book)](https://doc.rust-lang.org/book/)
- [Rust for Embedded Systems](https://docs.rust-embedded.org/book/)
- [Go by Example](https://gobyexample.com/)

---

## Backend & APIs

> Deploying an AI model is only half the work. Making it accessible via REST APIs or lightweight services completes the pipeline from trained model to working product. Currently learning FastAPI as part of active skill-building.

- [FastAPI Documentation — Official](https://fastapi.tiangolo.com/)
- [FastAPI Full Course — freeCodeCamp](https://www.youtube.com/watch?v=0sOvCWFmrtA)
- [REST API Design Best Practices](https://restfulapi.net/)
- [JWT Authentication Explained](https://jwt.io/introduction/)
- [Streamlit for ML Apps](https://docs.streamlit.io/)
- [Flask for ML Deployment](https://flask.palletsprojects.com/)

**Planned repo:** `fastapi-labs`

---

## Data Science & Analytics

- [Pandas Documentation](https://pandas.pydata.org/docs/getting_started/index.html)
- [NumPy Documentation](https://numpy.org/doc/stable/user/absolute_beginners.html)
- [Matplotlib Tutorials](https://matplotlib.org/stable/tutorials/index.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Scikit-Learn Getting Started](https://scikit-learn.org/stable/getting_started.html)
- [Kaggle Learn — Practical Data Science](https://www.kaggle.com/learn)

**Active repo:** [ibm-data-analytics](https://github.com/MrBQuantized/ibm-data-analytics)  
**Active repo:** [data-science-techcrush](https://github.com/MrBQuantized/data-science-techcrush)

---

## Machine Learning

- [Machine Learning Specialization — Andrew Ng (Coursera)](https://www.coursera.org/specializations/machine-learning-introduction)
- [Machine Learning Crash Course — Google](https://developers.google.com/machine-learning/crash-course)
- [CS229 Lecture Notes — Stanford](https://cs229.stanford.edu/notes2022fall/main_notes.pdf)
- [Interpretable Machine Learning (Book)](https://christophm.github.io/interpretable-ml-book/)
- [StatQuest — Bias and Variance](https://www.youtube.com/watch?v=EuBBz3bI-aA)
- [StatQuest — Cross Validation](https://www.youtube.com/watch?v=fSytzGwwBVw)
- [Hands-On Machine Learning — Aurélien Géron (Book)](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/)

**Active repo:** [ai-ml-techyjaunt](https://github.com/MrBQuantized/ai-ml-techyjaunt)  
**Planned repo:** `ml-labs`

---

## Deep Learning

- [Neural Networks: Zero to Hero — Andrej Karpathy](https://karpathy.ai/zero-to-hero.html)
- [MIT Introduction to Deep Learning](http://introtodeeplearning.com/)
- [Deep Learning Book — Goodfellow et al.](https://www.deeplearningbook.org/)
- [Dive into Deep Learning (Interactive)](https://d2l.ai/)
- [Deep Learning with PyTorch](https://pytorch.org/tutorials/)
- [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/)

### Transformers & LLMs

- [The Illustrated Transformer — Jay Alammar](https://jalammar.github.io/illustrated-transformer/)
- [Attention is All You Need (Paper)](https://arxiv.org/abs/1706.03762)
- [Stanford CS25 — Transformers United](https://web.stanford.edu/class/cs25/)

---

## Computer Vision

> Computer Vision is one of the most common Edge AI workloads — object detection on cameras, defect inspection, gesture recognition, and smart instrumentation. It is also a direct application of my physics and instrumentation background.

- [OpenCV Documentation](https://docs.opencv.org/)
- [OpenCV Crash Course — freeCodeCamp](https://www.youtube.com/watch?v=oXlwWbU8l2o)
- [CS231n — Stanford: CNNs for Visual Recognition](http://cs231n.stanford.edu/)
- [Deep Learning for Computer Vision — PyImageSearch](https://pyimagesearch.com/)
- [YOLOv8 Documentation — Ultralytics](https://docs.ultralytics.com/)
- [Pose Estimation with MediaPipe](https://developers.google.com/mediapipe/solutions/vision/pose_landmarker)

---

## AI Agents & Automation

> A parallel track running alongside the main chain. Reinforces systems thinking and orchestration skills that carry into Edge AI deployment pipelines.

- [LangChain Documentation](https://docs.langchain.com/)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [CrewAI Documentation](https://docs.crewai.com/)
- [n8n Documentation](https://docs.n8n.io/)
- [Flowise Documentation](https://flowiseai.com/)

**Active repo:** [ai-agents-track](https://github.com/MrBQuantized/ai-agents-track)

---

## MLOps

> MLOps is the bridge between ML research and production. It covers versioning, experiment tracking, CI/CD pipelines for models, and monitoring deployed systems. For Edge AI, it also governs how updated models get pushed to devices in the field.

- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)
- [DVC — Data Version Control](https://dvc.org/doc)
- [Weights & Biases — Experiment Tracking](https://docs.wandb.ai/)
- [CI/CD for ML — GitHub Actions](https://docs.github.com/en/actions)
- [Full Stack Deep Learning — MLOps](https://fullstackdeeplearning.com/)
- [Designing Machine Learning Systems — Chip Huyen (Book)](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/)

---

## Embedded Systems

> Where software meets hardware. Edge AI runs on real devices with real constraints — power budgets, limited memory, and often no operating system. This is where the Electronic Physics background becomes a direct engineering advantage.

### Firmware & RTOS

- [FreeRTOS Documentation](https://www.freertos.org/Documentation/RTOS_book.html)
- [Introduction to RTOS — DigiKey (YouTube)](https://www.youtube.com/playlist?list=PLEBQazB0HUyQ4hAPU1cJED6t3DU0h34bz)
- [Zephyr OS Documentation](https://docs.zephyrproject.org/)

### STM32

- [STM32 Getting Started — STMicroelectronics](https://www.st.com/content/st_com/en/products/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html)
- [Embedded Systems Shape The World — UT Austin (edX)](https://www.edx.org/learn/embedded-systems/the-university-of-texas-at-austin-embedded-systems-shape-the-world-microcontroller-input-output)

### ESP32 & Arduino

- [ESP-IDF Programming Guide — Espressif](https://docs.espressif.com/projects/esp-idf/en/latest/esp32/)
- [ESP32 with MicroPython — Random Nerd Tutorials](https://randomnerdtutorials.com/getting-started-micropython-esp32-esp8266/)
- [Arduino Official Documentation](https://docs.arduino.cc/)
- [Arduino Machine Learning](https://docs.arduino.cc/tutorials/nano-33-ble-sense/get-started-with-machine-learning/)

### Communication Protocols

- [I2C Protocol — NXP Reference](https://www.nxp.com/docs/en/user-guide/UM10204.pdf)
- [SPI Protocol Guide — SparkFun](https://learn.sparkfun.com/tutorials/serial-peripheral-interface-spi/all)
- [UART Explained — Circuit Basics](https://www.circuitbasics.com/basics-uart-communication/)
- [DMA — Embedded Artistry](https://embeddedartistry.com/blog/2017/08/28/dma-and-embedded-systems/)

**Planned repo:** `embedded-systems`

---

## Edge AI & Deployment

This is the destination. Edge AI combines everything above with hardware-aware thinking — my physics and electronics background is a direct asset here.

### TinyML & On-Device Inference

- [TinyML and Efficient Deep Learning — MIT 6.5940](https://hanlab.mit.edu/courses/2023-fall-65940)
- [TinyML — Pete Warden & Daniel Situnayake (Book)](https://www.oreilly.com/library/view/tinyml/9781492052036/)
- [Introduction to Embedded ML — Edge Impulse (Coursera)](https://www.coursera.org/learn/introduction-to-embedded-machine-learning)
- [TensorFlow Lite Documentation](https://www.tensorflow.org/lite/guide)
- [Edge Impulse Documentation](https://docs.edgeimpulse.com/)

### Model Optimization

- [Quantization in Deep Learning — HuggingFace](https://huggingface.co/docs/optimum/concept_guides/quantization)
- [Neural Network Pruning Explained](https://towardsdatascience.com/neural-network-pruning-101-af816aaea61d)
- [Knowledge Distillation — Keras](https://keras.io/examples/vision/knowledge_distillation/)
- [NVIDIA TensorRT Documentation](https://docs.nvidia.com/deeplearning/tensorrt/developer-guide/index.html)
- [Intel OpenVINO Documentation](https://docs.openvino.ai/)
- [ONNX — Open Neural Network Exchange](https://onnx.ai/)

### Hardware Progression

```
Arduino Nano 33 BLE Sense
  ↓ — C++, GPIO, sensors, TFLite Micro
ESP32
  ↓ — Wi-Fi, BLE, MicroPython, ESP-IDF
Raspberry Pi 4 / 5
  ↓ — Linux, camera modules, Python inference
NVIDIA Jetson Nano / Orin
  ↓ — GPU inference, TensorRT, CUDA basics
Production Edge Devices
     Google Coral · Intel NCS · Custom hardware
```

**Resources:**
- [Arduino Nano 33 BLE Sense — ML Getting Started](https://docs.arduino.cc/tutorials/nano-33-ble-sense/get-started-with-machine-learning/)
- [Raspberry Pi AI Kit Documentation](https://www.raspberrypi.com/documentation/accessories/ai-kit.html)
- [NVIDIA Jetson Getting Started](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit)
- [Google Coral Documentation](https://coral.ai/docs/)

**Planned repo:** `edge-ai-labs`

---

## Tools & Frameworks

### Languages

| Language | Purpose | Status |
|----------|---------|--------|
| Python | Data science, ML, AI agents | ✅ Active |
| SQL | Data querying, analytics | ✅ Active |
| Linux / Bash | Edge device OS, automation | 🔄 Learning |
| YAML | Configs, pipelines, deployment | 🔄 Learning |
| C / C++ | Embedded systems, on-device inference | 📋 Queued |
| Docker | Containerized ML deployment | 📋 Queued |
| Rust | Systems programming, inference runtimes | 📋 Queued |
| Go | Lightweight APIs, microservices | 📋 Optional |

### Frameworks & Tools

| Tool | Purpose | Status |
|------|---------|--------|
| Python + Anaconda | Core environment | ✅ Active |
| VS Code | IDE | ✅ Active |
| Git + GitHub | Version control | ✅ Active |
| Jupyter Notebook | Experimentation | ✅ Active |
| FastAPI | ML API deployment | 🔄 Learning |
| LangChain | AI Agents | 🔄 Learning |
| LangGraph | Agent workflows | 🔄 Learning |
| CrewAI | Multi-agent systems | 🔄 Learning |
| n8n / Flowise | No-code automation | 🔄 Learning |
| PyTorch | Deep learning | 📋 Queued |
| MLflow | Experiment tracking | 📋 Queued |
| DVC | Data versioning | 📋 Queued |
| TensorFlow Lite | Edge inference | 📋 Queued |
| Edge Impulse | Embedded ML | 📋 Queued |
| TensorRT | NVIDIA edge inference | 📋 Queued |
| OpenVINO | Intel edge inference | 📋 Queued |

---

## Projects

> Projects are the proof of work. Each one is chosen to demonstrate a specific layer of the roadmap rather than to collect a certificate.

### Beginner

| Project | Description | Stack | Status | Repo |
|---------|-------------|-------|--------|------|
| CLI Calculator | Python OOP and CLI fundamentals | Python | 📋 Planned | `python-foundations` |
| Student Management System | File I/O, data structures, clean code | Python | 📋 Planned | `python-foundations` |
| CLI Task Manager | Packaging, config files, logging | Python | 📋 Planned | `python-foundations` |
| SQL Practice Exercises | Queries, joins, CTEs, window functions | SQL | 📋 Planned | `sql-practice` |

### Intermediate

| Project | Description | Stack | Status | Repo |
|---------|-------------|-------|--------|------|
| UrbanNest Analytics | Hotel ADR prediction — TechCrush Cohort 6 capstone | Python, Pandas, Scikit-learn | ✅ Complete | [data-science-techcrush](https://github.com/MrBQuantized/data-science-techcrush) |
| PV Techno-Economic Tool | Solar PV financial analysis (CAPEX, NPV, IRR, LCOE) | Python, Matplotlib | ✅ Complete | — |
| ML Classification Pipeline | End-to-end classification with evaluation | Scikit-learn, FastAPI | 📋 Planned | `ml-labs` |
| ML Regression Pipeline | End-to-end regression with feature engineering | Scikit-learn | 📋 Planned | `ml-labs` |
| FastAPI ML Service | REST API wrapper around a trained model | FastAPI, Docker | 📋 Planned | `fastapi-labs` |

### Advanced

| Project | Description | Stack | Status | Repo |
|---------|-------------|-------|--------|------|
| CV Object Detection | Real-time object detection pipeline | PyTorch, OpenCV, YOLO | 📋 Planned | `ml-labs` |
| AI Agent System | Multi-agent workflow with memory and tool use | LangGraph, CrewAI | 📋 Planned | [ai-agents-track](https://github.com/MrBQuantized/ai-agents-track) |
| Embedded Sensor Logger | Real-time data logging from sensors via UART/I2C | C++, ESP32 | 📋 Planned | `embedded-systems` |

### Portfolio / Research

| Project | Description | Stack | Status | Repo |
|---------|-------------|-------|--------|------|
| Gesture Recognition (TinyML) | On-device gesture detection — Arduino Nano 33 BLE | C++, TFLite Micro | 📋 Planned | `edge-ai-labs` |
| Smart Energy Meter | Real-time energy monitoring with anomaly detection | Python, TFLite, Raspberry Pi | 📋 Planned | `edge-ai-labs` |
| Solar Fault Detection | CV-based fault detection on solar panels | OpenCV, YOLO, Raspberry Pi | 📋 Planned | `edge-ai-labs` |
| TinyML Wake Word | Always-on wake word detection on ESP32 | C++, ESP-IDF, TFLite Micro | 📋 Planned | `edge-ai-labs` |

### Dream Edge AI Projects

> Aspirational projects that combine Electronic Physics, AI, and Edge deployment. These are what this entire roadmap is building toward.

- **Smart Solar Fault Detection** — CV system that identifies panel degradation, shading, and faults in real time on a Raspberry Pi. Direct application of solar PV background.
- **TinyML Smart Energy Meter** — On-device anomaly detection for energy consumption patterns. Runs on ESP32 without cloud dependency.
- **Edge AI Predictive Maintenance** — Vibration and temperature sensor fusion model for equipment health monitoring. Runs inference on Jetson Nano.
- **Industrial Defect Detection** — Camera-based quality inspection system. OpenCV + YOLO on Raspberry Pi.
- **Wildlife Monitoring Camera** — Low-power, always-on object detection for wildlife camera traps. TFLite Micro on battery-powered hardware.
- **Offline Raspberry Pi AI Assistant** — Fully local voice assistant with on-device ASR and LLM inference. No cloud required.
- **Intelligent Laboratory Instrumentation** — Using CV to automate lab measurements traditionally done manually. Bridges physics instrumentation and Edge AI.
- **Embedded Computer Vision for Robotics** — Real-time visual odometry and obstacle detection for a small autonomous platform. Full-stack embedded AI.

---

## Bookshelf

### Currently Reading

| Book | Author | Topic |
|------|--------|-------|
| Hands-On Machine Learning | Aurélien Géron | ML / Deep Learning |
| The Linux Command Line | William Shotts | Linux / Systems |

### Next Up

| Book | Author | Topic |
|------|--------|-------|
| Deep Learning Book | Goodfellow, Bengio, Courville | Deep Learning |
| TinyML | Pete Warden & Daniel Situnayake | Edge AI |
| Designing Machine Learning Systems | Chip Huyen | MLOps |
| Computer Organization and Design (ARM) | Patterson & Hennessy | Computer Architecture |

### Reference

| Book | Author | Topic |
|------|--------|-------|
| Introduction to Algorithms (CLRS) | Cormen et al. | DSA |
| The Rust Programming Language | Steve Klabnik | Rust / Systems |
| Operating Systems: Three Easy Pieces | Remzi Arpaci-Dusseau | OS |
| Interpretable Machine Learning | Christoph Molnar | ML Explainability |
| Deep Learning for Embedded Systems | — | Edge AI |

---

## Active Learning Tracks

| Program | Track | Status |
|---------|-------|--------|
| IBM IT Experience | Data Analytics | 🔄 Active |
| TechCrush Cohort 6 | Data Science | ✅ Complete |
| TechyJaunt Cohort 8 | AI/ML | 🔄 Active |

---

## Changelog

### v3.0 — July 2026
- Added Engineering Principles section
- Added Now section
- Added Learning Milestones with checkboxes
- Added Bookshelf section
- Added Dream Edge AI Projects subsection
- Restructured Projects into Beginner / Intermediate / Advanced / Portfolio / Research
- Added planned repository placeholders throughout
- Improved wording for accuracy and tone throughout
- Added Changelog

### v2.0 — June 2026
- Added Computer Science Fundamentals section
- Added Backend & APIs section
- Added Computer Vision section
- Added MLOps section
- Added Embedded Systems section (expanded)
- Added Physics Applications section
- Added Current Stage section
- Reorganized learning progression
- Hardware list replaced with staged progression

### v1.0 — May 2026
- Initial roadmap published

---

## Resources

### Podcasts & Talks
- [Lex Fridman Podcast](https://lexfridman.com/podcast/)
- [The TWIML AI Podcast](https://twimlai.com/)
- [Practical AI](https://practicalai.fm/)
- [Embedded FM — Embedded Systems Podcast](https://embedded.fm/)

### Communities
- [Hugging Face Forums](https://discuss.huggingface.co/)
- [r/MachineLearning](https://www.reddit.com/r/MachineLearning/)
- [Papers With Code](https://paperswithcode.com/)
- [Edge Impulse Community](https://forum.edgeimpulse.com/)
- [Zindi — African AI competitions](https://zindi.africa/)

### Meta / Lists
- [Roadmap.sh — AI & Data Science](https://roadmap.sh/ai-data-scientist)
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
- [Awesome TinyML](https://github.com/gigwegbe/tinyml-papers-and-projects)

---

*Last updated: July 2026 · Open to collaborations and feedback*
