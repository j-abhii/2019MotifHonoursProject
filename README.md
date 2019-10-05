# 2019MotifHonoursProject
  Code and resources compiled together for 2019 Honours Project and Summer Work at the Wallace Lab on predicting the effects of 3'UTRs.


## Intro

All code is to be found under /src and data under /data. Code is written in .rmd format and should be opened in RStudio.

### Files and Information (As of 05/10/19):

Three files are present in root of _/src_ which contain the primary relevant code. 

1) *create_ref_dataset.Rmd* : Creates a ref_data df containing motif frequencies and codon usage in a single df from raw sun et al data.  

2) *project_report.Rmd* : Contains most recent version of primary analysis. Performs combined linear models with step selection of motifs. Does not include glmnet anymore.

__The other two files have not been updated/cleaned recently with new format/files but should work.__

3) *combined_v1.Rmd* : Original combined honours project code using Nadal-Ribelles et al scRNAseq data and decay data from both Sun et al and Chan et al. Linear modelling is done using glmnet_selection motifs. There is no codon usage etc in this.

4) *abhi_terminatome_model.Rmd* : Contains original code for simultaneous analysis of  2013 Yamanishi et al terminatome RelFI data for all yeast genes along with Chan et al DecayRate data. For each data, it performs Multiple linear models, step selected combined models, and also glmnet selection and comparison of motifs selected in each case and union of the two. 
