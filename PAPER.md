# World Mechanics

**Artificial intelligence as an instrument of physical description, quantum systems, and the asymmetry of understanding**

Sheshu Vardhan Akula  
Independent researcher · DevOps / platform engineer working with AI  
August 2026

**Status:** preprint draft for open posting (personal site + optional arXiv). This is not a peer-reviewed journal article. Claims below are synthesis and argument, not new experimental results.

**License:** CC BY 4.0 (free to read, share, and adapt with attribution)

---

## Abstract

Two computing programmes now sit inside the same laboratories: large-scale artificial intelligence and controllable quantum systems. A third, older programme — the scientific description of living matter — is being rewritten by both. This paper treats those intersections as *world mechanics*: the use of computational instruments to represent, search, and approximate the physical descriptions we already have, rather than as a substitute for physics or a new kind of mind.

Three claims are defended. First, quantum mechanics remains the best public language for microscopic physical systems; AI is useful here as a representation and search engine (wave-function characterisation, circuit synthesis, many-body approximation), not as a metaphysical upgrade. Second, the credible core of “quantum biology” is narrow and evidence-constrained: enzymatic hydrogen tunnelling and radical-pair spin chemistry are the most mature cases; long-lived functional electronic coherence in warm tissue remains contested. Third, current AI systems can be understood as statistical and mechanistic objects. They do not have emotions. Human intelligence is not derived from them. The useful comparison is functional and physical, not spiritual.

The paper reviews 2025–2026 work on AI for quantum characterisation, AI-generated quantum circuits for molecular simulation, quantum-many-body “AI physicists,” and generative AI in the life sciences. It then states limits: preprints are not peer review; fluency is not feeling; quantum language is not a licence for mysticism.

**Keywords:** quantum machine learning; quantum biology; mechanistic interpretability; life-sciences AI; philosophy of mind (physicalist)

---

## 1. Introduction: a language for the world

Human intelligence talks about the world in many dialects — ordinary speech, mathematics, experiment. Physics is the dialect that has been forced, over four centuries, to survive contact with measurement. Quantum theory is that dialect at small scales: amplitudes, operators, decoherence, and the statistics of outcomes.

Artificial intelligence, as it exists in 2026, is not another dialect of nature. It is an instrument. A model is a parameterised function trained to predict, generate, or control. When we “talk to” a language model, we are not entering a second mind. We are steering a next-token machine with words. Those words can still be useful. They can retrieve, compress, and recombine descriptions that humans already wrote. They can, in narrower systems, propose circuits, wave-function representations, or molecular candidates that then have to face experiment.

This paper is atheist-friendly in a precise sense. It assumes:

1. There is one physical world.
2. Scientific claims are those that can, in principle, be checked against observation.
3. Subjective experience in humans is a biological fact to be explained, not a licence to project experience onto software.
4. No extra substance — soul, spirit, cosmic mind — is required to state the arguments below.

The title *world mechanics* is therefore not poetry first. It is a job description: use computation to do mechanics of the world we actually have.

---

## 2. What “talking to AI” is

A large language model is trained to assign probabilities to tokens given context. The public interface looks like conversation. The mechanism is not conversation in the human sense.

Useful distinctions:

| Human-facing phrase | More accurate description |
|---|---|
| “It understands” | It produces outputs that match patterns of competent use in its training distribution and generalise within that family of tasks. |
| “It thinks” | It performs multi-step computation in weights, activations, and (often) a scratchpad of generated tokens. |
| “It feels” | There is no evidenced affective system: no body, no interoception, no valence circuitry homologous to animals. |
| “We derived human intelligence from AI” | False. Biological nervous systems evolved. Current AI was engineered, trained on human-generated data, and remains a different substrate. |

This is not a claim that AI is “just a calculator” in a dismissive sense. Modern models are extremely high-dimensional function approximators. They can be studied. Mechanistic interpretability tries to read internal features, circuits, and (in recent work) privileged reportable representations analogous to a global workspace at the *functional* level. That research is important. It is not a demonstration of phenomenal experience.

A 2026 line of work identifies verbalizable internal representations in language models — a small set of states the model can report and manipulate amid a much larger volume of automatic processing. That is a claim about access and control, not about what it is like to be the model. Authors of related synthetic tests of consciousness theories are explicit: the agents are reference implementations, not conscious beings.

The asymmetry is therefore worth keeping:

- Human intelligence is not derived from artificial intelligence.
- Artificial intelligence can still be understood (as engineering and as science).
- Human intelligence can be understood *to some extent* as a physical and computational system, without pretending that the current maps are complete.
- The missing piece in the machine is not a soul. It is, at minimum, the biological organisation that makes emotion and sensation possible in animals — and, more strongly, whatever additional conditions (if any) are required for subjective experience. Those conditions are not known to be satisfied by present models.

---

## 3. AI as an instrument for quantum description

The hard problem of many-body quantum systems is representation. The state space grows exponentially with particle number. Experiment gives partial views. Theory gives Hamiltonians we often cannot solve.

