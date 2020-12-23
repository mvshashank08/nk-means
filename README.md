# NK-means for Fast Noise Removal for k-Means Clustering
This project is a part of my work toward the course `CS 688` - **Machine Learning** at *George Mason University (GMU)*.

The paper "*Fast Noise Removal for k-Means Clustering*" proposed two algorithms `NK-MEANS` and `SAMPLE_CORESET` to solve the problem of *k-means with outliers* by removing at most *z* outliers. I implemented the above algorithms along with *Lloyd's algorithm*, *k-means++* and *k-means--* to reproduce the results from the paper.

## Datasets
* KDD - http://kdd.ics.uci.edu/databases/kddcup99/kddcup99.html
* SKIN - https://archive.ics.uci.edu/ml/datasets/Skin+Segmentation
* SUSY - https://archive.ics.uci.edu/ml/datasets/SUSY
* POWER - https://archive.ics.uci.edu/ml/datasets/Individual+household+electric+power+consumption

## Libraries Used
* `numpy`
* `matplotlib`
* `scipy`
* `pandas`

## Files
* `Project.ipynb` - The entire code is provided in the notebook file.
* `report.pdf` - The final report submitted for evaluation of my work.
* `paper.pdf` - The original paper "*Fast Noise Removal for k-Means Clustering*".
