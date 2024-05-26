# Image Compression with K-Means Algorithm (from Scratch)

This project implements image compression using the K-means clustering algorithm built from scratch. K-means groups similar pixels together based on their color values, allowing for efficient storage and transmission.

## Functionality

* **Compression:**
    * Reads an input image using PIL.
    * Converts the image data to a NumPy array for efficient processing.
    * Implements K-means clustering algorithm from scratch:
        - Initializes random centroids.
        - Iteratively assigns pixels to their nearest centroid.
        - Recalculates centroids based on assigned pixels.
        - Repeats until convergence or a maximum number of iterations is reached.
    * Reduces the color palette of the image to a specified number of clusters.
    * Replaces each pixel with the average color of its corresponding cluster.
    * Saves the compressed image using PIL.

## Usage

**Prerequisites:**

* Python 3.x
* NumPy (`pip install numpy`)

**Running the Script:**

1. Clone this repository.
2. Install the required library (NumPy) if not already installed.
3. Navigate to the project directory in your terminal.
4. find the 'input_image_name' variable and change its name accordingly.
5. Run all the cells of jupyter notebook to get the compressed image.
