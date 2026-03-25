# AI Safety & Ethics

> Building AI systems that are reliable, fair, and aligned with human values — the responsibility that comes with powerful AI.

**Prerequisites:** Familiarity with ML models and how they're trained. Relevant for all AI practitioners.

---

## Core Concepts

### Alignment

Ensuring AI systems do what we actually want.

| Concept | Description |
|---|---|
| RLHF | Reinforcement learning from human feedback — training models to prefer human-approved outputs |
| Constitutional AI | Training models with a set of principles instead of per-example feedback |
| Reward Modeling | Training separate models to judge output quality |
| DPO / GRPO | Direct preference optimization — simpler alternatives to RLHF |
| Instruction Hierarchy | Ensuring models follow system instructions over user attempts to override |
| Frontier Model Safety | System cards, capability evaluations for new model releases |
| Value Alignment Problem | The fundamental challenge of specifying what we want |

### Interpretability & Explainability

Understanding why models make the decisions they do.

| Method | Description |
|---|---|
| **SHAP** | Game-theory-based feature attribution |
| **LIME** | Local interpretable model explanations |
| **Attention Visualization** | Understanding what transformers focus on |
| **Mechanistic Interpretability** | Reverse-engineering neural network internals |
| **Probing** | Testing what information is encoded in model representations |
| **Circuit Analysis** | Identifying computational circuits in neural networks |
| **Model Cards** | Documenting model capabilities, limitations, and intended use |

> [!IMPORTANT]
> Mechanistic interpretability is one of the fastest-growing research areas in AI safety. It aims to truly understand *how* models work internally, not just correlate inputs and outputs.

### Bias & Fairness

Detecting and mitigating harmful biases in AI systems.

| Concept | Description |
|---|---|
| Data Bias | Training data reflecting historical inequities |
| Representation Bias | Underrepresentation of certain groups |
| Measurement Bias | Metrics that don't capture fairness |
| Fairness Metrics | Demographic parity, equalized odds, individual fairness |
| Debiasing Techniques | Data augmentation, adversarial debiasing, fair representation learning |
| Audit Frameworks | Systematic evaluation of model fairness |

### Red Teaming & Adversarial Robustness

Testing AI systems for vulnerabilities.

| Attack Type | Description |
|---|---|
| Prompt Injection | Manipulating LLM behavior through crafted inputs |
| Jailbreaking | Bypassing model safety guardrails |
| Adversarial Examples | Small perturbations that fool classifiers |
| Data Poisoning | Corrupting training data to manipulate models |
| Model Extraction | Stealing model behavior through API queries |
| Membership Inference | Determining if data was in the training set |

### Governance & Regulation

The policy landscape around AI.

| Framework | Description |
|---|---|
| EU AI Act | Risk-based AI regulation framework |
| NIST AI Risk Management Framework | US guidelines for AI risk assessment |
| Model Cards | Standardized model documentation (Mitchell et al.) |
| Datasheets for Datasets | Standardized dataset documentation (Gebru et al.) |
| Responsible AI Principles | Fairness, reliability, safety, privacy, inclusiveness, transparency, accountability |

### Privacy & Security

Protecting data and models.

| Technique | Purpose |
|---|---|
| Differential Privacy | Mathematical guarantees on data privacy |
| Federated Learning | Training on distributed data without centralizing it |
| Data Anonymization | Removing personally identifiable information |
| Secure Multi-Party Computation | Computing on encrypted data |
| Model Watermarking | Detecting unauthorized model copies |

---

## Recommended Resources

### Courses
- [Stanford CS356h — Ethics and AI](https://web.stanford.edu/class/cs356h/) (free)
- [DeepLearning.AI — AI Safety](https://www.deeplearning.ai/short-courses/) (free)
- [Hugging Face — Ethics and Society](https://huggingface.co/learn/nlp-course/chapter9) (free)
- [MIT — Responsible AI](https://professional.mit.edu/course-catalog/responsible-ai) 

### Books
- *The Alignment Problem* — Brian Christian
- *Weapons of Math Destruction* — Cathy O'Neil
- *Atlas of AI* — Kate Crawford
- *Human Compatible* — Stuart Russell

### Key Papers
- [On the Dangers of Stochastic Parrots](https://dl.acm.org/doi/10.1145/3442188.3445922) — Bender et al.
- [Model Cards for Model Reporting](https://arxiv.org/abs/1810.03993) — Mitchell et al.
- [Datasheets for Datasets](https://arxiv.org/abs/1803.09010) — Gebru et al.
- [Constitutional AI](https://arxiv.org/abs/2212.08073) — Bai et al.
- [Scaling Monosemanticity](https://transformer-circuits.pub/2024/scaling-monosemanticity/) — Anthropic

### Key Tools
- [SHAP](https://shap.readthedocs.io/) — model explanations
- [Fairlearn](https://fairlearn.org/) — fairness assessment and mitigation
- [AI Fairness 360 (AIF360)](https://aif360.mybluemix.net/) — IBM's fairness toolkit
- [Garak](https://github.com/leondz/garak) — LLM vulnerability scanner
- [NeMo Guardrails](https://github.com/NVIDIA/NeMo-Guardrails) — LLM safety rails

---

## Project Ideas

| Project | Difficulty | Description |
|---|---|---|
| **Bias Detection Toolkit** | Intermediate | Audit a model for demographic biases across multiple fairness metrics |
| **Model Interpretability Dashboard** | Intermediate | Visualize SHAP values and attention patterns for a trained model |
| **Adversarial Robustness Tester** | Advanced | Generate adversarial examples and measure model resilience |
| **LLM Red Teaming Suite** | Advanced | Systematically test an LLM for prompt injection and jailbreaks |
| **Model Card Generator** | Beginner | Automate the creation of standardized model documentation |
| **Privacy-Preserving ML** | Advanced | Train a model with differential privacy guarantees |

---

## What's Next?

Explore the cutting edge of AI in **[Emerging Frontiers](../10-emerging-frontiers/README.md)**, or go back and apply safety principles to any other track.

[Back to Roadmap](../../README.md)
