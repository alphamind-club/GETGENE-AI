
Identifying actionable drug targets is a critical challenge in cancer research, where high-dimensional genomic data and the complexity of tumor biology often hinder effective prioritization. To address this, we developed GETgene-AI, a novel computational framework that integrates network-based prioritization, machine learning, and automated literature analysis to identify and rank potential therapeutic targets. Central to GETgene-AI is the G.E.T. strategy, which combines three data streams: mutational frequency (G List), differential expression (E List), and known drug targets (T List). These components are iteratively refined and ranked using the Biological Entity Expansion and Ranking Engine (BEERE), leveraging protein-protein interaction networks, functional annotations, and experimental evidence. Additionally, GETgene-AI incorporates GPT-4, an advanced large language model, to automate literature-based ranking, reducing manual curation and increasing efficiency.
 
In this study, we applied GETgene-AI to pancreatic cancer as a case study. The framework successfully identified high-priority targets such as PIK3CA and PRKCA, validated through experimental evidence and clinical relevance. Benchmarking against GEO2R and STRING demonstrated GETgene-AI’s superior performance, achieving higher precision, recall, and efficiency in prioritizing actionable targets. Moreover, the framework mitigated false positives by deprioritizing genes lacking functional or clinical significance.
 
While demonstrated on pancreatic cancer, the modular design of GETgene-AI enables scalability across diverse cancers and diseases. By integrating multi-omics datasets with advanced computational and AI-driven approaches, GETgene-AI provides a versatile and robust platform for accelerating cancer drug discovery. This framework bridges computational innovations with translational research to improve patient outcomes.

Acess the preprint:
GETgene-AI: A Framework for Prioritizing Actionable Cancer Drug Targets
Adrian Gu, Jake Y Chen
bioRxiv 2025.01.21.634201; doi: https://doi.org/10.1101/2025.01.21.634201
