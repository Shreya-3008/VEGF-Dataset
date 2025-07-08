• **Project Title**: Binary Classification Model for VEGF Receptor 2 Bioactivity.


• **Description:** VEGFR2 is also known as KDR in humans. VEGF receptor 2 is a very crucial aspect in cancer research due to its role in angiogenesis. Multiple anti-angiogenic drugs that inhibit VEGFR2 activity are currently in clinical use or undergoing clinical trials. This project aims to apply machine learning to classify compounds as active or inactive against VEGFR-2 based on their IC50 values, using data from the ChEMBL database. This model is a self-study exercise to explore cheminformatics and machine learning concepts.
This project implements a binary classification model to predict compounds that inhibit VEGF receptor using a Random Forest classifier algorithm. The model also has SMILES strings, which are converted into Morgan Fingerprints.  
**Dataset**: The dataset was taken from the ChEMBL database. ChEMBL ID: CHEMBL279.
The data obtained from this database was saved in a CSV file. Compounds with IC50 < 1000 nM are labeled as Active (1), and others as Inactive (0). 


**•Requirements**:scikit-learn, pandas, NumPy, seaborn, matplotlib, RDkit, Google Colab.


**• Algorithm:** Random Forest Classifier. 


**Results:**  Key outcomes of the project are:
 1. Overall accuracy score: 0.82%. This shows that the model correctly predicted ~82% of the compounds.
    
2. From the confusion matrix, it can be understood that 86  compounds are True positives and 78 compounds are True Negatives. Also, 16 are false positives and 21 are false negatives.

    
**• Learning reflections:** Some code used in this project was guided by Google Colab suggestions and online tutorials. However, it was customized by me for this project.


**• Future work:** Include other important parameters such as molecular weight, ligand efficiency, and Ki values in the project. Work on Multiclass classification and consider hyperparameter tuning.


**References:**  ChEMBL database: https://www.ebi.ac.uk/chembl/


Barbara Zdrazil, Eloy Felix, Fiona Hunter, Emma J Manners, James Blackshaw, Sybilla Corbett, Marleen de Veij, Harris Ioannidis, David Mendez Lopez, Juan F Mosquera, Maria Paula Magarinos, Nicolas Bosc, Ricardo Arcila, Tevfik Kizilören, Anna Gaulton, A Patrícia Bento, Melissa F Adasme, Peter Monecke, Gregory A Landrum, Andrew R Leach, The ChEMBL Database in 2023: a drug discovery platform spanning multiple bioactivity data types and time periods, Nucleic Acids Research, Volume 52, Issue D1, 5 January 2024, Pages D1180–D1192,


RDKit documentation: https://www.rdkit.org/docs/
Scikit-learn documentation: https://scikit-learn.org/

