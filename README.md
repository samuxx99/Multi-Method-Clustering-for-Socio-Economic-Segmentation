# Multi-Method-Clustering-for-Socio-Economic-Segmentation
---
This project applies a range of clustering techniques to segment countries based on socio-economic indicators,
recognizing that these variables do not form perfectly distinct groups. Given the overlapping nature of the
data, soft clustering methods are particularly appropriate, as they allow for probabilistic membership rather
than rigid assignments.

To capture the underlying structure, model-based clustering is employed through **Gaussian Mixture Mod-
els (GMM)** and finite mixture models, leveraging the Expectation-Maximization algorithm for parameter
estimation. **Cluster-Weighted Models (CWM)** further refine the analysis by incorporating dependencies
between socio-economic variables, enhancing interpretability. In parallel, fuzzy clustering techniques provide
an alternative soft classification, offering a flexible approach to partitioning.
Among hard clustering methods, k-means has produced a well-defined partition, effectively capturing key
patterns in the data, while hierarchical approaches proved less effective. By integrating these diverse
methodologies, the project ensures a robust and nuanced segmentation, reflecting both the structure and
uncertainty inherent in socio-economic data.
