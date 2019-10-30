# [Mosaic View](http://vizome.org/aml/mosaic/)

## ![mosaic](img/mosaic.png)

### Data
This view displays data related to samples, including clinical and variant, and fusion data (if applicable). It is limited to samples with sequenced DNA.

Global filters affect this view. Any sample-based filters set [here](http://vizome.org/aml/) and/or variant filters set [here](http://vizome.org/aml/variant_filter/) determine what samples, variants, and/or fusions appear in this view.

### Visuals
Data appear color-coded in tabular sections, with samples as columns and variants, fusions, or clinical categories (or single values) as rows. Sections are separated by horizontal black lines.

For clinical data, if an entire category is added to the plot (such as "SpecimenType"), cells will be color-coded according to each sample's attributes, with a color legend appearing below. If one value for a clinical data category is added (such as "Bone Marrow Aspirate"), cells will appear blue if a sample has that attribute.

Presence of DNA variants in a gene are indicated in blue, and presence of fusions in a gene are indicated in magenta.

### User interactions
#### Creating sections
Drag a clinical data category to the container at right to add it to a section of the mosaic plot. You may also expand categories by clicking on the "+", which will then allow you to drag over single values.

Add genes via the drop-down menu or by entering a list of gene names separated by commas or line breaks. Once the genes have been added to the container at right, you may click on them to focus on specific variants within that gene. Enter an amino acid change (e.g., F433S) or more than one, separated by commas, and click "Convert" to change the row from a gene row into a variant row.

Add fusion data rows in the same manner, after switching to that tab. Once the genes have been added to the container at right, you may click on them to focus on a specific fusion. Otherwise, any fusions involving that gene will be shown.

When you have chosen the data that you want to see in a section, enter a name for the section, if desired, and click "Submit."

For gene and variant data rows, you may toggle between "Variant count" and "Max allele frequency" views, in addition to the default "Presence/absence" view.

#### Sorting
By default, rows will be added with "Stair-step" sorting, meaning that rows with the highest number of "present" values will be moved to the top, and columns will be sorted such that all as-yet-unsorted samples with "present" values are moved to the left within each row.

You may choose to display rows in the order they were added, instead of stair-stepping, if desired. There are toggle buttons for this at the top of the section-creation container at the right.

You may also change the column sort order at any time by clicking on the "Define sample order" button, and dragging elements to the right in the window that opens, in the order you want them to be sorted. Note: this only changes the sorting of columns, not rows. And it affects all columns, in all sections, so will override any stair-stepping or other previous sorting.