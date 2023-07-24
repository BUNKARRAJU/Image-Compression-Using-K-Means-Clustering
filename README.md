##Image Compression Using K-Means Clustering
#Objective
The purpose of this project is to demonstrate a simple image compression technique using the K-Means Clustering algorithm. The algorithm reduces the number of unique colors in an image, effectively compressing it while retaining visual quality to some extent.

#Description
This Python project uses the scikit-learn library for K-Means clustering and the OpenCV library for image handling. The compress_image function reads an image and applies K-Means clustering to group similar colors together. It then represents each group with the mean color, effectively reducing the color depth and compressing the image.

Note: The K-Means clustering technique employed in this project does not directly convert an 8-bit image to a 2-bit image. Instead, it quantizes the colors by reducing the number of unique colors in the image, but the image remains in its original bit-depth
