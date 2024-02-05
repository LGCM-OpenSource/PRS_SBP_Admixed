# PRS_SBP_Admixed

This repository contains data from the article entitle "Assessing the Predictive Efficacy of European-based Systolic Blood Pressure Polygenic Risk Scores in Diverse Brazilian Cohorts", which used UKB dataset for GWAS derivation and PRS training, as well as for PRS validation together with two highly admixed Brazilian population.  
The GWAS summary is available at GWAS catalog under GCP ID GCP000817.  
Here we made available the PRS scoring file and extrapolation and calculation with plink for all 3 populations alongside the phenotype used (SBP - SBP_Med_adjusted) and covariables (Age, Sex, BMI and first four PCs).  

## Columns in PRS scoring file:
1. rsID: Variant ID;
2. A1: Effect Allele;
3. LDPRED2_betas: Renormalized Betas with LDPred2

## Columns in files from testing datasets (UKB, Baependi and Pelotas):
1.	Sex: 0 – male, 1 – female;
2.	BMI: body mass index;
3.	Age;
4.	SBP_Med_adjusted: Indicates the Systolic Blood Pressure after Medication use correction (SBP was corrected adding 15mmHg if the sample uses Blood Pressure medication);
5.	DBP_Med_adjusted: Indicates the Diastolic Blood Pressure after Medication use correction (DBP was corrected adding 10mmHg if the sample uses Blood Pressure medication);
6.	LDPRED2_betas_SUM: PRs extrapolation based on PRS derived in UKB using LDPred2 algorithm;
7.	Deciles: Based on PRS distribution. 0 to 9.

