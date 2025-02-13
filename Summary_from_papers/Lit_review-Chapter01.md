## The following contains summary points from the selected 25 papers on Chapter 01 sysematic review
- AOB: Important AI tools for literature reviewing 
  01. Paper digest 
  02. Elicit.org 
  03. Litmaps
  04. Connected Papers 
  05. Research rabbits 
  06. Lateral.io 
 
## The title is on, "A Review on Genotyping for Model organisms" 

### 01. Summary points from a paper titled; "Overview of Genotyping Technologies and Methods" by Kockum et al. 
### Link/DOI: https://doi.org/10.1002/cpz1.727

#### Key points; 
- Commonly used genotyping methods (Taqman genotyping, Pyrosequencing, Microarray genotyping, NGS). 
- Criteria to select models organisms (mice, rats, flies, fish, worms, etc) consider consider similarities in genetics, anatomy, and physiology of the disease related factors. 
- The choice of a genotyping method depends on factors such as the number of genetic markers, precision needed, sample size, data processing capabilities, and budget.
- NGS based genotyping method has advantage over the other methods due to the ability to identify novel polymorphisms/mutations

#### Bonus concepts from the paper 
- Read on the `Concepts in genetic inheritance` & `Medical genetics` on pg 5  
- Read on the `Analysis and intepretation of genetic findings` on pg 14


### 02. Summary points from a paper titled, "Recommendations for Choosing the Genotyping Method and Best Practices for Quality Control in Crop Genome-Wide Association Studies" 
### Link/DOI: https://doi.org/10.3389/fgene.2020.00447

#### Key points: 
- WGR (Whole Genome Resequencing), RRS (Reduced Representation Sequencing), and SNP arrays identify SNPs for crop GWAS using sequencing or allele-specific probes, respectively. 
- SNP filtering by call rate ensures genotype accuracy, with thresholds typically ≥95–99%, but lower for low-depth NGS.
- Rare SNP variants are often excluded to avoid genotyping errors and low power, using MAF ≥1–5% or MAC ≥5–10 for reliable GWAS results.
- High individual missing data rates suggest poor DNA quality, so SNP filtering should precede individual filtering to minimize bias, especially in binary trait studies.

### 03 Summary points from a paper titled, "A Cost-effective, High-throughput, Highly Accurate Genotyping Method for Outbred Populations"
### Link/DOI:https://doi.org/10.1186/s13059-019-1720-5

### Key points; 
- SNP arrays often perform poorly in diverse populations, requiring costly population-specific designs, especially in structured model organisms.
- NGS sequencing with high depth coverage to make direct calls is expensive. 
- Pairing low coverage NGS (GBS/WGS) with imputation from reference panels provide a more economic solution 
- This was applicable on HS rats models 

### 04 Summary points from a paper title, "A joint use of pooling and imputation for genotyping SNPs" 
### Link/DOI:https://doi.org/10.1186/s12859-022-04974-7

### Key points; 
- Pooling can be combined with imputation methods to achieve high-density SNP genotyping while reducing the number of microarrays required. 
- Pooling alters allelic and genotypic distributions, introducing a unique structure that requires specialized processing for optimal imputation performance. 
- Simulations on human data show that coalescence-based imputation improves accuracy, and Prophaser was developed as an implementation for pooled genotype data.
- Future research should address genotyping errors in probabilistic decoding, as errors in SNP calling could impact haplotype reconstruction and overall imputation accuracy.

### 05 Summary points from a paper title, "Development of high-resolution multiple-SNP arrays for genetic analyses and molecular breeding through genotyping by target sequencing and liquid chip" 
### Link/DOI:https://doi.org/10.1016/j.xplc.2021.100230

