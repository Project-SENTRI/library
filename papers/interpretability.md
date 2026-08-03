# Interpretability & Mechanistic Analysis Papers

This section tracks papers investigating the inner representations, circuit analysis, and mechanistic inner workings of neural networks.

---

## Featured Papers

### 1. In-context Learning and Induction Heads (2022)
* **Authors:** Catherine Olsson, Nelson Elhage, Neel Nanda, Nicholas Joseph, et al. (Anthropic)
* **Focus:** Transformer circuits, induction heads, in-context learning mechanisms
* **Description:** Identifies "induction heads"—specific two-head transformer circuits responsible for majority of in-context learning capabilities in language models.
* **Link:** [arXiv:2209.11895](https://arxiv.org/abs/2209.11895)

### 2. Towards Monosemanticity: Decomposing Language Models with Dictionary Learning (2023)
* **Authors:** Trenton Bricken, Adly Templeton, Joshua Batson, Brian Chen, et al. (Anthropic)
* **Focus:** Sparse Autoencoders (SAEs), polysemanticity, monosemantic feature extraction
* **Description:** Applies sparse autoencoders to neural network activations to extract interpretable, monosemantic concepts from dense embedding spaces.
* **Link:** [Transformer Circuits Thread](https://transformer-circuits.pub/2023/monosemantic-features/index.html)

### 3. Locating and Editing Factual Associations in GPT (ROME) (2022)
* **Authors:** Kevin Meng, David Bau, Alex Andonian, Yonatan Belinkov
* **Focus:** Model editing, activation patching, factual knowledge localization
* **Description:** Uses causal interventions to locate specific factual storage within feed-forward layers of transformers and directly edit model memories without retraining.
* **Link:** [arXiv:2202.05262](https://arxiv.org/abs/2202.05262)
