# Reasoning & Agentic Problem-Solving Benchmarks

This section indexes benchmark suites that test AI models on complex mathematical reasoning, software engineering, long-context planning, and multi-step logic.

---

## Featured Benchmarks

### 1. SWE-bench (Software Engineering Benchmark)
* **Objective:** Real-world software engineering issue resolution in complex codebases.
* **Domain:** Agentic execution, code generation, debugging, and patch synthesis.
* **Description:** Evaluates LLM agents on their ability to resolve actual GitHub issues drawn from popular open-source Python repositories by executing test suites and creating functional code patches.
* **Link:** [GitHub Repository](https://github.com/swe-bench/SWE-bench) | [Paper](https://openreview.net/forum?id=VTF8yNQM66)

### 2. GPQA (Google-Proof Q&A)
* **Objective:** Domain-expert level reasoning and knowledge verification.
* **Domain:** Graduate-level Biology, Physics, and Chemistry.
* **Description:** A challenging, multiple-choice benchmark written by domain experts designed to resist retrieval-augmented search and baseline guessing strategies.
* **Link:** [GitHub Repository](https://github.com/idavidrein/gpqa) | [Paper](https://arxiv.org/abs/2311.12022)

### 3. GSM8K & MATH
* **Objective:** Multi-step quantitative and mathematical problem solving.
* **Domain:** Elementary grade-school math through competition-level mathematics.
* **Description:** Standard benchmarks testing step-by-step mathematical logic and chain-of-thought execution, ranging from word problems (GSM8K) to high school/Olympiad level math problems (MATH).
* **Link:** [GitHub Repository (MATH)](https://github.com/hendrycks/math) | [Paper](https://arxiv.org/abs/2103.03874)

### 4. ARC-AGI (Abstraction and Reasoning Corpus)
* **Objective:** Abstract pattern recognition and fluid intelligence.
* **Domain:** Generalization, inductive logic, and spatial reasoning.
* **Description:** Created by François Chollet, ARC evaluates an AI model's ability to efficiently learn new skills and abstract rules from minimal visual examples.
* **Link:** [GitHub Repository](https://github.com/fchollet/ARC-AGI) | [Official Site](https://arcprize.org/)
