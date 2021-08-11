# SMC2021-Challenge4

Understanding HPC facilities users' behaviors and how computational resources are requested and utilized is not only crucial for the cluster productivity, but also essential for designing and constructing future exascale HPC systems.

This paper tackles Challenge 4, "Analyzing Resource Utilization and User Behavior on Titan Supercomputer", of the 2021 Smoky Mountains Conference Data Challenge. Specifically, we dig deeper inside the records of Titan in order to discover patterns and extract relationships.

Our findings allow us to investigate how projects, jobs, nodes, GPUs and memory are related. Moreover, we provide insights about seasonality usage of resources and a predictive model for forecasting utilization of Titan Supercomputer. Furthermore, the described methodology can be easily applied to any other HPC facility.

This repository contains the four Jupyter notebooks implemented to perform the study submitted in the shape of a paper named "An Study on the Resource Utilization and User Behavior on Titan Supercomputer".
Following the paper structure, the scripts stick to the next order:

1- preliminary.ipynb

2- timeseries.ipynb

3- gpudataset.ipynb

4- prediction.ipynb

In order to replicate the Conda environment, users can execute:

$ conda env create -f environment.yml

Notice that dataset is not included in the repository, and the scripts expect to have at path "./dc21-rur-and-gpu-data/" which must directories: "dc21-rur-and-gpu-data/RUR/"
and  "dc21-rur-and-gpu-data/GPU/".
