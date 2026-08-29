---
layout: page
permalink: /software/
title: Software
description: R packages, Shiny applications and analysis tools developed in the lab.
nav: true
nav_order: 4
---

<!--
  MAINTAINER NOTE
  The "Repository" links below still point at personal accounts. As repos are
  transferred into github.com/PHI-Lab-UMD, update the URL here. GitHub redirects
  the old URLs automatically, so nothing breaks in the meantime -- but links that
  read PHI-Lab-UMD look considerably better on a lab page.

  Transfer status:
    [ ] adrd-moe-transfer-learning  -- gouravreddy02  (Gourav Velma, alum)
    [ ] fm-gpt                      -- tacanida       (Travis Canida, alum)
    [ ] mvBaSH                      -- tacanida       (Travis Canida, alum)
    [ ] CAR-NET                     -- kehongjie      (Hongjie Ke, alum)
    [ ] rPCor                       -- kehongjie      (Hongjie Ke, alum)
    [ ] BCMC                        -- kehongjie      (Hongjie Ke, alum)
    [ ] CoxTOTEM                    -- kehongjie      (Hongjie Ke, alum)
    [ ] rsfMRI_CBF                  -- kehongjie      (Hongjie Ke, alum)
    [ ] MEMM                        -- nwang123       (Neng Wang, alum)
    [ ] TIPS                        -- nwang123       (Neng Wang, alum)
    [ ] CQRM                        -- iamverywell    (account owner unidentified - ask before transferring)
    [-] CAMO                        -- CAMO-R org     (shared with Tseng group at Pitt; leave in place)
    [-] MetaOmics / MetaDE          -- metaOmics org  (shared with Tseng group at Pitt; leave in place)
    [!] BayesMetaSeq, CBM           -- currently Google Drive files only; consider moving to a repo
-->

## Precision health and risk prediction

**Deep Transfer Learning for Population-Specific ADRD Risk**
R Shiny app for estimating population-specific Alzheimer's disease and related dementia risk using a mixture-of-experts deep transfer learning framework.
[Repository](https://github.com/gouravreddy02/adrd-moe-transfer-learning)

## Genetics and multi-omics integration

**FM-GPT**
R package for fine-mapping of causal genes for phenome-wide transcriptome-wide association studies.
[Repository](https://github.com/tacanida/fm-gpt)

**TIPS**
R package for pathway-guided transcriptome-wide association studies.
[Repository](https://github.com/nwang123/TIPS)

**mvBaSH**
R package for multi-trait genetic fine mapping.
[Repository](https://github.com/tacanida/mvBaSH)

**MEMM**
R package implementing an estimation framework for high-dimensional multi-exposure to multi-mediator mediation analysis.
[Repository](https://github.com/nwang123/MEMM)

**CAR-NET**
R Shiny application with a graphical interface for constructing and analysing non-coding RNA regulatory networks from transcriptomic data and curated databases.
[Repository](https://github.com/kehongjie/CAR-NET)

**CQRM**
Composite quantile regression models for non-coding RNA differential expression analysis.
[Repository](https://github.com/iamverywell/CQRM)

## High-dimensional variable screening

**rPCor**
R package for fast and robust variable screening across a range of high-dimension to high-dimension omics integration problems.
[Repository](https://github.com/kehongjie/rPCor)

**RobustDC**
R package implementing robust distance correlation for variable screening.
[Repository](https://github.com/kehongjie/RobustDC)

**CoxTOTEM**
Two-stage variable selection procedure for detecting survival-associated biomarkers across multiple genomic studies.
[Repository](https://github.com/kehongjie/CoxTOTEM)

## Transcriptomic meta-analysis

**CAMO**
R package and Shiny application for congruence analysis and functional characterisation of differential transcriptomic systems across model organisms, with downstream tools for text mining, pathway clustering and topology.
[Repository](https://github.com/CAMO-R/Rpackage) · [Shiny app](https://github.com/CAMO-R/Rshiny) · [Manual](https://github.com/CAMO-R/other/blob/main/Rshiny_tutorial/CAMO_RShiny_Tutorial.pdf)

**MetaOmics**
R Shiny application for comprehensive transcriptomic meta-analysis across seven biological purposes.
[Repository](https://github.com/metaOmics/metaOmics) · [Tutorial](https://github.com/metaOmics/tutorial)

**MetaDE**
R package implementing twelve major meta-analysis methods for differential expression analysis. Part of MetaOmics.
[Repository](https://github.com/metaOmics/MetaDE) · [CRAN (archived)](https://cran.r-project.org/web/packages/MetaDE/index.html)

**BCMC**
R package for biomarker detection and categorisation across multiple transcriptomic studies, considering biological and statistical significance alongside concordance patterns.
[Repository](https://github.com/kehongjie/BCMC)

## Neuroimaging

**rsfMRI_CBF**
Code for predicting cerebral blood flow from voxel-wise resting-state functional MRI.
[Repository](https://github.com/kehongjie/rsfMRI_CBF)

## Bayesian meta-analysis (legacy)

These two packages are currently distributed as Google Drive downloads rather than repositories. Moving them into the lab organisation would make them installable with `devtools::install_github()` and citable via Zenodo.

**BayesMetaSeq**
R package combining multiple RNA-seq studies through a Bayesian hierarchical model for differential expression detection and biomarker categorisation.

**CBM (Cross-platform Bayesian Meta-analysis)**
R package combining RNA-seq and microarray studies through a Bayesian hierarchical model for differential expression detection.
