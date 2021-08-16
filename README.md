# nihsummer2021
This program functions with the purpose of making both genome alignment data plots and coverage plots. The program takes user input of bamFiles, chromosome numbers, base start and endpoints, and file paths to save plots to and from it generates alignment and coverage plots. The program primarily utilizes the GViz package to accomplish this. In addition, the program utilized the argparser package in R to read in user input. 

Example input: 
C:\Users\ria\Documents\R\R-4.1.0\bin\x64\rscript "C:\Users\ria\Documents\gviz visualization\gvizdtrackvisualization.R" hg38 5 39369776 39427335 C:\Users\ria\nih\fulldata\samples\hsa_dRNA_HeLa_Ars_polyA_5P_1\reads.1.sanitize.noribo.toGenome.sorted.uxi.bam,C:\Users\ria\nih\fulldata\samples\hsa_dRNA_HeLa_NoArs_polyA_5P_1\reads.1.sanitize.noribo.toGenome.sorted.uxi.bam C:\Users\ria\nih\finalplots.pdf NoAresenic,Arsenic

