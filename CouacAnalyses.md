CouacAnalyses
================
Bruno Hérault
12/16/2017

Materials and Methods
=====================

Sampled forests
---------------

This study involved 13 permanent plots, including 12 from the Guyafor network (Grau et al. 2017) distributed throughout the northern two-thirds of French Guiana (Figure 1). All individual trees (≥ 10 cm in diameter-at-breast-height) present in the plots were marked, mapped, measured and botanically identified. The total dataset included 8633 trees. All individuals not determined to generic level were removed (529 individuales, 6.13% of all individuals).

Archaeological diagnosis
------------------------

#### Prospection

The surface of each plot was diagnosed by archaeologists. Evidence for pre-Columbian human occupations (such as artifacts, dark soils, earthworks) was searched for in the field, by superficial prospection of the ground surface while walking and carefully examining soils expelled from burrows and mounds resulting from uprooted trees. Exploratory, localized pits were also dug to confirm surface observations and to establish archaeological sequences. This allowed classifying plots as either “Apparently Anthropized Plot” (AAP) or “Apparently Non-anthropized Plot” (ANP).

### Dating

Dating was performed by AMS by the Radiocarbon Laboratory (A. Mickiewicz University, Poznań, Poland) following their routine protocol. Briefly, samples of charcoal dug from pits (after mechanical removal of macroscopic contamination visible under a binocular microscope) were treated with 1M HCl (80°C, 20+ min), 0.025-0.2M NaOH and then 0.25M HCl (80°C, 1 hour). After treatment with each reagent, the samples were rinsed with deionized water (Millipore) until pH = 7. Content of 14C in samples of carbon was measured using the spectrometer "Compact Carbon AMS" (National Electrostatics Corporation, USA) as described by Goslar et al. (2004). The measurement was performed by comparing intensities of ionic beams of 14C, 13C and 12C measured for each sample and for standard samples (modern standard: “Oxalic Acid II” and standard of 14C-free carbon: “background”). In each AMS run, 30-33 samples of unknown age were measured, alternating with measurements of 3-4 samples of modern standard and 1-2 samples of background (coal). Conventional 14C age was calculated using correction for isotopic fractionation according to Stuiver and Polach (1977), based on the ratio of 13C/12C measured in the AMS spectrometer simultaneously with the ratio 14C/12C. Calibration of 14C age was performed using the program OxCal ver. 3.10 (Bronk Ramsey, 2001, 2005). Calibration was performed against the 14C calibration curve IntCal04 (Reimer, 2004).

Effect of anthropization on tree assemblages
--------------------------------------------

### Composition

The differences in floristic composition among plots were compared with a Detrended Correspondence Factor Analysis (DCA), using the “decorana” function (Hill and Gauch, 1980; Oksanen and Minchin, 1997) of the “vegan” package (Oksanen et al., 2015) available on R.

### Main family abundances

The distribution and the relative abundance of the 20 families that accounted for most individuals in the plots were submitted to a Wilcoxon-Mann-Whitney test to determine the significance of differences for each family in distribution between AAP and ANP plots.

### Indicator species

Indicator species are species whose abundance was found in this study to be correlated with Pre-Columbian occupation. This correlation can be either direct (managed species) or indirect (consequence of a specific pattern of recolonization after occupation), and positive (species for which human occupation is favorable) or negative (species for which past human occupation is detrimental). We used the Dufrene and Legendre (1997) methodology with the package indicspecies (De Cáceres et al.,2012).

### Diversity

Diversity profiles were drawn for each plot using the “entropart” package (Marcon and Hérault, 2014) available in R. Differences between AAP and ANP plots were tested using Wilcoxon-Mann-Whitney test for the 3 main used orders of diversity (richness, Shannon index, Simpson index). Diversity profiles integrate the three entropy measures. Alpha diversity varies depending on the order q, which is the weight given to rare species in the calculation of diversity. When the rank (q) is equal to 0, this is equivalent to species richness. When it is equal to 1, this corresponds to the Shannon index and when it is equal to 2, it is the Simpson index. Producing these profiles allows appreciation of the modulation of diversity within each studied plot. A community may be considered more diverse than another if its diversity profile is above that for another community for all the values of q. If the curves intersect, there is no ordering relation (Marcon, 2014).

Including Plots
---------------

You can also embed plots, for example:

![](CouacAnalyses_files/figure-markdown_github/pressure-1.png)

Note that the `echo = FALSE` parameter was added to the code chunk to prevent printing of the R code that generated the plot. yes

``` r
summary(cars)
```

    ##      speed           dist       
    ##  Min.   : 4.0   Min.   :  2.00  
    ##  1st Qu.:12.0   1st Qu.: 26.00  
    ##  Median :15.0   Median : 36.00  
    ##  Mean   :15.4   Mean   : 42.98  
    ##  3rd Qu.:19.0   3rd Qu.: 56.00  
    ##  Max.   :25.0   Max.   :120.00
