# Fall-2024-Biodiversity

Jeremy Borden, Chelsey Hunts, Dawit Mengesha, Yusup Amat, Sriram Raghunath

This repo contains the project 'Occupancy Modelling of Birds in the Amazon Rainforest. 
A brief summary of our project:
Our goals for this project were to test different occupancy modeling strategies to explore if and how climate change or forest loss has affected bird populations in the Amazonas region of Brazil over the time period of 2012 – 2021, and subsequently evaluate which models performed the best. We tested this for two species – a generalist species, Black vulture (Coragyps atratus) and a forest specialist, Screaming piha (Lipaugus vociferans). We used three different modeling approaches, two standard machine learning classification models – balanced random forest and binary logistic regression – and one modern occupancy modeling approach using the R package spOccupancy. 

The files contained in this repo:

- raw_data folder : Contains all the relevant data (in csv format)

- Occupancy_Modelling_Executive_Summary.pdf : A more comprehensive overview of our project, including details on our data collection, model development and testing, and project conclusions and outcomes 
  
- Occupancy_modeling_with_SpOccupancy.ipynb : Notebook containing our occupancy model implementations using the R-package spOccupancy

- ml_classification.ipynb : Notebook containing our machine learning classification approaches (implemented in python)

- pre-ebird_pre_preprocessing_example.Rmd : An R markdown file containing the earliest stage of prepreocessing (pre-processing) for eBird data. Note that the original eBird data set we obtained was very large and this pre-preprocessing was too memory-intensive to run for the whole data set at once. So this step was batched by splitting up the original eBird data set. The markdown file included here is an example of one such batch.

- pre-selecting_sites_and_species.ipynb : A preprocessing notebook where we select the sites and bird species within the Amazonas state to use for model development.
















