# Data Visualisation Codes
## Note: 
The data (i.e. MalariaGen Phase 2 data) for these plots was downloaded from the MalariaGen website.<br/>

### Folder with codes
[ Folder link ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/tree/main/Plink%20codes)<br/>


## Codes for:

### A. PCA Plots
The PCA plots were generated by the following steps:<br/>
1. Prune the data using the linkage pruning code:[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/tree/938a4fab789a1c51a68a8625e9090f8d81870e5e/Plink%20codes/Linkage%20Pruning%20of%20VCF%20Data)<br/>
2. Generate the PCA data using the output files from the linkage pruning analyses:[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/tree/main/Plink%20codes/PCA%20eigenvec%20and%20eigenval%20files%20generation)<br/>
3. Plot PCA data using R or Python codes. (Python plot code:[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/main/Codes%20for%20Different%20Data%20Visualisation%20Plots/Principal%20Component%20Analysis%20(PCA)0) and R plot code: [ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/tree/main/R%20Codes).

### B. Bar Chart Plots
1. Bar plots for multiallelic sites:[ link to code](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/646d0e7383333c9795ff5c9dd3e18bb478a04412/Codes%20for%20Different%20Data%20Visualisation%20Plots/Bar%20Plot%20for%20Triallelic%20Sites)<br/>
2. Bar plot (horizontal) for proportions of allelic sites:[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/acf5775d021d383801bfc59279d5055f71d16931/Codes%20for%20Different%20Data%20Visualisation%20Plots/Bar%20Plot%20for%20Allele%20Frequency%20Proportions)<br/>

### C. Heatmap Plots
1. Heatmap plots for Genetic Distances:<br/>
  a. compute the genetic distances from the vcf files using Plink code:[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/afee75dbac7e09f117793bbe1b931e4756ac71c4/Distance%20Matrix%20code)<br/>
  b. use the output from the computations from (1a) to plot the heatmap: [ link to code](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/26d3eefac7c9f8381b595bb8f72cefbd9ed3637f/Codes%20for%20Different%20Data%20Visualisation%20Plots/Heatmap%20using%20Genetic%20Distances)<br/>

2. Heatmap plots for Allele Frequencies:<br/>
   a. create sub vcf files for each population:[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/28179a9af8ee46b0aef99bc57a778b0f212116a2/Vcftools/Create%20sub%20vcf%20file)<br/>
   b. compute allele frequencies for each population:[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/43ccd8e8970bde34db436c9bbdd9555854fe0306/Vcftools/Compute%20Allele%20Frequencies)<br/>
   c. use the output from (2b) to plot heatmap:[ link to code](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/41d9294e83c55988099a9a4c75d43280c3e4ed2c/Vcftools/Generate%20heatmap%20plots%20using%20jupyter%20notebooks)<br/>

### D. Nucleotide Diversity Plots
1. Compute the nucleotide diversity values for each population:[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/f319116acce3c79ddc614511daf6c2d9530dea22/Codes%20for%20Different%20Data%20Visualisation%20Plots/Nucleotide%20diversity%20code%20using%20vcftools)<br/>
2. Create plot using the outputfile from (1a):[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/27a2505d1a2d439f47cfba8aefa4516630b28c02/Codes%20for%20Different%20Data%20Visualisation%20Plots/Nucleotide%20Diversity%20Plot)<br/>


### E. Tajima's D Plots 
1. 1. Compute the Tajima's D values for each population:[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/c7c55a81a38438850025a826662bbf81030599b8/Codes%20for%20Different%20Data%20Visualisation%20Plots/Tajima's%20D%20code%20using%20vcftools),br/>
   2. 2. Create plot using the outputfile from (1a):[ link to code ](https://github.com/aceneli/Anopheles-mosquitoes-March-24/blob/3b0ef545b4fa7fcbdd7dbd681017449d1f904ff9/Codes%20for%20Different%20Data%20Visualisation%20Plots/Tajima's%20D%20Plot).<br/>

