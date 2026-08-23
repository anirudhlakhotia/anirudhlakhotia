Software Engineer at [Couchbase](https://www.couchbase.com/) · Information Retrieval · Efficient ML

[Website](https://anirudhlakhotia.com) · [Google Scholar](https://scholar.google.com/citations?user=2hf7A6UAAAAJ) · [LinkedIn](https://www.linkedin.com/in/anirudhlakhotia/)

> I am interested in how representations behave under practical constraints.
> They have to preserve useful structure while remaining cheap to store and fast
> to serve.

## Research

### [Most MaxSim Winners Flip, Retrieval Survives](https://github.com/anirudhlakhotia/subbit-multivector-retrieval)

*ReNeuIR Workshop @ SIGIR 2026*

Sign coding flips most token-level MaxSim winners, yet retrieval survives because
the substitutes are low-margin. A random projection matches a trained one at
matched storage, and an fp32 rerank of the top 100 candidates recovers fp32
MRR@10.

[Paper](https://github.com/anirudhlakhotia/subbit-multivector-retrieval/blob/main/paper/paper_reneuir.pdf) · [Code](https://github.com/anirudhlakhotia/subbit-multivector-retrieval) · [Reproducibility](https://github.com/anirudhlakhotia/subbit-multivector-retrieval/blob/main/REPRODUCIBILITY.md)

### [UnoLoRA: Single Low-Rank Adaptation for Efficient Multitask Fine-tuning](https://openreview.net/forum?id=n6W0QkQBgw)

*FITML Workshop @ NeurIPS 2024*

One shared low-rank adapter supports multitask fine-tuning without duplicating a
separate adapter for every task.

### [Sampling Strategies for Multi-Task Learning](https://anirudhlakhotia.com/publications/#lakhotia2025sampling)

*ICEENG 2025*

Task-sampling strategies produce different internal representations even when
aggregate multitask performance is similar.

### Current work

I am working on compositionality in learned representations, and how to separate
learned structure from dataset-level effects.

## Engineering

At Couchbase I build SDKs and connectors for production data systems. My
[public contributions](https://github.com/search?q=is%3Apr+author%3Aanirudhlakhotia+is%3Amerged+org%3Acouchbase+org%3Acouchbaselabs&type=pullrequests)
span the Python, Node.js, JVM and C++ clients, analytics SDKs, and integration
and test infrastructure.
