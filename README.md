### Introduction

In this study, we aim to analyze and categorize a dataset containing various attributes related to individuals' demographics, lifestyle habits, and health metrics. The dataset includes information such as age, sex, region, occupation, smoking status, gym frequency, time spent in the gym, average steps per day, and other relevant features. Our objective is to employ clustering techniques to identify distinct groups within the data, and then evaluate specific hypotheses about these groups based on their characteristics.

### Abstract

This paper presents an analysis of a dataset to identify distinct clusters among individuals based on demographic and lifestyle attributes using hierarchical and K-means clustering techniques. The dataset includes features such as age, sex, occupation, region, smoking status, gym frequency, and average steps per day. We perform data preprocessing including scaling, clustering, and evaluation of cluster characteristics. The results reveal the formation of four clusters, each with unique attributes. This study provides insights into the relationships between lifestyle habits and demographic factors, highlighting patterns that could inform targeted interventions in health and wellness programs.

### Results

1. **Median Age Before and After Scaling:**
   - Median age before scaling: 39.0
   - Median age after scaling: 0.4565

2. **Hierarchical Clustering:**
   - Dendrogram with a threshold of 21.67 resulted in 4 clusters.
   - Cluster sizes: Cluster 0 (466), Cluster 1 (359), Cluster 2 (257), Cluster 3 (256)
   - Average age for each cluster: Cluster 0 (39.95), Cluster 1 (39.08), Cluster 2 (39.53), Cluster 3 (37.71)
   - Median average steps per day: Cluster 0 (8000), Cluster 1 (7900), Cluster 2 (7800), Cluster 3 (8100)

3. **Cluster Characteristics and Hypothesis Evaluation:**
   - Cluster 1 has a higher southeast ratio mean compared to other clusters.
   - Cluster 1 has no engineers.
   - Cluster 1 has a higher northeast ratio mean compared to other clusters.
   - Evaluation of specific statements showed varied results, highlighting specific characteristics unique to each cluster.

4. **K-means Clustering:**
   - Formed 4 clusters with the following sizes: Cluster 0 (321), Cluster 1 (326), Cluster 2 (365), Cluster 3 (326)
   - Cluster 0 has the highest smoker rate, a significant proportion of males, and the highest average age among clusters.
   - The number of instances with children: Cluster 0 (78), Cluster 1 (82), Cluster 2 (100), Cluster 3 (77)

5. **Additional Insights:**
   - Specific occupational distributions within Cluster 2: Artists (67), Doctors (66), Engineers (63), Others (112), Teachers (57)
   - Gym frequency distribution within Cluster 3: Frequency of 3 days (117), 2 days (97), 0 days (69), 1 day (43)

These results underscore the effectiveness of clustering techniques in identifying and interpreting patterns within complex datasets, providing a foundation for further analysis and potential applications in public health and personalized wellness strategies.
