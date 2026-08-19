# World Mechanics: AI as an Instrument for Describing Reality

## Representation, Prediction, and the Limits of Machine Understanding

**Sheshu Vardhan Akula**  
Independent Researcher / Platform Engineer  
World Mechanics — Open Research Preprint, Version 1.0  
August 2026

### Abstract

Artificial intelligence is becoming an increasingly capable instrument for representing, predicting, and controlling complex systems. In biology, models such as AlphaFold 3 and Evo 2 demonstrate that learned representations can recover useful structure across molecular and genomic domains. In physics, machine-learning methods are being used to predict properties of quantum many-body systems, process experimental quantum data, and support data-driven quantum-state control. At the same time, frontier language models exhibit internal computational structure that can support multi-step reasoning, while remaining imperfectly understood and capable of producing unfaithful explanations. These developments create a conceptual problem: when an artificial system successfully represents or predicts a part of reality, what exactly has been demonstrated about its “understanding”?

This review and position paper proposes **World Mechanics**, a five-level framework that separates representation, prediction, intervention, mechanistic explanation, and subjective experience. The central claim is deliberately conservative: success at the first four levels can be scientifically valuable without establishing the fifth. The framework is applied across large language models, biological foundation models, and AI-assisted quantum research. It argues for treating AI as a scientific instrument whose outputs should be evaluated through empirical accuracy, reproducibility, causal intervention, uncertainty, and mechanistic transparency rather than anthropomorphic language. The paper concludes with an open research programme for reproducible human-AI science.

**Keywords:** artificial intelligence; scientific machine learning; quantum systems; biological foundation models; mechanistic interpretability; cognition; consciousness; reproducibility; AI for science

---

## 1. Introduction

Scientific instruments extend human access to phenomena that are difficult or impossible to observe directly. Telescopes extend spatial reach; microscopes extend resolution; numerical simulation extends the range of tractable models. Modern artificial intelligence adds a different capability: it can learn high-dimensional representations from data and use those representations to classify, predict, generate, optimise, or control.

The significance of this capability is already visible in multiple scientific domains. AlphaFold 3 predicts joint structures of complexes containing proteins, nucleic acids, small molecules, ions, and modified residues within a unified deep-learning framework [1]. Evo 2 extends biological sequence modelling across all domains of life with a very large genomic foundation model [2]. In cell biology, universal cell embeddings and autonomous analysis agents are being developed to transfer learned structure across experiments and biological tasks [3,4]. In quantum science, classical machine learning has been applied to experimental data from superconducting quantum hardware and to the prediction of ground-state properties [5,6]. Recent work also frames AI as a general approach for representing and characterising scalable quantum systems [7].

These achievements are scientifically important, but they do not by themselves settle philosophical questions about intelligence or consciousness. A model can predict a protein complex without experiencing a molecule. It can classify a quantum phase without possessing a first-person perspective on quantum mechanics. It can generate a fluent explanation while the internal computation that produced the explanation remains partly opaque.

The purpose of this paper is therefore not to argue that AI “understands” or “does not understand” in an absolute sense. The word *understanding* is too overloaded to support useful scientific conclusions without decomposition. Instead, the paper proposes a framework that asks what kind of capability has actually been demonstrated.

The resulting position is secular and evidence-led. No religious or anti-religious premise is required. Claims are evaluated by empirical evidence, mathematical consistency, reproducibility, causal testing, and explicit acknowledgement of uncertainty.

### Scope and review method

This paper is a focused narrative review and position paper rather than a systematic review or meta-analysis. Sources were selected for direct relevance to four questions: (1) what modern AI systems can represent and predict; (2) how AI is being used in life-science and quantum-science workflows; (3) what mechanistic evidence can and cannot establish about model computation; and (4) how claims about cognition or consciousness should be separated from capability claims. Priority was given to peer-reviewed primary research and technical reviews in *Nature*, *Nature Communications*, *Nature Methods*, *npj Quantum Information*, and related venues. Preprints and laboratory technical reports are used only where they directly address interpretability or philosophy of language models and are identified as such [8,13,14]. The literature is illustrative rather than exhaustive, and the framework proposed below should be tested against additional domains and counterexamples.

