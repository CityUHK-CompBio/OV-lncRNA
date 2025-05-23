## Subtype-specific lncRNA ZFHX4-AS1 promotes invasion and metastasis of ovarian cancer by interacting with HuR RNA binding protein to stabilize its antisense gene ZFHX4

### 1. Background
Ovarian cancer (OvCa) is a heterogeneous disease, posing a significant challenge to women’s health globally. Currently, the biological function of long non-coding RNAs (lncRNAs) in different subtypes of OvCa remains poorly characterized. Among these subtypes, mesenchymal OvCa is the most aggressive subtype with unfavorable survival outcomes.   

### 2. Major findings   
We performed integrative network analysis to uncover the heterogeneity of lncRNAs in different OvCa subtypes. We identified ZFHX4-AS1 as a mesenchymal subtype-specific master regulator driving the epithelial-mesenchymal transition (EMT). Overexpression of ZFHX4-AS1 is a predictor of poor patient survival. Silencing ZFHX4-AS1 inhibits OvCa cell viability, migration, EMT, and stemness properties in vitro and reduces metastasis of OvCa in vivo. Mechanistically, by binding to the RNA binding protein (RBP) HuR, ZFHX4-AS1 promotes the interaction of HuR and mRNA of the target antisense gene ZFHX4, leading to enhanced ZFHX4 expression.   

### 3. Codes for data analysis
* Drug_sensitivity_analysis.Rmd: Code for drug sensitivity analysis. Gene expression profiles and drug sensitivity data of OvCa cell lines were downloaded from https://discover.nci.nih.gov/rsconnect/cellminercdb/. The processed results can be found in CTRP_OV.RData file in demo_data subdirectory.   

* Integrative_network_inference_and_master_regulator_analysis.Rmd: Code for developing the subtype-specific regulatory network using the TCGA-OV dataset. The processed results can be found in RTN_network.rda file in demo_data subdirectory.     

* Pan_cancer_analysis_of_lncRNA.Rmd: Code for the pan-cancer analysis (survival and correlation analysis)of ZFHX4-AS1 and ZFHX4.      

* TCGA_OV_data_preprocessing.Rmd: Code for the pre-processing of TCGA-OV dataset downloaded from [the University of California Santa Cruz (UCSC) Xena data portal](https://xenabrowser.net/datapages/).     

* Univariate_and_multivariate_Cox_analysis.Rmd: Code for uni-variate and multi-variate Cox analyzing and visualizing. The processed results can be found in Expr_OV.RData and RTN_network.rda files in demo_data subdirectory.      