### Key points; 
- mSNPs can be developed for various organisms, including plants, animals, and microorganisms, even in species with polyploid genomes or low genetic diversity
- mSNP arrays avoid repetitive sequences, do not require a perfect reference genome, and allow adjustable marker numbers to fit different research needs.
- The mSNP approach allows customizable and upgradable marker panels, unlike fixed chip-based platforms
- Unlike traditional GBS, the GBTS-based mSNP approach is free from patent restrictions, making it widely accessible for research and commercial applications
- The improved mSNP and GBTS system significantly reduces genotyping costs by at least half compared to chip-based platforms making it affordable for breeding programs, especially in developing countries

### 06 Summary points from a paper title, "A new mouse SNP genotyping assay for speed congenics: combining flexibility, affordability, and power" 
### Link/DOI:https://doi.org/10.1186/s12864-021-07698-9

### Key points; 
- This study introduces a cost-effective and flexible SNP genotyping assay using high-throughput sequencing for speed congenics in mice, an approach applicable to other model organisms.
- The assay surveys 1640 genome-wide SNPs, providing a high density of diagnostic markers for differentiating various mouse strains and substrains, which can accelerate the creation of congenic lines.
- A custom bioinformatic pipeline was developed to analyze the sequencing data, enabling SNP genotyping and calculation of the percentage of alleles matching the backcross recipient strain.
- The method's flexibility allows for adaptation to different strain combinations and integration of additional SNPs, making it a valuable tool for QTL mapping, ancestry analysis, and other genetic studies in model organisms

### 07 Summary points from a paper title, "Development of a next generation SNP genotyping array for wheat" 
### Link/DOI:https://doi.org/10.1111/pbi.14341

### Key points;
- This paper describes the development of the 'Triticum aestivum Next Generation' (TaNG) Axiom SNP array, a high-throughput genotyping tool for hexaploid wheat, a major crop model.
- The TaNG array leverages recent advances in wheat sequencing to provide improved genome-wide coverage and capture a greater range of genetic diversity compared to previous arrays.
- The array contains 43,372 SNPs selected using a novel haplotype optimization approach, resulting in a more even distribution of markers across the wheat genome.
- The TaNG array demonstrates improved performance for GWAS and CNV analysis, making it a valuable tool for genetic studies and breeding programs in wheat and potentially other complex plant genomes.

### 08 Summary points from a paper title, "Effects of spaced k-mers on alignment-free genotyping" 
### Link/DOI:https://doi.org/10.1093/bioinformatics/btad202

### Key points;
- This paper introduces MaskedPanGenie, an improved alignment-free genotyping tool that incorporates spaced k-mers to enhance sensitivity, particularly in low-coverage data.
- MaskedPanGenie builds on the existing PanGenie software, which leverages pangenome graphs and linkage disequilibrium to genotype variants rapidly and with reduced reference bias.
- The addition of spaced k-mers allows for more robust genotyping by accounting for sequencing errors and mutations, increasing the proportion of correctly mapped k-mers to variant alleles.
- The study demonstrates that spaced k-mers significantly improve sensitivity and F-score for genotyping SNPs, indels, and structural variants compared to contiguous k-mers, especially in challenging datasets.

### 09 Summary points from a paper title, "Development and Applications of a High Throughput Genotyping Tool for Polyploid Crops: Single Nucleotide Polymorphism (SNP) Array" 
### Link/DOI:https://doi.org/10.3389/fpls.2018.00104

### Key points;
- SNP arrays are a high-throughput and cost-efficient genotyping approach, but their application in polyploid crops lags behind diploid species due to the complexity of polyploid genomes.
- Next-generation sequencing (NGS) technologies, particularly genotyping-by-sequencing (GBS), have become valuable for SNP discovery and genotyping in polyploids, but require higher read depths than in diploids.
- Distinguishing between homologous, homoeologous, and paralogous SNPs in allopolyploids remains a significant challenge due to high sequence similarity between subgenomes.
- The review provides an overview of SNP array development and applications in polyploid crops, discussing SNP selection criteria, available arrays, genotype calling software, and future perspectives.