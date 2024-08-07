## Spatial Transcriptomics Course Project

As part of my CS 7641 (Intro to ML) course this summer, I participated in a group project exploring a spatial transcriptomics dataset from a 2023 paper by R Arora, et al.* I contributed the .ipynb found in this repo. 

Our task was to do a binary classification of groups of cells collected from tumors of patients with OSCC (a type of oral cancer) into 'tumor core' (TC) or 'leading edge' (LE) groups. The tumor samples were processed with spatial transcriptomics, which can map 3D-positional information to gene expression levels at an almost- cell-level granularity. Pathologist annotations were added to the dataset after it was generated.



The file here is an ML pipeline which was built to enable evaluation of 

1) Feature Selection paradigms 

2) Performance of RF, MLP, and SVM models

   

The file also uses parallel processing to take advantage of Pace, GT's HPC.





*[Spatial transcriptomics reveals distinct and  conserved tumor core and edge  architectures that predict survival and  targeted therapy response](https://www.nature.com/articles/s41467-023-40271-4)

