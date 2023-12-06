# Building tumor microenvironment-informed machine learning models to predict breast cancer prognostication/progression


## **Background and Rationale:** <br> 
Breast cancer accounts for 31% of all cancer cases and 15% of all cancer deaths among women worldwide. Currently existing genomic tests (Oncotype DX, MammaPrint, and PAM50) that guide treatment decisions only analyze expression of genes associated with the risk of recurrence and lack depth as they do not consider the full tumor microenvironment (TME). In this project, we hope to utilize and integrate single-cell transcriptomic methods (e.g. scRNA-seq) and spatial data (e.g. CyCIF imaging data) to uncover the interplay between diverse cell populations in the TME of breast cancer tissues from patients with non-recurring or recurrent disease in order to train and power our machine learning models to predict disease progression as it relates to clinical outcomes.

## **Project Outline:**

Task 1: Data retrieval and processing. <br>

Task 2: Extraction of TME features from single cell RNA-seq (scRNA-seq) data:
- Task 2a: scRNA-seq preprocessing, batch correction, and clustering.
- Task 2b: cell type annotation.
- Task 2c: Extraction of molecular profiles of cell types of interest. <br>

Task 3: Development of predictive models using the extracted features to predict disease progression/recurrence.
- Task 3a: Processing of the METABRIC dataset.
- Task 3b: Training of machine learning models to predict disease progression/recurrence.

## Data: ###

The scRNA-seq data used in this project were accessed using the [HTAN Data Portal](https://data.humantumoratlas.org/), and were generated as part of the Human Tumor Atlas Pilot Project (HTAPP). Gene expression and corresponding clinical data were obtained from the Molecular Taxonomy of Breast Cancer International Consortium (METABRIC) studies from [cBioPortal](https://www.cbioportal.org/study/summary?id=brca_metabric). 

## Tools and Frameworks Used
1. Python version 3.11
2. Scanpy version 1.9.6
3. Pandas version 2.1.1
4. Synapse client version 3.2.0
5. Hdf5 plugin 
6. Pathlib
   
## Installation and Setup

1. Clone the repository: `git clone https://github.com/NCI-HTAN-Jamborees/Breast-cancer-progression-models.git`
2. Install and load required packages: `pip install -r requirements.txt`

## Results: ###

## Future Directions: ###


## **Team:**
Mohamed Omar <br>
Zergham Ahmed <br>
Kristin Qian <br>
Taylor Marohl <br>
Jung Hun Oh <br>
Chi Zhang <br>
Bei Wei <br>
David Enoma <br>

## References

### **Acknowledgements:**

Thank you to the Human Tumor Atlas Network (HTAN), NIH, NCI, and Cancer Genomics Cloud (Seven Bridges) for your support during this project!