## 2. AI as a Scientific Instrument

An instrument need not possess the property it measures. A thermometer need not feel heat. A spectrometer need not see colour. Likewise, an AI system need not possess human-like subjective experience in order to provide scientifically useful representations of complex systems.

This analogy has limits. Unlike traditional instruments, learned models may compress large datasets into representations whose internal organisation is not explicitly designed by humans. Their behaviour depends on architecture, objective functions, training data, optimisation dynamics, prompting, and deployment context. For this reason, treating AI as an instrument does not make it simple. It instead imposes familiar scientific obligations: calibration, error analysis, validation, reproducibility, and careful interpretation.

The distinction is particularly important for generative systems. A generated answer can be useful evidence about a model's learned representation, but it is not automatically evidence that the model has executed the reasoning described in its own text. Mechanistic interpretability research has found examples of multi-step internal computation as well as cases where a model's verbal explanation is not faithful to the mechanism that produced its answer [8]. This is a strong reason to separate observable performance from claims about internal cognition.

This instrument framing also aligns with recent work on LLMs in the scientific method, which treats models as components of a human-supervised cycle of observation, hypothesis generation, experimentation, verification, and revision rather than as automatically authoritative sources [15]. In that role, model output is a candidate contribution to a scientific workflow; validation remains an independent step.

## 3. Representation Is Not the Same as Reality

All scientific models are selective. They preserve some structure and discard other structure. A weather model is not the atmosphere; a protein structure prediction is not the living cell; a language model's embedding is not the concept itself.

AI makes this distinction easy to forget because its representations can be extraordinarily useful. In AlphaFold 3, a learned system can predict interactions across diverse biomolecular components with high accuracy relative to specialised baselines [1]. In Evo 2, genomic sequence regularities are learned across a very large corpus spanning domains of life [2]. These results demonstrate that data-driven representations can contain scientifically valuable structure.

But representation should be assessed by what it enables: generalisation to new cases, prediction of withheld observations, recovery of experimentally meaningful structure, robustness under perturbation, and consistency with known constraints. A representation is scientifically stronger when it survives tests that were not used to construct it.

This suggests a first principle for World Mechanics:

> **A useful representation earns scientific status through predictive and experimental consequences, not through the fluency with which it can be described.**

## 4. Prediction, Reasoning, and Explanation

Prediction is a measurable relation between inputs and outputs. Reasoning is more difficult to define because it can refer to behaviour, internal computation, or a human-readable justification. Explanation adds another layer: an explanation should identify a mechanism, dependency, or model that makes an outcome intelligible and testable.

Language models complicate these categories because they can produce explicit chains of reasoning. Recent circuit-tracing work on a frontier language model reported internal structures consistent with multi-step processing in selected tasks, including intermediate representations connecting facts across steps [8]. The same research also showed that chain-of-thought text can be unfaithful: a model may generate a plausible rationale that does not accurately reflect the computation that led to the answer [8].

This means neither of two extreme positions is justified. It is too strong to say that language models are merely static lookup tables: mechanistic work demonstrates input-dependent internal computation. But it is also too strong to infer human-like understanding from fluent reasoning traces. Philosophical analyses of language models similarly emphasise that questions about semantic competence, grounding, world models and cognition require empirical investigation of what the systems actually represent and compute, rather than conclusions drawn from surface fluency alone [14]. The scientifically defensible position is to investigate the mechanisms and their limits.

## 5. Human Cognition as a Modelling Target

The boundary between machine and human intelligence is also complicated by the fact that aspects of human behaviour can themselves be modelled computationally. Centaur, a foundation model for human cognition, was trained across many psychological experiments and shown to predict human behaviour across a range of tasks [9]. Such work demonstrates that measurable regularities in human cognition can be captured by large computational models.

This should not be interpreted as a reduction of human subjective experience to a single predictive model. Predicting behaviour is not identical to reproducing every biological or experiential process that generates it. However, the result weakens an overly simple distinction in which “humans understand” while “machines merely predict.” Humans also produce behaviour with regularities that can be predicted, while machines can contain internal computational structure that is richer than their surface output alone reveals.

The more useful research question is therefore: **which properties of intelligence are being measured, and what evidence supports each property?**

