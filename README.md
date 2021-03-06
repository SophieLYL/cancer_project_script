# cancer project script

last modified: July. 18 2020

`CESanal_prepare.R`: data preparation (using `cancereffectsizeR` package)

`mutrate_scatter.R`: scatter plot for mutation rate comparison between different tumor sizes/stages

`selection_intensity_plot.R`: bar plot of selection intensity of genes/variants (highlight genes with multiple variants)

`common_var.R`: extract common/similar variants between different tumor sizes/stages

`dendro_heatmap_base.R`: generate heatmap with dendrogram for tumor and signatures

`trinuc_YL.R`: heatmap for upstream & downstream trinucleotide mutation weights

`summary_gene_info.R`: summarise information of genes with multiple variants (output table with columns: `gene`, `#variant`, `mean SI`, `sd`, `TopVariant`, `format`) 

`scatter_linear.R`: linear-scatter plot of gene mutation rate by stages/sizes (highlight genes of interest)

`si_box.R`: box plot for gene selection intensity by stages/sizes

`epistasis_plot.R`: epistasis plot for individual pair of genes
