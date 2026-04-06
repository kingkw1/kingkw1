# Kevin King
**AI Researcher & Engineer – Building Human-Centered, Multimodal AI**

I build and evaluate intelligent systems that sense, adapt to, and collaborate with people in real time. My work fuses affective computing, multimodal machine learning, and human-AI interaction to create AI that understands the nuances of human emotion and behavior.

**Research Focus:**
*   **Affective Computing:** Engineering systems that recognize, interpret, and simulate human emotions.
*   **Multimodal Perception:** Fusing video, audio, text, and physiological data to create robust models of human states.
*   **Adaptive Human-AI Teaming:** Building agents that dynamically adapt to user states to enhance collaboration and personalize experiences.

---

## 🚀 Featured Projects

### 🫁 The Lung Listener: Native Multimodal AI for Respiratory Acoustics

**Top 50 Winner | Google Gemini API Hackathon 2026**

*   Selected by Google DeepMind from over 4,000 global submissions for pushing the boundaries of native multimodal reasoning.
*   Bypasses standard text prompting to ingest and process raw clinical audio using **Gemini 3 Pro's native audio capabilities**.
*   **Visualizes** respiratory acoustics (ICBHI database) via real-time spectrograms and **analyzes** pathology with millisecond precision.
*   **Isolates** clinical signals by generating custom Python DSP filters to remove noise instantly.
*   Tech: Gemini 3 Pro API, Python, Digital Signal Processing (DSP), React, WaveSurfer.js

