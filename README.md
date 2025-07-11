# ORACLE2
This page contains the scripts and R Markdown files for the ORACLE2 analyses.

_Meulmeester FL et al. Inflammatory and clinical risk factors for asthma attacks (ORACLE2): a patient-level meta-analysis of control groups of 22 randomised trials. Lancet Respir Med. 2025 Jun;13(6):505-516. doi: 10.1016/S2213-2600(25)00037-2_

## Code

1. ORACLE2-IPD_Extraction_code-instructions.zip: SPSS and R scripts for Individual Patient Data extraction
2. ORACLE2-ROB2_IRPG_beta_v9.xlsm: Risk of Bias (RoB2) assessment of the ORACLE2 systematic review in Excel
3. ORACLE2-IDA_and_analyses.Rmd: Complete R Markdown for creating data, tables and figures presented in the ORACLE2 manuscript and supplementary files (Meulmeester et al. TLRM 2025)
4. ORACLE2-Analyses_weighted_by_person_years.Rmd: R Markdown for supplementary analyses weighted by person years
5. ORACLE2-Forestplot_weighted_by_person_years.Rmd: R Markdown for supplementary forest plots weighted by person years (Figure S7 A-V and Figure S8)

### Step-by-step R Markdown files

_All ORACLE2 (Meulmeester et al. TLRM 2025) data cleaning and analyses can also be found as R Markdown step-by-step files under:_
1. ORACLE2 Markdown_pt1_data_cleaning_Meulmeester: data cleaning and screening
2. ORACLE2 Markdown_pt2_inclusion_criteria_flowchart_Meulmeester: subset of the original dataset according to the inclusion criteria and an example of a flowchart
3. ORACLE2 Markdown_pt3_missing_value_patterns_Meulmeester: Figure S1-S4 for patterns of missing values
4. ORACLE2 Markdown_pt4_baseline_characteristics_Meulmeester: Table 2 with baseline characteristics
5. ORACLE2 Markdown_pt5_truncation_imputation_Meulmeester: Truncation of the dataset to 99th percentile and single imputation of vars Age, BMI and Pack years
6. ORACLE2 Markdown_pt6_multiple_imputation_mice_Meulmeester: Multiple imputation by chained equations (mice) of the missing values in the ORACLE2 dataset
7. ORACLE2 Markdown_pt7_cstat_membership_model_Meulmeester: Table S7 with Membership model and discriminative ability (c-statistic) per study
8. ORACLE2 Markdown_pt8_negative_binomial_regression_Meulmeester: Negative binomial regression models and R squared used for TLRM 2025 manuscript (univariable/multivariable)
9. ORACLE2 Markdown_pt9_forest_plots_Meulmeester: Figure 2, S9 and S10 (Forest plots)
10. ORACLE2 Markdown_pt10_spline_curves_density_plots_Meulmeester: Figure 3(A-D) and S16B (Spline curves and density plots)

## Contact

Fleur L. Meulmeester | PhD candidate Biomedical Data Sciences, Leiden University Medical Center (The Netherlands) | f.l.meulmeester@lumc.nl
