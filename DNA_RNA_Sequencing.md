# Next Generation Sequencing tools (RNA/DNA sequening)
Collection of tools for next generation sequencing (NGS) analysis of whole genome/exome/transcriptome data (not comprehensive)

#

**General tools/recommendations**

	Unix
	Perl/Python/bash scripting
	R for statistical analysis

**Quality control**

	FastQC	http://www.bioinformatics.babraham.ac.uk/projects/fastqc/

**Read extraction**

	Bazam https://github.com/ssadedin/bazam

**Read trimming (and adaptor removal)**

	Trimmomatic	http://www.usadellab.org/cms/?page=trimmomatic
	ConDeTri	https://github.com/linneas/condetri
	FASTX-Toolkit	http://hannonlab.cshl.edu/fastx_toolkit/
	cutadapt	https://github.com/marcelm/cutadapt
	BBDuk		https://sourceforge.net/projects/bbmap/

**Error correction**

	Quake   http://www.cbcb.umd.edu/software/quake/
	Echo    http://uc-echo.sourceforge.net/
	BBNorm	https://sourceforge.net/projects/bbmap/

**Short read aligner**

	bwa		https://github.com/lh3/bwa
	bowtie		http://bowtie-bio.sourceforge.net/index.shtml
	BBMap		https://sourceforge.net/projects/bbmap/
	Stampy		http://www.well.ox.ac.uk/project-stampy
	segemehl	http://www.bioinf.uni-leipzig.de/Software/segemehl/
	
**RNA-seq aligner**

	HISAT2	http://ccb.jhu.edu/software/hisat2/index.shtml
	STAR	https://github.com/alexdobin/STAR
	Tophat2	http://ccb.jhu.edu/software/tophat/index.shtml
	
**Pseudo-aligner for RNA-seq**

	kallisto	https://pachterlab.github.io/kallisto/
	Salmon		https://combine-lab.github.io/salmon/
	Sailfish	http://www.cs.cmu.edu/~ckingsf/software/sailfish/
    
**Variant calling**
    
	GATK		https://github.com/broadinstitute/gatk/releases
	VarScan2	http://dkoboldt.github.io/varscan/
	Samtools	http://www.htslib.org/
	FreeBayes	https://github.com/ekg/freebayes
	VarDict		https://github.com/AstraZeneca-NGS/VarDict
 
**Variant annotation**

	ANNOVAR		https://github.com/WGLab/doc-ANNOVAR/
	Oncotator	http://portals.broadinstitute.org/oncotator/
	SNPeff		http://snpeff.sourceforge.net/index.html
	VAT		http://vat.gersteinlab.org/
	VeP		http://www.ensembl.org/info/docs/tools/vep/index.html
	CADD		http://cadd.gs.washington.edu/
	Condel		http://bg.upf.edu/fannsdb/query/condel
	CGI		https://www.cancergenomeinterpreter.org/home

**Manipulating files (sam/bam/vcf/gff/gtf/...)**
    
	Picard tools	http://broadinstitute.github.io/picard/
	Samtools	http://www.htslib.org/
	BCFtools	http://www.htslib.org/
	bedtools	http://bedtools.readthedocs.io/en/latest/
	BamTools	https://github.com/pezmaster31/bamtools
	bam-readcount	https://github.com/genome/bam-readcount
	BBTools		http://jgi.doe.gov/data-and-tools/bbtools/

**Fusion genes**

	JAFFA		https://github.com/Oshlack/JAFFA
	DeFuse		http://compbio.bccrc.ca/software/defuse/
	EricScript	https://sites.google.com/site/bioericscript/
	pizzly		https://github.com/pmelsted/pizzly

**Quantitative analysis/Differential expression**

	sleuth	http://pachterlab.github.io/sleuth/
	limma	http://bioconductor.org/packages/release/bioc/html/limma.html
	DESeq2	http://bioconductor.org/packages/release/bioc/html/DESeq2.html
	edgeR	http://www.bioconductor.org/packages/release/bioc/html/edgeR.html
	
**Gene set enrichment analysis**

	MSigDB		https://www.gsea-msigdb.org/gsea/msigdb/index.jsp
	R::MSigDB	https://github.com/oganm/MSigDB
	Mouse v5.2	https://github.com/stephenturner/msigdf
	Mouse v7	https://github.com/ToledoEM/msigdf

**Visualisation**

	IGV	http://software.broadinstitute.org/software/igv/
	IGB	http://bioviz.org/igb/
	UCSC Genome browser
	
**Genome builds**

	hg38/GRCh38		Dec 2013
	hg19/GRCh37		Feb 2009
	hg18/NCBI Build 36.1	Mar 2006
	hg17/NCBI Build 35	May 2004
	hg16/NCBI Build 34	Jul 2003
	
	mm10/GRCh38		Dec 2011
	mm9/NCBI Build 37	Jul 2007
	mm8/NCBI Build 36	Feb 2006
	mm7/NCBI Build 35	Aug 2005
	
