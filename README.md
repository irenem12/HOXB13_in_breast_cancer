# HOXB13_in_breast_cancer
Code for HOXB13 in breast cancer analysis, collaboration with Dr. Dennis Sgroi

This is the code to generate all manuscript figures. 

All TCGA data in this manuscript is downloaded from these two NIH data download links:

https://gdc.cancer.gov/about-data/publications/pancanatlas

https://gdc.cancer.gov/about-data/publications/PanCan-CellOfOrigin
https://gdc.cancer.gov/node/905/

Cell. Volume 173 Issue 2: p291–304.e6, 5 April 2018 10.1016/j.cell.2018.03.022

Note: clinical_PANCAN_patient_with_followup.csv was originally clinical_PANCAN_patient_with_followup.tsv but due to encoding issues I had to load it into numbers and export as a csv. No data was changed, it was just encoded to a different file type.


Metabrick data was downloaded from CBioPortal at this link: https://www.cbioportal.org/study/summary?id=brca_metabric

which is combined from Nature 2012 and Nat Commun 2016. Original link is:
https://pubmed.ncbi.nlm.nih.gov/?term=27161491%2C30867590%2C22522925%5Buid%5D

DeepDive validation data is from: https://www.ncbi.nlm.nih.gov/pmc/articles/PMC5563978/

Packages used:

Seaborn: Waskom, M. L., (2021). seaborn: statistical data visualization. Journal of Open Source Software, 6(60), 3021, https://doi.org/10.21105/joss.03021.

MatplotLib: J. D. Hunter, "Matplotlib: A 2D Graphics Environment", Computing in Science & Engineering, vol. 9, no. 3, pp. 90-95, 2007.

Numpy: Harris, C.R., Millman, K.J., van der Walt, S.J. et al. Array programming with NumPy. Nature 585, 357–362 (2020). DOI: 10.1038/s41586-020-2649-2.

pandas: Harris, C. R., Millman, K. J., van der Walt, S. J., Gommers, R., Virtanen, P., Cournapeau, D., … Oliphant, T. E. (2020). Array programming with NumPy. Nature, 585, 357–362. https://doi.org/10.1038/s41586-020-2649-2

Scipy: Pauli Virtanen, Ralf Gommers, Travis E. Oliphant, Matt Haberland, Tyler Reddy, David Cournapeau, Evgeni Burovski, Pearu Peterson, Warren Weckesser, Jonathan Bright, Stéfan J. van der Walt, Matthew Brett, Joshua Wilson, K. Jarrod Millman, Nikolay Mayorov, Andrew R. J. Nelson, Eric Jones, Robert Kern, Eric Larson, CJ Carey, İlhan Polat, Yu Feng, Eric W. Moore, Jake VanderPlas, Denis Laxalde, Josef Perktold, Robert Cimrman, Ian Henriksen, E.A. Quintero, Charles R Harris, Anne M. Archibald, Antônio H. Ribeiro, Fabian Pedregosa, Paul van Mulbregt, and SciPy 1.0 Contributors. (2020) SciPy 1.0: Fundamental Algorithms for Scientific Computing in Python. Nature Methods, 17(3), 261-272.

Lifelines: Davidson-Pilon, (2019). lifelines: survival analysis in Python. Journal of Open Source Software, 4(40), 1317, https://doi.org/10.21105/joss.01317

SigProfilerMatrixGenerator: Khandekar, A., Vangara, R., Barnes, M. et al. Visualizing and exploring patterns of large mutational events with SigProfilerMatrixGenerator. BMC Genomics 24, 469 (2023). https://doi.org/10.1186/s12864-023-09584-y

SigProfilerSimulator: Bergstrom, E.N., Barnes, M., Martincorena, I. et al. Generating realistic null hypothesis of cancer mutational landscapes using SigProfilerSimulator. BMC Bioinformatics 21, 438 (2020). https://doi.org/10.1186/s12859-020-03772-3

SigProfilerAssignment: Marcos Díaz-Gay, Raviteja Vangara, Mark Barnes, Xi Wang, S M Ashiqul Islam, Ian Vermes, Stephen Duke, Nithish Bharadhwaj Narasimman, Ting Yang, Zichen Jiang, Sarah Moody, Sergey Senkin, Paul Brennan, Michael R Stratton, Ludmil B Alexandrov, Assigning mutational signatures to individual samples and individual somatic mutations with SigProfilerAssignment, Bioinformatics, Volume 39, Issue 12, December 2023, btad756, https://doi.org/10.1093/bioinformatics/btad756

SigProfilerExtractor: Islam, S. M. A., Díaz-Gay, M., Wu, Y., Barnes, M., Vangara, R., Bergstrom, E. N., He, Y., Vella, M., Wang, J., Teague, J. W., Clapham, P., Moody, S., Senkin, S., Li, Y. R., Riva, L., Zhang, T., Gruber, A. J., Steele, C. D., Otlu, B., Khandekar, A., … Alexandrov, L. B. (2022). Uncovering novel mutational signatures by de novo extraction with SigProfilerExtractor. Cell genomics, 2(11), 100179. https://doi.org/10.1016/j.xgen.2022.100179


