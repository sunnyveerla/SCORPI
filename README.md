# SCORPI "COMING SOON:::::"


<center> <img width="704" height="255" alt="SCORPI_Logo_image" src="https://github.com/user-attachments/assets/844a5445-231b-4a81-a2dd-9ebf5371dc32" /></center>

**SCORPI_GEL** is a Java-based tool for processing genomic data using VCF files or catalogue (SBS) files to predict HRD, APOBEC, and MMRD, with built-in support for downloading and indexing reference genomes such as hg38. <br>

**Download and index reference genome FASTA files**<br>
java -jar -Xmx4g SCORPI_GEL_v2.jar **Download** <build> <path-to-download><br>

_Example_
>java -jar -Xmx4g SCORPI_GEL_v2.jar **Download** hg38 /home/sunny/Sunnyveerla/Projects/ReferenceGenome/<br>

**Run SCORPI using a folder containing VCF files**<br>
java -jar -Xmx4g SCORPI_GEL_v2.jar **VCF** <path-to-ReferenceGenome> <path-to-VCF_folder> <FILTER (TRUE/FALSE)> <path-to-output_folder><br>

_Example_
>java -jar -Xmx4g SCORPI_GEL_v2.jar **VCF** /home/sunny/Sunnyveerla/Projects/ReferenceGenome/hg38/hg38.fa /home/sunny/Sunnyveerla/Projects/SCORPI_GEL/Test/test_new/ TRUE /home/sunny/Sunnyveerla/Projects/SCORPI_GEL/Test/<br>

**Run SCORPI using a Catalogue (SBS) File**<br>
java -jar -Xmx4g SCORPI_GEL_v2.jar **SBS** <path-to-catalogue_file> <path-to-output_folder><br>

_Example_
>java -jar -Xmx4g SCORPI_GEL_v2.jar **SBS** /home/sunny/Sunnyveerla/Projects/SCORPI_GEL/Test/rndm_2000snvs_r10_contextCountFile_complete_context.txt /home/sunny/Sunnyveerla/Projects/SCORPI_GEL/Test/<br>
