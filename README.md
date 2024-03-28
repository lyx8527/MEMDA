# MEMDA
A method to pre-complete the association matrix with different feature combinations, and then use a label propagation algorithm with error correction to predict microbe-drug associations, called MEMDA.




# Requirements
 * python == 3.9
 * pytorch == 2.0.1
 * scikit-learn == 1.3.0
 * numpy == 1.22.3
 * scipy == 1.11.2
 * seaborn == 0.13.2


# Files

1.Data

microbe-drug(DrugVirus).xlsx: The associations betwenn microbes and drugs.

Drug_atc.txt: Drug ATC code similarity.

Drug_simle.txt: Drug structure similarity.

Microbe_functional.txt: Microbe functional similarity.

Microbe_sequence.txt: Microbe sequence similarity.


2.Code

config_init.py: Initializing some parameters in MEMDA.

dataload.py: Loading microbial-drug association matrix, microbial similarities and drug similarites.

main.py: This function implements the workflow of the MEMDA model to predict the association between drugs and microbes.

utils.py: This function contains implementations of three algorithms used in MEMDA,including SNF, WKNKN and LNS.


# Run step

Run main.py to obtain the predicted scores for microbe-drug associations.


# Contact 
If you have any questions or suggestions with the code, please let us know. Contact Yuxiang Li at 224711078@csu.edu.cn































 
