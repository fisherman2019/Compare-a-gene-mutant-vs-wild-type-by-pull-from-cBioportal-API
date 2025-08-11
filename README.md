# Compare-a-gene-mutant-vs-wild-type-by-pull-from-cBioportal-API
The is an example r-markdown for pulling mRNA expression profile from glioma cancer for IDH1-R132H mutant, and compare with the expression profile of wild type.
Reference:https://waldronlab.io/cBioPortalData/reference/cBioPortal.html
The script include:

  1.finds a TCGA glioma study,
  
  2.locates the mutation profile and the mRNA expression profile,
  
  3.pulls mutation data to identify IDH1-R132H mutant samples,
  
  4.pulls expression (z-scores if available) for the samples,
  
  5.computes mean expression difference (mutant − wild-type),
  
  6.returns & plots the top 10 overexpressed genes.
