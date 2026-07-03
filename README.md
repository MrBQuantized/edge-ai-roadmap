# Edge AI Engineering Roadmap

> A living document of my learning journey from Physics graduate → Data Scientist → Edge AI Engineer.  
> Built in public. Updated as I grow.

**GitHub:** [@MrBQuantized](https://github.com/MrBQuantized) • **Background:** Physics | Electronics | Solar PV Design  
**Current Focus:** Data Science · AI/ML · Edge Deployment

---

## Table of Contents

- [Why Edge AI](#why-edge-ai)
- [Current Stage](#current-stage)
- [Learning Roadmap](#learning-roadmap)
- [Physics Applications](#physics-applications)
- [Computer Science Fundamentals](#computer-science-fundamentals)
  - [Computer Architecture](#computer-architecture)
  - [Operating Systems](#operating-systems)
  - [Computer Networks](#computer-networks)
  - [Databases](#databases)
  - [Data Structures & Algorithms](#data-structures--algorithms)
- [Mathematics](#mathematics)
  - [Linear Algebra](#linear-algebra)
  - [Statistics & Probability](#statistics--probability)
  - [Calculus & Optimization](#calculus--optimization)
- [Programming](#programming)
  - [Python](#python)
  - [SQL](#sql)
  - [Linux](#linux)
  - [C / C++](#c--c)
  - [Bash / Shell](#bash--shell)
  - [YAML](#yaml)
  - [Docker](#docker)
  - [Rust](#rust)
  - [Go](#go)
- [Backend & APIs](#backend--apis)
- [Data Science & Analytics](#data-science--analytics)
- [Machine Learning](#machine-learning)
- [Deep Learning](#deep-learning)
- [Computer Vision](#computer-vision)
- [AI Agents & Automation](#ai-agents--automation)
- [MLOps](#mlops)
- [Embedded Systems](#embedded-systems)
- [Edge AI & Deployment](#edge-ai--deployment)
  - [TinyML & On-Device Inference](#tinyml--on-device-inference)
  - [Model Optimization](#model-optimization)
  - [Hardware Progression](#hardware-progression)
- [Tools & Frameworks](#tools--frameworks)
- [Projects](#projects)
- [Active Learning Tracks](#active-learning-tracks)
- [Resources](#resources)

---

## Why Edge AI

My background is in physics and practical electronics — LED display systems, solar PV design, power systems.  
That foundation made one thing obvious: **the most impactful AI isn't in the cloud. It's at the edge.**

Edge AI means running intelligent models on constrained hardware — microcontrollers, embedded systems, mobile devices — where latency, power, and connectivity matter. It sits at the intersection of hardware intuition and software intelligence. That's where I'm headed.

---

## Current Stage

> Last updated: July 2026

### Completed
- Python (fundamentals → intermediate)
- Git & GitHub
- SQL (basics → intermediate)
- Statistics & Probability
- Data Cleaning & EDA
- Pandas · NumPy · Matplotlib · Seaborn

### Currently Learning
- Python (intermediate → advanced)
- Machine Learning (Scikit-learn)
- Data Structures & Algorithms
- LangChain & AI Agents
- FastAPI & REST APIs

### Queued
- Deep Learning (PyTorch)
- Computer Vision (OpenCV, CNNs)
- MLOps (Docker, MLflow)
- Embedded Systems (C/C++, ESP32)
- Model Optimization (TFLite, ONNX)
- Edge AI Deployment

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

AI Agents & Automation run as a parallel track throughout — not a prerequisite, but a compounding skill.

---

## Physics Applications

> My Electronic Physics background is not just context — it is a technical differentiator for Edge AI work. Most ML engineers approach this space from pure software. I approach it from hardware-first intuition.

**Signal Processing**  
Fourier transforms and filtering are used in audio and sensor preprocessing for on-device ML. Sampling theory and the Nyquist rate directly govern sensor data pipeline design.

**Sensors & Instrumentation**  
How physical sensors work (temperature, pressure, accelerometers, cameras), sensor calibration, noise, and drift — all affect model input quality. ADC/DAC fundamentals explain how analog signals become digital data.

**Control Systems**  
Feedback loops define how Edge AI models integrate with actuators and real-world systems. PID control is relevant to robotics and intelligent embedded systems.

**Power Electronics**  
A microcontroller running inference operates inside a fixed energy envelope. My solar PV design background maps directly to predictive maintenance and smart energy metering use cases.

**Computer Vision for Instrumentation**  
Using cameras as measurement instruments — dimension measurement, fault detection — bridges traditional instrumentation with modern CV-based Edge AI.

---

## Computer Science Fundamentals

> These are computer science foundations that many data science and ML learning paths spend relatively little time on. For Edge AI, they become increasingly important because understanding hardware and systems directly influences deployment and performance.

### Computer Architecture

Understanding how CPUs, memory, and caches actually work directly affects inference performance on constrained hardware. ARM is the dominant architecture on edge devices — Raspberry Pi, mobile, microcontrollers.

- [Computer Organization and Architecture — Neso Academy](https://www.youtube.com/playlist?list=PLBlnK6fEyqRgLLlzdgiTUKULKJPYc0A4q)
- [Nand to Tetris — Build a Modern Computer from First Principles (Coursera)](https://www.coursera.org/learn/build-a-computer)
- [Computer Architecture — CMU 15-213](https://www.cs.cmu.edu/~213/)
- [Patterson & Hennessy — Computer Organization and Design, ARM Edition (Book)](https://www.elsevier.com/books/computer-organization-and-design-arm-edition/patterson/978-0-12-801733-3)

Key concepts: CPU architecture, memory hierarchy, cache, registers, instruction pipelines, ARM vs x86.

### Operating Systems

- [Operating Systems: Three Easy Pieces (free book)](https://pages.cs.wisc.edu/~remzi/OSTEP/)
- [CS50's Introduction to Operating Systems](https://cs50.harvard.edu/)
- [Linux Kernel Programming — freeCodeCamp](https://www.youtube.com/watch?v=RZBcE2KLmLg)

Key concepts: processes, threads, memory management, scheduling, file systems. Directly relevant to managing inference processes on embedded Linux devices.

### Computer Networks

- [Computer Networking: A Top-Down Approach — Kurose & Ross (Book)](https://gaia.cs.umass.edu/kurose_ross/index.php)
- [Computer Networking Full Course — freeCodeCamp](https://www.youtube.com/watch?v=qiQR5rTSshw)
- [Networking Fundamentals — Practical Networking](https://www.youtube.com/playlist?list=PLIFyRwBY_4bRLmKfP1KnZA6rZbRHtxmXi)

Key concepts: TCP/IP, HTTP, REST, MQTT (IoT messaging protocol). Edge devices communicate back to cloud — knowing how matters.

### Databases

- [CMU 15-445 — Database Systems](https://15445.courses.cs.cmu.edu/)
- [CS50's Introduction to Databases with SQL](https://cs50.harvard.edu/sql/)
- [Use The Index, Luke — SQL performance](https://use-the-index-luke.com/)

### Data Structures & Algorithms

Efficient algorithms matter more on constrained hardware where compute and memory are limited. DSA also underpins every serious software engineering interview.

- [CS50x — Harvard (algorithm foundations)](https://cs50.harvard.edu/x/)
- [Algorithms — Abdul Bari (YouTube)](https://www.youtube.com/playlist?list=PLDN4rrl48XKpZkf03iYFl-O29szjTrs_O)
- [Algorithms — William Fiset (YouTube)](https://www.youtube.com/playlist?list=PLDV1Zeh2NRsB6SWUrDFW2RmDotAfPbeHu)
- [NeetCode — DSA Roadmap](https://neetcode.io/roadmap)
- [LeetCode — Practice](https://leetcode.com/)
- [Introduction to Algorithms — CLRS (Book)](https://mitpress.mit.edu/9780262046305/introduction-to-algorithms/)

---

## Mathematics

### Linear Algebra

- [Linear Algebra at MIT — Gilbert Strang](https://ocw.mit.edu/courses/18-06-linear-algebra-spring-2010/)
- [Essence of Linear Algebra — 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDPD3MizzM2xVFitgF8hE_ab)
- [Mathematics for Machine Learning — Linear Algebra (Coursera)](https://www.coursera.org/learn/linear-algebra-machine-learning)
- [Linear Algebra for Data Science (Book)](https://www.amazon.com/Linear-Algebra-Data-Science/dp/1108935990)

### Statistics & Probability

- [Khan Academy — Statistics and Probability](https://www.khanacademy.org/math/statistics-probability)
- [Introduction to Statistics — Stanford (Coursera)](https://www.coursera.org/learn/stanford-statistics)
- [Probability for Computer Scientists — Stanford CS109](https://web.stanford.edu/class/cs109/)
- [StatQuest with Josh Starmer (YouTube)](https://www.youtube.com/@statquest)

### Calculus & Optimization

- [Essence of Calculus — 3Blue1Brown](https://www.youtube.com/playlist?list=PLZHQObOWTQDMsr9K-rj53DwVRMYO3t5Yr)
- [Mathematics for Machine Learning — Multivariate Calculus (Coursera)](https://www.coursera.org/learn/multivariate-calculus-machine-learning)
- [Convex Optimization — Stanford](https://web.stanford.edu/class/ee364a/)
- [Understanding Gradient Descent](https://ruder.io/optimizing-gradient-descent/)

---

## Programming

### Python

- [Practical Python Programming — David Beazley](https://dabeaz-course.github.io/practical-python/)
- [100 Numpy Exercises](https://github.com/rougier/numpy-100)
- [From Python to Numpy](https://www.labri.fr/perso/nrougier/from-python-to-numpy/)
- [Python Data Science Handbook — Jake VanderPlas](https://jakevdp.github.io/PythonDataScienceHandbook/)
- [Real Python — Intermediate and Advanced Topics](https://realpython.com/)

### SQL

> SQL is the language of data. Every data science, analytics, and production ML role requires it. It is how you query databases, explore datasets, and build data pipelines.

- [CS50's Introduction to Databases with SQL](https://cs50.harvard.edu/sql/)
- [SQLZoo — Interactive SQL](https://sqlzoo.net/)
- [Mode SQL Tutorial](https://mode.com/sql-tutorial/)
- [PostgreSQL Documentation](https://www.postgresql.org/docs/)
- [Advanced SQL for Data Scientists — Mode](https://mode.com/sql-tutorial/intro-to-advanced-sql/)

### Linux

> The operating environment for most edge devices — Raspberry Pi, Jetson, and embedded Linux boards all run Linux. Essential early, not late.

- [The Linux Command Line (Book — free)](https://linuxcommand.org/tlcl.php)
- [Linux for Beginners — freeCodeCamp](https://www.youtube.com/watch?v=sWbUDq4S6Y8)
- [The Missing Semester — MIT (Shell, Git, CLI tools)](https://missing.csail.mit.edu/)
- [Linux Journey — Interactive](https://linuxjourney.com/)
- [Raspberry Pi Linux Getting Started](https://www.raspberrypi.com/documentation/computers/getting-started.html)

### C / C++

> Essential for embedded systems, microcontrollers, and on-device inference. Directly relevant to Edge AI hardware work.

- [C Programming for Beginners — freeCodeCamp](https://www.youtube.com/watch?v=KJgsSFOSQv0)
- [C++ for Embedded Systems — Embedded Artistry](https://embeddedartistry.com/beginners/)
- [Learn C++ — learncpp.com](https://www.learncpp.com/)
- [TensorFlow Lite for Microcontrollers (C++ API)](https://www.tensorflow.org/lite/microcontrollers)
- [Arduino C++ Reference](https://www.arduino.cc/reference/en/)

### Bash / Shell

> For automation, deployment scripts, and managing Linux-based edge devices like Raspberry Pi and Jetson.

- [The Missing Semester of Your CS Education — Shell Tools](https://missing.csail.mit.edu/2020/shell-tools/)
- [Bash Scripting Full Course — freeCodeCamp](https://www.youtube.com/watch?v=e7BufAVwDiM)
- [Linux Command Line Basics — Ubuntu](https://ubuntu.com/tutorials/command-line-for-beginners)

### YAML

> Used in ML pipelines, model configs, Docker, Kubernetes, n8n, and LangChain workflows.

- [YAML in 5 Minutes](https://www.youtube.com/watch?v=cdLNKUoMc6c)
- [YAML Official Specification](https://yaml.org/spec/1.2.2/)
- [YAML for DevOps — TechWorld with Nana](https://www.youtube.com/watch?v=1uFVr15xDGg)

### Docker

> Containerized deployment is standard in production ML and increasingly used at the edge. Bridges model training to real-world deployment.

- [Docker Getting Started — Official Docs](https://docs.docker.com/get-started/)
- [Docker for Beginners — TechWorld with Nana](https://www.youtube.com/watch?v=3c-iBn73dDE)
- [Docker for ML Engineers](https://testdriven.io/blog/docker-for-machine-learning/)
- [Running Docker on Raspberry Pi](https://www.raspberrypi.com/tutorials/use-docker-to-run-applications-on-raspberry-pi/)

### Rust

> Growing fast in systems programming and ML inference runtimes. Queued for later in the roadmap.

- [The Rust Programming Language (Book)](https://doc.rust-lang.org/book/)
- [Rust for Embedded Systems](https://docs.rust-embedded.org/book/)
- [Rustlings — Interactive Rust Exercises](https://github.com/rust-lang/rustlings)

### Go

> Optional specialization — useful for building lightweight APIs and microservices that serve ML models at the edge.

- [Go by Example](https://gobyexample.com/)
- [Go Documentation — Official](https://go.dev/doc/)
- [Building APIs with Go](https://www.youtube.com/watch?v=SonwZ6MF5BE)

---

## Backend & APIs

> Deploying an AI model is only half the work. Making it accessible — via REST APIs, lightweight services, or edge endpoints — is the other half. Backend skills complete the pipeline from trained model to working product. Currently learning FastAPI as part of active skill-building.

- [FastAPI Documentation — Official](https://fastapi.tiangolo.com/)
- [FastAPI Full Course — freeCodeCamp](https://www.youtube.com/watch?v=0sOvCWFmrtA)
- [REST API Design Best Practices](https://restfulapi.net/)
- [Building ML APIs with FastAPI](https://towardsdatascience.com/deploying-machine-learning-models-with-fastapi-1e30e4940f82)
- [JWT Authentication Explained](https://jwt.io/introduction/)
- [Streamlit for ML Apps](https://docs.streamlit.io/)
- [Flask for ML Deployment](https://flask.palletsprojects.com/)

---

## Data Science & Analytics

- [Fundamental Python Data Science Libraries: Numpy](https://numpy.org/doc/stable/user/absolute_beginners.html)
- [Fundamental Python Data Science Libraries: Pandas](https://pandas.pydata.org/docs/getting_started/index.html)
- [Fundamental Python Data Science Libraries: Matplotlib](https://matplotlib.org/stable/tutorials/index.html)
- [Fundamental Python Data Science Libraries: Scikit-Learn](https://scikit-learn.org/stable/getting_started.html)
- [Seaborn Documentation](https://seaborn.pydata.org/)
- [Data Engineering Roadmap](https://roadmap.sh/data-engineer)
- [How to build a data science project from scratch](https://medium.com/the-importance-of-being-earnest/how-to-build-a-data-science-project-from-scratch-dc4f096a62a1)
- [Kaggle Learn — Practical Data Science Courses](https://www.kaggle.com/learn)

---

## Machine Learning

- [Machine Learning Specialization — Andrew Ng (Coursera)](https://www.coursera.org/specializations/machine-learning-introduction)
- [Machine Learning Crash Course — Google](https://developers.google.com/machine-learning/crash-course)
- [CS229 Lecture Notes — Stanford](https://cs229.stanford.edu/notes2022fall/main_notes.pdf)
- [Understanding Machine Learning: From Theory to Algorithms (Book)](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/)
- [Interpretable Machine Learning (Book)](https://christophm.github.io/interpretable-ml-book/)
- [Machine Learning Fundamentals: Bias and Variance — StatQuest](https://www.youtube.com/watch?v=EuBBz3bI-aA)
- [Machine Learning Fundamentals: Cross Validation — StatQuest](https://www.youtube.com/watch?v=fSytzGwwBVw)
- [Hands-On Machine Learning — Aurélien Géron (Book)](https://www.oreilly.com/library/view/hands-on-machine-learning/9781098125967/)

---

## Deep Learning

- [Neural Networks: Zero to Hero — Andrej Karpathy](https://karpathy.ai/zero-to-hero.html)
- [MIT Introduction to Deep Learning](http://introtodeeplearning.com/)
- [Deep Learning Book — Goodfellow et al.](https://www.deeplearningbook.org/)
- [Dive into Deep Learning (Interactive)](https://d2l.ai/)
- [Deep Learning with PyTorch](https://pytorch.org/tutorials/)
- [Building Neural Networks from Scratch](https://github.com/rasbt/machine-learning-book)
- [fast.ai — Practical Deep Learning for Coders](https://course.fast.ai/)

### Transformers & LLMs

- [The Illustrated Transformer — Jay Alammar](https://jalammar.github.io/illustrated-transformer/)
- [Attention is All You Need (Paper)](https://arxiv.org/abs/1706.03762)
- [Stanford CS25 — Transformers United](https://web.stanford.edu/class/cs25/)
- [How Transformer LLMs Work](https://www.youtube.com/watch?v=wjZofJX0v4M)

---

## Computer Vision

> Computer Vision is one of the most common Edge AI workloads — object detection on cameras, defect inspection on production lines, gesture recognition, and more. Understanding CV is nearly mandatory for practical Edge AI work.

- [OpenCV Documentation](https://docs.opencv.org/)
- [OpenCV Crash Course — freeCodeCamp](https://www.youtube.com/watch?v=oXlwWbU8l2o)
- [CS231n — Stanford: CNNs for Visual Recognition](http://cs231n.stanford.edu/)
- [Deep Learning for Computer Vision — PyImageSearch](https://pyimagesearch.com/)
- [YOLOv8 Documentation — Ultralytics](https://docs.ultralytics.com/)
- [Image Segmentation — Papers with Code](https://paperswithcode.com/task/semantic-segmentation)
- [Pose Estimation with MediaPipe](https://developers.google.com/mediapipe/solutions/vision/pose_landmarker)

Key topics: image preprocessing, CNNs, object detection, YOLO, image segmentation, pose estimation, OpenCV pipelines.

---

## AI Agents & Automation

> A parallel track — runs alongside the main chain rather than being a single step in it. Reinforces systems thinking and orchestration skills that carry directly into Edge AI deployment pipelines.

- [LangChain Documentation](https://docs.langchain.com/)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [CrewAI Documentation](https://docs.crewai.com/)
- [DeepLearning.AI — LangChain for LLM Application Development](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)
- [n8n Documentation](https://docs.n8n.io/)
- [Flowise Documentation](https://flowiseai.com/)

**Active repo:** [ai-agents-track](https://github.com/MrBQuantized/ai-agents-track)

---

## MLOps

> MLOps is the bridge between ML research and production. It covers versioning, experiment tracking, CI/CD pipelines for models, and monitoring deployed systems. For Edge AI specifically, MLOps governs how updated models get pushed to devices in the field.

- [MLflow Documentation](https://mlflow.org/docs/latest/index.html)
- [DVC — Data Version Control](https://dvc.org/doc)
- [Weights & Biases (W&B) — Experiment Tracking](https://docs.wandb.ai/)
- [CI/CD for Machine Learning — GitHub Actions](https://docs.github.com/en/actions)
- [Full Stack Deep Learning — MLOps](https://fullstackdeeplearning.com/)
- [Machine Learning Engineering — Chip Huyen (Book)](https://www.oreilly.com/library/view/designing-machine-learning/9781098107956/)

Key tools: MLflow (experiment tracking), DVC (data versioning), W&B (monitoring), Docker + GitHub Actions (CI/CD pipeline).

---

## Embedded Systems

> Where software meets hardware. Edge AI runs on real devices with real constraints — power budgets, limited memory, no operating system in some cases. This section is where the physics background becomes a genuine engineering advantage.

### Firmware & RTOS

- [FreeRTOS Documentation](https://www.freertos.org/Documentation/RTOS_book.html)
- [Introduction to RTOS — DigiKey (YouTube)](https://www.youtube.com/playlist?list=PLEBQazB0HUyQ4hAPU1cJED6t3DU0h34bz)
- [Zephyr OS Documentation](https://docs.zephyrproject.org/)

### STM32

- [STM32 Getting Started — STMicroelectronics](https://www.st.com/content/st_com/en/products/microcontrollers-microprocessors/stm32-32-bit-arm-cortex-mcus.html)
- [STM32CubeIDE Tutorial — Controllers Tech (YouTube)](https:/