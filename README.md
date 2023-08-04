
# Segmentation of individual HeLa Cells from confocal fluorescent microscopic images
This algorithm is a deep learning assited watershed, consisting of three steps:
1) Distance Transform generation
2) Detection of cells from the distance transform images generated
3) Step 1 and Step 2 as input to the watershed algorithm

# Distance Transform

For generating the distance transform of an image, we used a simple encoder-decoder architecure and trained over 30 images.
