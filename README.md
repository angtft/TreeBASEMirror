# TreeBASEMirror

This repo contains MSAs from [TreeBASE](https://www.treebase.org/treebase-web/home.html) which we downloaded for our experiments, 
and - for most MSAs - the best trees we found after 100 [RAxML-NG](https://github.com/amkozlov/raxml-ng) tree searches under the "GTR+G" model for DNA and "LG" model for AA MSAs (with their respective inferred 
model parameters). We substituted the original taxon names since some of them were quite creative and made the parsers in the software we had to use
for our experiments cry. 

There is also a [SQLite](https://www.sqlite.org/index.html) database with our example scripts [here](https://github.com/angtft/RAxMLGroveScripts), that can be used for easier lookup of MSAs.


## References
* Piel, W. H., Chan, L., Dominus, M. J., Ruan, J., Vos, R. A., and V. Tannen (2009)
**TreeBASE v. 2: A Database of Phylogenetic Knowledge.**
*e-BioSphere 2009*.

* Vos, R. A., Balhoff, J. P., Caravas, J. A., Holder, M. T., Lapp, H. Maddison, W. P., Midford, P. E., Priyam, A., Sukumaran, J., Xia, X. and A. Stoltzfus (2012)
**NeXML: rich, extensible, and verifiable representation of comparative data and metadata.**
*Systematic Biology* 61(4): 675-689. 

* Alexey M. Kozlov, Diego Darriba, Tom&aacute;&scaron; Flouri, Benoit Morel, and Alexandros Stamatakis (2019)
**RAxML-NG: A fast, scalable, and user-friendly tool for maximum likelihood phylogenetic inference.** 
*Bioinformatics*, 35 (21), 4453-4455 
doi:[10.1093/bioinformatics/btz305](https://doi.org/10.1093/bioinformatics/btz305)
