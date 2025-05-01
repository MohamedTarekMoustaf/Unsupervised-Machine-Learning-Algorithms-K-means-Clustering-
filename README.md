# Unsupervised-Machine-Learning-Algorithms-K-means-Clustering-
In this project, I implement the K-means clustering algorithm and
apply it to compress an image. 

straightforward 24-bit color representation of an image, each pixel is repre-
sented as three 8-bit unsigned integers (ranging from 0 to 255) that specify
the red, green and blue intensity values. This encoding is often refered to as
the RGB encoding. Our image contains thousands of colors, and in this project, I reduce the number of colors to 16 colors.
By making this reduction, it is possible to represent (compress) the photo
in an efficient way. Specically, I only need to store the RGB values of
the 16 selected colors, and for each pixel in the image you now need to only
store the index of the color at that location (where only 4 bits are necessary
to represent 16 possibilities).
In this project, I will use the K-means algorithm to select the 16 colors
that will be used to represent the compressed image. Concretely, I will
treat every pixel in the original image as a data example and use the K-means
algorithm to find the 16 colors that best group (cluster) the pixels in the 3-
dimensional RGB space. Once you have computed the cluster centroids on
the image, you will then use the 16 colors to replace the pixels in the original
image.
![image](https://github.com/user-attachments/assets/655bd813-b1f2-4ce8-a1f7-55dabc767c1b)

