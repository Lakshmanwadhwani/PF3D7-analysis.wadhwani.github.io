

### Welcome to my page! I am really interested in mosquito's and the diseases they transmit. In my personal case it would be malaria which is transmitted by the anopheles mosquito, the definitive host of the plasmodium falciparum parasite. So lets take a peak at the genome of this unicellular protozoan parasite!

I am going to use the programming language R to do some basic statistcal analysis and then swithc to python to do some more advanced stuff like amino acid compostion etc.So lets delve right into it. Instructions for downloading R can be located in my R install folder. We would also need to install Bioconductor. Instruction that also can be located in the bioconductor folder. Now we need to get our hands on some data! Fortunatel,y we have tons of that to analyze from various databases within the NCBI web portal.

We begin the data acquisition process by going to the NCBI website [](https://www.ncbi.nlm.nih.gov).Once we get to the site locate the "all database" drop down menu to the left of the screen, click on the drop down menu, scroll down and select nucleotide.The Nucleotide database is a collection of sequences from several sources, including GenBank, RefSeq, TPA and PDB. Genome, gene and transcript sequence data provide the foundation for biomedical research and discovery.

![alt text](https://github.com/lmarkal/wadhwani.github.io/blob/master/ncbi image.jpg)

For this mini project i would be analyzing the Plasmodium falciparum 3D7 mitochondrion, complete genome (PF3D7). To retrieve our data we would use the NCBI accession for the Plasmodium falciparum 3D7 mitochondrion, complete genome To retrieve the DNA sequence this from NCBI, go to the NCBI website, type “NC_001477” in the Search box at the top of the webpage, and press the “Search” button beside the Search box: 