Recent work organises AI for this problem into overlapping paradigms: classical machine learning with guarantees, deep networks as wave-function ansatze, and language-model-style generators for circuits and protocols.

### 3.1 Representing and characterising quantum systems

A 2026 *Nature Reviews Physics* technical review frames two core tasks: predicting properties of scalable quantum systems, and reconstructing approximate descriptions of those systems from data. Efficient learning methods have been designed for linear properties and for classifying quantum phases. The point is not that the network “is” the quantum state in any mystical sense. The network is a compressed, queryable surrogate.

Neural representations of many-body wave functions have also been trained from probability and probability-current data, then used as pre-training for harder interacting problems, including fractional quantum Hall-type states. Overlaps reported in that literature are high on the tested cases; the scientific question remains scaling, physical inductive bias, and honesty about where the representation fails.

### 3.2 Circuits for molecules

A practical bridge into life sciences is electronic structure. Variational quantum algorithms spend much of their cost inventing a circuit that prepares an approximate ground state. Work reported in 2026 from teams including Quantinuum, NVIDIA, and Pfizer trains generative models (transformer-like generators plus reinforcement learning) to propose those circuits for molecular simulation, with large reported reductions in circuit-generation time relative to ADAPT-VQE on benchmarks, and execution of generated circuits on commercial hardware for a pharmaceutical molecule (imipramine).

If those results hold under wider scrutiny, the pattern is exactly world mechanics: AI searches a discrete space of quantum programmes; physics still decides whether the energy is right.

### 3.3 “AI physicists” and verifiable workflows

Two complementary worries dominate this literature. Language models hallucinate. Scientific code must not. Benchmarks such as QMP-Bench extract research-level quantum many-body tasks from high-impact journals and show that unaided models still fail often. Multi-agent frameworks that force programming checks and physics checks (self-correction, principle-based verifiers) improve reliability. Separate workflows that split theory extraction, formal specification, and implementation raise success rates on algorithms such as DMRG compared with “just write the code.”

This is the right epistemic posture: treat the model as a fallible junior theorist whose outputs must be forced through conservation laws, symmetries, and numerical tests.

### 3.4 Generative quantum models

A different claim is *advantage*: families of generative quantum models that are hard to simulate classically, trainable without the usual barren-plateau story, and demonstrated on large superconducting processors for learning classically intractable distributions and for learning circuits that accelerate physical simulation. That is a hardware-plus-theory result. It does not make the model a mind. It makes a particular sampling task cheaper on a quantum device.

---

## 4. Life sciences: molecules, cells, and the temptation to overclaim

AI in the life sciences is no longer a side tool. Protein structure prediction is a routine input. Generative models propose backbones and sequences. Multi-agent systems draft hypotheses and analysis plans. Genome-scale sequence models exist. The infrastructure story in 2026 is compute and platforms, not a single magic molecule.

A useful brake appears in a 2026 *Cell* perspective that lists fifteen challenges for generative AI at the *cellular* scale. Molecular successes do not automatically become reliable models of cells, tissues, and disease. Data are sparse relative to the combinatorial reality of cell states. Phenotypes are multicellular. That paper is a map of what is still missing.

For this project, the honest join between quantum and biology is not “quantum consciousness.” It is:

1. **Quantum for biology** — using quantum computers and quantum-inspired algorithms to simulate molecules and materials that matter to drugs and enzymes.
2. **Quantum in biology** — asking where living systems actually use non-classical physical effects.

A 2026 evidence map of the quantum–biology interface is careful. The most mature “quantum in biology” cases remain mechanistically constrained tunnelling in some enzymatic hydrogen-transfer reactions, and radical-pair spin chemistry as a viable framework for magnetoreception. Photosynthetic complexes show ultrafast oscillatory signals that can be modelled with coherent or vibronically mixed excitonic dynamics; whether those signals are *functionally* long-lived electronic coherences under physiological conditions is still debated, because vibrations and ensemble effects can mimic the signatures.

That is the scientific attitude this paper adopts. Warm, wet tissue is a hostile place for delicate superposition. Sometimes quantum kinetics still matters. Sometimes a classical story is enough. The experiment decides.

---

## 5. World mechanics: a compact framework

The following is a working ontology for this site and for later work. It is not a new physical theory.

**Level 0 — World.**  
One spacetime, quantum fields or their effective descendants, chemistry, organisms. No second world.

**Level 1 — Description.**  
Hamiltonians, rate equations, statistical models, diagrams. These are human-made objects that earn their keep by predicting measurements.

**Level 2 — Instrument.**  
Telescopes, sequencers, quantum processors, neural networks. Instruments transform data and search description-space. They are not additional substances.

**Level 3 — Interface language.**  
Natural language, code, circuit diagrams, lab protocols. This is how humans steer instruments and how instruments return results. Fluency at the interface is easy to mistake for a person on the other side.

**Level 4 — Understanding.**  
A system (human or machine) *understands* a domain, in the modest sense used here, when it can be used to generate reliable, checkable predictions and interventions in that domain, and when its failures are localisable. Human understanding also typically includes feeling, care, and a body. Machine “understanding” in 2026 is the first half at best.

