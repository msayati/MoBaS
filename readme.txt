This is the source code and jar file for Modularity Based Scoring Method. You can find the article and detail of algorithm at http://link.springer.com/article/10.1186%2Fs13637-015-0025-6

//*************************

MoBaS.jar : You can double click on it to run MoBaS if you do not want to compile the code. 

src: source code of MoBaS

MappingSNPtoGene: If you do not have mapping for snps to gene, you can use the jar file in that folder.

SampleData: It contains the instruction to run MoBaS on sample data including the following:
	permutedPPI: contains 100 PPI permutation such that the degree of each node preserved. 
	permutedGenotype: contains association of SNP to phenotype while permuted label of samples in GWAS data. 
	snp_gene_mapping: sample for the mapping between SNP and Genes
	OriginalSNP.assoc: a sample association of SNPs without any permutation
	ppi: is HPRD PPI that you can use for your analysis.
	
	

//**************************

If you have any question, please contact me at marzieh@case.edu

Thanks for using MoBaS. :-)