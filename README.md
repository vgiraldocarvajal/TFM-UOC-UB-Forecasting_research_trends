## Supervised Learning to Forecast Trends Based on Metadata from Scientific Literature
### **Master's in Bioinformatics & Biostatistics - UOC & UB**


© Valeria Giraldo Carvajal

All rights reserved. The total or partial reproduction of this work by any means or processes, including printing, reprography, microfilm, computer processing or any other system, as well as the distribution of copies by rental and loan, is prohibited without the written authorization of the author or the limits authorized by the Intellectual Property Law.


### Abstract

Scientific literature metadata, such as the authors, institutions, and keywords associated with a paper, could provide insights into trends and patterns in the research being conducted. In this project, supervised learning algorithms were trained to verify whether scientific trends could be identified from scientific literature metadata. This was done for a collection of scientific publications discussing technologies in the domain of gene and genome editing (e.g., CRISPR-Cas9, TALENs). 

The selected learning algorithms were classification and regression trees, random forests, support vector machines and logistic regressions. Each algorithm was trained based on 15 different variables obtained from metadata to predict the binary variable recency, which is an indicator of trendiness for a topic (type of technology) within a given context (genome editing). 

When the “technology” variable was included, the models tested showed a very good performance (accuracies and AUC >0.95), especially for the logistic regression. The models trained in absence of the “technology” variable performed worse but still reasonably well (accuracies and AUC between 0.7-0.8), in particular random forest. Excluding the “technology” enabled clearly seeing the impact of metadata variables beyond the type of technology. In that sense, certain metadata had a strong impact on recency (e.g., the publication year). Beyond that, excluding the “technology” in the models, enabled seeing that presumably unexpected variables (e.g., the abstract length) also have an impact on the forecasting models.
 
Overall, these results suggest that valuable information hidden in metadata can be useful to predict trends in scientific literature. 



### Description of the files

The GitHub repository contains the following files:
1.	A “markdown” formatted report containing the code used throughout the development of this project. The analyses done in the “markdown” file should also be reproducible for different data sets, as long as they have been obtained from Scopus in a similar manner.
2.	Two XML files, corresponding to the download of the data set from Scopus, which was done in two parts.
3.	An Excel file, corresponding to the metadata linked to scientific journal metrics.
4.	A high resolution pdf containing the field map of the genome editing pool.

