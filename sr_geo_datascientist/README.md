## Sr. Geospatal Data Scientist

This task is intended to be a tool to help us gauge your mindset when you tackle geospatial data science problems. You are welcome to use Python (or R) for any analysis questions. 

### Instructions

1. Ensure you document & describe any assumptions or approaches you take and why you took them. 
2. Produce a jupyter notebook or a set of scripts that can be run locally, end-to-end by evaluators (beware of dependencies that can't be run in a new environment easily). You are also welcome to create a shared google collab or equivalent. 
3. Please answer the questions below. Feel free to highlight challenges and uncertainties. There is not one exact answer. We are interested in how you think.
4. Share the material back to the recruiters. 
5. Time limit: Please do not spend more than 3 hours on this task. Use your best judgement -- it is not intended to exhaust you.


### Questions

The [Cloud2Street Flood Dataset](https://mlhub.earth/data/c2smsfloods_v1) contains 900 sets of near-coincident Sentinel-1 and Sentinel-2 chips from 18 global flood events. Each chip contains a water label for both Sentinel-1 and Sentinel-2, as well as a cloud/cloud shadow mask for Sentinel-2. (citation: Cloud to Street, Microsoft, Radiant Earth Foundation. (2022). A global flood events and cloud cover dataset (Version 1.0). [May 2023]. Radiant MLHub.). 

* Geospatially, where are these events located?
* Are you able to determine what location has the largest area of continuous flood? What is the area? 
* For a set of AOIs (your choice) OR the full dataset, are you able to determine a correlation in signal between the S1 and S2 data for any given flood (in which there is a coincident collection)?
* Using an approach of your choice, create a basic model that uses information from either the S1 or S2 data to infer flood in the opposite image (e.g. using S1 flood, predict flood in S2 or vice versa). Understanding the limitations in time and compute, test your approach against a few data samples. Describe limitations, performance, and approach.
