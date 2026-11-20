# Advanced Career Development Roadmap

## Goal
Progress from a plant genomics and molecular breeding profile towards a researcher who can independently design, analyse and communicate computational quantitative-genetics and AI-enabled crop-improvement studies.

## Five connected skill pillars

### 1. Quantitative and statistical genetics — essential
- Linear models, generalized linear models and mixed models
- Variance components, heritability and genetic correlations
- BLUP/BLUE, relationship matrices and pedigree/genomic models
- GWAS, population structure, kinship and multiple-testing control
- QTL mapping, linkage analysis and fine mapping
- Genotype × environment interaction and multi-environment trials

**Evidence to publish:** a reproducible analysis notebook with a documented dataset, model assumptions, diagnostics and interpretation.

### 2. Genomic selection and prediction — essential
- Genomic relationship matrices and marker QC
- GBLUP and rrBLUP
- Bayesian methods (BayesA/B/Cπ, Bayesian LASSO)
- Cross-validation strategies that avoid data leakage
- Prediction accuracy, bias and calibration
- Training population design and updating
- Multi-trait and multi-environment prediction

**Evidence to publish:** benchmark at least three prediction approaches using a public or simulated dataset and a transparent validation design.

### 3. Machine learning and AI — high priority
- Data preparation, missingness and feature engineering
- Regularized regression, random forest and gradient boosting
- Support vector machines and neural networks
- Model tuning, nested cross-validation and explainability
- Deep learning only where sample size and data structure justify it
- Compare ML methods with sound statistical-genetic baselines

**Evidence to publish:** a benchmark that compares ML models against GBLUP/rrBLUP, reports uncertainty and discusses biological interpretability.

### 4. Multi-omics, pangenomics and functional genomics — high priority
- RNA-seq and differential expression
- eQTL and expression-informed candidate prioritization
- Structural variation and presence/absence variation
- Crop pangenomes and graph-genome concepts
- Integration of genomic, transcriptomic, metabolomic and phenomic data
- Functional annotation and pathway analysis

**Evidence to publish:** a small, well-documented public-data integration case study.

### 5. Digital, speed and precision breeding — high priority
- High-throughput phenotyping and image analysis
- Environmental and weather data integration
- Crop growth and prediction models
- Speed breeding concepts and breeding-cycle optimization
- Marker-assisted backcrossing and gene editing concepts
- Decision support and breeding pipeline optimization

**Evidence to publish:** a documented case study or prototype linked to a clear breeding decision.

## Suggested 12-month sequence

| Period | Main focus | Portfolio deliverable |
|---|---|---|
| Months 1–2 | R/Python, Linux, Git, reproducibility, mixed models | Reproducible analysis repository |
| Months 3–4 | GWAS, QTL, population genetics | GWAS/QTL case study |
| Months 5–6 | Genomic prediction and validation | GBLUP/rrBLUP/Bayesian comparison |
| Months 7–8 | G×E and multi-environment prediction | Multi-environment modelling project |
| Months 9–10 | ML and explainable modelling | ML vs genomic prediction benchmark |
| Months 11–12 | Multi-omics/pangenomics or phenomics | Integrated public-data case study |

Adjust the pace to your work commitments. Depth, validation and reproducibility matter more than completing many shallow tutorials.

## Research questions with strong potential
- Can multi-environment genomic prediction improve selection across target environments?
- When do ML models outperform, or fail to outperform, established genomic prediction methods?
- Can genomic, phenomic and environmental data improve prediction of drought/heat tolerance?
- How can structural variation and pangenome resources improve allele discovery?
- Can explainable ML help prioritize useful markers or candidate genomic regions?
- How can prediction models be translated into practical parent and line selection?

## Definition of done for every portfolio project
1. Clear biological/breeding question.
2. Public, simulated or permission-cleared data.
3. Data dictionary and quality-control report.
4. Reproducible scripts/notebooks and software versions.
5. Appropriate baseline methods and validation.
6. Results with figures/tables and limitations.
7. README with commands to reproduce.
8. Citations and data/software licenses.
