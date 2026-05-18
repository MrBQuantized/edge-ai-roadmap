# Edge AI Engineering Roadmap

> A living document of my learning journey from Physics graduate → Data Scientist → Edge AI Engineer.  
> Built in public. Updated as I grow.

**GitHub:** [@MrBQuantized](https://github.com/MrBQuantized) • **Background:** Physics | Electronics | Solar PV Design  
**Current Focus:** Data Science · AI/ML · Edge Deployment

---

## Table of Contents

- [Why Edge AI](#why-edge-ai)
- [Learning Roadmap](#learning-roadmap)
- [Mathematics](#mathematics)
  - [Linear Algebra](#linear-algebra)
  - [Statistics & Probability](#statistics--probability)
  - [Calculus & Optimization](#calculus--optimization)
- [Programming](#programming)
  - [Python](#python)
  - [C / C++](#c--c)
  - [YAML](#yaml)
  - [Bash / Shell](#bash--shell)
  - [Rust](#rust)
  - [Algorithms & Data Structures](#algorithms--data-structures)
- [Data Science & Analytics](#data-science--analytics)
- [Machine Learning](#machine-learning)
- [Deep Learning](#deep-learning)
- [AI Agents & Automation](#ai-agents--automation)
- [Edge AI & Deployment](#edge-ai--deployment)
  - [TinyML & On-Device Inference](#tinyml--on-device-inference)
  - [Model Optimization](#model-optimization)
  - [Hardware & Embedded Systems](#hardware--embedded-systems)
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

## Learning Roadmap

```
Physics + Electronics
        ↓
  Python & Math Foundations
        ↓
  Data Science & Analytics
        ↓
   Machine Learning
        ↓
    Deep Learning
        ↓
  AI Agents & Automation
        ↓
  Edge AI & Deployment  ← destination
```

**Active tracks:**
- IBM IT Experience — Data Analytics
- TechCrush Cohort 6 — Data Science
- TechyJaunt Cohort 2 — AI/ML

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

### C / C++

> Essential for embedded systems, microcontrollers, and on-device inference. Directly relevant to Edge AI hardware work.

- [C Programming for Beginners — freeCodeCamp](https://www.youtube.com/watch?v=KJgsSFOSQv0)
- [C++ for Embedded Systems — Embedded Artistry](https://embeddedartistry.com/beginners/)
- [Learn C++ — learncpp.com](https://www.learncpp.com/)
- [TensorFlow Lite for Microcontrollers (C++ API)](https://www.tensorflow.org/lite/microcontrollers)
- [Arduino C++ Reference](https://www.arduino.cc/reference/en/)

### YAML

> Used in ML pipelines, model configs, Docker, Kubernetes, n8n, and LangChain workflows.

- [YAML in 5 Minutes](https://www.youtube.com/watch?v=cdLNKUoMc6c)
- [YAML Official Specification](https://yaml.org/spec/1.2.2/)
- [YAML for DevOps — TechWorld with Nana](https://www.youtube.com/watch?v=1uFVr15xDGg)

### Bash / Shell

> For automation, deployment scripts, and managing Linux-based edge devices like Raspberry Pi and Jetson.

- [The Missing Semester of Your CS Education — Shell Tools](https://missing.csail.mit.edu/2020/shell-tools/)
- [Bash Scripting Full Course — freeCodeCamp](https://www.youtube.com/watch?v=e7BufAVwDiM)
- [Linux Command Line Basics — Ubuntu](https://ubuntu.com/tutorials/command-line-for-beginners)

### Rust

> Growing fast in systems programming and ML inference runtimes. Queued for later in the roadmap.

- [The Rust Programming Language (Book)](https://doc.rust-lang.org/book/)
- [Rust for Embedded Systems](https://docs.rust-embedded.org/book/)
- [Rustlings — Interactive Rust Exercises](https://github.com/rust-lang/rustlings)

### Algorithms & Data Structures

- [A&DS — Pavel Mavrin](https://www.youtube.com/c/pavelmavrin)
- [Introduction to Algorithms and Machine Learning](https://algorithmsbook.com/)

---

## Data Science & Analytics

- [Fundamental Python Data Science Libraries: Numpy](https://numpy.org/doc/stable/user/absolute_beginners.html)
- [Fundamental Python Data Science Libraries: Pandas](https://pandas.pydata.org/docs/getting_started/index.html)
- [Fundamental Python Data Science Libraries: Matplotlib](https://matplotlib.org/stable/tutorials/index.html)
- [Fundamental Python Data Science Libraries: Scikit-Learn](https://scikit-learn.org/stable/getting_started.html)
- [Data Engineering Roadmap](https://roadmap.sh/data-engineer)
- [How to build a data science project from scratch](https://medium.com/the-importance-of-being-earnest/how-to-build-a-data-science-project-from-scratch-dc4f096a62a1)

---

## Machine Learning

- [Machine Learning Specialization — Andrew Ng (Coursera)](https://www.coursera.org/specializations/machine-learning-introduction)
- [Machine Learning Crash Course — Google](https://developers.google.com/machine-learning/crash-course)
- [CS229 Lecture Notes — Stanford](https://cs229.stanford.edu/notes2022fall/main_notes.pdf)
- [Understanding Machine Learning: From Theory to Algorithms (Book)](https://www.cs.huji.ac.il/~shais/UnderstandingMachineLearning/)
- [Interpretable Machine Learning (Book)](https://christophm.github.io/interpretable-ml-book/)
- [Machine Learning Fundamentals: Bias and Variance — StatQuest](https://www.youtube.com/watch?v=EuBBz3bI-aA)
- [Machine Learning Fundamentals: Cross Validation — StatQuest](https://www.youtube.com/watch?v=fSytzGwwBVw)

---

## Deep Learning

- [Neural Networks: Zero to Hero — Andrej Karpathy](https://karpathy.ai/zero-to-hero.html)
- [MIT Introduction to Deep Learning](http://introtodeeplearning.com/)
- [Deep Learning Book — Goodfellow et al.](https://www.deeplearningbook.org/)
- [Dive into Deep Learning (Interactive)](https://d2l.ai/)
- [Deep Learning with PyTorch](https://pytorch.org/tutorials/)
- [Building Neural Networks from Scratch](https://github.com/rasbt/machine-learning-book)

### Transformers & LLMs

- [The Illustrated Transformer — Jay Alammar](https://jalammar.github.io/illustrated-transformer/)
- [Attention is All You Need (Paper)](https://arxiv.org/abs/1706.03762)
- [Stanford CS25 — Transformers United](https://web.stanford.edu/class/cs25/)
- [How Transformer LLMs Work](https://www.youtube.com/watch?v=wjZofJX0v4M)

---

## AI Agents & Automation

- [LangChain Documentation](https://docs.langchain.com/)
- [LangGraph Documentation](https://langchain-ai.github.io/langgraph/)
- [CrewAI Documentation](https://docs.crewai.com/)
- [DeepLearning.AI — LangChain for LLM Application Development](https://www.deeplearning.ai/short-courses/langchain-for-llm-application-development/)
- [n8n Documentation](https://docs.n8n.io/)
- [Flowise Documentation](https://flowiseai.com/)

**Active repo:** [ai-agents-track](https://github.com/MrBQuantized/ai-agents-track)

---

## Edge AI & Deployment

This is the destination. Edge AI combines everything above with hardware-aware thinking — my physics and electronics background is a direct asset here.

### TinyML & On-Device Inference

- [TinyML and Efficient Deep Learning Computing — MIT 6.5940](https://hanlab.mit.edu/courses/2023-fall-65940)
- [TinyML — Pete Warden & Daniel Situnayake (Book)](https://www.oreilly.com/library/view/tinyml/9781492052036/)
- [Introduction to Embedded Machine Learning — Edge Impulse (Coursera)](https://www.coursera.org/learn/introduction-to-embedded-machine-learning)
- [TensorFlow Lite Documentation](https://www.tensorflow.org/lite/guide)
- [Edge Impulse Documentation](https://docs.edgeimpulse.com/)

### Model Optimization

- [Making Deep Learning Go Brrrr From First Principles](https://horace.io/brrr_intro.html)
- [A Meticulous Guide to Advances in Deep Learning Efficiency over the Years](https://arxiv.org/abs/2112.06359)
- [Quantization in Deep Learning](https://huggingface.co/docs/optimum/concept_guides/quantization)
- [Neural Network Pruning Explained](https://towardsdatascience.com/neural-network-pruning-101-af816aaea61d)
- [Knowledge Distillation](https://keras.io/examples/vision/knowledge_distillation/)

### Hardware & Embedded Systems

- [Arduino Machine Learning](https://docs.arduino.cc/tutorials/nano-33-ble-sense/get-started-with-machine-learning/)
- [Raspberry Pi AI Kit Documentation](https://www.raspberrypi.com/documentation/accessories/ai-kit.html)
- [NVIDIA Jetson Getting Started](https://developer.nvidia.com/embedded/learn/get-started-jetson-nano-devkit)
- [OpenCV for Embedded Systems](https://opencv.org/opencv-for-embedded-systems/)

---

## Tools & Frameworks

| Tool | Purpose | Status |
|------|---------|--------|
| Python + Anaconda | Core environment | ✅ Active |
| VS Code | IDE | ✅ Active |
| Git + GitHub | Version control | ✅ Active |
| LangChain | AI Agents | 🔄 Learning |
| LangGraph | Agent workflows | 🔄 Learning |
| CrewAI | Multi-agent systems | 🔄 Learning |
| n8n / Flowise | No-code automation | 🔄 Learning |
| PyTorch | Deep learning | 📋 Queued |
| TensorFlow Lite | Edge inference | 📋 Queued |
| Edge Impulse | Embedded ML | 📋 Queued |

---

## Projects

*This section grows as I build.*

| Project | Description | Stack | Repo |
|---------|-------------|-------|------|
| — | Coming soon | — | — |

---

## Active Learning Tracks

| Program | Track | Status |
|---------|-------|--------|
| IBM IT Experience | Data Analytics | 🔄 Active |
| TechCrush Cohort 6 | Data Science | 🔄 Active |
| TechyJaunt Cohort 2 | AI/ML | 🔄 Active |

---

## Resources

### Podcasts & Talks
- [Lex Fridman Podcast](https://lexfridman.com/podcast/)
- [The TWIML AI Podcast](https://twimlai.com/)
- [Practical AI](https://practicalai.fm/)

### Communities
- [Hugging Face Forums](https://discuss.huggingface.co/)
- [r/MachineLearning](https://www.reddit.com/r/MachineLearning/)
- [Papers With Code](https://paperswithcode.com/)

### Meta / Lists
- [Roadmap.sh — AI & Data Science](https://roadmap.sh/ai-data-scientist)
- [Awesome Machine Learning](https://github.com/josephmisiti/awesome-machine-learning)
- [Awesome TinyML](https://github.com/gigwegbe/tinyml-papers-and-projects)

---

*Last updated: May 2026 · Open to collaborations and feedback*
