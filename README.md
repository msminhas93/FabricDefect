# FabricDefect
A weakly annotated fabric defect dataset. Contains 24 512x512 images. Every image has a 512x512 mask. The mask has one rectangular bounding box covering the entire defect but has pixels of fabric without defect. This makes the defect detection task challenging.

AnoNet was used on this dataset. [arXiv link](https://arxiv.org/pdf/1911.10608.pdf)

The segmentation results for different filter bank configurations on two test images are shown below.

![Segmentation Results AnoNet](/Results/fabricfilter_m25.png)

The AUROC and F1 Score values for these experiments are shown below.

![AnoNet Filter Bank Results](/Results/FabricFilter.png)