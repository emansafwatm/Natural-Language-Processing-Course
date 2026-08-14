# Natural Language Processing: From Foundations to Large Language Models

> A complete, university-level Natural Language Processing course covering linguistic foundations, classical NLP, neural networks, Transformers, Hugging Face, Large Language Models, machine translation, advanced NLP applications, and end-to-end intelligent systems through executable Jupyter notebooks.

**Author:** Eman Khater  
**Course status:** Complete  
**Structure:** 10 modules · 62 sequential lessons · Jupyter notebooks  
**License:** MIT

---

## Table of Contents

- [Course Overview](#course-overview)
- [Course Status](#course-status)
- [Why This Course?](#why-this-course)
- [Learning Outcomes](#learning-outcomes)
- [Target Audience](#target-audience)
- [Prerequisites](#prerequisites)
- [Course Curriculum](#course-curriculum)
- [Complete 62-Lesson Index](#complete-62-lesson-index)
- [Repository Structure](#repository-structure)
- [Installation](#installation)
- [Recommended Environment](#recommended-environment)
- [Dependencies and Model Downloads](#dependencies-and-model-downloads)
- [How to Use This Course](#how-to-use-this-course)
- [Course Projects and Capstones](#course-projects-and-capstones)
- [Reproducibility and Execution Notes](#reproducibility-and-execution-notes)
- [Contributing](#contributing)
- [References](#references)
- [Citation](#citation)
- [License](#license)
- [Possible Future Extensions](#possible-future-extensions)
- [Acknowledgments](#acknowledgments)

---

## Course Overview

Natural Language Processing (NLP) enables computers to process, analyze, understand, and generate human language. Modern NLP supports applications such as search, machine translation, question answering, summarization, conversational AI, information retrieval, document intelligence, and Large Language Models (LLMs).

This repository provides a structured learning path from foundational linguistic and statistical concepts to neural sequence models, Transformers, pretrained models, Retrieval-Augmented Generation (RAG), LLM applications, machine translation, multimodal NLP, and end-to-end intelligent document systems.

The course emphasizes both **conceptual understanding** and **implementation**. Lessons combine theory, mathematical intuition where appropriate, executable Python, evaluation, error analysis, multilingual considerations, knowledge checks, and unsolved exercises.

---

## Course Status

**The main course sequence is complete.**

- **10 modules**
- **62 sequential lessons**
- Foundations through advanced applications
- Multiple end-to-end capstones
- CPU-friendly core demonstrations where practical
- Optional pretrained-model extensions for advanced workflows
- Multilingual examples, including Arabic-focused material

The final lesson is an end-to-end **Intelligent Document Assistant Capstone** integrating retrieval, question answering, summarization, multimodal reasoning, evaluation, grounding, and deployment design.

---

## Why This Course?

Many NLP resources teach individual techniques or libraries in isolation. This course instead presents NLP as a connected progression:

```text
Linguistic Foundations
        ↓
Classical NLP
        ↓
Word Representations
        ↓
Neural Sequence Models
        ↓
Attention and Transformers
        ↓
Pretrained Models and Hugging Face
        ↓
Large Language Models and RAG
        ↓
Machine Translation
        ↓
Advanced NLP Applications
        ↓
Integrated Intelligent NLP Systems
```

Each stage builds on ideas introduced earlier.

---

## Learning Outcomes

After completing the course, learners should be able to:

### Foundations and Linguistics
- Explain the major components and historical development of NLP.
- Analyze morphology, syntax, semantics, pragmatics, and discourse.
- Work with corpora, annotation, and linguistic resources.

### Classical NLP
- Build text preprocessing and normalization pipelines.
- Implement tokenization, stemming, lemmatization, N-grams, Bag-of-Words, and TF-IDF.
- Build classical text classification, information retrieval, topic modeling, and sequence-labeling systems.

### Representation Learning
- Explain distributional semantics.
- Work with Word2Vec, GloVe, FastText, sentence embeddings, and document embeddings.

### Deep Learning
- Explain neural-network foundations for NLP.
- Build and analyze RNN, LSTM, GRU, encoder-decoder, and attention-based models.

### Transformers and Pretrained Models
- Explain self-attention and Transformer encoder, decoder, and encoder-decoder architectures.
- Use pretrained Transformer workflows.
- Fine-tune models for classification, token classification, question answering, generation, summarization, and translation.
- Understand parameter-efficient fine-tuning with PEFT and LoRA.

### Large Language Models
- Explain LLM scaling, instruction tuning, prompting, structured outputs, and in-context learning.
- Build and evaluate RAG pipelines.
- Understand hallucination, reliability, tool use, agents, and multimodal LLM foundations.

### Machine Translation
- Explain statistical, neural, and Transformer-based machine translation.
- Analyze Arabic-English translation challenges involving morphology, tokenization, and diacritization.
- Evaluate translation systems using multiple automatic and statistical methods.
- Design reproducible MT experiments.

### Advanced NLP Applications
- Build advanced retrieval and reranking pipelines.
- Implement extractive and faithfulness-aware summarization workflows.
- Build evidence-grounded question answering.
- Design task-oriented dialogue systems with state and memory.
- Understand multimodal NLP, OCR-aware reasoning, and document intelligence.
- Integrate multiple NLP components into an end-to-end intelligent assistant.

---

## Target Audience

This course is suitable for:

- Undergraduate and graduate students in AI, Computer Science, Data Science, or related fields.
- University instructors seeking structured teaching material.
- Researchers entering NLP, machine translation, multilingual NLP, or LLM research.
- Machine Learning engineers expanding into language technologies.
- Software developers building intelligent text systems.
- Self-learners seeking a complete progression from fundamentals to modern NLP.

No prior NLP knowledge is assumed.

---

## Prerequisites

### Required
- Basic Python programming.
- Familiarity with variables, functions, loops, classes, and standard data structures.
- Basic secondary-school mathematics.

### Recommended
- Introductory Machine Learning.
- Basic Linear Algebra.
- Elementary Probability and Statistics.
- Familiarity with Jupyter Notebook or JupyterLab.

---

# Course Curriculum

| Module | Lessons | Title | Main Topics |
|---|---:|---|---|
| 1 | 1–4 | Foundations of NLP | Introduction, history, NLP pipeline, Python ecosystem |
| 2 | 5–10 | Linguistic Foundations | Morphology, syntax, semantics, pragmatics, discourse, linguistic resources |
| 3 | 11–20 | Classical NLP | Preprocessing, tokenization, stemming, lemmatization, N-grams, TF-IDF, classification, IR, topic modeling, sequence labeling, capstone |
| 4 | 21–25 | Word Embeddings | Distributional semantics, Word2Vec, GloVe, FastText, pretrained embeddings, sentence/document embeddings |
| 5 | 26–30 | Deep Learning for NLP | Neural foundations, RNN, LSTM, GRU, seq2seq, attention |
| 6 | 31–34 | Transformer Architectures | Self-attention, encoder models, decoder models, encoder-decoder models |
| 7 | 35–42 | Hugging Face and Fine-Tuning | Pretrained workflows, classification, token classification, QA, generation, summarization, translation, PEFT/LoRA |
| 8 | 43–50 | Large Language Models | LLM foundations, prompting, RAG, advanced RAG, evaluation, agents, multimodal LLMs, capstone |
| 9 | 51–56 | Machine Translation | SMT, NMT, multilingual Transformers, Arabic-English MT, evaluation, end-to-end MT project |
| 10 | 57–62 | Advanced NLP Applications | Advanced IR, summarization, QA, dialogue systems, multimodal NLP, final intelligent document assistant |

---

# Complete 62-Lesson Index

## Module 1 — Foundations of NLP
Folder: [`notebooks/Module_01_Foundations/`](notebooks/Module_01_Foundations/)

1. Introduction to Natural Language Processing  
2. History and Evolution of NLP  
3. NLP Pipeline  
4. Python Ecosystem for NLP  

## Module 2 — Linguistic Foundations
Folder: [`notebooks/Module_02_Linguistics/`](notebooks/Module_02_Linguistics/)

5. Language Structure and Linguistic Levels for NLP  
6. Morphology and Word Formation for NLP  
7. Syntax and Sentence Structure for NLP  
8. Semantics and Meaning Representation for NLP  
9. Pragmatics, Discourse, and Context in NLP  
10. Linguistic Resources, Corpora, and Annotation for NLP  

## Module 3 — Classical NLP
Folder: [`notebooks/Module_03_Classical_NLP/`](notebooks/Module_03_Classical_NLP/)

11. Text Preprocessing and Normalization  
12. Tokenization and Sentence Segmentation  
13. Stemming and Lemmatization in Practice  
14. Stop Words, N-Grams, and Feature Engineering  
15. Bag-of-Words and TF-IDF Representation  
16. Classical Text Classification  
17. Information Retrieval and Document Similarity  
18. Topic Modeling with Latent Dirichlet Allocation  
19. Sequence Labeling and Named Entity Recognition Foundations  
20. Classical NLP End-to-End Capstone  

## Module 4 — Word Embeddings
Folder: [`notebooks/Module_04_Word_Embeddings/`](notebooks/Module_04_Word_Embeddings/)

21. Distributional Semantics and Word Embedding Foundations  
22. Word2Vec: Skip-Gram and CBOW  
23. GloVe, FastText, and Subword-Aware Embeddings  
24. Pretrained Embeddings and Embedding-Based Text Classification  
25. Sentence and Document Embeddings  

## Module 5 — Deep Learning for NLP
Folder: [`notebooks/Module_05_Deep_Learning/`](notebooks/Module_05_Deep_Learning/)

26. Neural Network Foundations for NLP  
27. Recurrent Neural Networks for Sequence Modeling  
28. LSTM and GRU Networks for Long-Range Dependencies  
29. Sequence-to-Sequence Learning with Encoder-Decoder Networks  
30. Attention Mechanisms for Neural Sequence Models  

## Module 6 — Transformer Architectures
Folder: [`notebooks/Module_06_Transformers/`](notebooks/Module_06_Transformers/)

31. Self-Attention and Transformer Architecture Foundations  
32. Transformer Encoder Models and Contextual Embeddings  
33. Transformer Decoder Models and Autoregressive Language Modeling  
34. Transformer Encoder-Decoder Models for Conditional Generation  

## Module 7 — Hugging Face and Fine-Tuning
Folder: [`notebooks/Module_07_Hugging_Face/`](notebooks/Module_07_Hugging_Face/)

35. Pretrained Transformer Models and Hugging Face Workflows  
36. Fine-Tuning Pretrained Transformers for Text Classification  
37. Token Classification with Pretrained Transformers  
38. Question Answering with Pretrained Transformers  
39. Text Generation with Pretrained Language Models  
40. Text Summarization with Pretrained Encoder-Decoder Models  
41. Machine Translation with Pretrained Multilingual Transformers  
42. Parameter-Efficient Fine-Tuning with PEFT and LoRA  

## Module 8 — Large Language Models
Folder: [`notebooks/Module_08_LLMs/`](notebooks/Module_08_LLMs/)

43. Large Language Model Foundations, Scaling, and Instruction Tuning  
44. Prompt Engineering, In-Context Learning, and Structured Outputs  
45. Retrieval-Augmented Generation Foundations and Vector Search  
46. Advanced RAG: Dense Embeddings, Reranking, and Retrieval Evaluation  
47. LLM Evaluation, Hallucination, and Reliability  
48. LLM Agents, Tool Use, and Function Calling  
49. Multimodal Large Language Models and Vision-Language Foundations  
50. LLM Course Capstone: End-to-End Intelligent NLP Application  

## Module 9 — Machine Translation
Folder: [`notebooks/Module_09_Machine_Translation/`](notebooks/Module_09_Machine_Translation/)

51. Statistical Machine Translation  
52. Neural Machine Translation with Encoder-Decoder Networks and Attention  
53. Transformer-Based Machine Translation and Pretrained Multilingual Models  
54. Arabic-English Machine Translation: Morphology, Tokenization, and Diacritization  
55. Machine Translation Evaluation: BLEU, chrF, COMET, Semantic Similarity, and Statistical Significance  
56. Machine Translation End-to-End Project: Data Preparation, Fine-Tuning, Evaluation, and Experiment Reporting  

## Module 10 — Advanced NLP Applications
Folder: [`notebooks/Module_10_Advanced_Applications/`](notebooks/Module_10_Advanced_Applications/)

57. Advanced Information Retrieval: Neural Retrieval, Re-Ranking, and Production Search Pipelines  
58. Advanced Text Summarization: Extractive, Abstractive, Long-Document, and Faithfulness-Aware Summarization  
59. Advanced Question Answering: Extractive, Generative, Retrieval-Augmented, and Evidence-Grounded QA  
60. Conversational AI and Dialogue Systems: Intent, State Tracking, Response Generation, Memory, and Evaluation  
61. Advanced Multimodal NLP: Vision-Language Models, Document Understanding, OCR-Aware Reasoning, and Multimodal Retrieval  
62. Final End-to-End Intelligent Document Assistant Capstone: Retrieval, QA, Summarization, Multimodal Reasoning, Evaluation, and Deployment  

---

# Repository Structure

```text
Natural-Language-Processing-Course/
│
├── notebooks/
│   ├── Module_01_Foundations/
│   ├── Module_02_Linguistics/
│   ├── Module_03_Classical_NLP/
│   ├── Module_04_Word_Embeddings/
│   ├── Module_05_Deep_Learning/
│   ├── Module_06_Transformers/
│   ├── Module_07_Hugging_Face/
│   ├── Module_08_LLMs/
│   ├── Module_09_Machine_Translation/
│   └── Module_10_Advanced_Applications/
│
├── datasets/
├── figures/
├── assets/
├── projects/
├── requirements.txt
├── LICENSE
├── CITATION.cff
├── README.md
└── .gitignore
```

Exercises remain inside the educational notebooks. The public repository does not include a separate answer-key or solutions directory.

---

# Installation

Clone the repository:

```bash
git clone https://github.com/emansafwatm/Natural-Language-Processing-Course.git
cd Natural-Language-Processing-Course
```

Create a virtual environment.

### Windows PowerShell

```powershell
py -3.10 -m venv NLP_inv
.\NLP_inv\Scripts\Activate.ps1
python -m pip install --upgrade pip
pip install -r requirements.txt
```

### Linux / macOS

```bash
python3.10 -m venv NLP_inv
source NLP_inv/bin/activate
python -m pip install --upgrade pip
pip install -r requirements.txt
```

Launch Jupyter:

```bash
jupyter notebook
```

or:

```bash
jupyter lab
```

---

# Recommended Environment

## Reference Environment

**Python 3.10 is the recommended reference version for the course.**

Newer Python versions may work for many lessons, but compatibility is not guaranteed uniformly across all optional NLP, evaluation, and pretrained-model libraries.

## Hardware

For most foundational and classical lessons:

- Modern dual-core or quad-core CPU
- 8 GB RAM minimum
- 16 GB RAM recommended

For deeper neural, pretrained Transformer, LLM, or multimodal experiments:

- A CUDA-capable NVIDIA GPU is helpful but not required for the core educational path.
- GPU memory requirements depend on the selected model and fine-tuning method.

---

# Dependencies and Model Downloads

The course uses libraries such as:

- NumPy
- Pandas
- Matplotlib
- Scikit-learn
- NLTK
- spaCy
- PyTorch
- Hugging Face Transformers
- Datasets
- Tokenizers
- Sentence Transformers
- Evaluate
- Accelerate
- PEFT
- Jupyter

Install the repository requirements with:

```bash
pip install -r requirements.txt
```

### Offline vs Downloaded Models

Many notebooks use small local examples and CPU-compatible implementations for teaching and validation.

Some advanced sections demonstrate pretrained models from external model hubs. These optional workflows may require:

- internet access for the initial model/checkpoint download;
- additional packages;
- more memory;
- GPU acceleration for practical training or inference speed.

Where such models are optional, the notebook should clearly separate the downloadable workflow from the offline core demonstration.

---

# How to Use This Course

The recommended path is sequential.

For each lesson:

1. Read the conceptual explanation.
2. Run the notebook from top to bottom.
3. Inspect intermediate outputs and visualizations.
4. Modify examples and parameters.
5. Complete the knowledge check.
6. Attempt the unsolved exercises.
7. Attempt the challenge exercises.
8. Review the cited references.
9. Continue to the next lesson.

Learners with prior experience may jump directly to a later module, but the course is designed so later material builds on earlier concepts.

---

# Course Projects and Capstones

The course includes increasingly integrated practical work, including:

- classical NLP pipelines;
- text classification;
- information retrieval;
- topic modeling;
- named entity recognition;
- sequence-to-sequence systems;
- pretrained Transformer applications;
- RAG;
- LLM evaluation;
- agents and tool use;
- multimodal NLP;
- machine translation;
- advanced retrieval;
- summarization;
- question answering;
- dialogue systems;
- intelligent document processing.

Major capstones include:

- **Lesson 20:** Classical NLP End-to-End Capstone
- **Lesson 50:** LLM End-to-End Intelligent NLP Application
- **Lesson 56:** Machine Translation End-to-End Project
- **Lesson 62:** Final Intelligent Document Assistant Capstone

---

# Reproducibility and Execution Notes

The course favors reproducible educational experiments.

Where applicable, notebooks use:

- fixed random seeds;
- explicit evaluation metrics;
- error analysis;
- train/dev/test separation;
- CPU-compatible baseline implementations;
- clearly separated optional model downloads;
- experiment summaries and reproducibility notes.

For research use, learners should additionally record:

- package versions;
- model checkpoint names;
- dataset versions;
- hardware;
- training configuration;
- random seeds;
- evaluation scripts;
- preprocessing decisions.

---

# Contributing

Contributions are welcome.

Examples include:

- fixing errors;
- improving explanations;
- adding references;
- improving reproducibility;
- adding carefully scoped examples;
- improving multilingual coverage;
- reporting broken dependencies or outdated APIs.

Suggested workflow:

1. Fork the repository.
2. Create a feature branch.
3. Make and test the change.
4. Commit with a descriptive message.
5. Submit a Pull Request.

Please preserve the course's sequential organization and educational focus.

---

# References

The course draws on established textbooks, research papers, and official documentation, including:

- Jurafsky, D., & Martin, J. H. *Speech and Language Processing*.
- Eisenstein, J. *Introduction to Natural Language Processing*.
- Manning, C. D., & Schütze, H. *Foundations of Statistical Natural Language Processing*.
- Goodfellow, I., Bengio, Y., & Courville, A. *Deep Learning*.
- Vaswani, A., et al. *Attention Is All You Need*.
- Official documentation for PyTorch, Hugging Face, spaCy, NLTK, and Scikit-learn.

Additional references are provided inside individual notebooks.

---

# Citation

If you use this course in research, teaching, training, or educational material, please cite the repository.

```bibtex
@misc{Khater2026NLP,
  author       = {Eman Khater},
  title        = {Natural Language Processing: From Foundations to Large Language Models},
  year         = {2026},
  publisher    = {GitHub},
  howpublished = {\url{https://github.com/emansafwatm/Natural-Language-Processing-Course}}
}
```

The repository also includes `CITATION.cff` for GitHub-compatible citation metadata.

---

# License

This project is released under the **MIT License**.

See [`LICENSE`](LICENSE) for the complete terms.

---

# Possible Future Extensions

The core 62-lesson course is complete. Future additions, if developed, should extend the existing curriculum rather than duplicate material already covered.

Possible extensions include:

- Knowledge Graphs for NLP
- Speech and Spoken Language Processing
- Model Compression and Quantization
- Efficient LLM Inference
- Distributed Training
- Deeper AI Alignment and Preference Optimization
- Foundation-Model Evaluation Benchmarks
- Advanced Long-Context Architectures
- Production NLP/MLOps case studies

---

# Acknowledgments

This course was developed as an open educational resource for students, educators, researchers, engineers, and practitioners interested in Natural Language Processing and Artificial Intelligence.

Special thanks to the open-source community and to the researchers and developers whose libraries, datasets, models, and publications make modern NLP education possible.

---

## Support the Project

If this repository is useful to you, you can support it by:

- starring the repository;
- reporting issues;
- suggesting improvements;
- contributing educational enhancements;
- sharing it with learners and instructors.

---

# Happy Learning

> “The limits of my language mean the limits of my world.”  
> — Ludwig Wittgenstein
