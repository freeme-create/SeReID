# Spatially Enhanced Person Re-identification
The official code for [Se-ReID: Spatially Enhanced Representation Learning for Scalable Person Re-identiffcation](https:).
It implements the fundamental idea of our paper: We propose the Se-ReID framework with spatially enhanced representation learning for person re-identification. It includes two adaptive instance-level losses (TriHard+ and TriWeight) to stabilize hard sample mining and preserve intra-class structure, together with a global CentroidM loss that unifies absolute and relative spatial constraints beyond mini-batch limits. We further introduce 1st & 2nd order masks to remove repeated sample interference and maintain unbiased data distribution. Without relying on ReRank, our method achieves superior performance on Market-1501 and DukeMTMC-ReID, with interpretable clustering improvements on MNIST.
This code is based on an early version of [mikwieczorek/centroids-reid](https://github.com/mikwieczorek/centroids-reid) and [On the unreasonable effectiveness of centroids in image retrieval.](https:).

## Demonstration

[comment]:<img src="https://raw.githubusercontent.com/freeme-create/MMBNNet/blob/main/WholeModel.png" width="623" height="300">
<img src="https://github.com/freeme-create/MMBNNet-for-Person-ReID/blob/main/WholeModel.png" width="823" height="400">
