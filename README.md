# socialism-clustering-analysis
Principal Component Analysis (PCA), clustering, K-means, hierarchical clustering, socialism, OECD, World Bank, social welfare, data mining, R programming, unsupervised learning, political analysis, public spending, computational social science.
This project explores the concept of socialism across countries by applying Principal Component Analysis (PCA) and clustering techniques to socioeconomic indicators. The goal was to identify and group countries based on their alignment with socialist principles, using publicly available data related to education, welfare, and housing expenditures.

The dataset, originally compiled for a course titled Digital Strategies for Social Sciences at Linköping University, includes variables from OECD and World Bank sources. It contains data on 46 countries and over 200 indicators. After selecting the most relevant variables and handling missing data through imputation, I applied PCA to reduce dimensionality and identify key components that explain most of the variance.

Following the PCA, I used K-means clustering and hierarchical clustering to group countries into clusters based on their similarity in social spending and demographic structure. The analysis revealed consistent patterns, with countries like Sweden, France, and Finland forming the most socialist-like cluster, while USA, UK, and Chile appeared in the least socialist group.

The project was done entirely in R, using libraries such as FactoMineR, factoextra, ggplot2, and cluster. The results were visualized to highlight groupings and explain the political-economic insights.

This project not only demonstrates how data science methods can support political analysis, but also shows how unsupervised learning can help uncover hidden structures in socioeconomic datasets. It contributes to the broader field of computational social science by combining quantitative techniques with theoretical reflection on governance and welfare.
