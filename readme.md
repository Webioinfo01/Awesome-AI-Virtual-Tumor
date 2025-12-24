# Awesome AI Virtual Tumor[![Awesome](https://awesome.re/badge.svg)](https://awesome.re)
[![Website](https://img.shields.io/website?url=http%3A//awesomeaivt.webioinfo.top/)](http://awesomeaivt.webioinfo.top/)
[![GitHub Stars](https://img.shields.io/github/stars/Webioinfo01/Awesome-AI-Virtual-Tumor?style=social)](https://github.com/Webioinfo01/Awesome-AI-Virtual-Tumor) 
[![visitors](https://visitor-badge.laobi.icu/badge?page_id=Webioinfo01.Awesome-AI-Virtual-Tumor)](https://github.com/Webioinfo01/Awesome-AI-Virtual-Tumor)

**Visit the official website at: http://awesomeaivt.webioinfo.top/**

This project is collaboratively maintained by our self-developed AI agent (aweagent) and human experts in a human-in-the-loop workflow, combining automated discovery with expert curation to provide a comprehensive survey of AI systems for virtual tumor modeling and simulation.

This repository organizes AI applications for virtual tumor research into fourteen main categories: "Static Models", "Dynamic Models", "Sequence Models", "Drug Models", "Other Models", "AI Agents", "Databases", "Tools & Infrastructure", "Benchmarks", "Evaluation Frameworks", "Methodology", "Reviews", "Other Domain Foundation Models", and "Paper Before 2024".

## 📋 Table of Contents
- [📊 Static Models](#Static-Models) - Static representation models (e.g., scGPT, bulkformer) that do not incorporate perturbation data. These models are commonly used to represent fixed properties of biological systems, such as the topological structure of protein interaction networks, snapshots of gene expression profiles, or cell states at specific time points.
- [🌊 Dynamic Models](#Dynamic-Models) - Dynamic models that incorporate perturbation data and temporal differences, simulating or predicting how biological processes respond to perturbations (e.g., environmental changes, drug treatments).
- [🧬 Sequence Models](#Sequence-Models) - Sequence-based models that process sequential biological data (e.g., DNA, RNA, protein sequences).
- [💊 Drug Models](#Drug-Models) - Drug models for molecule design and drug discovery (e.g., SketchMol, GeminiMol).
- [🔧 Other Models](#Other-Models) - Other representative machine learning models that contribute to virtual tumor modeling.
- [🤖 AI Agents](#AI-Agents) - AI agents and systems for automated virtual tumor analysis.
- [💾 Databases](#Databases) - Databases and data repositories related to sequences and single-cell data for virtual tumor research.
- [🔧 Tools & Infrastructure](#Tools--Infrastructure) - Tools and infrastructure for virtual tumor research, including annotation frameworks, simulation tools, and standardization utilities.
- [📈 Benchmarks](#Benchmarks) - Benchmark datasets and evaluation standards for virtual tumor prediction.
- [⚖️ Evaluation Frameworks](#Evaluation-Frameworks) - Novel evaluation frameworks and metrics (e.g., Systema: a framework for evaluating genetic perturbation response prediction beyond systematic variation).
- [🔬 Methodology](#Methodology) - Methodological approaches and frameworks (e.g., Monod: model-based discovery and integration through fitting stochastic transcriptional dynamics to single-cell sequencing data).
- [📚 Reviews](#Reviews) - Review papers and surveys on AI virtual tumor research.
- [🌐 Other Domain Foundation Models](#Other-Domain-Foundation-Models) - Foundation models from other domains (e.g., cognitive science) that can be applied to virtual tumor modeling.
- [📜 Paper Before 2024](#Paper-Before-2024) - Historical papers published before 2024.
- [🔗 Other Awesome Projects](#Other-Awesome-Projects)
## Static Models
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.12 | **A lung CT vision foundation model facilitating disease diagnosis and medical imaging.** | Qionghai Dai |  |  | CT imaging foundation model | Nature communications | [Link](https://www.semanticscholar.org/paper/37e1003be2e2cc4c1f09352c17363597d47f6740) |  |
| 2025.11 | **A multimodal whole-slide foundation model for pathology** | Faisal Mahmood |  |  | Multimodal pathology foundation model | Nature Medicine | [Link](https://www.semanticscholar.org/paper/27ef41325e809dc35657540d14bcbb79cadad20f) |  |
| 2024.06 | **scFoundation: Large-scale foundation model on single-cell transcriptomics** | Le Song, Xuegong Zhang | [Link](https://github.com/biomap-research) | Biomap research | single cell RNA | Nature Communications | [Link](https://www.nature.com/articles/s41592-024-02305-7) | [Link](https://github.com/biomap-research/scFoundation) ![GitHub Stars](https://img.shields.io/github/stars/biomap-research/scFoundation) |
| 2024.02 | **scGPT: toward building a foundation model for single-cell multi-omics using generative AI** | Bo Wang | [Link](https://github.com/bowang-lab) |  | single cell RNA | Nature Methods | [Link](https://www.nature.com/articles/s41592-024-02201-0) | [Link](https://github.com/bowang-lab/scGPT) ![GitHub Stars](https://img.shields.io/github/stars/bowang-lab/scGPT) |
## Dynamic Models
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.12 | **SpatialProp: tissue perturbation modeling with spatially resolved single-cell transcriptomics** | James Zou | [Link](https://github.com/zou-group) | Stanford University | Spatial scRNA perturbation modeling | bioRxiv | [Link](https://www.semanticscholar.org/paper/2629ead85b953e97d426e01a4445bfa27815b383) | [Link](https://github.com/abuendia/spatial-prop) ![GitHub Stars](https://img.shields.io/github/stars/abuendia/spatial-prop) |
| 2025.12 | **Scouter predicts transcriptional responses to genetic perturbations with large language model embeddings.** | Jun Li |  |  | LLM embeddings to predict transcriptional responses | Nature computational science | [Link](https://www.semanticscholar.org/paper/ef1e5451d11c0684b4867e410682daf776ab91c8) |  |
| 2025.10 | **Tahoe-x1: Scaling Perturbation-Trained Single-Cell Foundation Models to 3 Billion Parameters** | Nima Alidoust | [Link](https://github.com/ArcInstitute) | tahoebio(but in arc's repository) |  | bioRxiv | [Link](https://www.semanticscholar.org/paper/f9338636c63e8057025be2fe4170b725da1f47bc) |  |
| 2025.05 | **A visual–omics foundation model to bridge histopathology with spatial transcriptomics** | Guangyu Wang | [Link](https://guangyuwanglab.github.io/web/) |  | histopathology and spatial single cell RNA | Nature Methods | [Link](https://www.nature.com/articles/s41592-025-02707-1) | [Link](https://github.com/GuangyuWangLab2021/Loki) ![GitHub Stars](https://img.shields.io/github/stars/GuangyuWangLab2021/Loki) |
| 2025.01 | **A foundation model of transcription across human cell types** |  |  |  | transcriptional regulation(ATAC-seq) | Nature | [Link](https://www.nature.com/articles/s41586-024-08391-z) | [Link](https://github.com/GET-Foundation) ![GitHub Stars](https://img.shields.io/github/stars/GET-Foundation/get_model) |
| 2025.01 | **Predicting cell morphological responses to perturbations using generative modeling** | Fabian J. Theis, Mohammad Lotfollahi | [Link](https://github.com/theislab) |  | phenotype morphological responses to perturbation | Nature Communications | [Link](https://www.nature.com/articles/s41467-024-55707-8) | [Link](https://github.com/theislab/IMPA) ![GitHub Stars](https://img.shields.io/github/stars/theislab/IMPA) |
## Sequence Models
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.11 | **mRNABERT: advancing mRNA sequence design with a universal language model and comprehensive dataset** | Tingjun Hou |  |  | mRNA Sequence Design with Language Models | Nature Communications | [Link](https://www.semanticscholar.org/paper/c9cd1f5b57f86be3a656f17a0dc0ed32a4e82825) |  |
| 2024.07 | **DNA language model GROVER learns sequence context in the human genome** |  |  |  | DNA | Nature Machine Intelligence | [Link](https://www.nature.com/articles/s42256-024-00872-0) | [Link](https://zenodo.org/records/13374192) |
| 2025.07 | **RiNALMo: general-purpose RNA language models can generalize well on structure prediction tasks** |  |  |  | RNA | Nature Communications | [Link](https://www.nature.com/articles/s41467-025-60872-5) | [Link](https://github.com/lbcb-sci/RiNALMo) ![GitHub Stars](https://img.shields.io/github/stars/lbcb-sci/RiNALMo) |
| 2025.07 | **Scalable emulation of protein equilibrium ensembles with generative deep learning** | Microsoft Research(Frank Noé) | [Link](https://github.com/microsoft) |  | Protein | Science | [Link](https://www.science.org/doi/10.1126/science.adv9817) | [Link](https://github.com/microsoft/bioemu) ![GitHub Stars](https://img.shields.io/github/stars/microsoft/bioemu) |
| 2025.06 | **Generalized biological foundation model with unified nucleic acid and protein language** | Zhaorong Li | [Link](https://github.com/LucaOne) | Alibaba | DNA/RNA/Protein | Nature Machine Intelligence | [Link](https://www.nature.com/articles/s42256-025-01044-4) | [Link](https://github.com/LucaOne/LucaOne) ![GitHub Stars](https://img.shields.io/github/stars/LucaOne/LucaOne) |
| 2025.04 | **xTrimoPGLM: Unified 100B-Scale Pre-trained Transformer for Deciphering the Language of Protein** | Le Song | [Link](https://github.com/biomap-research) | Biomap research | Protein | Nature Methods | [Link](https://arxiv.org/abs/2401.06199) | [Link](https://github.com/biomap-research/xTrimoPGLM) ![GitHub Stars](https://img.shields.io/github/stars/biomap-research/xTrimoPGLM) |
| 2025.01 | **Simulating 500 million years of evolution with a language model** | Alexander Rives | [Link](https://github.com/evolutionaryscale) | EvolutionaryScale | Protein | Science | [Link](https://www.science.org/doi/10.1126/science.ads0018) | [Link](https://github.com/evolutionaryscale/esm) ![GitHub Stars](https://img.shields.io/github/stars/evolutionaryscale/esm) |
| 2025.11 | **A pre-trained large generative model for translating single-cell transcriptomes to proteomes** | Jianhua Yao |  | Tencent | translating single-cell transcriptomes to proteomes | Nature Biomedical Engineering | [Link](https://www.nature.com/articles/s41551-025-01528-z) | [Link](https://github.com/TencentAILabHealthcare/scTranslator) ![GitHub Stars](https://img.shields.io/github/stars/TencentAILabHealthcare/scTranslator) |
| 2025.06 | **A multimodal conversational agent for DNA, RNA and protein tasks** | Thomas Pierrot | [Link](https://huggingface.co/InstaDeepAI) | InstaDeep | Diverse Omics include DNA/RNA/Protein | Nature Machine Intelligence | [Link](https://www.nature.com/articles/s42256-025-01047-1) | [Link](https://huggingface.co/InstaDeepAI/ChatNT) |
| 2025.05 | **CellFM: a large-scale foundation model pre-trained on transcriptomics of 100 million human cells** |  |  |  | single cell RNA | Nature Communications | [Link](https://www.nature.com/articles/s41467-025-59926-5) | [Link](https://github.com/biomed-AI/CellFM) ![GitHub Stars](https://img.shields.io/github/stars/biomed-AI/CellFM) |
| 2024.11 | **Nucleotide Transformer: building and evaluating robust foundation models for human genomics** |  |  |  | DNA | Nature Methods | [Link](https://www.nature.com/articles/s41592-024-02523-z) | [Link](https://github.com/instadeepai/nucleotide-transformer) ![GitHub Stars](https://img.shields.io/github/stars/instadeepai/nucleotide-transformer) |
| 2024.05 | **Accurate structure prediction of biomolecular interactions with AlphaFold 3** | John M. Jumper | [Link](https://github.com/google-deepmind) | Google DeepMind | Protein | Nature | [Link](https://www.nature.com/articles/s41586-024-07487-w) | [Link](https://github.com/google-deepmind/alphafold3) ![GitHub Stars](https://img.shields.io/github/stars/google-deepmind/alphafold3) |
## Drug Models
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.01 | **SketchMol: Image-based generation for molecule design with SketchMol** |  |  |  | Image-based molecule generation | Nature Machine Intelligence | [Link](https://www.nature.com/articles/s42256-025-00982-3) |  |
| 2025.01 | **Conformational Space Profiling Enhances Generic Molecular Representation for AI-Powered Ligand-Based Drug Discovery** |  |  |  | Molecular representation for drug discovery |  | [Link](https://pubmed.ncbi.nlm.nih.gov/39206753/) |  |
## Other Models
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.12 | **Multimodal AI generates virtual population for tumor microenvironment modeling.** | H. Poon |  |  |  | Cell | [Link](https://www.semanticscholar.org/paper/27e339e417eaa5af813d5f6ddba760c7d7175949) |  |
| 2025.10 | **Active learning framework leveraging transcriptomics identifies modulators of disease phenotypes** | Fabian J. Theis | [Link](https://github.com/theislab) | Technical University of Munich | close-in-the-loop predict drugs for disease phenotypes | Science | [Link](https://www.science.org/doi/10.1126/science.adi8577) |  |
| 2025.08 | **Squidiff: Predicting cellular development and responses to perturbations using a diffusion model** | Kam W. Leong |  |  |  | Nature Methods | [Link](https://www.semanticscholar.org/paper/db387c9cbd2439200aa403bc390457d238dfa36d) | [Link](https://github.com/siyuh/Squidiff) ![GitHub Stars](https://img.shields.io/github/stars/siyuh/Squidiff) |
| 2025.07 | **Prediction of cellular morphology changes under perturbations with a transcriptome-guided diffusion model** | Le Song | [Link](https://github.com/biomap-research) | Biomap research | cellular morphology changes under perturbations | Nature Communications | [Link](https://www.semanticscholar.org/paper/46c13678b2b4044e693ec907a2080c77fdd7c906) | [Link](https://github.com/biomap-research/MorphDiff) ![GitHub Stars](https://img.shields.io/github/stars/biomap-research/MorphDiff) |
| 2025.06 | **A deep generative model for deciphering cellular dynamics and in silico drug discovery in complex diseases** | Jun Ding |  |  |  | Nature Biomedical Engineering | [Link](https://www.semanticscholar.org/paper/4914ea0eb460861de190e3976e11567806b59ffe) |  |
| 2025.04 | **AI-driven predictive biomarker discovery with contrastive learning to improve clinical trial outcomes.** | Etai Jacob |  |  |  | Cancer Cell | [Link](https://www.semanticscholar.org/paper/aa8ccacaab79ff169945cc5c68d3c984e3bdc9d0) |  |
| 2025.03 | **Cell morphological representations of genes enhance prediction of drug targets** | Shantanu Singh |  | Broad Institute |  | bioRxiv | [Link](https://www.semanticscholar.org/paper/9924f439a76927ce3b7feb27a61ec80c26600f34) |  |
| 2024.10 | **Predicting transcriptional responses to novel chemical perturbations using deep generative model for drug discovery** | Yi Zhao |  |  |  | Nature Communications | [Link](https://www.semanticscholar.org/paper/c63fa5a62a2c54de65ceaedf720d826d3b92129b) |  |
| 2024.06 | **Deep representation learning of chemical-induced transcriptional profile for phenotype-based drug discovery** | Mingyue Zheng |  |  |  | Nature Communications | [Link](https://www.semanticscholar.org/paper/4c5916a879490d67fb48ad872b52d27539ca4a54) |  |
| 2024.04 | **Masked Autoencoders for Microscopy are Scalable Learners of Cellular Biology** | Berton Earnshaw | [Link](https://www.rxrx.ai/) | Recursion | microscopy data | CVPR 2024 Highlight | [Link](https://arxiv.org/abs/2404.10242) | [Link](https://www.rxrx.ai/phenom) |
| 2024.04 | **PERCEPTION predicts patient response and resistance to treatment using single-cell transcriptomics of their tumors** | E. Ruppin |  |  |  | Nature Cancer | [Link](https://www.semanticscholar.org/paper/ffc5edf31ff74929bdf67e64bc922c3d121ffeb8) |  |
## AI Agents
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.12 | **CASSIA: a multi-agent large language model for automated and interpretable cell annotation.** | C. Kendziorski |  |  | automated single-cell annotation via multi-agent LLMs | Nature communications | [Link](https://www.semanticscholar.org/paper/7de5beff1eb163c66310e4291928c6f2d7bb34ac) |  |
| 2025.11 | **AI mirrors experimental science to uncover a mechanism of gene transfer crucial to bacterial evolution** | Tiago R D Costa |  | Imperial College London | General Scientific Research(AI co-scientist) | Cell | [Link](https://arxiv.org/pdf/2502.18864v1) |  |
| 2025.11 | **Multimodal learning enables chat-based exploration of single-cell data** | Christoph Bock |  | Medical University of Vienna | Single-cell data exploration | Nature Biotechnology | [Link](https://www.nature.com/articles/s41587-025-02857-9) | [Link](https://github.com/epigen/cellwhisperer) ![GitHub Stars](https://img.shields.io/github/stars/epigen/cellwhisperer) |
| 2025.07 | **The Virtual Lab: AI Agents Design New SARS-CoV-2 Nanobodies with Experimental Validation** | James Zou | [Link](https://github.com/zou-group) | Stanford University | General Scientific Research | Nature | [Link](https://www.nature.com/articles/s41586-025-09442-9) | [Link](https://github.com/zou-group/virtual-lab) ![GitHub Stars](https://img.shields.io/github/stars/zou-group/virtual-lab) |
| 2025.06 | **CellVoyager: AI CompBio Agent Generates New Insights by Autonomously Analyzing Biological Data** | James Zou | [Link](https://github.com/zou-group) | Stanford University | single cell RNA | bioRxiv | [Link](https://www.biorxiv.org/content/10.1101/2025.06.03.657517v1) | [Link](https://github.com/zou-group/CellVoyager) ![GitHub Stars](https://img.shields.io/github/stars/zou-group/CellVoyager) |
| 2025.05 | **PlantGPT: An Arabidopsis-Based Intelligent Agent that Answers Questions about Plant Functional Genomics.** | Qinlong Zhu |  |  | PlantGPT: LLM agent for plant functional genomics question answering | Advanced Science | [Link](https://www.semanticscholar.org/paper/b0b726a254ede59afe4ab6635fb23c916ceacb94) |  |
| 2025.03 | **DrBioRight 2.0: an LLM-powered bioinformatics chatbot for large-scale cancer functional proteomics analysis** |  |  |  | proteomics | Nature Communications | [Link](https://www.nature.com/articles/s41467-025-57430-4) | [Link](https://drbioright.org/) |
| 2024.10 | **An AI Agent for Fully Automated Multi-Omic Analyses** |  |  |  | Multi-omics Pipelines | Advanced Science | [Link](https://advanced.onlinelibrary.wiley.com/doi/10.1002/advs.202407094) | [Link](https://github.com/JoshuaChou2018/AutoBA) ![GitHub Stars](https://img.shields.io/github/stars/JoshuaChou2018/AutoBA) |
## Databases
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.11 | **BV-BRC: a unified bacterial and viral bioinformatics resource with expanded functionality and AI integration.** | Rick L. Stevens |  |  | Bacterial and Viral Bioinformatics Resource | Nucleic acids research | [Link](https://www.semanticscholar.org/paper/693c203c962996b3a53f115787aa2ad849ba4f16) |  |
| 2025.06 | **X-Atlas/Orion: Genome-wide Perturb-seq Datasets via a Scalable Fix-Cryopreserve Platform for Training Dose-Dependent Biological Foundation Models** |  |  |  | Genome-wide Perturb-seq Datasets | bioRxiv | [Link](https://www.biorxiv.org/content/10.1101/2025.06.11.659105v1) | [Link](10.25452/figshare.plus.29190726) |
| 2025.05 | **scCompass: An Integrated Multi-Species scRNA-seq Database for AI-Ready** | Yuanchun Zhou |  |  | Multi-species scRNA-seq database for AI-ready applications | Advanced Science | [Link](https://www.semanticscholar.org/paper/f5af8e3f7acd968b7baeb788f5b33cf7d868616e) |  |
| 2025.03 | **RxRx3-core: Benchmarking drug-target interactions in High-Content Microscopy** | Imran S. Haque | [Link](https://www.rxrx.ai/) | Recursion | microscopy perturbation data | ICLR 2025 | [Link](https://arxiv.org/abs/2503.20158v2) | [Link](https://www.rxrx.ai/datasets) |
| 2025.02 | **scBaseCount: an AI agent-curated, uniformly processed, and continually expanding single cell data repository** | Arc Institute(Yusuf H. Roohani) | [Link](https://github.com/ArcInstitute) |  | preprocess scRNA data | bioRxiv | [Link](https://www.biorxiv.org/content/10.1101/2025.02.27.640494v2) | [Link](https://github.com/ArcInstitute/SRAgent) ![GitHub Stars](https://img.shields.io/github/stars/ArcInstitute/SRAgent) |
| 2025.02 | **Tahoe-100M: A Giga-Scale Single-Cell Perturbation Atlas for Context-Dependent Gene Function and Cellular Modeling** | tahoebio(but in arc's repository) | [Link](https://github.com/ArcInstitute) |  | Drug perturbation scRNA | bioRxiv | [Link](https://www.biorxiv.org/content/10.1101/2025.02.20.639398v3) | [Link](https://github.com/ArcInstitute/arc-virtual-cell-atlas) ![GitHub Stars](https://img.shields.io/github/stars/ArcInstitute/arc-virtual-cell-atlas) |
| 2024.02 | **Cell Painting Gallery: an open resource for image-based profiling** | Shantanu Singh |  |  |  | Nature Methods | [Link](https://www.semanticscholar.org/paper/24cd61ff858138b9c2086364eef75bb0d93ce0a7) |  |
| 2024.01 | **scPerturb: harmonized single-cell perturbation data** |  |  |  | scRNA perturbation(44 public datasets, drugs and genes) | Nature Methods | [Link](https://www.nature.com/articles/s41592-023-02144-y) | [Link](https://github.com/sanderlab/scPerturb/) ![GitHub Stars](https://img.shields.io/github/stars/sanderlab/scPerturb) |
| 2023.03 | **JUMP Cell Painting dataset: morphological impact of 136,000 chemical and genetic perturbations** | Anne E Carpenter |  |  |  | bioRxiv | [Link](https://www.semanticscholar.org/paper/1f96460299f3c74965b4fe8e64c28957ada06c74) |  |
| 2022.10 | **Morphology and gene expression profiling provide complementary information for mapping cell state** | Anne E Carpenter |  |  |  | bioRxiv | [Link](https://www.semanticscholar.org/paper/1f7bb6a080c1db96c778793514bf2b1638b623ab) |  |
| 2022.01 | **Three million images and morphological profiles of cells treated with matched chemical and genetic perturbations** | Anne E Carpenter |  |  |  | bioRxiv | [Link](https://www.semanticscholar.org/paper/3e173f19037739ae6e84bc3b9f97957c42412660) |  |
| 2021.09 | **High-Dimensional Gene Expression and Morphology Profiles of Cells across 28,000 Genetic and Chemical Perturbations** | Anne E Carpenter |  |  |  | bioRxiv | [Link](https://www.semanticscholar.org/paper/bff33206f1782c889c393aecb87bbd7939af61f0) |  |
| 2017.06 | **Image Data Resource: a bioimage data integration and publication platform** | J. Swedlow |  |  |  | Nature Methods | [Link](https://www.semanticscholar.org/paper/e0986b9ed19d71d2d48b3f1bd6cec0b9b9236b4f) |  |
| 2012.06 | **Annotated high-throughput microscopy image sets for validation** | Anne E Carpenter |  |  |  | Nature Methods | [Link](https://www.semanticscholar.org/paper/ff8a3d41bf4a3a6415d77a84ba58cd9b0b2c4869) |  |
## Tools & Infrastructure
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.11 | **CellOntologyMapper: Consensus mapping of cell type annotation** |  |  |  | Consensus mapping of cell type annotation | iMetaOmics | [Link](https://onlinelibrary.wiley.com/doi/10.1002/imo2.70064) | [Link](https://github.com/Starlitnightly/CellOntologyMapper) ![GitHub Stars](https://img.shields.io/github/stars/Starlitnightly/CellOntologyMapper) |
| 2025.02 | **PhenoProfiler: Advancing Phenotypic Learning for Image-based Drug Discovery** | Qianqian Song |  |  |  | Nature Communications | [Link](https://www.semanticscholar.org/paper/937922c62c76efc089ed7fcf73f30d19c8066f01) |  |
| 2025.04 | **scMultiSim: simulation of single-cell multi-omics and spatial data guided by gene regulatory networks and cell–cell interactions** |  |  |  | Simulation of single-cell multi-omics and spatial data | Nature Methods | [Link](https://www.nature.com/articles/s41592-025-02651-0) | [Link](https://github.com/ZhangLabGT/scMultiSim/) ![GitHub Stars](https://img.shields.io/github/stars/ZhangLabGT/scMultiSim) |
| 2025.04 | **uHAF: a unified hierarchical annotation framework for cell type standardization and harmonization** | Xuegong Zhang |  |  | Hierarchical Framework for Cell Type Annotation and Harmonization | Bioinformatics | [Link](https://www.semanticscholar.org/paper/e3ce9b990c9604648ad39e38275cd61b7711415a) |  |
| 2022.08 | **Learning representations for image-based profiling of perturbations** | Juan C. Caicedo |  |  |  | bioRxiv | [Link](https://www.semanticscholar.org/paper/6c26c1c68782bb2b4821f9f2343431d3785b3b59) |  |
| 2018.07 | **CellProfiler 3.0: Next-generation image processing for biology** | Anne E Carpenter |  |  |  | PLoS Biology | [Link](https://www.semanticscholar.org/paper/713e881b5c3134debf934026edf6f0ba3cb42c3c) |  |
## Benchmarks
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.12 | **scDrugMap: Benchmarking Large Foundation Models for Drug Response Prediction** | Qianqian Song |  | University of Florida | Benchmarking foundation models for single-cell drug response prediction | Nature Communications | [Link](https://www.nature.com/articles/s41467-025-67481-2) | [Link](https://github.com/QSong-github/scDrugMap) ![GitHub Stars](https://img.shields.io/github/stars/QSong-github/scDrugMap) |
| 2025.12 | **Benchmarking algorithms for generalizable single-cell perturbation response prediction.** | Qi Liu |  |  |  | Nature Methods | [Link](https://www.semanticscholar.org/paper/e8eeb58f3cdd1461d1c761db907dfe7ef7b23057) | [Link](https://github.com/bm2-lab/scPerturBench/) ![GitHub Stars](https://img.shields.io/github/stars/bm2-lab/scPerturBench) |
| 2025.08 | **High-level visual representations in the human brain are aligned with large language models** | Ian Charest |  |  | Alignment of brain visual representations with LLM embeddings | Nature Machine Intelligence | [Link](https://www.semanticscholar.org/paper/bc5d6c636c36f5ddc9af61da414511d43373b8e0) |  |
## Evaluation Frameworks
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.08 | **Systema: a framework for evaluating genetic perturbation response prediction beyond systematic variation.** | Maria Brbić |  |  |  | Nature Biotechnology | [Link](https://www.semanticscholar.org/paper/4cd1f83c8b5d89b30355e9210ae9f67a489873d0) |  |
| 2023.02 | **Community-developed checklists for publishing images and image analyses** | H Germany |  |  |  | Nature Methods | [Link](https://www.semanticscholar.org/paper/65a9382c999cb3f9533265e818d2ea8664944e6f) |  |
## Methodology
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.11 | **Monod: model-based discovery and integration through fitting stochastic transcriptional dynamics to single-cell sequencing data** | L. Pachter |  |  |  | bioRxiv | [Link](https://www.semanticscholar.org/paper/f8c2fc7128c26bc5abab6e6b55b61154c691c749) |  |
| 2025.10 | **In silico biological discovery with large perturbation models** | Patrick Schwab |  | GSK plc | Use large perturbation models by representing perturbation, readout and context as disentangled dimensions | Nature Computational Science | [Link](https://www.nature.com/articles/s43588-025-00870-1) | [Link](https://github.com/perturblib/perturblib) ![GitHub Stars](https://img.shields.io/github/stars/perturblib/perturblib) |
| 2025.10 | **Efficient and accurate search in petabase-scale sequence repositories** | André Kahles |  | ETH Zurich | Efficient and accurate search in petabase-scale sequence repositories | Nature | [Link](https://www.nature.com/articles/s41586-025-09603-w) | [Link](https://github.com/ratschlab/metagraph) ![GitHub Stars](https://img.shields.io/github/stars/ratschlab/metagraph) |
| 2025.08 | **Deep active optimization for complex systems** | D. Raabe |  |  |  | Nature Computational Science | [Link](https://www.semanticscholar.org/paper/5d62699e29224d34eba3fecfdf7ca1b87b3576fc) |  |
| 2025.04 | **OmniCellTOSG: The First Cell Text-Omic Signaling Graphs Dataset for Joint LLM and GNN Modeling** | Fuhai Li |  |  | Text-omic signaling graph dataset | ArXiv | [Link](https://www.semanticscholar.org/paper/fd87bf03430232aa9c2aeb733bd8d6dc023c4ef7) | [Link](https://github.com/FuhaiLiAiLab/OmniCellTOSG) ![GitHub Stars](https://img.shields.io/github/stars/FuhaiLiAiLab/OmniCellTOSG) |
| 2024.06 | **Learning Molecular Representation in a Cell** | Shantanu Singh |  |  |  | International Conference on Learning Representations | [Link](https://www.semanticscholar.org/paper/6db33b94c598876b05b7af83901a3a69d60eb47d) |  |
| 2024.05 | **Continuously evolving rewards in an open-ended environment** | Richard M. Bailey |  |  |  | arXiv.org | [Link](https://www.semanticscholar.org/paper/d8b10ccccd1fd7295ce86e0c214925b37f6a22de) |  |
## Reviews
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.12 | **Multimodal foundation transformer models for multiscale genomics.** | Jesper N. Tegnér |  |  | Multimodal transformer for genomics | Nature Methods | [Link](https://www.semanticscholar.org/paper/336d539daa17f126463a3373d00df732a0f04c83) |  |
| 2025.08 | **Large language models for clinical decision support in gastroenterology and hepatology** | J. Kather |  |  | Gastroenterology decision support with LLM | Nature Reviews Gastroenterology & Hepatology | [Link](https://www.semanticscholar.org/paper/5b813012fba35e20e1892f6b01f1dd323a1e1c3d) |  |
| 2025.07 | **Human interpretable grammar encodes multicellular systems biology models to democratize virtual cell laboratories** | Paul Macklin |  | Indiana University | Virtual cell | Cell | [Link](https://pubmed.ncbi.nlm.nih.gov/40713951/) | [Link](https://github.com/physicell-models/grammar_samples) ![GitHub Stars](https://img.shields.io/github/stars/physicell-models/grammar_samples) |
| 2025.07 | **The generative era of medical AI** | Pranav Rajpurkar |  | Harvard Medical School | Medical AI | Cell | [Link](https://pubmed.ncbi.nlm.nih.gov/40645169/) |  |
| 2025.04 | **Towards multimodal foundation models in molecular cell biology.** | Bo Wang |  |  | Multimodal molecular biology foundation models | Nature | [Link](https://www.semanticscholar.org/paper/7f65931fb6bbfca0496c919e83ed40e910b2dc5f) |  |
| 2025.01 | **Learning the language of life with AI.** | E. Topol |  |  | Multiomic foundation models for biomolecule prediction | Science | [Link](https://www.semanticscholar.org/paper/864031c9cc2195153f6fc08fed9d67131ddee8c4) |  |
| 2024.12 | **Cell Painting: a decade of discovery and innovation in cellular imaging** | A. Carpenter |  |  |  | Nature Methods | [Link](https://www.semanticscholar.org/paper/39d589719ee47fb817006f37ed1c231ddd88fdeb) |  |
| 2024.10 | **Empowering biomedical discovery with AI agents** |  |  |  | Biomedical Agents | Cell | [Link](https://pubmed.ncbi.nlm.nih.gov/39486399/) |  |
| 2024.08 | **Transformers in single-cell omics: a review and new perspectives** |  |  |  | Single cell foundation models | Nature Methods | [Link](https://www.nature.com/articles/s41592-024-02353-z) |  |
| 2024.08 | **Language models for biological research: a primer** |  |  |  | biological foundation models | Nature Methods | [Link](https://www.nature.com/articles/s41592-024-02354-y) |  |
| 2023.11 | **From intuition to AI: evolution of small molecule representations in drug discovery** | Vincent Blay |  |  |  | Briefings Bioinform. | [Link](https://www.semanticscholar.org/paper/fda524f3c8a733c747aa17d00127c339659accf7) |  |
| 2022.05 | **Phenotypic drug discovery: recent successes, lessons learned and new directions** | M. Mercola |  |  |  | Nature reviews. Drug discovery | [Link](https://www.semanticscholar.org/paper/2d09c3857d4b0db8c4d47ef44702393861071c88) |  |
| 2020.12 | **Image-based profiling for drug discovery: due for a machine-learning upgrade?** | Anne E Carpenter |  |  |  | Nature reviews. Drug discovery | [Link](https://www.semanticscholar.org/paper/082c82bfec1b087395db9ff377131600ac75b8e4) |  |
## Other Domain Foundation Models
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2025.07 | **A foundation model to predict and capture human cognition** | Eric Schulz |  |  |  | Nature | [Link](https://www.semanticscholar.org/paper/a4e64dee0d0f284edc160a9a8bc2b4385577249a) | [Link](https://huggingface.co/marcelbinz/Llama-3.1-Centaur-70B-adapter) |
| 2025.01 | **Accurate predictions on small data with a tabular foundation model** | Frank Hutter |  |  |  | Nature | [Link](https://www.semanticscholar.org/paper/6b238b17e419c7dd3912b9845449496bfb0a571a) |  |
## Paper Before 2024
| Year | Title | Team | Team Website | Affiliation | Domain | Venue | Paper/ Source | Code/Product |
| -----| ------| -----| -------------| ------------| -------| ------| --------------| -------------|
| 2023.10 | **ProGen2: Exploring the boundaries of protein language models** | Ali Madani | [Link](https://github.com/salesforce) | Salesforce Research | Protein | Cell Systems | [Link](https://pubmed.ncbi.nlm.nih.gov/37909046/) | [Link](https://github.com/salesforce/progen) ![GitHub Stars](https://img.shields.io/github/stars/salesforce/progen) |
| 2023.08 | **Predicting transcriptional outcomes of novel multigene perturbations with GEARS** | J. Leskovec |  |  |  | Nature Biotechnology | [Link](https://www.semanticscholar.org/paper/85906593661911c9a076cbb96391b9bb61a996bc) |  |
| 2023.07 | **An interpretable deep learning framework for genome-informed precision oncology** | Xinghua Lu |  |  |  | bioRxiv | [Link](https://www.semanticscholar.org/paper/16a77da1c7e35ad72fd9aa3aecae2ed6ae15675b) |  |
| 2023.05 | **Transfer learning enables predictions in network biology** |  |  |  | General scRNA tasks, discovery of key network regulators and candidate therapeutic targets | Nature | [Link](https://www.nature.com/articles/s41586-023-06139-9) | [Link](https://huggingface.co/ctheodoris/Geneformer) |
| 2023.04 | **Predicting compound activity from phenotypic profiles and chemical structures** | Anne E Carpenter |  |  |  | Nature Communications | [Link](https://www.semanticscholar.org/paper/0a25e1bcacbc6eecc491dfe1fd2211b622efd7c7) |  |
| 2023.02 | **Enabling Single‐Cell Drug Response Annotations from Bulk RNA‐Seq Using SCAD** | Ka-chun Wong |  |  |  | Advancement of science | [Link](https://www.semanticscholar.org/paper/f8729b20b63c8c841a399bf428e611a7ab8aa6ae) |  |
| 2022.10 | **Deep transfer learning of cancer drug responses by integrating bulk and single-cell RNA-seq data** | Qin Ma |  |  |  | Nature Communications | [Link](https://www.semanticscholar.org/paper/9146e8e6d209d4ea6933f8c1c93ec4fc41664aa5) |  |

## Other Awesome Projects

| Title                                           | Project                                                                                                                                                                             |
| ----------------------------------------------- | ----------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **Awesome AI Meets Biology**                    | [Link](https://github.com/Webioinfo01/Awesome-AI-Meets-Biology) ![GitHub Stars](https://img.shields.io/github/stars/Webioinfo01/Awesome-AI-Meets-Biology)                           |
| **Awesome-LLMs-meet-genomes**                   | [Link](https://github.com/ychuest/Awesome-LLMs-meet-genomes) ![GitHub Stars](https://img.shields.io/github/stars/ychuest/Awesome-LLMs-meet-genomes)                                 |
| **Awesome-Virtual-Cell**                        | [Link](https://github.com/Boom5426/Awesome-Virtual-Cell) ![GitHub Stars](https://img.shields.io/github/stars/Boom5426/Awesome-Virtual-Cell)                                         |
| **Awesome-Phenotypic-Drug-Discovery**           | [Link](https://github.com/Boom5426/Awesome-Phenotypic-Drug-Discovery) ![GitHub Stars](https://img.shields.io/github/stars/Boom5426/Awesome-Phenotypic-Drug-Discovery)               |
| **Awesome-LLM-Scientific-Discovery**            | [Link](https://github.com/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery) ![GitHub Stars](https://img.shields.io/github/stars/HKUST-KnowComp/Awesome-LLM-Scientific-Discovery)     |
| **Awesome bioagent papers**                     | [Link](https://github.com/aristoteleo/awesome-bioagent-papers) ![GitHub Stars](https://img.shields.io/github/stars/aristoteleo/awesome-bioagent-papers)                             |
| **Awesome LLM Agents for Scientific Discovery** | [Link](https://github.com/zhoujieli/Awesome-LLM-Agents-Scientific-Discovery) ![GitHub Stars](https://img.shields.io/github/stars/zhoujieli/Awesome-LLM-Agents-Scientific-Discovery) |
| **Awesome Papers on Agents for Science**        | [Link](https://github.com/OSU-NLP-Group/awesome-agents4science) ![GitHub Stars](https://img.shields.io/github/stars/OSU-NLP-Group/awesome-agents4science)                           |
| **awesome-single-cell**                         | [Link](https://github.com/seandavi/awesome-single-cell) ![GitHub Stars](https://img.shields.io/github/stars/seandavi/awesome-single-cell)                                           |
| **Awesome-Bioinformatics**                      | [Link](https://github.com/danielecook/Awesome-Bioinformatics) ![GitHub Stars](https://img.shields.io/github/stars/danielecook/Awesome-Bioinformatics)                               |
| **awesome**                                     | [Link](https://github.com/sindresorhus/awesome) ![GitHub Stars](https://img.shields.io/github/stars/sindresorhus/awesome)       

## Contributing

Contributions are welcome! Please see [how_to_update.md](how_to_update.md) for instructions on how to add new entries.

## License

This project is licensed under the Mozilla Public License 2.0 - see the [LICENSE](LICENSE) file for details.

## Citation

If you find this repository useful, please consider citing:

```bibtex
@misc{awesome-ai-virtual-tumor,
  title={Awesome AI Virtual Tumor},
  author={Webioinfo01},
  year={2025},
  url={https://github.com/Webioinfo01/Awesome-AI-Virtual-Tumor}
}
```
