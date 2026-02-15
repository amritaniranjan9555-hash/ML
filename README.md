## Face Clustering and Distance-Based Classification using KMeans

### Aim

To detect faces from an image, extract HSV color features (Hue and Saturation), cluster the detected faces using KMeans, and classify a template image using distance-based comparison with cluster centroids.

### Methodology

Detect faces using OpenCV Haar Cascade.

Convert detected faces to HSV color space.

Extract mean Hue and Saturation values as feature vectors.

Apply KMeans(n_clusters=2) for clustering the faces.

Compute the centroids of the clusters.

Calculate Euclidean distance between the template image features and each cluster centroid.

Assign the template image to the cluster with the minimum distance.

Visualize clustering results using a scatter plot with centroids and template image.

### Results

Faces were grouped based on HSV color similarity.

Two clusters were formed using KMeans.

Centroids were calculated for both clusters.

Euclidean distance was used to classify the template image into the nearest cluster.

The template image was successfully assigned to the most similar group.

### Conclusion

KMeans effectively clustered faces based on color features. Distance-based classification helped determine the similarity between the template image and cluster centroids. Although clustering results may vary slightly due to random initialization, similar faces were grouped correctly and classification was performed

### Technologies Used

Python, OpenCV, NumPy, Matplotlib, Scikit-learn, SciPy
