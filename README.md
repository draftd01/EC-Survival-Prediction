# Endometrial Carcinoma (EC) Survival Prediction
## Summary
This final project for the NYU Advanced Integratic Omics course sought to use a multi-omic approach to predict EC paitient survival using normalized RNA read counts, as well as relevant abundance of protein and phosphosites identified with Tandem Mass Spectrometry (TMT), measured using z-statistic and adjusted log2-ratio respectively. Dimensionality reduction of the omics data was performced using variance thresholding follwed by one of two methods, either Lasso with cross-validation (LassoCV), or recurrent feature elimination with cross-validation (RFECV).

## Methods
Two methods of feature selection were tested before training a random forest regressor    

## Data
The dataset for this project may be found in the Pride archive PXD055203

## Reference Paper
Yu J, Gui X, Zou Y, Liu Q, Yang Z, An J, Guo X, Wang K, Guo J, Huang M, Zhou S, Zuo J, Chen Y, Deng L, Yuan G, Li N, Song Y, Jia J, Zeng J, Zhao Y, Liu X, Du X, Liu Y, Wang P, Zhang B, Ding L, Robles AI, Rodriguez H, Zhou H, Shao Z, Wu L, Gao D. A proteogenomic analysis of cervical cancer reveals therapeutic and biological insights. Nat Commun. 2024 Nov 22;15(1):10114. doi: 10.1038/s41467-024-53830-0. PMID: 39578447; PMCID: PMC11584810.
 
