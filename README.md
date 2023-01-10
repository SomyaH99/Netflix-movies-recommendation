

![netflix-logo-png-2574](https://user-images.githubusercontent.com/109465304/211595011-1e60ee8c-b4ab-4303-95c0-bf2d163f370c.png)
 
**Netflix Movies And TV Shows Clustering**

![05cItXL96l4LE9n02WfDR0h-6](https://user-images.githubusercontent.com/109465304/211597623-50275392-3869-45af-90c1-760e23897a15.png)




                     
We have clustered Netflix Movies And TV Shows Data with K-Means Clustring and built a recommender system in Google Colab which recommends 5 movies based on input movie using cosin similarity.

 **Project Files Description**
 
 This Project includes 1 colab notebook, 1 technical documentation as well as 1 presentation:
 
 
**Executable Files:**
* Netflix movie clustering.ipynb - Includes all functions required for classification operations.

**Output:**
* Google Colab - All the outputs are visible in the provided colab notebook.

**Data Source:**
* Dataset - https://www.kaggle.com/shivamb/netflix-shows

![rainbow](https://user-images.githubusercontent.com/109465304/211596527-7be7221e-8097-4d03-a9be-83f1b6f79876.png)

**K-Means Clustering**

* k=8 is found to be an optimal value for clusters with highest silhouette score of 0.909 using which we grouped our data into 8 distinct clusters.
* Using dendograms and comparing various distance thresholds, a distance of 20 produced the highest silhouette score of 0.90 with 8 clusters produced the highest silhouette score of 0.90 with 8 clusters

![rainbow](https://user-images.githubusercontent.com/109465304/211596527-7be7221e-8097-4d03-a9be-83f1b6f79876.png)

Execution Instruction
The order of execution of the colab notebook is as follows:

1) TEAM_REALITY_ANDRIOD_AUTHENTICITY_PREDICTION.ipynb
   * First, click on the open in colab button present on the top center of the notebook.

2) Kaggle Dataset
   * Downlaod the dataset from kaggle through provided link.Then, connect to the runtime and execute the cell to mount the drive or upload the data file to the current runtime.

3) Cell Path
   * Finally, delete the path in the dataset loading cell and replace it with the path of your current data file. Run each cell to see the output below it.



