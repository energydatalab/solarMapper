# What you get is not always what you see—pitfalls in solar array assessment using overhead imagery
**Authors:** Wei Hu, Kyle Bradbury, Jordan M. Malof, Boning Li, Bohao Huang, Artem Streltsov, K. Sydny Fujita, and Ben Hoen

[**LINK TO INTERACTIVE WEBPAGE**](https://energydatalab.github.io/solarMapper/)

**Abstract**: Effective integration planning for small, distributed solar photovoltaic (PV) arrays into electric power grids requires access to high quality data: the location and power capacity of individual solar PV arrays.  Unfortunately, national databases of small-scale solar PV do not exist; those that do are limited in their spatial resolution, typically aggregated up to state or national levels. While several promising approaches for solar PV detection have been published, strategies for evaluating the performance of these models are often highly heterogeneous from study to study. The resulting comparison of these methods for practical applications for energy assessments becomes challenging and may imply that the reported performance evaluations overly optimistic. The heterogeneity comes in many forms, each of which we explore in this work: the degree of diversity of the locations and sensors (e.g. different satellites, aerial photography ) from which the training and validation data originate, the validation of ground truth (manual annotation of imagery vs known solar PV locations), the level of spatial aggregation (e.g. array-level vs regional estimates), and inconsistencies in the training and validation datasets (e.g. different datasets are used for each study and those data are not always made accessible). For each, we discuss emerging practices from the literature to address them or suggest directions of future research. As part of our investigation, we evaluate solar PV identification performance in two large regions: the entire state of Connecticut and the city of San Diego, CA. In Connecticut, we also use 33,114 known parcel-level solar PV installations from Berkeley Lab’s Tracking the Sun dataset to evaluate parcel-level performance and evaluate capacity estimates using 169 municipalities. We also make our code (which we call SolarMapper), pre-trained models, training data, and predictions publicly available and provide a web portal for interactively inspecting each prediction that was made. Our findings suggest that traditional performance evaluation of the automated identification of solar PV from satellite imagery may be optimistic due to common limitations in the validation process. The takeaways from this work are intended to inform and catalyze the large-scale practical application of automated solar PV assessment techniques by energy researchers and professionals.

[**Full text on arXiv**](https://arxiv.org/abs/1902.10895)

## Data

[**Connecticut predictions data available here**](https://github.com/energydatalab/solarMapper/blob/main/revised_duke_centroids.geojson)

[**Connecticut Solar PV Training Data**](https://figshare.com/articles/dataset/Connecticut_Solar_PV_Semantic_Segmentation_Dataset/18982199/5)

## Code

[**Code for the SolarMapper model**](https://github.com/energydatalab/mrs). This link also contains a tutorial on how the model can be trained and applied.

Visulization webpage created by Wayne Hu. Built with Mapbox; storage for data tiles provided by Mapbox.
