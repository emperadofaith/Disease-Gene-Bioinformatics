
# Exploring a Human Disease Gene Using UCSC Genome Browser and NCBI ClinVar

Name: Emperado, Faith Denielle

Assigned Gene: BRCA2 

Associated Disease: Hereditary breast ovarian cancer (HBOC)

## Assigned Gene and Disease

**Gene:** BRCA2 (BRCA2 DNA Repair Associated)

BRCA2 is a tumor suppressor gene located on chromosome 13q13.1. It encodes a protein involved in repairing DNA double-strand breaks through homologous recombination, helping maintain genomic stability and prevent the accumulation of harmful mutations.

**Associated Disease:** Hereditary Breast and Ovarian Cancer (HBOC) Syndrome

HBOC is an inherited cancer predisposition syndrome commonly associated with pathogenic variants in the BRCA1 and BRCA2 genes. Pathogenic BRCA2 variants can impair DNA repair, increasing the risk of breast, ovarian, prostate, pancreatic, and certain other cancers. HBOC follows an autosomal dominant inheritance pattern, meaning that inheriting one pathogenic variant can increase cancer susceptibility, although not every carrier develops cancer.

# Part B #

## USCS Gene Location

**Genome assembly:** GRCh38/hg38

**Gene:** BRCA2

**Chromosome:** 13

**Coordinates:** chr13:32,315,077–32,400,268

**Strand:** Positive (+)

**Approximate gene length:** 85,192 bp

**Screenshot 1. UCSC Gene Location**
<img width="1000" height="538" alt="image" src="https://github.com/user-attachments/assets/f44d1b69-55ee-457d-ba61-89498c9e7db5" />

# Part C. #

## Exons, Introns, and Transcripts

The selected BRCA2 transcript, ENST00000380152.8, contains 27 exons based on the GENCODE V50 annotation track. Multiple transcript models were visible, indicating the presence of alternative transcripts or isoforms.

Exons are regions retained in mature RNA after splicing, whereas introns are intervening sequences removed during RNA processing. In the displayed BRCA2 gene structure, introns generally appear longer than exons because the connecting regions occupy more genomic space than the exon blocks.

**Screenshot 2. BRCA2 Gene Structure**

<img width="1000" height="538" alt="image" src="https://github.com/user-attachments/assets/f9499a47-4fb5-4f5a-b6c1-a7b49e424b94" />

# Part D. #

## Genome Browser Annotation Tracks

The GENCODE V50 and NCBI RefSeq tracks were used to examine the BRCA2 gene. The ClinVar Variants track displayed numerous reported variants across the genomic region, representing different clinical interpretations.

The 100 Vertebrates Basewise Conservation by PhyloP track showed varying levels of evolutionary conservation. Some regions displayed stronger conservation signals, while others showed weaker signals. Highly conserved regions may indicate biological importance because their sequences have been maintained across different species, suggesting that they may contribute to important biological functions.

**Screenshot 3. Examined Genome Browser Tracks**
<img width="1498" height="707" alt="image" src="https://github.com/user-attachments/assets/dc35e164-ea9a-4d82-924d-2bff176271a7" />

# Part E. #

## ClinVar Variant Analysis

