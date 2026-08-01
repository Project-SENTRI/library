# General LLM & Multi-Task Capabilities Benchmarks

This section indexes foundational benchmark suites evaluated on general knowledge, instruction following, multi-task understanding, and core language capabilities across Large Language Models (LLMs).

---

## Featured Benchmarks

### 1. MMLU-Pro (Massive Multitask Language Understanding - Pro)
* **Objective:** Multi-task general knowledge and complex reasoning assessment.
* **Domain:** 14 domains including CS, Law, Physics, Engineering, Business, and Health.
* **Description:** An upgraded, robust version of the original MMLU. MMLU-Pro increases question difficulty, expands answer choices from 4 to 10 to minimize random guessing, and introduces complex multi-step reasoning questions.
* **Link:** [GitHub Repository](https://github.com/TIGER-AI-Lab/MMLU-Pro) | [Paper](https://arxiv.org/abs/2406.01574)

### 2. AlpacaEval
* **Objective:** Automated instruction-following and response quality evaluation.
* **Domain:** Open-ended user prompts and instruction execution.
* **Description:** An LLM-based automatic evaluation harness that measures how well models follow complex instructions compared to reference baseline models.
* **Link:** [GitHub Repository](https://github.com/tatsu-lab/alpaca_eval) | [Paper](https://arxiv.org/abs/2305.14387)

### 3. Chatbot Arena / LMSYS Arena Hard
* **Objective:** Human-preference rating and hard instruction execution.
* **Domain:** Open-ended user interaction, coding, and multi-turn conversations.
* **Description:** LMSYS Crowdsourced Elo-rating platform measuring real-world human preferences, combined with Arena-Hard—a benchmark designed to differentiate top-tier model performance on complex queries.
* **Link:** [GitHub Repository](https://github.com/lm-sys/FastChat) | [Website](https://chat.lmsys.org/)

### 4. HELM (Holistic Evaluation of Language Models)
* **Objective:** Comprehensive, multi-metric standard evaluation across capabilities and risks.
* **Domain:** Accuracy, Calibration, Robustness, Bias, Efficiency, and Toxicity.
* **Description:** Developed by Stanford CRFM, HELM standardizes language model evaluation across dozens of tasks, datasets, and capability dimensions simultaneously.
* **Link:** [GitHub Repository](https://github.com/stanford-crfm/helm) | [Paper](https://arxiv.org/abs/2211.09110)
