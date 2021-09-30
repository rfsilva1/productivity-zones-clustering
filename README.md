
# A data-driven framework for identifying productivity zones and the impact of agricultural droughts in sugarcane using SPI and unsupervised learning
## Description
This repository contains the code, and the final dataset used dataset for the paper A data-driven framework for identifying productivity zones and the impact of agricultural droughts in sugarcane using SPI and unsupervised learning, by Roberto F. Silva, Gabriela C. Gesualdo, Marcos R. Benso, Maria C. Fava, Eduardo M. Mendiondo, Antonio M. Saraiva, and Alexandre C. B. Delbem. We implemented the proposed framework for identifying productivity zones (with a specific interest on the productivity of drought-affected zones) using the k-means clustering and the sci-kit learn library. This paper was accepted at the 2021 IEEE MetroAgriFor (2021 IEEE International Workshop on Metrology for Agriculture and Forestry) scientific event. Descriptions of the implementation and the dataset are contained in the paper. The PDF will be available in this repository as soon as the final version of the paper is accepted. The code is composed of 1 Colab notebook. The dataset available in this repository is the final dataset (after data processing).

The datasets used were:
- Official sugarcane agricultural productivity in kg/ha for all cities in São Paulo state (SIDRA IBGE: https://sidra.ibge.gov.br/pesquisa/pam/tabelas)
- Historical meteorological data (precipitation, maximum and minimum temperature, wind speed, and solar radiation) based on the spatial interpolation of around 4000 rain gauges and weather stations in Brazil, developed by Xavier, A.C., King, C.W. and Scanlon, B.R., 2016. Daily gridded meteorological variables in Brazil (1980–2013). International Journal of Climatology, 36(6), pp.2644-2659.

The data processing code (not included in this repository) was developed by Gabriela C. Gesualdo and Marcos R. Benso. The clustering implementation code was developed by Roberto F. Silva.

Reference of the paper and to cite this repository: 
- The reference will be inserted after the final version of the paper is accepted

## To Do (further research, out of the scope of this paper):
- optimize code for deployment in production
- better integrate the data processing and clustering implementation codes
- automate data collection
- deploy code on webapp for evaluating multiple crops, years, and hazards
- incorporate new variables and more recent data
- implement other clustering models and compare the final results
- implement and evaluate additional metrics

## Credits for the code:
The code was implemented using Google Colab to improve replicability (https://colab.research.google.com/) and was based on the following:
- A demo of K-Means clustering on the handwritten digits data from the scikit-learn tutorial: http://scikit-learn.org/stable/auto_examples/cluster/plot_kmeans_digits.html
- K-means Clustering Python Example by Cory Maklin on Medium (2018): https://towardsdatascience.com/machine-learning-algorithms-part-9-k-means-example-in-python-f2ad05ed5203
- SILVA, R.F.; MOSTAÇO, G.M.; XAVIER, F.; SARAIVA, A.M.; CUGNASCA, C.E. Comparison of the k-means and self-organizing maps techniques to label agricultural supply chain data. In: Conference of the European Federation for Information Technology in Agriculture, Food and the Environment (EFITA), 2019, Rhodes, Greece.

The authors would like to thank the authors of the codes for providing them as examples for the use of the libraries and model implementation. 

The authors would also like to thank all the developers that were and are involved on the development of the following Python libraries: 
- Pandas: https://pandas.pydata.org/
- Scikit-Learn: https://scikit-learn.org/
- Matplotlib: https://matplotlib.org/
- NumPy: https://numpy.org/
- Seaborn: https://seaborn.pydata.org/
- SciPy: https://www.scipy.org/
- Geopandas: https://geopandas.org/

The authors would also like to thank all the developers that were and are involved on the development of the following R libraries: 
- insert R libraries

## Credits for the dataset:
The authors would like to thank the following institutions/researchers for providing the data collected:
- Official sugarcane agricultural productivity in kg/ha for all cities in São Paulo state (SIDRA IBGE: https://sidra.ibge.gov.br/pesquisa/pam/tabelas ). Online resource.
- Historical meteorological data (precipitation, maximum and minimum temperature, wind speed, and solar radiation): Xavier, A.C., King, C.W. and Scanlon, B.R., 2016. Daily gridded meteorological variables in Brazil (1980–2013). International Journal of Climatology, 36(6), pp.2644-2659.

## Acknowledgements:
This work was carried out at the Center for Artificial Intelligence (C4AI-USP) with support from the following institutions: São Paulo Research Foundation (FAPESP) Grants \#2019/07665-4 and \#2014/50848-9, IBM Corporation, Coordenação de Aperfeiçoamento de Pessoal de Nível Superior – CAPES (finance code 001), CAPES Grant 16/2014, Conselho Nacional de Desenvolvimento Científico e Tecnológico (CNPq) Grant 465501/2014-1, National Institute of Science and Technology for Climate Change Phase 2 (INCT-II), the graduate program in Hydraulics and Sanitary Engineering (USP-EESC), and regular funding to post-graduate program in Hydraulics and Sanitation of USP.
