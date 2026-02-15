## Face Clustering using KMeans

### Aim

To detect faces from an image, extract HSV color features (Hue and Saturation), and cluster the faces using KMeans. A template image is also classified into one of the clusters.

### Methodology

Detect faces using OpenCV Haar Cascade.

Convert detected faces to HSV color space.

Extract mean Hue and Saturation values.

Apply KMeans(n_clusters=2) for clustering.

Predict cluster for the template image.

Visualize results using a scatter plot.

### Results

Faces were grouped based on color similarity.

Centroids were calculated for both clusters.

The template image was assigned to the nearest cluster.

### Conclusion

KMeans successfully clustered faces using simple color features. Results may slightly vary due to random centroid initialization, but similar faces are grouped together correctly.

### Technologies Used

Python, OpenCV, NumPy, Matplotlib, Scikit-learn
