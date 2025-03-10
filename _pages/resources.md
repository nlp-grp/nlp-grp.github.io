---
title: "Resources"
layout: textlay
excerpt: "Resources"
sitemap: false
permalink: /resources/
---


## **Resources**

This page provides an overview of the computational resources available to the USF NLP Group for research and experimentation. These resources support deep learning, large-scale NLP model training, and other computationally intensive tasks.

### **USF Advanced Computing Resources**  

The University of South Florida's advanced computing resources are managed by **Research Computing (RC)**, which operates the **CIRCE** cluster. CIRCE consists of approximately **350 nodes** with over **9,000 processor cores**, **57TB of shared memory**, and **158 GPUs**, running **Red Hat Enterprise Linux v7**. The cluster supports high-speed computation with **100GB Omnipath, 100GB Infiniband, and 40GB Infiniband** interconnects.  

For storage, CIRCE utilizes three parallel file systems:  
- **2.9PB GPFS** for high-speed data access  
- **819TB BeeGFS** for intensive I/O workloads  
- **350TB encrypted BeeGFS** for secure storage  

RC provides access to **120+ scientific software packages**, remote system access, and expert support for research projects involving high-performance computing, advanced data analysis, and visualization. **User training and assistance** are available upon request.
- **Access:** Requires an account and allocation. See [Connecting to Circe](https://wiki.rc.usf.edu/index.php/Connecting_To_CIRCE) for more details.  

### GAIVI  

The **GAIVI** CSE cluster is a high-performance computing cluster supports large-scale computational research, primarily in support USF's faculty working in computing and AI. It provides access to advanced GPU resources, facilitating deep learning, scientific simulations, and data-intensive tasks.  

#### **System Overview**  
GAIVI consists of multiple compute nodes, including general-purpose CPUs and high-performance GPUs. The system includes:  
- **Front Nodes:** GAIVI1 and GAIVI2, used for user logins and job management, featuring up to 20 CPU cores and 128GB of memory.  
- **GPU Compute Nodes:** Equipped with AMD EPYC and Intel Xeon processors, memory configurations ranging from 128GB to 2TB, and various GPU setups including NVIDIA A100, H100, Titan RTX, L40S, and RTX A6000.  
- **Specialized Nodes:** Intel PHI compute nodes for specific workloads.  
- **Storage Nodes:** Supporting high-speed and large-scale data management with up to 512GB memory.  

GAIVI uses the **SLURM** scheduling environment for job submissions, ensuring efficient resource allocation. Researchers and students can access training and documentation to optimize their workflow.  

For more details, visit the [GAIVI Documentation](https://docs.gaivi.cse.usf.edu/doku.php?id=main%3Agaivi%3Astart) or contact GAIVI administrators.

## **Cloud Computing Resources**  
- **Description:** Access to cloud computing credits for large-scale experiments.  
- **Providers:**  
  - Google Cloud (GCP)  
  - Amazon Web Services (AWS)  
  - Microsoft Azure  
  - Hugging Face Spaces (for model hosting and inference)  
- **Access:** Limited credits available. Contact [TBD] for allocation requests.  

## **Shared Storage & Data Repositories**  
- **Description:** Secure storage for datasets, model checkpoints, and experimental results.  
- **Resources:**  
  - Networked storage on HPC cluster  
  - Lab-managed NAS for long-term data storage  
  - Cloud-based storage (Google Drive, AWS S3, etc.)  
- **Access:** Request access via [TBD]. Follow data management best practices.  

## **Software & Tools**  
- **Preinstalled Frameworks:**  
  - PyTorch  
  - TensorFlow  
  - Hugging Face Transformers  
  - spaCy, NLTK, and other NLP libraries  
- **Code Repositories:**  
  - Private GitHub repository for NLP projects ([TBD] for access)  
  - Shared JupyterHub instance for collaborative work  

## **Requesting Resources**  
To request access to any of the resources listed above, please contact [TBD] with details on your project and computing needs.  

For troubleshooting or technical support, reach out to [TBD] or check the lab’s documentation.
