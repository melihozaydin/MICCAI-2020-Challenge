ABCs MICCAI 2020 challenge dataset description
Questions: abcsmiccai@mgh.harvard.edu

The training data consists of 225 images in MHA format,
split into three ZIP archives for easier downloading.
For each of the 45 cases, there are five files:
NNN_ct.mha, NNN_t1.mha, NNN_t2.mha are CT, MR T1, and MR T2 images
NNN_labelmap_task1.mha, NNN_labelmap_task2.mha are groud truth labels
for the structures to be segmented in Task 1 and Task 2.
Indexing of the structures in the labelmaps is provided below.

All images have the same dimensions and resolution. 
For each case, both MR images were rigidly registered to the CT.

NNN is a numeric case identifier in %03d format. 
Case identifiers are unique but not continuous within training and test datasets.

Task 1 Label to Structure key
1 Cerebellum 
2 Falx  
3 Sinuses 
4 Tentorium  
5 Ventricles 
	
Task 2 Label to Structure key
1 Brainstem
2 Chiasm
3 Cochlea_L
4 Cochlea_R
5 Eye_L
6 Eye_R
7 Lacrimal_L
8 Lacrimal_R
9 OpticNerve_L
10 OpticNerve_R