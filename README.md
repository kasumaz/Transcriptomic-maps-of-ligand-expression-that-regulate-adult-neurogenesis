# Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis

ABSTRACT In the adult central nervous system (CNS), the subventricular zone (SVZ) of the forebrain is the largest and most active source of neural stem cells (NSCs) that generates mainly neurons and few glial cells lifelong that are regulated by a number of external stimuli. A large body of evidences in the field have shed light on the effects of distinct families of signaling ligands (i.e. morphogens, growth factors, secreted molecules that alter signaling pathways) in regulating NSC biology. However, most of the research has focused on the mRNA expression of individual or few signaling ligands and their pathway components in specific cell types of the CNS in the context of neurogenesis. A single unifying study that underlines the expression of such molecules comprehensively in different cell types in spatial contexts has not yet been reported. In this study, by using whole genome transcriptome datasets of individual purified cell specific populations of the adult CNS, the SVZ niche, NSCs, and performing a bioinformatic meta-analysis of signaling ligands, their expression in the forebrain were uncovered. Therein, we report that a large plethora of ligands are abundantly expressed in the SVZ niche, largely from the vasculature than from other sources that may regulate neurogenesis. Intriguingly, this sort of analysis revealed a number of ligands with unknown functions in neurogenesis contexts that warrants further studies. Altogether, this study serves as a framework for investigators in the field for understanding the expression patterns of signaling ligands and pathways regulating neurogenesis. 


Mouse Affymetrix datasets used in this study from GEO Pubmed (GSE numbers): 
Adult NSCs of different subtypes (GSE54653) [postnatal day (P) ~70] (Codega et al., 2014); 
Neural precursors (NPs)\TAPs, neuroblasts and ependymal cells (GSE18765) (P60) (Beckervordersandforth et al., 2010); 
Oligodendroglia at different stages of development (GSE9566) (P16) (Cahoy et al., 2008); 
Endothelial pericytes from the cerebral cortex (GSE47067; GSE48209) (~P70) (Nolan et al., 2013; Coppiello et al., 2015); (GSE29284) (Olson and Soriano, 2011); 
Choroid plexus (GSE82308) (P60) (Silva-Vargas et al., 2016); 
Astrocytes (GSE35338) (P30-35) (Zamanian et al., 2012); 
Microglia (GSE58483) (~P60) (Israelsson et al., 2014). 

![Datasets used](https://user-images.githubusercontent.com/31452870/79250904-b6244c80-7e7f-11ea-85a7-74892c326d12.jpg)



![Slide18](https://user-images.githubusercontent.com/31452870/79250952-cccaa380-7e7f-11ea-8cda-fbd971aa3dd5.PNG)
Schematic overview of ligands identified that regulate adult neurogenesis. An overview of ligands detected with a focus on novel ligand expression in studied regions and cell types. Bottom left hand corner inset shows an overview of a coronal section of the brain highlighting the lateral ventricle (lv), corpus callosum (cc) and cortex (ctx). Imaged made by Dr Jadasz: https://www.linkedin.com/in/janusz-jadasz-0b8a83170/



Figure 1: 

[Figure 1A - PCA Matrix.zip](https://github.com/Gliogenesis/Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis/files/4476646/Figure.1A.-.PCA.Matrix.zip)

[Figure 1D -  Pathway Work.zip](https://github.com/Gliogenesis/Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis/files/4476647/Figure.1D.-.Pathway.Work.zip)

![Figure 1](https://user-images.githubusercontent.com/31452870/79250913-bb819700-7e7f-11ea-9b1a-abb578725c23.PNG)




Figure 2:
![Figure 2](https://user-images.githubusercontent.com/31452870/79250921-c0dee180-7e7f-11ea-8145-91cd174a618b.PNG)




Figure 3:
![Figure 3](https://user-images.githubusercontent.com/31452870/79250927-c2a8a500-7e7f-11ea-81a1-88d59da84243.PNG)




Figure 4:
![Figure 4](https://user-images.githubusercontent.com/31452870/79250934-c50aff00-7e7f-11ea-8c1a-6ed7f6653e32.PNG)



Figure 5:
![Figure 5](https://user-images.githubusercontent.com/31452870/79250941-c805ef80-7e7f-11ea-870c-412d04f1a292.PNG)





![Supplementary Figures](https://user-images.githubusercontent.com/31452870/79250959-cf2cfd80-7e7f-11ea-9d8a-c7d2a373bfdc.PNG)





Above and below you will find the raw data used for this study. 

[All Figures - Gene Lists and Analysis.zip](https://github.com/Gliogenesis/Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis/files/4476643/All.Figures.-.Gene.Lists.and.Analysis.zip)

[All Figures - Reactome Pathway Analysis.zip](https://github.com/Gliogenesis/Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis/files/4476644/All.Figures.-.Reactome.Pathway.Analysis.zip)

[All Figures - RMA Normalised Matrix.zip](https://github.com/Gliogenesis/Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis/files/4476645/All.Figures.-.RMA.Normalised.Matrix.zip)

[Glial Cell Specific Ligands Lists.zip](https://github.com/Gliogenesis/Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis/files/4476650/Glial.Cell.Specific.Ligands.Lists.zip)

[Niche Cell Specific Ligands Lists.zip](https://github.com/Gliogenesis/Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis/files/4476651/Niche.Cell.Specific.Ligands.Lists.zip)

[Supplementary qNSCs vs aNSCs.zip](https://github.com/Gliogenesis/Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis/files/4476652/Supplementary.qNSCs.vs.aNSCs.zip)

[Table 1 - Niche Ligand Classification.zip](https://github.com/Gliogenesis/Transcriptomic-maps-of-ligand-expression-that-regulate-adult-neurogenesis/files/4476654/Table.1.-.Niche.Ligand.Classification.zip)



The main webtool used was the R online environment: 
https://carmaweb.genome.tugraz.at/carma/

The R Package (older version of the following link)
https://www.bioconductor.org/packages/devel/workflows/vignettes/maEndToEnd/inst/doc/MA-Workflow.html
Can be used to obtain very similar data. 

See the manuscript for the other tools and analysis performed. 

Please cite us at: 
Azim et al. Transcriptional Profiling of Ligand Expression in Cell Specific Populations of the Adult Mouse Forebrain That Regulates Neurogenesis. Front Neurosci. 2018; 12: 220.
https://www.frontiersin.org/articles/10.3389/fnins.2018.00220/full#h5
