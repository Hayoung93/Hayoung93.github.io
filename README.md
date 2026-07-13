# Hayoung Park

### Machine Learning Engineer & Researcher

I am a machine learning engineer and researcher specializing in computer vision, continual learning, domain generalization, and deepfake detection.

My work focuses on building machine learning systems that remain robust under changing data distributions. I am particularly interested in continual adaptation, parameter-efficient learning, multi-domain evaluation, and deployable vision systems.

I received my M.S. in Electronic Engineering from Hanyang University and my B.S. in Electronic Engineering from Hanyang University ERICA.

[Resume](./assets/resume.pdf) ·
[Curriculum Vitae](./assets/cv.pdf) ·
[Google Scholar](YOUR_GOOGLE_SCHOLAR_URL) ·
[LinkedIn](YOUR_LINKEDIN_URL) ·
[Email](mailto:YOUR_EMAIL)

---

## Research Interests

- Continual Learning
- Domain Generalization and Domain Adaptation
- Deepfake and Digital Forgery Detection
- Vision Transformers
- Parameter-Efficient Fine-Tuning
- Mixture-of-Experts
- Robust and Efficient Machine Learning

---

## Selected Research

### Interference-Gated Continual Learning for Deepfake Detection

A continual learning framework that determines whether a new forgery domain should be merged with an existing expert or isolated into a new expert based on measured post-training interference.

- Designed a verify-rollback mechanism that tentatively trains a candidate expert and restores the previous state when harmful interference is detected.
- Built a grouped expert architecture using Vision Transformers, LoRA, and soft expert routing.
- Evaluated the method on continual learning streams containing up to 30 forgery domains.
- Achieved **89.2 mAUC with 16 expert groups**, compared with full domain isolation using 30 experts.
- Reduced average AUC forgetting to **2.6**.

**Status:** Submitted to ACCV 2026

[Project Details](./projects/interference-gated-cl.md) ·
[Paper](YOUR_PAPER_URL) ·
[Code](YOUR_CODE_URL)

---

### Cache-Based Curriculum Learning for Domain-Incremental Deepfake Detection

A curriculum learning method that selects informative training samples from an online cache and controls the order in which samples are presented during domain-incremental learning.

- Developed a cache-based sample selection and curriculum strategy for deepfake detection.
- Analyzed the relationship between sample difficulty, domain order, and catastrophic forgetting.
- Built reproducible multi-domain training and stage-wise evaluation pipelines.
- Received the **Best Paper Award at CVPRW 2026**.

[Project Details](./projects/cache-curriculum.md) ·
[Paper](YOUR_PAPER_URL) ·
[Code](YOUR_CODE_URL)

---

### Dual-Space Augmentation for Domain-Generalized Object Detection

A domain generalization approach that augments both image-level appearance and feature-level representations to improve object detection under unseen domain shifts.

- Studied domain robustness in object detection.
- Designed complementary input-space and feature-space augmentation strategies.
- Evaluated generalization performance across multiple visual domains.

**Published at WACV 2025**

[Project Details](./projects/dual-space-augmentation.md) ·
[Paper](YOUR_PAPER_URL) ·
[Code](YOUR_CODE_URL)

---

## Engineering Projects

### Dockerized Deepfake Detection Application

A deployable deepfake detection prototype integrating preprocessing, model inference, and result visualization.

- Built a PyTorch inference backend for image and video forgery detection.
- Developed a Gradio-based user interface.
- Containerized the application using Docker.
- Integrated model loading, preprocessing, inference, and confidence visualization.
- Designed the system to support configurable model checkpoints.

[Project Details](./projects/deepfake-application.md) ·
[Repository](YOUR_REPOSITORY_URL)

---

### Local LLM Agent Interface

A local-LLM-based agentic AI prototype with a user-configurable function pool.

- Developed a web interface for registering and managing executable functions.
- Enabled an LLM agent to select and invoke tools based on user requests.
- Integrated local model inference with an extensible tool execution workflow.

[Project Details](./projects/llm-agent.md) ·
[Repository](YOUR_REPOSITORY_URL)

---

## Publications

### 2026

**Interference-Gated Continual Learning for Deepfake Detection**  
Hyunyoung Park, et al.  
Submitted to ACCV 2026.

**Cache-Based Curriculum Learning for Domain-Incremental Deepfake Detection**  
Hyunyoung Park, et al.  
CVPR Workshops, 2026. **Best Paper Award.**

### 2025

**On the Importance of Dual-Space Augmentation for Domain Generalized Object Detection**  
Hyunyoung Park, et al.  
Winter Conference on Applications of Computer Vision, 2025.

[View Full Publication List](./publications.md)

---

## Technical Skills

### Machine Learning

- Python
- PyTorch
- Vision Transformers
- LoRA and Parameter-Efficient Fine-Tuning
- Continual Learning
- Domain Generalization
- Domain Adaptation
- Model Evaluation and Ablation Studies

### Engineering

- Docker
- Gradio
- Linux
- Git
- OpenCV
- NumPy
- Pandas
- Experiment Automation
- GPU-Based Training and Inference

---

## Current Interests

I am currently interested in:

- Continual adaptation of foundation models
- Domain-adapted LLM and VLM training
- Efficient post-training and parameter-efficient adaptation
- Robust evaluation under changing data distributions
- Bridging research prototypes and deployable machine learning systems

---

## Education

**M.S. in Electronic Engineering**  
Hanyang University

**B.S. in Electronic Engineering**  
Hanyang University ERICA

---

## Contact

- Email: [YOUR_EMAIL](mailto:YOUR_EMAIL)
- GitHub: [github.com/YOUR_USERNAME](https://github.com/YOUR_USERNAME)
- LinkedIn: [YOUR_LINKEDIN](YOUR_LINKEDIN_URL)
- Google Scholar: [Profile](YOUR_GOOGLE_SCHOLAR_URL)