![](https://github.com/kingkw1/lung-listener/blob/main/assets/dashboard.png)

* [📝 Kaggle Technical Write-up](https://www.kaggle.com/competitions/gemini-3/writeups/new-writeup-1765574905570)
* [💻 GitHub Repository](https://github.com/kingkw1/lung-listener)
* [🎥 Hackathon Demo Video](https://www.youtube.com/watch?v=DeplSlKUGN4)
* [🚀 Try the App on AI Studio](https://ai.studio/apps/drive/1mwEeTs57pYeME4xJuWNaXOxVR9NWiQpR)

---

### ❤️ AffectLink: Multimodal Emotion Consistency Tracking for Telehealth
🏆 **Winner – 1st Place, HP & NVIDIA Developer Challenge 2025**

*   **Impact:** Won 1st place in the HP & NVIDIA Developer Challenge for a privacy-preserving system that improves clinician awareness by detecting emotional inconsistency in telehealth sessions. Featured by <a href="https://www.hp.com/us-en/workstations/workstation-ai/ai-studio.html">HP AI Studio</a> and <a href="https://www.nvidia.com/en-us/deep-learning-ai/solutions/rtx/">NVIDIA RTX</a> for its innovative local-first AI architecture.
*   **Core Functionality:** Combines **facial expression**, **vocal tone**, and **speech content** into an **Emotional Consistency Index (ECI)**.
*   **Tech:** Python, PyTorch, Whisper, DeepFace, Hugging Face Transformers, Streamlit, MLflow, OpenCV, Flask, FAISS, Ollama

![](https://github.com/kingkw1/AffectLink/blob/main/assets/thumbnail.png)

*   [📝 GitHub Repository](https://github.com/kingkw1/AffectLink)
*   [🎥 Hackathon Demo Video](https://www.youtube.com/watch?v=rzp9CGChHJ4)

---
### 🧭 Aspirational Recommendation Engine (Contextual Bandit)
* Designed a proof-of-concept recommendation system for a digital health platform that optimizes for long-term user goals rather than just short-term engagement clicks.
* Built a **Contextual Bandit architecture** that balances historical user behavior with an "aspirational state" extracted from conversational AI logs via NLP embeddings. 
* Developed a Streamlit dashboard to evaluate recommendation footprint alignment (Cosine Similarity) and epsilon-greedy exploration strategies. 
* *Tech: Python, Contextual Bandits, NLP/Embeddings, Streamlit, Plotly.*

*   [📝 GitHub Repository](https://github.com/kingkw1/aspirational-rec-engine)
*   [🚀 Streamlit Demo](https://aspirational-rec-engine.streamlit.app/)
---

### 🎭 2Truths-1Lie: A Research Platform for Multimodal Deception Data (In-Progress)
*   **Impact:** Pioneers a novel, engagement-driven approach to dataset generation for affective computing by creating a social video game to collect the largest open-source dataset of labeled multimodal emotion and deception data. This solves a critical bottleneck in multimodal AI research.
*   **Core Functionality:** The platform handles complex audio/video preprocessing pipelines and ensures user privacy through local-first processing, creating a scalable solution for high-quality data generation.
*   **Tech:** React Native, FastAPI, Python, FFmpeg, Computer Vision & Audio processing libraries

**Future Work & Roadmap:**
*   Integration of advanced, multimodal emotion detection models.
*   A competitive scoreboard to incentivize participation.
*   Premium filters and features for an enhanced user experience.
*   Release of an anonymized dataset for the research community.

---

### 🤖 Adaptive VR/AR: Human-State Aware AI for Simulations
*   **Impact:** Demonstrates a closed-loop system where an AI model adapts virtual scenarios in real time based on user EEG and eye-tracking, advancing human-agent collaboration and personalized immersive experiences.
*   **Core Functionality:** The model uses EEG, eye-tracking, and behavioral cues to infer user state, leveraging reinforcement learning to dynamically adjust the simulation.
*   **Tech:** Unreal Engine, Python, PyTorch, TensorFlow, Reinforcement Learning, EEG/Physiological Signal Processing

<p align="center">
    <img src="https://github.com/kingkw1/public_media/blob/main/gifs/bomb_defusal_looping.gif" alt="Bomb Defusal Looping GIF"/>
</p>

*   [Using Multi-Modal Physiological Markers and Latent States to Understand Team Performance and Collaboration](https://openaccess.cms-conferences.org/publications/book/978-1-964867-13-7/article/978-1-964867-13-7_5) (CSMR 2024)
*   [Latent State Synchronization in Dyadic Partners using EEG](https://ieeexplore.ieee.org/document/10394383) (IEEE Transactions on Neural Systems and Rehabilitation Engineering, 2024)
*   [Decoding neural activity to assess individual latent state in ecologically valid contexts](https://iopscience.iop.org/article/10.1088/1741-2552/acee20/pdf) (Journal of Neural Engineering, 2024)

---

### 📊 Multimodal AI for Behavioral Analysis
*   **Impact:** Delivered a quantitative framework for analyzing and predicting team dynamics by engineering machine learning pipelines that integrate speech, video, and physiological data, providing objective, real-time insights into high-stakes human collaboration.
*   **Core Functionality:** Engineered deep learning pipelines integrating NLP, computer vision, and statistical analysis to model team performance and leadership dynamics.
*   **Tech:** Python, Hugging Face, TensorFlow, PyTorch, Pandas, SciPy, Computer Vision, NLP

*   [Granger Leadership in a Novel Dyadic Search Paradigm](https://ieeexplore.ieee.org/document/10394167) (IEEE Transactions on Neural Systems and Rehabilitation Engineering, 2024)
*   [Hierarchical Multi-Agent Reinforcement Learning with Explainable Decision Support for Human-Robot Teams](https://aaquibtabrez.github.io/assets/pdf/publications/xhri24.pdf) (XHRI Workshop, 2023)

---

### 💬 Codebase Chatbot: LLM-Powered Developer Augmentation
*   **Impact:** Demonstrated the practical application of LLMs to augment developer productivity by building an intelligent agent that analyzes entire code repositories to generate documentation and strategic insights, showcasing AI as a collaborative partner in software engineering.
*   **Core Functionality:** Built an intelligent agent that analyzes entire code repositories to generate documentation and provide strategic insights.
*   **Tech:** Python, LLMs, Retrieval-Augmented Generation (RAG), FAISS, Vector Embeddings, OpenAI API, Ollama

---

### 🧠 Neural Engineering for Neurorehabilitation
*   **Impact:** Contributed to foundational techniques in neurorehabilitation by developing closed-loop neuromodulation systems that restore motor function and sensory feedback for individuals with quadriplegia through targeted microstimulation and adaptive control.
*   **Core Functionality:** This work in decoding biological signals and designing human-in-the-loop systems for motor control directly informs my current research in building AI that understands and responds to human physiological and behavioral cues.
*   **Tech:** MATLAB, Python, Signal Processing, Neural Interfaces, Closed-Loop Control

![](https://media.springernature.com/full/springer-static/image/art%3A10.1186%2Fs42234-019-0034-y/MediaObjects/42234_2019_34_Fig3_HTML.png?as=webp)

*   [Closed-loop neuromuscular electrical stimulation using feedforward-feedback control and textile electrodes to regulate grasp force in quadriplegia](https://link.springer.com/article/10.1186/s42234-019-0034-y) (Journal of NeuroEngineering and Rehabilitation, 2019)
*   [DRG microstimulation evokes postural responses in awake, standing felines](https://iopscience.iop.org/article/10.1088/1741-2552/ab50f4/pdf) (Journal of Neural Engineering, 2019)

---

## 🛠️ Technical Expertise

*   **Programming:** Python, C++, MATLAB, C#, R
*   **Machine Learning:** PyTorch, TensorFlow, Hugging Face, Scikit-learn, FAISS, MLflow, OpenCV
*   **Cloud & DevOps:** AWS, Docker, Kubernetes, CI/CD
*   **AR/VR & Simulation:** Unity, Unreal Engine, Custom Reinforcement Learning
*   **Multimodal AI:** Speech & Audio Processing, Emotion Recognition, Multimodal Synchrony, Affective Computing, Behavioral Modeling

---

## 📣 Exploring New Challenges

I am passionate about solving complex problems in human-centered AI. I am always open to discussing new challenges and opportunities where I can apply my expertise in multimodal machine learning and affective computing to build impactful, state-of-the-art systems.

If my work on adaptive, emotionally-aware AI aligns with the challenges your team is tackling, I would be very interested to connect.

👉 <a href="linkedin.com/in/kingkw1"> LinkedIn </a> | 📫 king.kevin.w@gmail.com
