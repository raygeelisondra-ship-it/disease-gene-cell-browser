# UCSC Cell Browser Disease Gene Lab Activity

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
  Non-hepatocytic cells (such as Liver Endothelial Cells, Kupffer cells, and immune cells like T cells and B cells).
* **d. Is the expression pattern broad or cell-type restricted?** 
  Cell-type restricted, as expression is heavily concentrated within the hepatocyte compartment rather than distributed broadly across all liver   cell.

## Marker Genes
* **a. Cluster/cell type examined:** Pericentral Hepatocyte
* **b. Marker gene 1:** CYP3A4
* **c. Marker gene 2:** CYP2E1
* **d. Marker gene 3:** ADH4
* **e. Does your assigned gene behave like a cell-type marker in this dataset? Explain briefly:** 
  No. Cell-type markers are highly restricted to define specific metabolic states or cellular identities. In contrast, LDLR is a functional receptor gene expressed broadly across multiple hepatocyte sub-populations because its role is to carry out a systemic physiological function (clearing cholesterol from the bloodstream) rather than serving as an identity label for a single unique cell cluster.

## PART H. Compare Your Assigned Gene With One Marker Gene
* **a. Assigned disease gene:** LDLR
* **b. Marker gene:** CYP3A4
* **c. Which gene shows a more cell-type-restricted expression pattern?** 
  CYP3A4 shows a more strictly restricted expression pattern, as it acts as a metabolic zonation marker specifically localized to pericentral hepatocytes.
* **d. Which gene appears more broadly expressed?** 
  LDLR appears more broadly expressed across multiple hepatocyte subpopulations (such as both pericentral and periportal hepatocytes) because its physiological role involves systemic clearance of LDL cholesterol across the functional liver tissue.
* **e. What does this comparison teach you about the difference between a disease-associated gene and a cell-type marker gene?** 
  It shows that cell-type or zone-specific markers often exhibit tightly confined expression profiles reflecting specialized metabolic states or distinct cellular identities. In contrast, disease-associated functional genes like LDLR can be active across broader cell compartments (the entire functional hepatocyte pool) to maintain core systemic homeostasis, meaning their disease pathology arises from functional disruption rather than unique cell-type restriction.
  

## PART I. Connect the Cell Browser Result to Your Previous Genome Activity
* **1. On which chromosome is your assigned gene located?** 
  Chromosome 19 (specifically band 19p13.2).
* **2. What disease-associated variant did you examine previously?** 
  Pathogenic missense or structural variants in the LDLR gene associated with familial hypercholesterolemia, which disrupt normal LDL receptor folding, transport, or ligand binding.
* **3. In the current Cell Browser dataset, which cell type(s) express the gene?** 
  Hepatocytes (parenchymal cells, spanning both pericentral and periportal populations).
* **4. Does the observed cell expression make biological sense based on what you already know about the gene's function or associated disease? Explain in 3-5 sentences.** 
  Yes, the expression pattern aligns perfectly with physiological expectations. The liver's primary parenchymal cells (hepatocytes) are responsible for clearing the vast majority of circulating low-density lipoproteins from the bloodstream. Because LDLR encodes the receptor responsible for this uptake, heavy expression in hepatocytes is essential for maintaining systemic cholesterol homeostasis. Mutations that impair LDLR function in these exact cells prevent proper clearance, leading to the severe hypercholesterolemia characteristic of the disease.
* **5. Can this single Cell Browser dataset prove that the gene causes the disease?**
  No, a single single-cell RNA sequencing dataset cannot prove causality on its own. While it demonstrates  where and to what extent* the gene is transcribed in healthy liver cells, proving disease causation requires combining genomic sequencing (identifying inherited variants), clinical association data (like ClinVar), and functional assays to show how specific mutations physically disrupt protein structure and receptor-mediated endocytosis.


## PART J. Short Reflection
* **1. What did the UCSC Cell Browser show you that the UCSC Genome Browser could not?** 
  The UCSC Cell Browser revealed single-cell resolution expression patterns across distinct, heterogeneous cell populations within the liver tissue, whereas the Genome Browser provides bulk genomic coordinates, exon-intron structures, and population-level variant annotations without single-cell lineage context.
* **2. Why can the same gene have different expression levels among different cell types?** 
  Different cell types activate distinct regulatory networks, transcription factors, and epigenetic landscapes based on their specialized metabolic tasks and physiological roles within the organ.
* **3. Why should you be careful when interpreting a gene that shows zero or very low expression in single-cell data?** 
  Single-cell RNA sequencing frequently suffers from "dropout" events—where lowly expressed transcripts fail to be captured or reverse-transcribed during library preparation—meaning true biological absence must be distinguished from technical artifact.
* **4. Why is it useful to combine information about genomic location, genetic variants, and cell-specific gene expression?** 
  Combining these layers bridges macro-level genetics with micro-level tissue physiology, allowing researchers to pinpoint exactly *where* a mutated gene acts and how a sequence variant disrupts function within the specific target cells responsible for a disease phenotype.
* **5. What was the most interesting observation you made about your assigned gene?** 
  Discovering that *LDLR* maintains broad functional expression across the entire hepatocyte compartment rather than acting as a restricted zonation marker, highlighting its systemic role in whole-body metabolic homeostasis.



  
