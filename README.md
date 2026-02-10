# SCORPI "COMING SOON:::::"


<center> <img width="704" height="255" alt="SCORPI_Logo_image" src="https://github.com/user-attachments/assets/844a5445-231b-4a81-a2dd-9ebf5371dc32" /></center>

**SCORPI_GEL** is a Java-based tool for processing genomic data using VCF files or catalogue (SBS) files to predict HRD, APOBEC, and MMRD, with built-in support for downloading and indexing reference genomes such as hg38.

**Download and index reference genome FASTA files**
java -jar -Xmx4g SCORPI_GEL_v2.jar Download hg38 /home/sunny/Sunnyveerla/Projects/ReferenceGenome/

**Run SCORPI using a folder containing VCF files**
java -jar -Xmx4g SCORPI_GEL_v2.jar VCF /home/sunny/Sunnyveerla/Projects/ReferenceGenome/hg38/hg38.fa /home/sunny/Sunnyveerla/Projects/SCORPI_GEL/Test/test_new/ TRUE /home/sunny/Sunnyveerla/Projects/SCORPI_GEL/Test/

**Run SCORPI using a Catalogue (SBS) File**
java -jar -Xmx4g SCORPI_GEL_v2.jar SBS /home/sunny/Sunnyveerla/Projects/SCORPI_GEL/Test/rndm_2000snvs_r10_contextCountFile_complete_context.txt /home/sunny/Sunnyveerla/Projects/SCORPI_GEL/Test/
