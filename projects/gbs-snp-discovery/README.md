# GBS SNP Discovery and Variant Analysis

**Status:** planned / in-progress / completed (select one)

## Research question
[Describe the crop, population, biological question and intended use of the variants.]

## Workflow outline
1. Sample metadata and read-file validation
2. Raw-read quality assessment
3. Adapter and quality trimming
4. Reference genome and annotation preparation
5. Read alignment
6. Sorting, indexing and alignment QC
7. Variant calling and filtering
8. Sample/variant QC and population-level checks
9. Annotation and downstream analysis
10. Reproducible reporting

## Project structure
```text
gbs-snp-discovery/
├── README.md
├── config/
├── metadata/
├── scripts/
├── workflow/
├── results/          # keep large/generated outputs out of Git
├── docs/
└── environment/
```

## Reproducibility
Record reference genome assembly/version, sample manifest, software versions, parameters and command logs. Do not upload restricted raw reads or unpublished sample metadata.

## Outputs
[Add QC summaries, filtered variant statistics, plots and downstream-ready files.]

## Limitations and citations
[Document mapping/reference bias, missing data, filtering choices and relevant methods.]
