# Bioinformatics Assignment: LDLR Expression Analysis in the Human Liver Cell Atlas

## Assigned Gene and Disease
* **Assigned Gene:** Low-Density Lipoprotein Receptor (LDLR)
* **Associated Disease / Condition:** Familial Hypercholesterolemia. Mutations in the LDLR gene disrupt receptor-mediated endocytosis of low-density lipoproteins from the bloodstream, leading to severely elevated LDL-cholesterol levels, and increased risk of cardiovascular disease.


## Organ/Tissue Choice and Dataset Information
* **Organ / Tissue:** Human Liver 
* **Dataset Name:** Human Liver Cell Atlas 
* **Dataset Scale:** Explores hundreds of thousands of single cells ($>524,000$ cells loaded), capturing both parenchymal cells (hepatocytes) and diverse non-parenchymal populations (Kupffer cells, endothelial cells, cholangiocytes, and immune cells).

## Understanding the Cell Map
* **a. Type of visualization:** UMAP (Uniform Manifold Approximation and Projection). It is a non-linear dimensionality reduction technique used to project high-dimensional single-cell RNA sequencing data into a 2D space.
* **b. What does one dot represent?** A single cell specifically, the individual gene expression profile of one single cell.
* **c. What do the clusters represent in this particular dataset?** Distinct cell types, cell states, or subpopulations within the human liver (e.g., pericentral hepatocytes, periportal hepatocytes, liver sinusoidal endothelial cells, Kupffer cells, T cells, etc.). Cells that share similar overall transcriptomic / gene expression profiles are grouped closely together into clusters.
* **d. List at least three cell-type or cluster labels visible in the dataset.**
  1. Pericentral Hepatocyte
  2. Periportal Hepatocyte
  3. Kupffer Cells (or CD8 T Cells / Cholangiocytes)

## Assigned Gene Expression
* **a. Assigned gene symbol:** LDLR
* **b. Dataset used:** Human Liver Cell Atlas (All Cells)
* **c. Is expression widespread, restricted, or low/undetected?** 
  Restricted (concentrated specifically within the parenchymal/hepatocyte compartments rather than distributed uniformly across all cell lineages).
* **d. Which cluster(s) appear to contain cells with stronger expression?** 
  Hepatocyte clusters, specifically pericentral and periportal hepatocyte populations.
* **e. Which cluster(s) appear to contain little or no detectable expression?** 
  Non-hepatocytic and immune cell clusters (such as B cells, NK cells, T cells, and various endothelial/stromal populations).

## Expression plot
* **a. Cell type/cluster with the strongest visible expression:** 
  Hepatocytes (specifically pericentral and periportal hepatocyte populations).
* **b. Another cell type/cluster with detectable expression:** 
  Alternative hepatocyte sub-population sharing the primary functional cluster.
* **c. Cell type/cluster with relatively low or undetected expression:** 
  Non-hepatocytic cells (such as Liver Sinusoidal Endothelial Cells, Kupffer cells, and immune cells like T cells and B cells).
* **d. Is the expression pattern broad or cell-type restricted?** 
  Cell-type restricted, as expression is heavily concentrated within the hepatocyte compartment rather than distributed broadly across all liver   cell.

## Marker Genes
* **a. Cluster/cell type examined:** Pericentral Hepatocyte
* **b. Marker gene 1:** CYP3A4
* **c. Marker gene 2:** CYP2E1
* **d. Marker gene 3:** ADH4
* **e. Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly:** 
  No. Cell-type markers (such as CYP3A4 for pericentral zonation) are highly restricted to define specific metabolic states or cellular identities. In contrast, LDLR is a functional receptor gene expressed broadly across multiple hepatocyte sub-populations because its role is to carry out a systemic physiological function (clearing cholesterol from the bloodstream) rather than serving as an identity label for a single unique cell cluster.



  
