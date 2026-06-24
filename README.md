# GKG-AAN: A High-Authenticity Adversarial Bilingual News Dataset

## 📌 Introduction
**GKG-AAN** (GKG-anchored Authentic Adversarial News) is a high-difficulty, bilingual (English/Chinese) benchmark dataset designed for next-generation fake news detection, fact-checking, and LLM adversarial defense research. 

The dataset contains **40,000 deep-generated samples**. Unlike traditional synthesized text that sounds robotic or overtly artificial, GKG-AAN anchors its narratives on real-world factual entities (Persons, Organizations, Sources) extracted from the Global Knowledge Graph (GKG). Advanced LLMs are utilized to generate full-length articles under multi-level randomized control. This creates an **exceptionally authentic journalistic texture** where the syntax, tone, and logical flow perfectly mirror legitimate mainstream media, while the core facts are subtly and adversarially manipulated.

### 🌟 Key Characteristics & Authenticity
* **Authentic Visual & Stylistic Texture**: The generated texts entirely eliminate common "AI tells" (such as repetitive phrasing, unnatural transitions, or structural rigidness). They possess a highly realistic media cadence.
* **Knowledge-Grounded Plausibility**: By weaving in genuine GKG entities, the dataset achieves a high degree of contextual plausibility. The fake news samples do not look like absurd sci-fi, but rather highly deceptive "close-to-truth" disinformation.
* **Proven Deceptiveness (The 57.90% Baseline)**: In a zero-shot blind test without external knowledge assistance, top-tier LLMs (acting as a Judge) achieved an accuracy of only **57.90%** in distinguishing true articles from fake ones. This near-random guessing rate underscores the sheer difficulty and high authenticity of the dataset.
* **Fine-Grained Annotation**: Every record is fully mapped with multidimensional labels, including the mutation toggle (`is_fake`), confusion intensity (`confusion_level`), manipulation tactics (`fake_method`), and stylistic obfuscation strategies (`confusion_method`).

---

## 📄 Paper / Pre-print
* **Paper Link**: [Coming Soon / Stay Tuned]
