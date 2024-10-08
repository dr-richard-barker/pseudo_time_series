---
description: >-
  This can be done using the new NASA GeneLab multi-study visualisation tools:
  https://visualization.genelab.nasa.gov/data/
---

# Metadata, PCA and heatmap figures

**Similarities and differences in methods GeneLab Metadata mining reveals similarities between these studies** GeneLab Data System (GLDS) Identifiers enable tracking of specific datasets within a larger repository. These identifiers, such as GLDS-37, GLDS-38, GLDS-120, GLDS-218, GLDS-321, etc., are crucial for cross-referencing and detailed analysis of the spaceflight experiments involving Arabidopsis thaliana. By cataloging experiments in this manner, the GeneLab researchers enabled efficient access allowing comparison of different studies and enhancing our understanding of plant responses to spaceflight conditions.

<figure><img src="../More_slides_and_figures/Slide3.png" alt=""><figcaption></figcaption></figure>

**Figure 2:** Filtering using GeneLabv metadata identifies similar studies (as described by Barker et al., 2023).

**A. Key Similarities between studies:** These studies were selected as they have several key methodologies and conditions that are conserved that is the use of agar nutrient gels in petri dishes to be used as the primary source of moisture and nutrients. The use of BRIC hardware has allowed the assessment of a range of ecotypes and genotypes on Phytagel plates in Petri dish fixation units (PDFU). The BRIC hardware has been used as its specialized PDFU growth chambers provide a controlled dark environment for plant growth in orbit. There is a notable uniformity in the short-duration nature of these studies, with plants being harvested in their nascent stages, providing insights into early growth dynamics. The addition of light in GLDS-120, allows comparison of plants that undergo photomorphogenesis in perpetual light to those that undergo skotomorphogensis in complete darkness, which is another pivotal aspect as this enables oxygen production via photosynthesis. The selection of this variation is not arbitrary but deliberate, aimed at unravelling the intricate effects of light on plant growth, development and morphogenesis. The choice of ecotypes/genotypes in these studies is not diverse but rather concentrated on specific, well-characterized strains such as Col-0, WS-0, and mutant variations of Col. This choice indicates a preference for using genetically familiar and extensively studied plant lines, facilitating comparative analysis and consistency in results. Lastly, there's a discernible emphasis on studying specific plant tissues, primarily roots, shoots and etiolated seedlings. This focus is indicative of a keen interest in understanding how different environmental stimuli influence the early stages of root and seedling development, crucial for comprehending the broader aspects of plant growth and adaptability.

**B. Key differences:** The differences between the GLDS studies are quite pronounced, especially when considering the hardware used and the lighting conditions, both of which significantly impact the type of tissue studied. In GLDS-38, GLDS-37, and GLDS-321, the use of BRIC hardware has been a defining feature. This specific type of hardware likely influences the nature of the experiments and the results obtained, particularly in terms of how the plant tissues respond to different environmental conditions. On the other hand, GLDS-120 uses Phytagel plates, and GLDS-218 is conducted with the Vegetable Production System, suggesting variations in how the plants are grown and observed. These differences in hardware may directly influence the types of tissues that can be effectively studied and the conditions under which these tissues develop. In terms of lighting conditions, each study has a unique approach that shapes the nature of the tissue studied. GLDS-38 is unique for its experiments conducted in complete darkness, while GLDS-120 features a variety of lighting conditions including continuous light and a combination of light activation followed by dark growth. GLDS-218's use of continuous purple light is particularly noteworthy, as it represents a specific wavelength that can have unique effects on plant growth and development. GLDS-37 and GLDS-321, meanwhile, incorporate studies in both complete darkness and periods of light activation followed by dark growth. These varied lighting conditions are crucial as they directly affect the physiological and developmental processes in plants, influencing the type of tissue that can be effectively studied in each experiment. The age at harvest and the specific ecotype and genotype being studied are also key differentiators among these studies. GLDS-120 investigates several ecotypes/genotypes including Col-0, WS-0, and Col-0 PhyD, offering a broad perspective on how different genetic backgrounds respond to the experimental conditions. GLDS-37 goes even further by focusing on a wider range of ecotypes/genotypes, such as Ws-2, Ler-0, Cvi-0, and Col-0. This diversity in genetic material is crucial for understanding the range of responses in plant biology. GLDS-321 studies variations of Col, including Col, Col bzip20, and Col bzip 60, allowing for a more nuanced understanding of how slight genetic variations can impact plant responses. Conversely, GLDS-38 and GLDS-218 limit their studies to the Col-0 and WS-0 ecotypes/genotypes, respectively, offering a more focused but potentially less diverse set of data. The age at harvest presents another layer of complexity and interesting research opportunity related to confronting a pseudo-time series. GLDS-38 and GLDS-321 are notable for their extremes in harvest ages – as short as 3 days and as long as 14 days, respectively. This contrasts with GLDS-120, GLDS-218, and GLDS-37, which all have similar ages at harvest, around 8-12 days. The age at harvest is crucial, as it determines the developmental stage of the plant tissues being studied. Younger tissues may respond differently to environmental conditions than more mature tissues. This aspect, coupled with the specific ecotypes/genotypes under investigation, provides insights to the natural variation in the plant's developmental response to spaceflight.



