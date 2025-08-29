# AI Road Map

## Aim (Quick Summary)
Personal, structured roadmap documenting my journey to become a practical AI / NLP engineer. The repository tracks progressive learning: core math & theory, implementation of foundational models, reproduction of classic papers, and building small applied projects. Each stage emphasizes understanding through code, experiment tracking, and concise technical notes.

## Current Focus
- Course: Stanford CS224N (Natural Language Processing with Deep Learning)
- Active Topic: Word representations (from classic distributional semantics to modern contextual embeddings)
- Immediate Goals:
	- Implement and compare Word2Vec (CBOW & Skip-Gram), GloVe, and subword/character-based approaches
	- Analyze embedding quality (intrinsic: similarity/analogy; extrinsic: downstream task impact)
	- Build intuition on bias, dimensionality, and geometry of embeddings

## Scope & Evolution
1. Foundations: Linear algebra, probability, optimization refresh
2. NLP Core: Tokenization, embeddings, sequence models, attention, transformers
3. Model Reproduction: Re-implement selected papers (e.g., word2vec, GloVe, Transformer, BERT miniature)
4. Applied Tracks: Information retrieval, question answering, summarization, evaluation
5. Systems & MLOps: Experiment tracking, efficient inference, deployment patterns

## Principles
- Learn by building minimal yet faithful implementations
- Validate with tests, baselines, ablations, and metrics
- Keep notes distilled (why it works > surface recipe)
- Prioritize clarity, reproducibility, and incremental complexity

## Repository Structure (Growing)
```
notes/          Concept summaries & derivations
implementations/  From-scratch model & training code
experiments/    Configs, logs, analysis notebooks
projects/       Small applied end-to-end builds
references/     Paper lists & reading trackers
```

## Progress Log (Snapshot)
- [ ] Word2Vec implementations
- [ ] GloVe training
- [ ] Embedding evaluation suite
- [ ] Subword embedding exploration
- [ ] Comparative report

## Next Up After Embeddings
Sequence modeling (RNN variants, attention) leading into transformer fundamentals.

---
This file will evolve; early focus is depth over breadth. Later sections will add concrete links to implemented modules, experiment results, and replication reports.