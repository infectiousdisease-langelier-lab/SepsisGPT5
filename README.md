
# Sepsis GPT-5.2 classifier

## Folder code/

### GPT-5.2 API calls

Sepsis GPT-5.2 score: [20260319_versa_api.ipynb](code/20260319_versa_api.ipynb).

Mortality GPT-5.2 score: [20260407_versa_api_mortality.ipynb](code/20260407_versa_api_mortality.ipynb)

### Figures

Figure 2: produced by [20260529_ai_classifier.Rmd](code/20260529_ai_classifier.Rmd).
- A, C: gpt52_gene_sepsis_roc_derivation.svg.
- B, D: gpt52_gene_sepsis_roc_validation.svg.
- E, F: integrated_sepsis_confusion_matrix_validation.svg.

Figure 3: produced by [20260529c_ai_classifier.Rmd](code/20260529c_ai_classifier.Rmd).
- A, C: gpt52_protein_mortality_roc_derivation.svg.
- B, D: gpt52_protein_mortality_roc_validation.svg.
- E, F: integrated_mortality_confusion_matrix_validation.svg.

Figure 4: produced by [20260529b_ai_classifier.Rmd](code/20260529b_ai_classifier.Rmd).
- A, C: gpt52_clinical_mortality_roc_derivation.svg.
- B, D: gpt52_clinical_mortality_roc_validation.svg.

Supp Figure 1:
- A, B: gpt52_sepsis_confusion_matrix.svg, produced by [20260529_ai_classifier.Rmd](code/20260529_ai_classifier.Rmd).
- C, D: gpt52_mortality_confusion_matrix.svg, produced by [20260529c_ai_classifier.Rmd](code/20260529c_ai_classifier.Rmd).

Supp Figure 2:
- A-F: original_sepsis_sepsis.svg, produced by [20260529_ai_classifier.Rmd](code/20260529_ai_classifier.Rmd)
- G-K: original_sepsis_mortality.svg, produced by [20260529c_ai_classifier.Rmd](code/20260529c_ai_classifier.Rmd)

## Folder input/

- `metadata_derivationcohort.csv`: derivation-cohort metadata and precomputed GPT-5.2 scores; used by all three analysis notebooks.
- `metadata_validationcohort.csv`: validation-cohort metadata and precomputed GPT-5.2 scores; used by all three analysis notebooks.
- `earli_counts_kallisto_derivation.csv`: derivation-cohort gene counts; used by [20260529_ai_classifier.Rmd](code/20260529_ai_classifier.Rmd).
- `earli_counts_kallisto_validation.csv`: validation-cohort gene counts; used by [20260529_ai_classifier.Rmd](code/20260529_ai_classifier.Rmd).
- `20260429_derivation_validation_il6_il8.csv`: IL-6 and IL-8 protein measurements; used by [20260529c_ai_classifier.Rmd](code/20260529c_ai_classifier.Rmd).
