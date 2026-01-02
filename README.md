To build the "Automatic Blurriness Culling Tool" (Idea #56), we use a mathematical approach called the Variance of the Laplacian.
This method works by convolving the image with a Laplacian kernel (which highlights edges) and calculating the variance. A sharp image has high variance (lots of distinct edges), while a blurry image has low variance (the edges are "smeared" together).
