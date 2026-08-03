# Interpretability & Mechanistic Analysis Tools

This section indexes tools, visualizers, and libraries designed to inspect neural network weights, analyze transformer circuits, extract features, and probe model internals.

---

## Featured Tools

### 1. TransformerLens
* **Developer:** Neel Nanda
* **Focus:** Mechanistic Interpretability, Activation Patching, Transformer Circuits
* **Description:** A PyTorch library designed for mechanistic interpretability of generative language models, allowing researchers to inspect intermediate activations, perform activation patching, and trace internal circuits.
* **Link:** [GitHub Repository](https://github.com/neelnanda-io/TransformerLens)

### 2. Captum
* **Developer:** PyTorch (Meta)
* **Focus:** Model Interpretability, Integrated Gradients, Feature Attribution
* **Description:** A comprehensive model interpretability library for PyTorch providing state-of-the-art gradient-based and attribution algorithms to understand feature importance and neuron behavior.
* **Link:** [GitHub Repository](https://github.com/pytorch/captum) | [Official Site](https://captum.ai/)

### 3. SAE Lens (Sparse Autoencoder Lens)
* **Developer:** Delphia / Alignment Research Community
* **Focus:** Sparse Autoencoders (SAEs), Monosemantic Feature Extraction
* **Description:** A library built specifically for training, analyzing, and evaluating Sparse Autoencoders (SAEs) on language model activations to extract monosemantic concepts.
* **Link:** [GitHub Repository](https://github.com/jbloomAus/SAELens)

### 4. NNsight
* **Developer:** NDIF (National Deep Inference Fabric)
* **Focus:** Deep Model Probing, Cross-Layer Interventions, Large Scale Mechanistic Analysis
* **Description:** An open-source Python package that provides a clean syntax for inspecting and editing the internal states and activations of large neural networks locally or remotely.
* **Link:** [GitHub Repository](https://github.com/ndif-team/nnsight) | [Documentation](https://nnsight.net/)
