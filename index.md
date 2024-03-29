<img src="Sfold_logo_banner.png" alt="Sfold Logo" width="1200" height="80">

Sfold is a software program developed to predict probable [RNA](https://en.wikipedia.org/wiki/RNA) [secondary structures](https://en.wikipedia.org/wiki/Nucleic_acid_secondary_structure) through structure ensemble sampling and centroid predictions [1,2], with a focus on assessment of  RNA target accessibility [3], for the key applications to the rational design of siRNAs [4]  for the suppression of gene expressions, and for the identification of targets for regulatory RNAs particularly [microRNAs](https://en.wikipedia.org/wiki/MicroRNA) [5,6].  

**Development** 

The core RNA secondary structure prediction algorithm is based on rigorous statistical (stochastic) sampling of Boltzmann ensemble of RNA secondary structures, enabling statistical characterization of any local structural features of potential interest to experimental investigators. The sampling approach is the focus of a review [7], and its potential was discussed in an earlier review [8]. Predictions by Sfold have lead to new biological insights [9-11]. The ideas of ensemble sampling and centroids have been adopted by others not only for RNA problems, but also for other fundamental problems in computational biology and genomics [12-16]. The implementation stochastic sampling has been included in two widely used RNA software, RNA structure [17] and the Vienna RNA package [18], which are also based on the Turner RNA thermodynamic parameters [19].

Sfold-based bioinformatics tools for biological applications were developed from successful collaboration with [Kathleen McDonough](https://www.wadsworth.org/senior-staff/kathleen-mcdonough) on antisense oligos [20], [Erasmus Schneider](https://www.linkedin.com/in/erasmus-schneider-32865b5) on hammerhead ribozymes [21], [Victor Ambros](https://en.wikipedia.org/wiki/Victor_Ambros) on microRNA targeting [6], and [Jun Lu](https://medicine.yale.edu/profile/jun-lu/) on primary microRNA processing [22]. 

Development of bioinformatics tools and the Sfold software was funded by the [National Science Foundation (NSF)](https://www.nsf.gov) (grant 0650991, 0200970) and the [National Institutes of Health (NIH)](https://www.nih.gov) (grant R01 GM116855, R01 GM068726, R01 GM 099811, R01 GM 138856).

**Media coverage**

Sfold and biological application work have been featured on a *Nucleic Acids Research* cover [23], highlighted in *Science* NetWatch [24] and *Nature* Research Highlights [25], and were reported in a feature article by *Genome Technology* (now *GenomeWeb*) [26] and a four-page keynote interview by *Research Media* [27].

**Distribution**

Sfold runs on Linux, and is freely available to the scientific community for non-commercial applications, and is available under license for commercial applications. Both the source code and the executables are available at GitHub. 

<table>
  <tr> 
    <td>Original authors</td>
    <td> <a href="https://www.albany.edu/sph/faculty/ye-ding">Ye Ding</a> and <a href="https://en.wikipedia.org/wiki/Charles_Lawrence_(mathematician)">Charles E. Lawrence</a> </td>
  </tr>
  <tr> 
    <td>Application model developers</td>
    <td>Dang Long and Chaochun Liu</td>
  </tr>
  <tr> 
    <td>Software developers</td>
    <td>Clarence Chan, Adam Wolenc, William A. Rennie and Charles S. Carmack          </td>
  </tr>
  <tr> 
    <td>Initial release date</td>
    <td>April 1, 2003</td>
  </tr>
</table>

**External links**

•	**[Sfold GitHub repository](https://github.com/Ding-RNA-Lab/Sfold)**

•	**[Sfold commercial licensing](https://www.healthresearch.org/sfold-software-for-sirna/)**

**References**

1.	 Ding, Y; Lawrence, CE (2003). "A statistical sampling algorithm for RNA secondary structure prediction". *Nucleic Acids Res.*, **31** (24): 7280–301. doi:10.1093/nar/gkg938. PMC 297010. PMID 14654704.
2.	 Ding, Y; Chan, CY; Lawrence, CE (2005). "RNA secondary structure prediction by centroids in a Boltzmann weighted ensemble". *RNA*, **11** (8): 1157–66. doi:10.1261/rna.2500605. PMC 1370799. PMID 16043502.
3.	 Ding, Y; Lawrence, CE (2001). "Statistical prediction of single-stranded regions in RNA secondary structure and application to predicting effective antisense target sites and beyond". *Nucleic Acids Res.*, **29** (5): 1035–46. doi:10.1093/nar/29.5.1034. PMC 29728. PMID 11222752. 
4.	Elbashir, SM; Harborth, J; Lendeckel, W; Yalcin, A; Weber, K; Tuschl, T (2001). “Duplexes of 21-nucleotide RNAs mediate RNA interference in cultured mammalian cells”. *Nature*, **411** (6836):494-8. doi: 10.1038/35078107.
5.	Lee, RC; Feinbaum, RL; Ambros, V (1993). “The C. elegans heterochronic gene lin-4 encodes small RNAs with antisense complementarity to lin-14”. *Cell*, **75** (5):843-54. doi: 10.1016/0092-8674(93)90529-y.
6.	 Long, D; Lee, R; William, P; Chan, CY; Ambros, V; Ding, Y (2007). "Potent effect of target secondary structure on microRNA function". *Nat Struct Mol Biol*., **14** (4): 287–94. doi:10.1038/nsmb1226. PMID 17401373. S2CID 650349.
7.	Mathews, D (2006). "Revolutions in RNA secondary structure prediction". *J. Mol. Biol.*, **359** (3): 526–532. doi:10.1016/j.jmb.2006.01.067. PMID 16500677.
8.	 Zucker, M. (2000). "Calculating nucleic acid secondary structure". *Curr. Opin. Struct. Biol.*, **10** (3): 303–310. doi:10.1016/s0959-440x(00)00088-9. PMID 10851192.
9.	 Adams, L. (2017). "Pri-miRNA processing: structure is the key". *Nature Reviews Genetics*, **18** (3): 145. doi:10.1038/nrg.2017.6. PMID 28138147. S2CID 30513706.
10.	 Liu, C., Rennie, W.A., Carmack, C.S., Kanoria, S., Cheng, J., Lu, J. and Ding, Y. (2014) Effects of genetic variations on microRNA:target interactions. *Nucleic Acids Res.*, **42** (15), 9543-52; doi: 10.1093/nar/gku675. PMID: 25081214; PMCID: PMC4150780
11.	 Shaveta Kanoria, William Rennie, C. Steven Carmack, Jun Lu and Ye Ding (2022). N6- methyladenosine enhances post-transcriptional gene regulation by microRNAs. *Bioinformatics Advances*, **2** (1), vbab046.
12.	 Huang, F. W.; Qin, Jing; Reidys, Christian M; Stadler, Peter F (2009). "Target prediction and a statistical sampling algorithm for RNA-RNA interaction". *Bioinformatics*, **26** (2): 175–181. doi:10.1093/bioinformatics/btp635. PMC 2804298. PMID 19910305.
13.	 Harmanchi, Arif Ozgun; Gaurav, Sharma; Mathews, David H (2009). "Stochastic sampling of the RNA structural alignment space". *Nucleic Acids Research.*, **37** (12): 4063–4075. doi:10.1093/nar/gkp276. PMC 2709569. PMID 19429694.
14.	 Hamada, M; Kiryu, H; Mituyama, T; Asai, K (2009). "Prediction of RNA secondary structure using generalized centroid estimators". *Bioinformatics*, **25** (4): 465–473. doi:10.1093/bioinformatics/btn601. PMID 19095700.
15.	 Carvalho, L. E.; Lawrence, C. E. (2008). "Centroid estimation in discrete high- dimensional spaces with applications in biology". *Proc Natl Acad Sci.*, **105** (9): 3209–14. Bibcode:2008PNAS..105.3209C. doi:10.1073/pnas.0712329105. PMC 2265131. PMID 18305160.
16.	 Newberg, L. A.; Thompson, W. A.; Colan, S; Smith, T. M.; McCue, L. A.; Lawrence, C. E. (2007). "Centroid estimation in discrete high- dimensional spaces with applications in biology". *Bioinformatics*, **23** (14): 1718–27. doi:10.1093/bioinformatics/btm241. PMC 2268014. PMID 17488758.
17. Bellaousov, S; Reuter, JS; Seetin, MG; Mathews, DH (2013). ”RNAstructure: web servers for RNA secondary structure prediction and analysis”. *Nucleic Acids Res.*, **41** (Web Server issue): W471–W474. 
18. Gruber, AR; Lorenz, R; Bernhart, SH; Neuböck, R; Hofacker, IL (2008). “The Vienna RNA Websuite”. *Nucleic Acids Res.*, **36** (Web Server issue): W70–W74.
19. Mathews, DH; Sabina, J; Turner DH (1999).“ Expanded sequence dependence of thermodynamic parameters improves prediction of RNA secondary structure”. *J. Mol Biol.*, **288** (5):911-40. doi: 10.1006/jmbi.1999.2700.
20. Shao Y, Wu Y, Chan CY, McDonough K, Ding Y (2006). Rational design and rapid screening of antisense oligonucleotides for prokaryotic gene modulation. *Nucleic Acids Res.*, **34** (19):5660-9.
21. Shao, Y., Wu, S., Chan, C.Y., Klapper, J.R., Schneider, E. and Ding, Y. (2007) A structural analysis of in vitro catalytic activities of hammerhead ribozymes (2007). *BMC Bioinformatics*, **8**: 469.
22. Roden, C.A., Gaillard, J., Kanoria, S., Rennie, W., Barish, S., Cheng, J., Pan, W., Liu, J., Cotsapas, C., Ding, Y., Lu, J. (2017) Novel determinants of mammalian primary microRNA processing revealed by systematic evaluation of hairpin-containing transcripts and human genetic variation. *Genome Res.*, **27** (1) doi: 10.1101/gr.208900.116. PMID: 28087842; PMCID: PMC5340965.
23.  <https://academic.oup.com/nar/article/31/24/7280/2904423>
24. "TOOLS: Nucleic Acid Origami". *Science*, **300** (5621): 873. 2003. doi:10.1126/science.300.5621.873d. S2CID 220109027.
25. "Cell Biology: Predictions on target". *Nature*, **446**, 587, 2007, Research Highlights <https://www.nature.com/articles/446586a#Cell-Biology>

26. "Surefire siRNAs". *Genome Technology* (now Genomeweb), July 1, 2003, Meredith W Salisbury <https://www.genomeweb.com/archive/surefire-sirnas#.Y0gvFC-B28c>
27. "The Sfold Project: Computational tools for regulatory RNA studies". International Innovation. Bristol, UK: *Research Media Ltd*. February 2010. pp. 22-25.
