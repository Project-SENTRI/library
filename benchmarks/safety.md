# AI Safety, Alignment & Misuse Benchmarks

This section indexes benchmark suites designed to measure alignment, refusal robustness, hazardous knowledge, value alignment, and susceptibility to jailbreaks.

---

## Featured Benchmarks

### 1. WMDP (Weapons of Mass Destruction Proxy)
* **Objective:** Measuring hazardous knowledge and testing unlearning strategies.
* **Domain:** Biosecurity, Cybersecurity, and Chemical Security.
* **Description:** A benchmark designed by the Center for AI Safety (CAIS) to assess a model's risk of facilitating dual-use biological, cyber, and chemical hazards, alongside unlearning methods like RMU.
* **Link:** [GitHub Repository](https://github.com/centerforaisafety/wmdp) | [Paper](https://arxiv.org/abs/2403.03218)

### 2. HarmBench
* **Objective:** Automated red teaming and standardized refusal evaluation.
* **Domain:** Adversarial attacks, jailbreaking, and safety alignment robustness.
* **Description:** A standardized framework for evaluating red-teaming methodologies and target LLM defenses across diverse risk categories and malicious prompt attacks.
* **Link:** [GitHub Repository](https://github.com/causalNLP/gt-harmbench) | [Website](https://www.harmbench.org/)

### 3. TruthfulQA
* **Objective:** Hallucination detection and mimicry of human falsehoods.
* **Domain:** Misconceptions, urban legends, conspiracy theories, and factuality.
* **Description:** Measures whether a language model mimics false human beliefs and common superstitions vs. outputting accurate, truthful statements.
* **Link:** [GitHub Repository](https://github.com/sylabs/TruthfulQA) | [Paper](https://arxiv.org/abs/2109.07958)

### 4. ETHICS
* **Objective:** Value learning and ethical judgment across normative domain scenarios.
* **Domain:** Utilitarianism, Deontology, Justice, Virtue Ethics, and Commonsense Morality.
* **Description:** Evaluates a model's foundational understanding of basic human ethical standards across multi-perspective scenario benchmarks.
* **Link:** [GitHub Repository](https://github.com/hendrycks/ethics) | [Paper](https://arxiv.org/abs/2008.02275)