| Attribute | Result |
|---|---|
| Gene | BRCA2 |
| Variant | NC_000013.11:g.32315358_32316294del |
| Variant type | Deletion |
| ClinVar Variation ID | 873424 |
| ClinVar accession | VCV000873424.2 |
| dbSNP ID | rs2072242904 |
| Chromosome | 13 |
| Cytogenetic location | 13q13.1 |
| Genome assembly | GRCh38 |
| Genomic location | chr13:32,315,356–32,316,292 |
| Deletion length | 937 bp |
| Associated condition | Breast-ovarian cancer, familial susceptibility, type 2 |
| Clinical significance | Pathogenic |
| Review status | Single-submitter classification |
| Submitter | King Laboratory, University of Washington |
| Submission accession | SCV001251365.1 |
| Last evaluated | September 1, 2019 |
| First submitted | June 7, 2020 |
| ClinVar record | [VCV000873424.2](https://www.ncbi.nlm.nih.gov/clinvar/variation/873424/) |

### ClinGen Gene Dosage Sensitivity

| Assessment | Evidence |
|---|---|
| Haploinsufficiency (HI) | Sufficient evidence for dosage pathogenicity |
| Triplosensitivity (TS) | No evidence available |

**Screenshot 4. Chosen NCBI Variant**
<img width="1182" height="988" alt="image" src="https://github.com/user-attachments/assets/de42db5a-c020-4f09-81b5-299595e7ba1a" />

# Part F. #

## Locating the Selected Variant in UCSC

### a. Where is the variant located relative to your gene?

The selected 937-bp deletion (NC_000013.11.32315358_32316294del) is located near the beginning of the BRCA2 gene on chromosome 13, within the GRCh38/hg38 assembly.

### b. Is it in an exon, intron, UTR, splice region, or another region?

The deletion appears to overlap both exonic and intronic regions of BRCA2, potentially affecting exon-intron boundaries involved in RNA splicing.

### c. Is it likely in a coding or non-coding region?

The deletion appears to affect protein-coding regions because it overlaps thick exon blocks in the GENCODE and RefSeq annotations. It also includes intervening intronic sequences.

### d. How might the variant affect the gene or gene product?

The deletion may disrupt BRCA2 coding sequences or RNA splicing, potentially producing an abnormal or nonfunctional BRCA2 protein. This could impair homologous recombination, a DNA repair mechanism essential for maintaining genomic stability.

### e. What additional evidence would be needed before concluding that the variant causes disease?

Transcript analysis, RNA-splicing studies, functional assays of BRCA2 DNA repair activity, and clinical or family segregation data would help confirm the deletion's molecular effects and disease association.

**Screenshot 5.**
<img width="1000" height="538" alt="image" src="https://github.com/user-attachments/assets/a5161088-fb2f-441f-af7e-0b6aee37ae66" />

<img width="1000" height="538" alt="image" src="https://github.com/user-attachments/assets/605a3266-fabd-4f10-9887-12a4243bda24" />

# Part G #

## Short Reflection
### 1. What did UCSC show you about your gene that was not obvious from simply reading about the gene's function?

The UCSC Genome Browser showed the exact genomic location and structure of BRCA2 on chromosome 13, including its exons, introns, and alternative transcripts. It also displayed clinically reported variants and conservation patterns, providing information about the gene's organization and potential biological importance beyond its role in DNA repair.

### 2. Why is knowing the exact genomic location of a disease-associated variant useful?

Knowing the exact genomic location helps determine whether a variant affects an exon, intron, splice region, or regulatory sequence. This information is important for predicting how the variant may alter gene expression, protein function, and disease susceptibility.

### 3. What is one limitation of predicting a variant's effect only from its genomic location?

Genomic location alone cannot confirm how a variant affects gene expression or protein function. Additional evidence, such as RNA analysis, functional experiments, and clinical studies, is needed to determine its actual biological and disease-related effects.

### 4. What was the most interesting feature you observed about your assigned gene?

The most interesting feature was the presence of numerous clinically reported BRCA2 variants with different classifications, including pathogenic, benign, and uncertain significance. The selected 937-bp deletion was particularly interesting because it overlaps annotated gene regions and is classified as pathogenic in ClinVar, highlighting how changes in BRCA2 may contribute to hereditary cancer susceptibility.

# Reference

### UCSC Assigned gene

https://genome-asia.ucsc.edu/cgi-bin/hgTracks?db=hg38&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chr13%3A32315508%2D32400268&hgsid=951505547_hZttnILgmI1b6RzG4nVmFavZtaGT

### NCBI Accesion

https://www.ncbi.nlm.nih.gov/clinvar/variation/873424/

### UCSC Variant genome

https://genome-asia.ucsc.edu/cgi-bin/hgTracks?db=hg38&lastVirtModeType=default&lastVirtModeExtraState=&virtModeType=default&virtMode=0&nonVirtPosition=&position=chr13%3A32315000%2D32317000&hgsid=951505341_dWJaKvqehsSF5q8TOJRyFmQArcsC


