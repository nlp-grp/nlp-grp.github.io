---
title: "Resources"
layout: textlay
excerpt: "Resources"
sitemap: false
permalink: /resources/
---


## **Resources**
---
This page provides an overview of the computational resources for research and experimentation. These resources support deep learning, large-scale NLP model training, and other computationally intensive tasks.

## **USF Advanced Computing Resources** 
---
The University of South Florida's advanced computing resources are managed by **Research Computing (RC)**, which operates the **CIRCE** cluster. CIRCE consists of approximately **350 nodes** with over **9,000 processor cores**, **57TB of shared memory**, and **158 GPUs**, running **Red Hat Enterprise Linux v7**. The cluster supports high-speed computation with **100GB Omnipath, 100GB Infiniband, and 40GB Infiniband** interconnects.  

For storage, CIRCE utilizes three parallel file systems:  
- **2.9PB GPFS** for high-speed data access  
- **819TB BeeGFS** for intensive I/O workloads  
- **350TB encrypted BeeGFS** for secure storage  

RC provides access to **120+ scientific software packages**, remote system access, and expert support for research projects involving high-performance computing, advanced data analysis, and visualization. **User training and assistance** are available upon request.
- **Access:** Requires an account and allocation. See [Connecting to Circe](https://wiki.rc.usf.edu/index.php/Connecting_To_CIRCE) for more details.  

## **GAIVI**
---
The **GAIVI** CSE cluster is a high-performance computing cluster supports large-scale computational research, primarily in support USF's faculty working in computing and AI. It provides access to advanced GPU resources, facilitating deep learning, scientific simulations, and data-intensive tasks.  

#### **System Overview**  
GAIVI consists of multiple compute nodes, including general-purpose CPUs and high-performance GPUs. The system includes:  
- **Front Nodes:** GAIVI1 and GAIVI2, used for user logins and job management, featuring up to 20 CPU cores and 128GB of memory.  
- **GPU Compute Nodes:** Equipped with AMD EPYC and Intel Xeon processors, memory configurations ranging from 128GB to 2TB, and various GPU setups including NVIDIA A100, H100, Titan RTX, L40S, and RTX A6000.  
- **Specialized Nodes:** Intel PHI compute nodes for specific workloads.  
- **Storage Nodes:** Supporting high-speed and large-scale data management with up to 512GB memory.  

GAIVI uses the **SLURM** scheduling environment for job submissions, ensuring efficient resource allocation. Researchers and students can access training and documentation to optimize their workflow.  

For more details, visit the [GAIVI Documentation](https://docs.gaivi.cse.usf.edu/doku.php?id=main%3Agaivi%3Astart) or contact GAIVI administrators.

## **NSF ACCESS Cloud Computing Resources**  
---
The **NSF ACCESS (Advanced Cyberinfrastructure Coordination Ecosystem: Services & Support)** program provides researchers and educators with access to advanced computing resources, including supercomputers, AI and machine learning platforms, and big data analysis tools. Funded by the **National Science Foundation (NSF)**, ACCESS is designed to support a wide range of computational research needs beyond standard desktops and laptops.  

#### **Key Features:**  
- **Diverse Computing Systems:** From supercomputers to specialized compute clusters, each offering unique capabilities.  
- **Data & Storage Services:** High-performance storage solutions for large-scale research projects.  
- **Expert Support:** Assistance in optimizing computational workflows and removing technical barriers.  
- **Scientific Applications & Gateways:** Tools and platforms tailored for specific research domains.  
- **Education & Training:** Resources for classroom use, training workshops, and helpdesk services.  
- **Collaborative Communities:** Opportunities to connect with other researchers in shared interest areas.  

### **Who Can Use ACCESS?**  
ACCESS resources are **free** for U.S. researchers, educators, students, and eligible international collaborators. Commercial organizations can also apply for allocations, though some services may require fees.  

For more details and to apply for resources, visit: [NSF ACCESS](https://access-ci.org/)

## **Software & Tools** 
---
Here’s a list of popular **open-source NLP software** tools commonly used for natural language processing tasks:

### 1. **SpaCy**
   - **Description:** A fast and efficient library for industrial-strength NLP in Python, including tokenization, part-of-speech tagging, named entity recognition, and dependency parsing.
   - **Link:** [SpaCy](https://spacy.io/)

### 2. **NLTK (Natural Language Toolkit)**
   - **Description:** A comprehensive library for symbolic and statistical NLP, including a wide range of linguistic resources like corpora and lexical resources.
   - **Link:** [NLTK](https://www.nltk.org/)

### 3. **Hugging Face Transformers**
   - **Description:** A library for state-of-the-art NLP models based on transformer architectures. It includes pre-trained models for tasks such as text classification, translation, and summarization.
   - **Link:** [Hugging Face](https://huggingface.co/transformers/)

### 4. **Gensim**
   - **Description:** A library for unsupervised learning on text data, especially for topic modeling and document similarity. Gensim is known for its implementation of Word2Vec and other vector space models.
   - **Link:** [Gensim](https://radimrehurek.com/gensim/)

### 5. **AllenNLP**
   - **Description:** A deep learning library for NLP built on PyTorch, designed to support research in language understanding, including question answering and semantic role labeling.
   - **Link:** [AllenNLP](https://allennlp.org/)

### 6. **Stanford NLP**
   - **Description:** A suite of NLP tools from Stanford University, providing robust solutions for tasks like part-of-speech tagging, named entity recognition, and dependency parsing.
   - **Link:** [Stanford NLP](https://stanfordnlp.github.io/CoreNLP/)

### 7. **TextBlob**
   - **Description:** A simple library for NLP tasks in Python, offering tools for text classification, part-of-speech tagging, noun phrase extraction, and more.
   - **Link:** [TextBlob](https://textblob.readthedocs.io/en/dev/)

### 8. **OpenNLP**
   - **Description:** An Apache project providing machine learning-based NLP tools for tasks like tokenization, sentence splitting, part-of-speech tagging, and named entity recognition.
   - **Link:** [OpenNLP](https://opennlp.apache.org/)

### 9. **CoreNLP (Stanford CoreNLP)**
   - **Description:** A Java-based NLP toolkit from Stanford, providing robust and accurate algorithms for many NLP tasks such as tokenization, named entity recognition, and parsing.
   - **Link:** [CoreNLP](https://stanfordnlp.github.io/CoreNLP/)

### 10. **Flair**
   - **Description:** A simple framework for state-of-the-art NLP, focusing on providing easy-to-use models for text classification, named entity recognition, and more.
   - **Link:** [Flair](https://github.com/flairNLP/flair)

### 11. **BERT (Bidirectional Encoder Representations from Transformers)**
   - **Description:** A pre-trained transformer-based model for NLP tasks such as question answering and text classification, available through the Hugging Face library and other implementations.
   - **Link:** [BERT](https://github.com/google-research/bert)

### 12. **DeepPavlov**
   - **Description:** A library for building conversational AI and NLP systems, focusing on machine learning and deep learning models for dialogue systems, named entity recognition, and question answering.
   - **Link:** [DeepPavlov](https://github.com/deepmipt/DeepPavlov)

### 13. **Fairseq**
   - **Description:** A sequence-to-sequence learning toolkit for PyTorch by Facebook AI Research, specializing in machine translation, text summarization, and other sequence-based tasks.
   - **Link:** [Fairseq](https://fairseq.readthedocs.io/)

### 14. **Berkeley Neural Parser**
   - **Description:** A neural network-based parser designed for syntactic analysis of text.
   - **Link:** [Berkeley Neural Parser](https://github.com/harvardnlp/berkeleyparser)

### 15. **PyTorch-NLP**
   - **Description:** A library built on top of PyTorch providing efficient and easy-to-use NLP tools, including data loaders and transformers.
   - **Link:** [PyTorch-NLP](https://pytorchnlp.readthedocs.io/en/latest/)
