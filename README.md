# Files used for ReMA Thesis

**Thesis Title:** _Exploring the Effect of Differences in Logical Form on the Evaluation of Model Capabilities: A Comparison Between the COGS and ReCOGS Benchmarks_

**Author:** _Marina Munuera Esteller_


This repository contains the datasets and scripts used to run the experiments in my masters thesis. It also contains the evaluation code used for both the quantitative and qualitative evaluation of the results.

---------
# Data

Folders:
- COGS_MyVersion
- ReCOGS_MyVersion
- ReCOGSpos_MyVersion

Files include the versions of the COGS, ReCOGS, and ReCOGSpos datasets used for this thesis. All folders include the training, development, test, and generalisaiton sets. 

Note that for my experiments, the ReCOGS and ReCOGSpos training ser were downsized to the original COGS version of the training set.

---------
# Experiments

Files:
- ReCOGS_MyVersion.zip

The zip file includes the full folder of files used to run the experiments. The version of the folder included here is the one used to train models on my adjusted version of the ReCOGS dataset, it therefore also includes these data files. For the other three datasets the folders were exactly the same except for the LF specific dataset.

These files were taken from the ReCOGS github: https://github.com/frankaging/ReCOGS

---------
# Evaluation Code

Files:
- EvalMetric.ipynb
- ErrorAnalysis.ipynb

These files are the notebooks used to perform the quantitative (EvalMetric) and qualitative (ErrorAnalysis) evaluations on the model output files.