***

**Separate analysis:** Reanalysis of OSD-37 , OSD-38 , OSD-120, OSD-231 and OSD-321 will provide new insights.

Each of the studies can be analysed separately

https://visualization.genelab.nasa.gov/data/OSD-37

https://visualization.genelab.nasa.gov/data/OSD-38

https://visualization.genelab.nasa.gov/data/OSD-120

https://visualization.genelab.nasa.gov/data/OSD-218

https://visualization.genelab.nasa.gov/data/OSD-321



**Combined analysis:** Combining analysis of OSD-37 , OSD-38 , OSD-120, OSD-231 and OSD-321 will provide new insights.



<figure><img src="../More_slides_and_figures/Slide41.png" alt=""><figcaption><p>Summary of OSD accessions that can be merged for meta-analysis. Heatmap showing the transcriptional variation of the most 1000 variable loci with dendrograms showing sample connectivity based on expression variation. <br></p></figcaption></figure>

<figure><img src="../More_slides_and_figures/Slide51.png" alt=""><figcaption><p>Comparison of the data distribution and how it is affected by normalisation using the OSDR multi-study visualisation application. PC1, PC2, PC3 and PC4 are all shown in minimal pairwise comparisons. </p></figcaption></figure>



\


\




<figure><img src="../More_slides_and_figures/Slide50.png" alt=""><figcaption><p>Further analysis and clustering revealed that PC1 is the strain (genotype&#x26;ecotype). PC2 is the tissue mission factor, PC3  is the ecotype mission factor, PC4 is correlated with the gravitational factor (Flight vs ground), PC5 may be radiation. </p></figcaption></figure>

![SlFigure 3: PCA, MDS and t-sne plots showing combined samples. Color grouping is by OSD-#, Strain and gravitational factor respectively. (slide49)](../More\_slides\_and\_figures/Slide49.png)



***

***

<figure><img src="../More_slides_and_figures/Slide61.png" alt=""><figcaption><p>Heat map showing transcriptional variance across 5 OSR studies. Default thersholds and clustering options were used. </p></figcaption></figure>

<figure><img src="../More_slides_and_figures/Slide62.png" alt=""><figcaption><p>Heat map showing transcriptional variance across 5 OSR studies. Default thersholds and clustering options were used. </p></figcaption></figure>

<figure><img src="../More_slides_and_figures/Slide63.png" alt=""><figcaption><p>Heat map showing transcriptional variance across 5 OSR studies. Default thersholds and clustering options were used. </p></figcaption></figure>

<figure><img src="../More_slides_and_figures/Slide64.png" alt=""><figcaption><p>Heat map showing transcriptional variance across 5 OSR studies. Default thersholds and clustering options were used. </p></figcaption></figure>

![Heat map showing transcriptional variance across 5 OSR studies. Default thersholds and clustering options were used. ](../More\_slides\_and\_figures/Slide65.png)

**Figure 4:** A series of heat maps showing the top most significantly differentially expression loci's expression across all studies but selected by on DESeq models calculated for each OSD-# accession.

***

**Seed germination and seedling development involve a series of environmentally regulated genetic circuits.**

