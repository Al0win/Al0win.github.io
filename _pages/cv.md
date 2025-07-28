---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}

Education
======
* B.E. in Computer Science, Birla Institute of Technology and Science (BITS Pilani), Goa, 2026 (expected)
  * October 2022 - May 2026
  * Relevant Coursework: Reinforcement Learning, Generative AI*, Natural Language Processing*, Machine Learning, Computer Programming, Logic in CS, Theory of Computation*, Object-Oriented Programming
  * *Received an excellent grade of A or A-

Research Experience
======
* October 2024 - Present: **ADAPT: Adaptive Driver Behaviour Modelling**
  * APPCAIR, Goa, India
  * Supervisors: Prof. Snehanshu Saha and Prof. Santonu Sarkar
  * Proposed and leading development of an autonomous driving agent architecture using the NavSim framework
  * Designing a transformer-based architecture that fuses multi-modal inputs including kinematic and camera data using hierarchical attention mechanisms to detect and quantify anomalous driving in an explainable way
  * Creating a novel dataset to benchmark anomaly detection models in the CARLA simulator

* July 2025 - Present: **nDNA: A Geometric Framework for Tracing the Latent Genome of AI**
  * Pragya.ai, Goa, India
  * Supervisor: Dr. Amitava Das
  * Analyzing the latent geometry of AI models (LLMs, VLMs, Diffusion Models etc.) through Neural Genomics
  * Applying Neural DNA (nDNA), a novel diagnostic framework that integrates Riemannian geometry and statistical thermodynamics to quantify a model's internal belief structures and epistemic traits

Work Experience
======
* May 2024 - July 2024: **Data Engineer Intern**
  * Digital India Bhashini Division, Delhi, India
  * Contributed to the Intelligent Data Pipeline project for scalable GenAI-ready NLP data processing
  * Migrated pipeline infrastructure from Google Cloud to Azure, enabling dataset curation for LLM training

Technical Skills
======
* **Programming Languages**: Python, LaTeX
* **Machine Learning & AI Frameworks**: PyTorch, TensorFlow, Hugging Face Transformers, Scikit-Learn, LangChain, FAISS
* **Specialized Skills**: Computer Vision, NLP, Multimodal AI, Vector Databases, Retrieval Augmented Generation

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>

Projects
======
* **LLMExam: AI-Driven Question Paper Generation** (Spring 2025)
  * Developed a multimodal system using a local VLM (Qwen2.5-VL) to automatically extract textual questions, diagrams, and graphs from PDFs
  * Employed vector search for topic-based retrieval and designed an LLM-driven topic tagging mechanism for precise question classification

* **Zero-Shot Learning using RoBERTa** (Fall 2024)
  * Enhanced classification accuracy by iteratively optimizing label prompts using generative language models (Gemma2-9B, Qwen2.5-32B, and Nemotron-70B)
  * Improved performance metrics, achieving a significant increase in accuracy from 48.5% to 82.13% with Nemotron-70B

* **MonetAI: Generating Artistic Images using GANs** (Fall 2024)
  * Developed a generative model replicating Claude Monet's artistic style using CycleGANs

Activities and Leadership
======
* **Teaching Assistant**, CS F425 Deep Learning, BITS Pilani, Goa (January 2024 - Present)
  * Designed and conducted tutorials and homework assignments on deep learning concepts for undergraduate and graduate students
* **Teaching Assistant**, CS F437 Generative AI, BITS Pilani, Goa (Fall 2025)
  * Supporting students in understanding cutting-edge generative AI technologies and applications
* **Undergraduate Volunteer**, IndoML 2024, Goa, India (December 2024)
  * Co-organized the AI symposium, ensuring seamless execution of lectures and Q&A sessions
  * Oversaw logistical arrangements for guest accommodations and overall event coordination