## 6. AI and the Life Sciences

Life sciences provide one of the clearest demonstrations of AI as a high-value scientific instrument. Biological systems are multiscale, combinatorial, and data-rich. They therefore create a natural role for representation learning.

AlphaFold 3 demonstrates unified prediction across biomolecular interactions, including proteins, nucleic acids, small molecules, ions, and modified residues [1]. Its importance is not that the model “experiences” molecular structure; it is that its predictions can be compared against experimentally determined structures using quantitative metrics.

Evo 2 extends the foundation-model approach to genomic sequence. The model was trained on trillions of DNA bases across all domains of life and targets both predictive and generative genomic tasks [2]. The scale of this training does not guarantee biological truth, but it provides a large learned representation from which hypotheses can be generated and tested.

In 2026, further work demonstrated a universal cell embedding intended to transfer information across cell biology datasets [3]. CellVoyager explored AI agents that autonomously analyse complex biological data and generate candidate insights [4]. Robin integrated literature-search and data-analysis agents in a system designed to support iterative scientific discovery [10]. Together, these systems show an emerging pattern: AI is moving from isolated prediction toward integrated scientific workflows.

This progression increases the need for validation. Autonomous hypothesis generation does not remove the requirement for experimental confirmation. If anything, systems that can generate hypotheses rapidly increase the burden on methods for prioritisation, uncertainty estimation, provenance, and reproducibility.

## 7. AI and Quantum Systems

Quantum mechanics is an attractive domain for AI because the dimensionality of quantum state spaces creates severe computational challenges. However, the phrase “AI understands quantum mechanics” should be avoided unless the term *understands* is defined operationally.

A more precise claim is that AI and machine-learning methods can support specific quantum tasks. Lewis and colleagues developed a classical machine-learning algorithm for predicting ground-state properties with an inductive bias based on geometric locality [6]. Cho and Kim applied classical machine learning to experimental data obtained from superconducting quantum hardware, demonstrating tasks including ground-state property prediction and phase classification with systems up to dozens of qubits [5].

More recent work has expanded the scope. A 2026 technical review describes AI approaches for quantum property prediction and quantum-system reconstruction, including machine learning, deep learning, and language-model-based approaches [7]. A separate 2025 review surveys AI across the quantum-computing stack, including device design, control, optimisation, error correction and post-processing [16]. Data-driven state representations have also been used with reinforcement learning to control unknown quantum states from limited measurement information [11]. Work on learning quantum observables continues to clarify where classical and quantum learning advantages may arise [12].

These results support a practical interpretation: AI can be part of the measurement, representation, inference, and control stack for quantum systems. They do not imply that a model has a subjective grasp of superposition, entanglement, or measurement.

## 8. The World Mechanics Five-Level Framework

World Mechanics proposes five levels for discussing increasingly strong claims about an intelligent system. The levels are not presented as a psychological theory or a validated scale of consciousness. They are a conceptual framework for preventing category errors.

### Level 1 — Representation

The system constructs an internal or external encoding that preserves useful structure in data.

**Evidence:** embeddings, reconstructed states, learned features, compression, transfer learning.

### Level 2 — Prediction

The system uses representations to forecast, classify, generate, or estimate observations beyond the immediate training examples.

**Evidence:** held-out accuracy, calibration, out-of-distribution performance, benchmark results, prospective validation.

### Level 3 — Intervention and Control

The system selects actions or interventions that reliably change a target system in predicted ways.

**Evidence:** closed-loop control, causal interventions, experimental optimisation, successful manipulation under constraints.

### Level 4 — Mechanistic Explanation

The system's relevant computation can be mapped to mechanisms, dependencies, or causal structures that are independently testable.

**Evidence:** causal tracing, ablations, activation interventions, interpretable intermediate variables, reproducible mechanistic models.

### Level 5 — Subjective Experience

The system possesses first-person phenomenal experience: there is something it is like to be that system.

**Evidence:** consciousness research can derive theory-based indicator properties, but there is no generally accepted operational test that establishes subjective experience in an artificial system. A prominent multidisciplinary assessment proposed computational indicators grounded in neuroscientific theories and concluded that the AI systems it examined did not satisfy a case for consciousness, while also arguing that future systems should be assessed empirically rather than by surface behaviour alone [13].

