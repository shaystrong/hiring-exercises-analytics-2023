## Background

Oasis Loss Modelling Framework is an open source framework intended to better unlock community development and understanding of catastrophic modeling and its implications. This platform facilitates the development, deployment, and execution of catastrophic models in a consistent and open standard way. From an ICEYE perspective, we are very interested in using this open source model in conjunction with ICEYE flood depth data to explore vulnerability and loss.

### Task

Using randomly generated flood depth data from 2020 - 2022 for Australia Gold Coast region, create a new vulnerability curve for the 'policies' represented in the dataset provided in [data/](https://github.com/shaystrong/hiring-exercises-analytics-2023/blob/main/senior_catastrophe_modeller/data/sample_pif_2020_2022.geojson). The `sample_pif_2020_2023.geojson` file includes latitude, longitude, flood depth, and event year. 

Use the curve you create in the Oasis Loss Modelling Framework (the toy ‘PiWind Model’ can be adapted) to demonstrate an end-to-end loss calculation. Assumptions and variable simplifications are fine. Please make them as needed. Please document all assumptions and approaches as part of an interactive jupyter notebook. 

Please try to limit work to < 3 hours (so take appropriate judgment calls). 

There is no 'right' or 'wrong' answer as we are more interested in the methodology you use and your thought process, as well as your ability to explain to the team you work.

You will present a lecture as part of this analysis to a mixed team of ICEYE scientists and engineers. The lecture should include:

* A short description of the event and its impact on the affected area
* The modeling approach used and assumptions made, along with the potential implications of making these choices
* Discussion of the results of the analysis and how it informs risk management decisions

### Task Requirements: 

* Install the Oasis Loss Modeling framework (https://oasislmf.github.io/).  
* Run the toy model PiWind (https://github.com/OasisLMF/OasisPiWind) with your ICEYE vulnerability curves.
* Produce a jupyter notebook of your approach following the simplified PiWind approach and share the notebook back to email address provided or by checking it into Github here.
* Prepare a lecture for the ICEYE analytics team about the approach, methodology, and simplifications. If more data is required as part of your demonstration, feel free to reach out to Shay. Your lecture will be 45 min with 15 min reserved for questions/discussion and will be open to the entire ICEYE Analytics team to attend.
