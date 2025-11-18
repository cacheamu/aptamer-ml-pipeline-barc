# Aptamer Feature Engineering & Machine Learning Binding Prediction Pipeline
MSc Thesis + Bhabha Atomic Research Centre Internship (Jan–May 2025)

Full end-to-end pipeline developed at BARC, Mumbai

Workflow:
1. Built database of ~600 published aptamers (Excel + SQL)
2. Secondary structure & MFE prediction → ViennaRNA (RNAfold)
3. Z-score calculation for thermodynamic stability ranking
4. Integrated sequence length + Kd values from public databases
5. DeepChem Graph Neural Network setup for binding affinity prediction

Sample Top Candidates (most stable + strongest binders)
| Aptamer            | MFE     | Z-score  | Kd (nM) | Target       |
|-------------------|---------|----------|---------|--------------|
| VEGF aptamer      | -28.40  | -2.31    | 0.14    | VEGF         |
| Theophylline      | -11.70  | -1.92    | 0.32    | Theophylline |
| Thrombin          | -15.80  | -1.88    | 0.5     | Thrombin     |

Tech stack: Python • ViennaRNA • DeepChem • Pandas • RDKit • AWS • Linux

Developed by Pooja Binukumar  
MSc Bioinformatics | BARC Research Intern 2025  
Email: poojabk713@gmail.com