The key claim is:

> **Evidence for Levels 1–4 does not logically establish Level 5.**

This separation allows strong claims about AI capability without silently importing claims about consciousness.

## 9. Why Language Matters

Natural language is becoming a general-purpose control surface for artificial intelligence. Humans can express goals, constraints, hypotheses, code, mathematical structure, or experimental plans in language; models transform those instructions into actions, representations, or tool calls.

This makes language more than a communication layer. It is increasingly an interface between human intention and computational systems. Yet language can also encourage anthropomorphism. Words such as *think*, *know*, *want*, and *understand* are convenient shorthand, but they can obscure the distinction between observed behaviour and inferred mental state.

World Mechanics therefore adopts a simple rule: anthropomorphic language may be used informally, but scientific claims should be translated into operational terms whenever possible.

This is consistent with the broader philosophical debate around language models: linguistic competence, internal representation, grounding, cognition and consciousness are related but non-identical questions, and evidence for one should not be silently substituted for evidence for another [14].

Instead of “the model knows X,” ask whether X can be decoded from internal representations or reliably used in new tasks. Instead of “the model understands the experiment,” ask whether it can predict outcomes, identify causal variables, design discriminating tests, or adapt after contradictory evidence.

## 10. Human–AI Scientific Collaboration

The strongest near-term model of AI-assisted science is collaboration with explicit human responsibility. Humans contribute goals, domain values, experimental context, ethical judgement, and accountability. AI systems contribute search, representation, simulation, generation, optimisation, and increasingly complex automated workflows. Recent reviews of LLMs in science similarly emphasise human alignment, evaluation metrics, and verification when models participate in the scientific cycle [15].

This collaboration should be designed as an observable system. Every transformation from source to conclusion should preserve provenance. Model outputs should be linked to evidence. Computational experiments should be versioned. Environments should be reproducible. Negative results and limitations should be recorded rather than hidden.

This is where platform engineering becomes scientifically relevant. Research software is infrastructure. Reproducible science depends on reliable environments, versioned code, automated tests, data provenance, monitoring, and repeatable deployment. These practices are common in production engineering and should be treated as part of the research method rather than administrative overhead.

## 11. Proposed Open Research Programme

World Mechanics is intended as an open programme rather than a single essay. The next stages should move from conceptual synthesis to executable experiments.

### Experiment A — Prediction vs explanation

Select a small open model and a benchmark requiring multi-step reasoning. Compare answer accuracy, stated chain-of-thought or concise rationale, and mechanistic probes. Test whether changes to internal features causally affect intermediate steps.

### Experiment B — AI-assisted quantum toy system

Use a classical simulator for a small spin system. Train a simple model to predict an observable or phase from generated data. Publish the simulator, training code, held-out evaluation, and error analysis.

### Experiment C — Biological sequence representation

Use an openly licensed biological dataset and an open sequence model. Evaluate whether embedding-space structure predicts a biologically meaningful label better than a simple baseline. Explicitly separate correlation from causal biological explanation.

### Experiment D — Reproducibility layer

Package each experiment in containers with fixed dependencies, automated tests, provenance metadata, and one-command execution. Track model versions, dataset checksums, random seeds, and evaluation outputs.

These experiments would turn World Mechanics from a position paper into a cumulative research portfolio.

## 12. Limitations

This paper is a review and position paper, not a report of new laboratory discoveries. It does not establish that any current artificial system is conscious, nor does it prove that artificial consciousness is impossible. Assessments of AI consciousness remain theory-dependent and contested; current proposals rely on indicator properties rather than a decisive test [13]. The five-level framework is not a validated psychological scale. It is intended to clarify categories of evidence and should itself be criticised, tested and revised.

The literature reviewed here is rapidly evolving. Many AI systems are proprietary, which limits reproducibility and mechanistic access. Benchmarks can overestimate generalisation. Biological and quantum applications may inherit biases from training data, measurement processes, or simulation assumptions. Finally, scientific utility can exist even when interpretability is incomplete; therefore mechanistic transparency should be pursued without pretending that it is always immediately attainable.

## 13. Conclusion

