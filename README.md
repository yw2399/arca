Introduction for the following work(s):
* [EuroMLSys 2025 Oral] <a href="https://github.com/yw2399/arca/blob/main/paper/ARCA_EuroMLSys.pdf">Diagnosing and Resolving Cloud Platform Instability with Multi-modal RAG LLMs</a>


## 📰 News
* **[Feb. , 2025]**: Our initial work of [ARCA](https://github.com/yw2399/arca/blob/main/paper/ARCA_EuroMLSys.pdf) has been accepted by [EuroMLSys 2025](https://euromlsys.eu/) for oral presentation.
* **[Dec. , 2024]**: We have created a data set of 800 IT support tickets reporting cloud incidents for micro-services. The data is created with Death Star microbenchmark.


## What is ARCA?
ARCA is the acronym for "AI for Root Cause Analysis". It's an AI-Ops tool for diagnosing and mitigating software issues faced by cloud platforms. Think it like a robot that can help Software Reliability Engineers (SREs) fix cloud service interruptions.

Different from other tools, ARCA features
* **Multi-modality**: ARCA works on software system logs (semi-structured text), telemetric data (numbers) and human descriptions (unformatted natural language).
*  **Genericity**: ARCA is built without proprietary models. We use off-the-shelf AI models only, e.g., BGE-M3, GPT-4O, GPT-Embedding-Large.
* **Search-based Augmentation**: ARCA uses RAG LLM to augment its answer quality. It also optimizes the query efficiency when querying the knowledge base.

## Interesting side benefits
If we use the triaging part of ARCA alone, ARCA becomes a log-clustering tool and it's the current SOTA solution in this area, in terms of F-1 score.
