# Roche ML Scientist – Key Concepts

## 🔬 Scientific Focus
- Large Molecule Drug Discovery (LMDD)

**Large Language Molecule Discovery (LLMD)** refers to the use of **large language models (LLMs)** — originally developed for human language — in the domain of **biological and chemical sequences**, such as proteins (FASTA), DNA/RNA, or small molecules (SMILES), with the goal of accelerating **therapeutic discovery**.

These models are trained on massive biomolecular datasets to learn their **syntax, structure, and semantics**, enabling applications like:

- Predicting protein **function, folding, or structure**
- Designing **new antibodies, peptides, or protein scaffolds**
- Modeling **molecular interactions** (e.g., binding or immunogenicity)
- Generating novel molecules with desired properties
- Building **agents** for scientific reasoning and knowledge retrieval

---

## 💡 Core Concepts

| Concept | Description |
|--------|-------------|
| **Protein Language Models** | LLMs trained on amino acid sequences (e.g. ESM-2, ProtGPT2) to learn biological "grammar" |
| **SMILES Transformers** | LLMs for chemical strings (e.g. ChemBERTa, MolBERT) that model molecular properties |
| **Masked Language Modeling (MLM)** | A self-supervised training objective where random tokens are masked and predicted |
| **Transfer Learning** | Using pretrained LLMs and fine-tuning on smaller, task-specific biological datasets |
| **LLM Agents** | LLMs enhanced with tools (e.g., databases, structure prediction APIs) to reason about biology and chemistry |
| **Structure-Conditioned Generation** | Generating sequences that are constrained by structural, physical, or functional parameters |

---

## 🧪 Application Domains

| Field | Use Case |
|-------|----------|
| **Immunology** | Predict antigen-antibody binding, design immune-stable sequences |
| **Oncology** | Generate cancer-targeting peptides or inhibitory proteins |
| **Rare Diseases** | Predict mutation impact on protein function or misfolding |
| **Drug Repurposing** | Use embeddings to find molecular similarity or therapeutic overlap |
| **Synthetic Biology** | Generate entirely new proteins or enzymes with desired functions |

---

## 🏭 Roche & Prescient Design’s Focus

Roche — and its AI-first biotech unit **Prescient Design** — are at the forefront of LLMD, actively developing:

- **Foundational models** for large molecule drug discovery (e.g., antibodies, biologics)
- Systems combining **biological priors with generative models**
- **Agents** capable of retrieving, reasoning, and designing across complex biological datasets

Their mission is to enable **autonomous scientific discovery** through deeply integrated AI and domain-specific biological modeling.
---

- Protein structure-function prediction
**Protein structure-function prediction** is the task of using computational methods — especially **machine learning** and **molecular modeling** — to predict how a protein's **structure** (its 3D shape) determines or influences its **function** (what it does in the body).

It is based on the biological principle that:

> **"Structure determines function."**  
> A protein's 3D conformation directly governs how it interacts with other molecules, which defines its role in biological processes.

---

## 🧬 Key Concepts

| Concept | Description |
|--------|-------------|
| **Primary structure** | The raw amino acid sequence (FASTA format) |
| **Secondary/tertiary structure** | Local folding patterns (e.g., alpha helices, beta sheets) and the full 3D shape |
| **Function** | What the protein does: binding, signaling, catalysis, structural support, etc. |
| **Prediction Goal** | Infer a protein’s function based on its sequence or predicted structure |

---

## 🧪 Use Cases in Drug Discovery

| Application | Description |
|-------------|-------------|
| **Target Identification** | Predict if a protein is involved in a disease pathway |
| **Binding Site Prediction** | Identify potential pockets for drug docking or ligand binding |
| **Mutational Impact Modeling** | Understand how mutations affect protein stability/function (e.g., in rare diseases or cancer) |
| **Antibody Design** | Predict the binding efficiency of antibody-antigen interactions |
| **Synthetic Protein Engineering** | Design novel proteins with specific activities or stability profiles |

---

## 🤖 ML Models Used

| Model Type | Role |
|------------|------|
| **Protein LLMs (e.g., ESM-2, ProtBERT, ProtT5)** | Learn representations from sequences to predict structure/function |
| **AlphaFold 2 / 3** | Predict 3D structure from amino acid sequence |
| **Graph Neural Networks (GNNs)** | Represent 3D atomic structure to predict function or interaction |
| **Contrastive Models** | Learn embeddings where proteins with similar function are closer |

---

## 🔗 Tools & Datasets

- **AlphaFold DB** — 3D structures for millions of proteins  
- **PDB (Protein Data Bank)** — Gold standard for experimental 3D structures  
- **UniProt** — Annotated protein sequences with functional data  
- **ESM (Meta)** — Transformer-based models for protein sequence embeddings  
- **D-SCRIPT / DeepFRI / ProtCNN** — Deep learning models for function prediction  

---
- Immunogenicity modeling
- Multi-omics integration
- Binding site identification

## 🧠 ML Techniques Emphasized
- Foundational Models (ESM-2, ProtGPT2, BioGPT, MolBERT)
- Self-supervised learning (contrastive, masked LM)
- Transfer learning for protein/molecule prediction
- LLMs & Agents for therapeutic design and knowledge access
- Generative models for sequence and molecule generation

## 🧪 Data Types & Challenges
- Biological sequences (FASTA)
- Structural data (PDB, AlphaFold)
- Gene expression / proteomics / epitope data
- Heterogeneous sources: multi-modal fusion
- Scarce labels + High dimensionality

## 🧩 Roche Mindset
- Impact-first, patient-centered research
- Reproducible, scalable, and explainable AI
- Scientific rigor + creativity + real-world impact
- Cross-functional collaboration with domain experts
- Initiative and independent research capability