AI is becoming an important instrument for describing and manipulating parts of the physical and biological world. Its scientific value can be established through representation quality, prediction, intervention, and mechanistic investigation without requiring claims about subjective experience.

The World Mechanics framework separates those claims into five levels. It treats machine intelligence neither as magic nor as trivial pattern matching. Instead, it asks for evidence appropriate to each capability.

The research programme that follows is practical: build models, test them, trace mechanisms where possible, publish code and data, preserve provenance, and state uncertainty. The objective is not to make machines sound human. It is to use computation to expand what humans can investigate while remaining precise about what has—and has not—been demonstrated.

---

## AI-Assistance and Authorship Statement

The author used generative AI as a research and drafting assistant for literature discovery, synthesis, language editing, and software prototyping. The author remains responsible for the selection of claims, interpretation, verification of references, publication decisions, and any errors in the final work. AI systems are not listed as authors.

## Conflict of Interest

No conflict of interest is declared for this independent research draft.

## References

1. Abramson J, Adler J, Dunger J, et al. Accurate structure prediction of biomolecular interactions with AlphaFold 3. *Nature*. 2024;630:493–500. doi:10.1038/s41586-024-07487-w.
2. Brixi G, et al. Genome modelling and design across all domains of life with Evo 2. *Nature*. 2026. doi:10.1038/s41586-026-10176-5.
3. Rosen Y, Roohani Y, Agrawal A, et al. Universal cell embedding provides a foundation model for cell biology. *Nature*. 2026. doi:10.1038/s41586-026-10689-z.
4. Alber S, Chen B, Sun E, et al. CellVoyager: AI CompBio agent generates new insights by autonomously analyzing biological data. *Nature Methods*. 2026;23:749–759. doi:10.1038/s41592-026-03029-6.
5. Cho G, Kim D. Machine learning on quantum experimental data toward solving quantum many-body problems. *Nature Communications*. 2024;15:7552. doi:10.1038/s41467-024-51932-3.
6. Lewis L, Huang H-Y, Tran VT, et al. Improved machine learning algorithm for predicting ground state properties. *Nature Communications*. 2024;15:895. doi:10.1038/s41467-024-45014-7.
7. Du Y, Zhu Y, Zhang Y-H, et al. Artificial intelligence for representing and characterizing quantum systems. *Nature Reviews Physics*. 2026. doi:10.1038/s42254-026-00962-5.
8. Lindsey J, Gurnee W, Ameisen E, et al. On the Biology of a Large Language Model. *Transformer Circuits Thread*. 2025. https://transformer-circuits.pub/2025/attribution-graphs/biology.html
9. Binz M, Akata E, Bethge M, et al. A foundation model to predict and capture human cognition. *Nature*. 2025;644:1002–1009. doi:10.1038/s41586-025-09215-4.
10. Ghareeb AE, Chang B, Mitchener L, et al. A multi-agent system for automating scientific discovery. *Nature*. 2026;655:497–505. doi:10.1038/s41586-026-10652-y.
11. Zhu Y, Xiao T, Zeng G, Chiribella G, Wu Y-D. Controlling unknown quantum states via data-driven state representations. *npj Quantum Information*. 2026. doi:10.1038/s41534-026-01269-0.
12. Molteni R, Gyurik C, Dunjko V. Exponential quantum advantages in learning quantum observables from classical data. *npj Quantum Information*. 2026;12:19. doi:10.1038/s41534-025-01162-2.
13. Butlin P, Long R, Elmoznino E, et al. Consciousness in Artificial Intelligence: Insights from the Science of Consciousness. *arXiv preprint*. 2023. arXiv:2308.08708.
14. Millière R, Buckner C. A Philosophical Introduction to Language Models — Part I: Continuity With Classic Debates. *arXiv preprint*. 2024. arXiv:2401.03910.
15. Zhang Y, Khan SA, Mahmud A, et al. Exploring the role of large language models in the scientific method: from hypothesis to discovery. *npj Artificial Intelligence*. 2025;1:14. doi:10.1038/s44387-025-00019-5.
16. Alexeev Y, Farag MH, Patti TL, et al. Artificial intelligence for quantum computing. *Nature Communications*. 2025;16:10829. doi:10.1038/s41467-025-65836-3.