This framework forbids two popular errors:

- **Animism of the model.** Because it speaks, it must feel.
- **Dismissal of the model.** Because it does not feel, it cannot be a scientific instrument.

Both are lazy.

---

## 6. Limits, ethics, and publication honesty

**This document is a synthesis.** It does not report a new wet-lab result, a new theorem, or a new trained foundation model. Anyone using it in a visa, job, or grant file should say exactly that. A preprint on a personal site or on arXiv is a public draft. It is not a Nature paper.

**arXiv is free to read and usually free to submit**, but it is not peer review. First-time submitters in a category often need endorsement from an existing author. LaTeX is preferred.

**Attribution.** The empirical claims cited here belong to their authors. The framing (“world mechanics,” the four-level scheme, the emphasis on the human/AI asymmetry) is the contribution of this draft.

**Emotions.** There is no evidence that current AI systems have emotions. Treating them as if they do is a category error that also has social costs: it confuses users, and it can cheapen the moral status of animals and humans, who actually suffer.

**Quantum rhetoric.** Quantum mechanics is strange enough without adding souls. Superposition is a fact about amplitudes. It is not a metaphor for personality.

---

## 7. What to build next

A serious follow-on — the kind that could later support research careers — would pick *one* of these and do it for real:

1. Reproduce a published AI-for-quantum-circuits result on a public molecule and report energy errors, circuit depth, and failure cases.
2. Write a verified, tested implementation of a standard many-body method with an LLM-assisted workflow, and publish the audit trail.
3. Build a small, open benchmark that asks models to distinguish legitimate quantum-biology claims from popular overclaims, then score them.
4. A mechanistic-interpretability note: locate and ablate features related to physical-unit consistency or conservation-law talk in a science-tuned model.

Those are projects. This paper is the map.

---

## Author note

Sheshu Vardhan Akula works as a DevOps and platform engineer with AI systems: the layer that makes models runnable, observable, repeatable, and safe to put in front of other people. This paper is a synthesis from that vantage — instruments, interfaces, and limits — not a claim of a university physics appointment.

## Acknowledgements

Written with assistance from a large language model used as an instrument (search, structuring, drafting). All scientific citations should be checked against the original papers before any formal submission. The author remains responsible for what is posted under their name.

---

## References

1. Du, Y. et al. Artificial intelligence for representing and characterizing quantum systems. *Nat. Rev. Phys.* (2026). https://doi.org/10.1038/s42254-026-00962-5

2. Swayne, M. Researchers: AI can learn to build quantum circuits for drug molecules… *The Quantum Insider* (30 July 2026). Reporting on Quantinuum / NVIDIA / Pfizer work.

3. Evaluating large language models on quantum mechanics… arXiv:2602.19006 (2025/2026).

4. Towards verifiable and self-correcting AI physicists for quantum many-body simulations. arXiv:2604.00149 (2026).

5. Zhou, Y. From paper to program: accelerating quantum many-body algorithm development… arXiv:2604.04089 (2026).

6. Huang, H.-Y. et al. Generative quantum advantage for classical and quantum problems. arXiv:2509.09033 (2025).

7. Artificial intelligence for quantum matter: finding a needle in a haystack. arXiv:2507.13322 (2026 update).

8. When AI meets quantum information: a comprehensive review. arXiv:2607.00365 (2026).

9. Scalable quantum state preparation via large-language-model-driven discovery. arXiv:2505.06347.

10. Quantum in biology, quantum for biology, and biology for quantum: mapping the evidence… arXiv:2605.00205 (2026).

11. The rationality of radical pair mechanism in real biological systems. arXiv:2512.05974 (2025).

12. Dupire, L. et al. Fifteen challenges for generative AI applications to cell biology. *Cell* (2026). https://doi.org/10.1016/j.cell.2026.07.004

13. AI systems devise hypotheses and ways to test them. *Nature* **655**, 313–314 (2026).

14. Verbalizable representations form a global workspace in language models. Transformer Circuits (2026).

15. Phua, Y. J. Can we test consciousness theories on AI? arXiv:2512.19155 (2025).

16. Keller, Y. & Eisenmann, T. Understanding large language models. arXiv:2607.01006 (2026).

17. UKRI. Global Talent visa expanded to innovative research businesses (6 August 2026). Context only; not a scientific source.

18. arXiv.org. Submission overview. https://info.arxiv.org/help/submit/index.html

---

## Appendix A. How to put your name on this

Replace the author line. Add a short affiliation or “independent researcher.” Add an ORCID if you have one. Do not add fictional degrees or fictional institutions.

If you later submit to arXiv, convert this file to LaTeX, choose categories such as `quant-ph`, `cs.AI`, and `q-bio.QM` as appropriate, and do not claim peer review.

## Appendix B. One-sentence versions

- For physicists: AI is becoming a practical ansatz and search layer on top of quantum description.
- For biologists: the quantum part that currently matters is mostly molecular simulation plus a short list of lab-constrained quantum-in-biology effects.
- For everyone else: the model can be understood; it does not feel; the world is still physical.
