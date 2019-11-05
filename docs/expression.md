# [Expression Stratification View](http://vizome.org/aml/expression_strat/)

## ![expression](img/expression.png)

### Data
This view displays RNA-Seq expression for a given gene and various sample attributes.

The presence of DNA variants in the genes can be indicated in this view.

Mutations (rolled up to genes) can be compared between highest and lowest expression samples for the given gene.

Global filters affect this view. Any sample-based filters set [here](http://vizome.org/aml/) and/or variant filters set [here](http://vizome.org/aml/variant_filter/) determine what samples and variants appear in this view.

### Visuals
A small gray summary plot showing expression values for all samples for the selected gene appears at top left. Within that plot, any sample that also has a variant in the selected gene is outlined in black.

In the large plot to the right, the same expression data is plotted with the selected sample attribute, with a dotted median line for each group if the selected attribute is categorical.

Variants in the large plot are indicated as red circles with orange outlines (when an additional gene has been selected).

Any samples that have RNAseq but low to no expression for the selected gene appear as light green circles within the gray rectangle at the bottom of the large plot. Samples without RNAseq appear as gray circles in that area, but only when variants are being displayed.

In the "Compare groups" section, groups of genes are shown as color-coded segments of a circle. The three segments represent genes carrying mutations only in the highest-expression samples, those with mutations only in the lowest-expression samples, and those with mutations in both groups.

### User interactions
Select a gene via the drop-down menu at top left to view expression data for it.

Select a sample attribute from the drop-down menu at top middle to stratify samples accordingly.

Select a gene from the drop-down menu at top right to show which samples have variants in it. If any are found they will appear in the plot, and clicking the green arrow button will export them as a CSV.

For long sample attribute labels that have been truncated, mousing over them will reveal the full text of the label.

Below the large plot, to compare highest and lowest-expression samples, adjust the percentage (if desired), and click "Submit."

Each of the three result sets can be opened as a custom gene set by clicking on the "Create gene set" icon: ![expression_geneset_button](img/expression_geneset_button.png). They can also be exported via the green arrow buttons.
