# Spatial-statistics-to-reveal-patterns-and-connections-in-the-historic-landscape
The R script code was developed by dr. F. Brandolini (Newcastle University, UK) to accompany the paper: "Brandolini F.,  Turner S.,  - Revealing patterns and connections in the historic landscape of the northern Apennines (Vetto, Italy)", submitted to the Journal of Maps.

*Abstract*

In the Northern Apennines, significant modifications to the characteristic historic features of landscapes occurred since the 1950s as agriculture declined in importance and villages were progressively depopulated. Today European and national policies are promoting the repopulation of these regions in order to help preserve the cultural identity of territories and to reduce demographic pressure in urban areas. Such initiatives increase the need for cultural and natural landscape management to be better integrated using interdisciplinary approaches. Sustainable landscape management is a dynamic process involving the formulation of a set of strategies to underpin the preservation of landscape heritage and to foster local development on the basis of the values and opportunities provided by landscapes themselves. This study uses landscape archaeology and spatial statistics to provide insights into which parts of the historic landscape retain the greatest time-depth and which parts reflect more recent radical change, enabling an understanding which goes beyond the basic spatial relationships between landscape components.

Methods

This dataset was explored with two spatial statistical tools using the programming language R (R Core Team 2021): Local Indicators for Categorical Data (LICD) and Point Pattern analysis (PPA). The LICD method is based on join-count statistics (JCS), a solid method to measure the correlation between binomial variables and the distance between observations. LICD has been recently employed in landscape archaeological studies for verifying visible patterns and disclosing hidden spatial relationships (article: Carrer et al. 2021, Data: Zenodo Repository)

The application of PPA in landscape studies has been widely applied in Ecology and it is growing popular also in Archaeology (Knitter and Nakoinz 2018; Brandolini and Carrer 2020; Costanzo et al. 2021). In this study, PPA was employed to provide a quantitative assessment of the correlations between different components of the Vetto landscape.

List of files included in Brandolini_Turner_tjom_2022.zip:

R_script_code named "tjom_supplementary" in .rmd format
Output folder: png and .txt products of the R script code
GeoTiff folder (.TIFF file format):
Geomorphons
Euclidean distances from Irregular Fields (IF)
Euclidean distances from Combined Fields (CF)
EsriSHP folder (.shp file format):
H_sites folder: historic settlements (h_sites.shp)
rural_ruins folder: abandoned rural ruins (rural_ruins.shp)
hlc folder:
HLC_periods.shp
HLC_types.shp
roi folder: Region Of Interest (roi.shp)
Contacts

dr. F. Brandolini: filippo.brandolini@newcastle.ac.uk
Acknowledgements

The authors would like to acknowledge the help of the mayor Mr Fabio Ruffini and all the staff of Vetto d’ Enza, Dr. Alessandra Curotti and Dr. Chiara Cantini and (Unione Montana dei Comuni dell’Appennino Reggiano) and Dott.ssa Annalisa Capurso (Soprintendenza Archeologia Belle Arti e Paesaggio per la città metropolitana di Bologna e le province di Modena, Reggio Emilia e Ferrara) for their administrative assistance in preparation of the project fieldwork activities. Also, we wish to thank Dr Anna Campeol and Mr Davide Cavecchi (Provincia di Reggio Emilia - Ufficio Topografico) for their help in retrieving and digitising the Nuovo Catasto Terreni cadastral map. The authors also thank the AsRe (Archivio Stato di Reggio Emilia) and AsPr (Archivio Stato di Parma) administration and staff for giving the right to digitise the historical maps and for helping during the consultation at the archives. Finally, we thank Francesco Carrer (Newcastle University, Newcastle upon Tyne, UK) for his comments on the R script code, and Christopher Sevara (Newcastle University, Newcastle upon Tyne, UK) for his suggestions in retrieving historical satellite images.
