# Code to support Lynall 2019 B cells and stress

## bcellstress01.Rmd

- 

## bcellstress02.Rmd

- 

## bcellstress03.Rmd

- 

## bcellstress04.Rmd

- 

## bcellstress05.Rmd

- 

## bcellstress06.Rmd

- Extracts meningeal flow data from FlowJo workspaces and FCS files, QCs, then saves.

## bcellstress07.Rmd

- Clusters meningeal flow cytomery data using flowSOM and ConsensusClusterPlus
- Downsamples data to produce tSNE
- Tests effects of strain and condition on median meningeal function marker expression (on automatically detected clusters) and plots this as tile plots
- Makes:
  - Figure S3B
  - Figure S11B - ridges and heatmap for automated clusters
  - Figure 3A - automated clustering
  - Figure S3A
  - Figure 3F
  - Figure 5E

## bcellstress08a.Rmd

- Pre-processing of myeloid splenic flow cytometry data

## bcellstress08b.Rmd

- Pre-processing of lymphoid splenic flow cytometry data

## bcellstress09.Rmd

- Test effects of strain and condition on splenic median function marker expression and plots this as tile plots

## bcellstress10.Rmd

- Debatch variables for the effect of cohort (for purposes of visualization and correlation plots) 
  - Box-Cox transform variables to make distribution more normal as necessary (not necessary for the rlog-transformed counts)
  - Debatch using limma
  - Inverse the Box-Cox transform. 

## bcellstress11.Rmd

- Statistics and plots for cytokine data

## bcellstress12.Rmd

- Meningeal microarray data: stressed vs. homecage
- Makes figures 3G, S4A, 3D and 4A, S3C

## bcellstress13.Rmd

- Makes:
  - Figure S2E: Correlations between splenic cell counts and behaviour in stressed group
  - Figure 3H: Correlation between behaviour and cell counts
  - Figure S7E and S7G: comparison of effects of stress in CD19 and WT mice

## bcellstress14.Rmd

- Statistical testing for effects of stress and strain on splenic and meningeal percentage marker expression
- Barplots for count data
- Makes figures:
  - Fig 2C (stress: effect on splenic B cells)
  - Fig 5A (CD19 deficiency: effect on B cells)
  - Fig 2E (Splenic B cell MHCII+, CD25+ and Cd69+ plots: effect of stress)
  - Fig 3E (Meningeal B cell CD69 and MHCII: effects of stress)
  - Fig S2D (splenic percs: condition effect)
  - Fig S2C (splenic counts: condition effect)
  - Fig S3D (splenic percs: stress effect)
  - Fig S7B (splenic percs: strain effect)
  - Fig S7C (meningeal percs: strain effect)
  
## bcellstress15.Rmd

- WT vs. CD19 stressed mice: RNAseq data: alignment to transcriptome using Salmon

## bcellstress16.Rmd

- WT vs. CD19 stressed mice: RNAseq data: summarise transcript data to gene level

## bcellstress17.Rmd

- WT vs. CD19 stressed mice: RNAseq data: Generate counts table, do differential expression analysis, VST

## bcellstress18.Rmd

- WT vs. CD19 stressed mice: RNAseq data: GSEA
- Makes Figure 5G and Figure S8

## bcellstress19.Rmd

- CD19-/- vs. WT behaviour
- Makes Figure 5F and S7H
