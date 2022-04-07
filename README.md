# PCA and K Means with R
Author's : Aliriza Hamonangan Matondang
## Instruction

Dataset: Iris

Task: 

Doing the PCA so that it reduces Iris data to only 2 columns.
Then, doing K-Means Clustering from the successful Iris data
reduced. After that, answering the 3 questions below:

Question:
- What are values of the eigenvalue 1 and eigenvalue 2 of the Iris dataset?
- How much information can still be 'explained' by the reduced data?
- Find the optimal 'k' value based on the Elbow and Silhouette method.Is the value of k = 3 still the best 'k' value?

## The results
1. The Optimal Clusters by Elbow Method is 2
<img width="436" alt="000003" src="https://user-images.githubusercontent.com/92624520/162211781-d74ad920-2825-47ff-a4d8-cd18ac1c753c.png">

2. The Optimal Clusters by Silhouette is 2
<img width="436" alt="000005" src="https://user-images.githubusercontent.com/92624520/162212092-3336f04e-553d-466c-b880-208980c98ef4.png">

3. The Cluster plot
<img width="436" alt="000003" src="https://user-images.githubusercontent.com/92624520/162212656-c9ac9588-2ec2-42cf-98d5-d18b0da094ca.png">


## Conclusion
- Eigenvalue 1: 2.91849782 Eigenvalue 2: 0.91403047
- If we only choose PC1, we are still able to explain 72.9% of the data spread. If we choose PC1 and PC2, we are still able to explain 95.8% of the data spread
- The optimal K value = 2, the best K value is 2 because if we choose 3, it is no longer in the elbow and a normal decrease is seen (increasing the number of clusters is no longer significant in reducing WSS) after k = 2 and if we compare the results k = 2 with k = 3, the results tend to be close to or similar to k = 3 for k = 2, so it is better to combine them into k = 2 because there is no significant difference
