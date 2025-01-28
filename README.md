# Building a Classifier For MoTrPAC Endurance Training Data Based on Lipoprotein Receptor Levels in the Gastrocnemius
Classifier for endurance training duration based on metabolite levels in the gastrocnemius, using the [MoTrPAC Endurance Training Dataset](https://github.com/MoTrPAC/MotrpacRatTraining6moData?tab=readme-ov-file). 

## Motivation
Given that the gastrocnemius is fundamental to running and given that previous research has shown that metabolites related to lipid metabolism were enriched in the gastrocnemius, can a model be built that uses the results of gastrocnemius lipoprotein receptor assays to assign training duration?

## Methods
Multinomial logistic regression and random forest models were built for the data. These models were further tuned using recursive feature elimination. More details on the methods used for this project are included in 'Research Paper.pdf'. 

## References
MoTrPAC Study Group., Lead Analysts. & MoTrPAC Study Group. Temporal dynamics of the multi-omic response to endurance exercise training. Nature 629, 174–183 (2024). https://doi.org/10.1038/s41586-023-06877-w

MoTrPAC Study Group. 2022. Temporal dynamics of the multi-omic response to endurance exercise training across tissues. bioRxiv doi: 10.1101/2022.09.21.508770
