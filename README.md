# Code to support Lynall 2019 B cells and stress

## bcellstress01.Rmd

- Mindful student analysis - makes Figure 1A, 1B, 1C 

## bcellstress02.Rmd

- Process murine cytokine data

## bcellstress03.Rmd

- Percentage plots to complement absolute count plots: Figure 3C, S3C boxplots
- Process splenic count data.
- Makes:
  - Figure 2B (effects of stress on cell counts)
  - Figure 5B (effects of CD19 deficiency on cell counts)
  - Figure S9D (effects of stress on cell counts in CD19 deficient animals)

## bcellstress04.Rmd

- Effects of stress on B cell IL10 (ex vivo stimulation)
- Makes Figure 2D

## bcellstress05.Rmd

- Process meningeal count data:
- Makes:
  - Figure 3B, 3C
  - Figure 5D
  - Figure S9F

## bcellstress06.Rmd

- Extracts meningeal flow data from FlowJo workspaces and FCS files, QCs for automated clustering analysis, then saves.

## bcellstress07.Rmd

- Clusters meningeal flow cytomery data using flowSOM and ConsensusClusterPlus
- Downsamples data to produce tSNE
- Tests effects of strain and condition on median meningeal function marker expression (on automatically detected clusters) and plots this as tile plots
- Makes:
  - Figure 3A - automated clustering tSNE
  - Figure S4A - manual and automated subset comparison
  - Figure S13B - heatmap of marker expression for automated cluster detection
  - Figure S4B - automated counts volcano SD vs. HC
  - Figure 3F - effects of stress on flow marker expression
  - Figure 5E -  effects of Cd19-/- on flow marker expression

## bcellstress08a.Rmd

- Pre-processing of myeloid splenic flow cytometry data

## bcellstress08b.Rmd

- Pre-processing of lymphoid splenic flow cytometry data

## bcellstress09.Rmd

- Test effects of strain and condition on splenic median function marker expression and plots this as tile plots
- Makes Figure 2F and 5C

## bcellstress10.Rmd

- Debatch variables for the effect of cohort (for purposes of visualization and correlation plots) 
  - Box-Cox transform variables to make distribution more normal as necessary (not necessary for the rlog-transformed counts)
  - Debatch using limma
  - Inverse the Box-Cox transform. 

## bcellstress11.Rmd

- Statistics and plots for cytokine data
- Makes Figure S3B and S9A

## bcellstress12.Rmd

- Meningeal microarray data: stressed vs. homecage
- Makes:
  - Figure 3G (GSEA - top 10 results)
  - Figure S5A (full GSEA results) 
  - Figure 3D (subset of deconvolution results)
  - Figure S4C (full deconvolution results)
  - Figure 4A (cytokine heatmap)

## bcellstress13.Rmd

- Makes:
  - Figure S5: correlation plot of meningeal vs. splenic cell counts
  - Figure S3E: Correlations between splenic cell counts and behaviour in stressed group
  - Figure 3H: Correlation between behaviour and cell counts
  - Figure S9E, S9G and 5G: comparison of effects of stress in CD19 and WT mice

## bcellstress14.Rmd

- Statistical testing for effects of stress and strain on splenic and meningeal percentage marker expression
- Barplots for count data
- Makes figures:
  - Figure 2C (stress: effect on splenic B cells)
  - Figure 5A and Figure 5B inset (CD19 deficiency: effect on B cells and neutrophils) 
  - Figure 2E (Splenic B cell MHCII+, CD25+ and Cd69+ plots: effect of stress)
  - Figure 3E (Meningeal B cell CD69 and MHCII: effects of stress)
  - Figure S3D (splenic percentage marker positivity: stress effect)
  - Figure S3C (splenic counts: stress effect)
  - Figure S4D (meningeal percentage marker positivity: stress effect)
  - Figure S9B (splenic percentage marker positivity: strain effect)
  - Figure S9C (meningeal percentage marker positivity: strain effect)
  
## bcellstress15.Rmd

- WT vs. CD19 stressed mice: RNAseq data: alignment to transcriptome using Salmon

## bcellstress16.Rmd

- WT vs. CD19 stressed mice: RNAseq data: summarise transcript data to gene level

## bcellstress17.Rmd

- WT vs. CD19 stressed mice: RNAseq data: Generate counts table, do differential expression analysis, VST

## bcellstress18.Rmd

- WT vs. CD19 stressed mice: RNAseq data: GSEA
- Makes:
  - Figure 5H (top GSEA results)
  - Figure S10A (full GSEA results)
  - Figure S10B (leading edge - comparison of SD vs. HC and CD19 vs. WT for interferon pathways)

## bcellstress19.Rmd

- CD19-/- vs. WT behaviour
- Makes Figure 5F and S9H

# Single cell analysis

## bcellstress20.Rmd
- Single cell - read data and call cells

## bcellstress21.Rmd
- Single cell - doublet calling, normalization, identification of highly variable genes, mutual nearest neighbour batch correction

## bcellstress22.Rmd
- Single cell - cell cycle estimation

## bcellstress23.Rmd
- Single cell - Leiden clustering and marker identification

## bcellstress24.Rmd
- Makes Figure S7B (clustering UMAP)
- Single cell - cluster annotation

## bcellstress25.Rmd
- Makes Figure 4B (B cell cluster UMAP)
- Makes Figure S8E (Adam 2017 stress genes)
- Single cell - differential expression analysis

## bcellstress26.Rmd
- Further analysis and visualization of differential expression results
- Makes:
  - Figures 4C, 4D, 4E
  - Figures S8A, S8B, S8C, S8D

