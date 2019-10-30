# [Compare Gene Variants View](http://vizome.org/aml/compare_genes/)

## ![compare](img/compare.png)

### Data
This view allows you to compare a set of genes selected via DNA variants found in either individual samples or groups of samples.

Global filters affect this view. Any sample-based filters set [here](http://vizome.org/aml/) and/or variant filters set [here](http://vizome.org/aml/variant_filter/) determine what genes appear in this view. If no global filters are set, all are shown.

### Visuals
If genes are selected via individual samples, they appear in a grid of color-coded cells with genes as rows and samples as columns. Light blue cells indicate that only one sample has a variant in that gene; red cells indicate more than one sample has a variant in that gene.

If genes are selected via groups of samples, they appear as color-coded segments of a circle. The three segments represent genes carrying mutations only in the first group, those with mutations only in the second group, and those with mutations in both groups.

If a segment is clicked, a new plot appears below, showing genes in that segment plotted with (number of samples with a variant in gene) / (total samples) on the y-axis. A detail of this plot appears if you click and drag over a subset.

### User interactions
To compare individual samples, select sample ids via the drop-down menu. In the resulting grid plot, gene names can be clicked for a list of options, and individual cells can be clicked to view information about variants found in that gene.

If a global filter of two sample groups is set, a circular plot will appear. Clicking a segment of it will generate a new plot of frequencies below. Click and drag to select a subset of that plot to view more information.