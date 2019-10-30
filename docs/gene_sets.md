# [Gene Sets](http://vizome.org/aml/geneset/)

## ![genesets_main](img/genesets_main.png)

### Data
This view allows you to define a set of genes, or to select a pre-defined set, which you may then explore in a variety of ways.

Global filters do not affect this view, and this view does not set any global filters.

### User interactions
Add or remove genes from a set by typing in the large text box at top left, separating them with commas or line breaks. You may also add genes by selecting them from the drop-down menu (start typing to narrow the choices).

Give the set a name, if desired, in the small text box below. This name will appear in new windows opened from this page, however it is not saved in the system for future use.

Alternatively (or in addition), click on one of the pre-defined custom gene sets to load the genes in that set.

Once your gene set has been entered, choose an option to work with it.

These four buttons: ![genesets_freq_button](img/genesets_freq_button.jpg) ![genesets_pathways_button](img/genesets_pathways_button.jpg) ![genesets_chron_button](img/genesets_chron_button.jpg) ![genesets_network_button](img/genesets_network_button.jpg) open the gene set as a custom frequency view, an interactions/pathways view, a chronology set view, or a network/expression view, respectively. These buttons will open a new window when clicked.

Clicking the export buttons ![genesets_export_button](img/genesets_export_button.jpg) will prepare a CSV of the corresponding variants for all genes in the set.

## ![genesets_variantsview](img/genesets_variantsview.png) [Gene Set Variants View](http://vizome.org/aml/genes_variants/)

### Data
This view shows both the frequency and type of unique DNA variants within a given list of genes. Uniqueness is determined by the combination of chromosome, reference allele, alternative allele, start position, and end position.

It also displays gene frequencies, calculated as the number of samples with a variant in that gene divided by the total number of samples. The count of samples with a variant in that gene is taken after global filters have been applied.

If a global sample filter is active, it also displays group comparisons.

Global filters affect this view. Any sample-based filters set here and/or variant filters set here determine what variants appear in this view. If no global filters are set, all are shown.

### Visuals
Each unique DNA variant within the selected genes is plotted with cohort frequency on the y-axis and gene name on the x-axis. Variants are color-coded by type.

The number in parentheses after each gene name indicates the number of unique variants in the gene.

In the comparison plot, if applicable, each unique DNA variant is again color-coded by type and plotted with the gene name on the x-axis, but the y-axis represents the difference in group frequencies.

The bottom plot displays gene frequencies.

### User interactions
All variant types can be shown/hidden with the checkboxes at right.

Drag an area of the gene frequency plot to select a subset of genes and view more information about them, and/or export data from that selection.

Clicking on a gene name will bring up a set of options for that gene: View gene model, View interactions, View chronology, and go to GeneCards page.

Clicking the "Edit gene set" button ![genesets_editgeneset_button](img/genesets_editgeneset_button.png) will allow you to edit the gene list in a new window.

Clicking export buttons ![genesets_export_button](img/genesets_export_button.jpg) will prepare a CSV of the corresponding variants for all listed genes.