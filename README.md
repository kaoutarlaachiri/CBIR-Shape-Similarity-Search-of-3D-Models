# CBIR-Shape-Similarity-Search-of-3D-Models

The **objective** of this project is to implement a **content-based 3D model indexing and retrieval system**. 
The system will be able to process .obj files and compute shape descriptors for each model. These shape descriptors will then be used to measure the similarity of the model to other models in the example database. The goal is to allow users to search for similar models in the database based on their shape, rather than relying on manual labeling or other metadata. The implementation must be able to compare and retrieve the closest match(es) to the queried pattern.


We  tried to create a shape similarity search application similar to the one described in this article. 
To do this, we used Google Colab as a development space to facilitate our work. We also used libraries such as **sklearn** and **trimesh** to process 3D models and extract shape features. 


We implemented the dissimilarity calculation method described in the paper to measure similarity between shapes and used normalization techniques to ensure that the models are compared fairly. 


We tested our application on a 3D model database, '**3DPotteryDataset**' and obtained promising results in terms of shape similarity. However, there are still improvements to be made to make our application more efficient and reliable for real use.

Article link : https://www.researchgate.net/publication/3998806_Shape-Similarity_Search_of_Three-Dimensional_Models_Using_Parameterized_Statistics
