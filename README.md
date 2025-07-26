# Computational Practice: Functional Enrichment with Toppfun

## Lab Overview 
Sometimes, researchers find a gene associated with a phenotype.  More often, researchers find a set of genes that change between biological conditions using differential gene expression or other analysis.  It is genes (not gene) that control biological processes.  Once one has a set of genes,, one can see if there is a non-random enrichment of gene annotations using Function Enrichment Analysis.

## Lab Objectives
In this lab we will find a set of genes that are physically interacting with a seed gene using the gene interaction database, BioGrid.  If proteins are sticking together into complexes, they are likely performing similar biochemical tasks.

* Identify a set of genes interacting in a protein:protein interaction database.
* Perform functional enrichment with the TopFunn Tool
* Find Protein Interactors With DNA Polymerase.

Follow these lab instructions:

### Task A

#### Step 1
Go to the Biogrid database (https://thebiogrid.org/ ) and search for gene product interactions with human DNA polymerase gamma POLG.

#### Step 2
Download the interactors with POLG by clicking the ‘Download Curated Information for this protein’ button.
Use Excel or other tool to extract the  list of all the unique POLG nodes (use official gene symbols).  The ‘Remove Duplicates’ feature in Excel is very useful but do it any way you like.
#### Step 3
Paste these genes the ToppFun functional enrichment analysis tool: https://toppgene.cchmc.org/enrichment.jsp

#### Step 4
Click the ‘Download All’ button to get text file of all the enriched terms.  Load this into Excel or other tool and sort the list by the ‘q-value FDR B&Y’ significance value.  Use a q-value FDR B&Y q-value less than 1e-10 (aka 1 x 10^-10) as significant. Look at the enriched term ‘name’.  Do these sound like function enriched for POLG?

