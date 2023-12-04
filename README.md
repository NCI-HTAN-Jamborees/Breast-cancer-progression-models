# Breast-cancer-progression-models

## **Goal**: Build tumor microenvironment-informed machine learning models to predict breast cancer prognostication/progression <br>


### **Background:** <br> 
Breast cancer accounts for 31% of all cancer cases and 15% of all cancer deaths among women worldwide. Currently existing genomic tests (Oncotype DX, MammaPrint, and PAM50) that guide treatment decisions only analyze expression of genes associated with the risk of recurrence and lack depth as they do not consider the full tumor microenvironment (TME). In this project, we hope to utilize and integrate single-cell transcriptomic methods (e.g. scRNA-seq) and spatial data (e.g. CyCIF imaging data) to uncover the interplay between diverse cell populations in the TME of breast cancer tissues from patients with non-recurring or recurrent disease in order to train and power our machine learning models to predict disease progression.

### **Project Outline:**

Task 1: Data retrieval and processing. <br>

Task 2: Extraction of TME features from single cell RNA-seq (scRNA-seq) data:
- Task 2a: scRNA-seq preprocessing and clustering.
- Task 2b: cell type annotation.
- Task 2c: Extraction of molecular profiles of cell types of interest. <br>

Task 3: Development of predictive models using the extracted features to predict disease progression/recurrence.
- Task 3a: Processing of the METABRIC dataset.
- Task 3b: Training of machine learning models to predict disease progression/recurrence.
