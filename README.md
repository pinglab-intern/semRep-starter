# SemRep

Knowledge Graph Exploration with NLM semrep

**Title:** A study of Drug to cardiovascular disease (CVD) Association with SemRep and Deep learning

**Description**: Starting with well defined oxidative stress categories (e.g., Initiation, Regulation and Outcome of Oxidative Stress) and a list of drugs in cardiovascular disease (CVD), we will explore semrep to extract all relevant SPO- triplet. We further build knowledge graphs with these triplets and prepare a muli-order association matrix to represent graph data structure. Using this graph structure, we will build a sequence prediction model for drug to CVD association. This project will provide a detailed analysis of drugs to CVD association with both qualitative evidence and quantitative scores.

**Leaders/Instructors:**
Dr. Dibakar Sigdel & Dr. David Liem (Mr. Vincent Kyi for technical support)

### Participants
- **Vladimir Guevara**
- **Maya Gupta**
- Alex Zhang*
- Ethan Tran*
- Aaliyah

Note: Participants with * sign are also involved in other projects in Project 1 (A,B and C)

**Project walk-through**

Get familiar with NLM SemRep for Biomedical Documents (https://semrep.nlm.nih.gov/).
Learn to extract Drug information from DrugBank API(https://www.drugbank.ca/) and learn a curated list of oxidative stress categories and associated molecules.
Extract knowledge graph triplets (SPO) for drug and CVD association from SemRep tool and create a graph data structure (Association Matrix).
Build RNN (LSTM)  model to predict/classify/partition the drug/molecule for the category of oxidative stress with associated information and analysis.
Organize codes and prepare project documentation sites at PingLab Intern GitHub account.
Final presentation at lab meeting.

**Education goals**: The students will learn how to work with innovative text mining tools (e.g., semrap, caseOLAP, Neo4J)  for biomedical documents and machine learning approach (RNN, LSTM)  for model development and implementation to answer important biomedical questions.

**Scientific goals**: The students will explore knowledge graphs for drug and CVD associations with a focus on oxidative stress categories (e.g., Initiation, Regulation and Outcome) and underlying molecular mechanism.


### Preparing Foundation
- Create an account at NLM/UMLS account
- Get Familiar with the following:
    - [MeSH tree](https://meshb.nlm.nih.gov/treeView): Madical Subject Headings
    - [ICD codes](https://icd.who.int/browse11/l-m/en): International Classification of Disease
    - [Uniprot](https://www.uniprot.org): Database of proteins organized with Protein ID, synonyms, Abbr, associated Genes and biomolecules
    - [Reactome](https://reactome.org) : Database of Pathways and associated documents in Graph structure
    - [Drugbank](https://www.drugbank.ca) : Database of Drugs and associated documents
- Install Python([Anaconda](https://www.anaconda.com/products/individual))
- Install [Neo4J](https://neo4j.com/) and take available tutorials
- Get Familiar with [NLTK](https://www.nltk.org/) NLP package in Python
- Get introductory idea of Machine Learning from [Scikit](https://scikit-learn.org/stable) Learn and [Tensorflow](https://www.tensorflow.org/) (Specially, LSTM)

### Project Detail

- **Step -1**: Prepare required CVD entities (e.g, UMLS dictionary, MeSH Tree, ICD Tree, Proteins, Genes, RNASeq, Drugs)
- **Step -2**: Explore semRep for CVD cases with CVD entities
- **Step -3**: Prepare a CVD KG from available SPO triplets
- **Step -4**: Create a Graph association Matrix and artifacts
- **Step -5**: Build and test LSTM models
- **Step -6**: Analyse the result
- **Step -7**: Present the result
- **Step -8**: Organize the documentation with Mkdocs


### References

1. Github for SemRep (https://github.com/CaseOLAP/SemRep)
2. SemRep Paper (https://ieeexplore.ieee.org/stamp/stamp.jsp?tp=&arnumber=8574025)
3. SemRep NLM (https://semrep.nlm.nih.gov/)
