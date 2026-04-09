---
layout: about
title: About Me
permalink: /
subtitle: <strong>Ph.D.</strong> <a href='https://www.iiitd.ac.in/'>(IIIT, Delhi, India)</a>

profile:
  align: right
  image: prof_pic.jpg
  image_circular: false # crops the image to make it circular
  more_info: 

selected_papers: true # includes a list of papers marked as "selected={true}"
social: true # includes social icons at the bottom of the page

announcements:
  enabled: false # includes a list of news items
  scrollable: true # adds a vertical scroll bar if there are more than 3 news items
  limit: 5 # leave blank to include all the news in the `_news` folder

latest_posts:
  enabled: false
  scrollable: true # adds a vertical scroll bar if there are more than 3 new posts items
  limit: 3 # leave blank to include all the blog posts
---

I am a Computer Science researcher working at the intersection of applied machine learning, geospatial analytics and causal inference, with a focus on social development and environmental applications. My ongoing research centres on the impact evaluation of Natural Resource Management interventions, with the broader objective of understanding and strengthening water security in rural India.

I completed my Ph.D. from IIIT-Delhi in 2022, under the supervision of [Prof. Vikram Goyal](https://www.iiitd.ac.in/vikram) and [Dr. Venkata M . V. Gunturi](https://www.lboro.ac.uk/departments/compsci/staff/venkata-maruti-viswanath-gunturi/), where I developed computational methods for transportation problems on road networks. This provided a strong foundation in geospatial data analysis, spatial algorithms for route planning and matching, and spatial data mining using open-source datasets. This methodological training has shaped my subsequent work in applying computational approaches to real-world development contexts.

In my postdoctoral research at IIT Delhi, I have extended this expertise to the domain of sustainable resource management and climate adaptation in the agricultural sector. I work with the [ACT4D](https://www.cse.iitd.ac.in/%7Easeth/advertisement-for-act4d-projects-ethnographic-and-design-research.html) (Appropriate Computing Technologies for Development) research group at IIT Delhi, mentored by [Prof. Aaditeshwar Seth](https://www.cse.iitd.ac.in/%7Easeth/). 

My research focuses on the impact evaluation of Natural Resource Management (NRM) interventions, particularly the construction and maintenance of water harvesting structures (e.g., farm ponds and check dams), and waterbody rejuvenation efforts. My work leverages satellite imagery and computational methods to evaluate the effectiveness of these interventions in enhancing agricultural productivity and drought resilience, and to perform site suitability analysis, for the broader aim of informing strategies for sustainable agricultural practices, in the face of climate change.

My broader research interests lie in the use of ICT for development, with a focus on leveraging computational methods to drive sustainability and equity in both rural and urban contexts.

------

## **Research Interests**
Causal inference, Applied Machine Learning, Natural Resource Management, Impact evaluation, Systems thinking

------

## **Research Projects**
###### **Estimating Average Treatment Effects for MGNREGA farm ponds**
A large-scale impact evaluation of MGNREGA farm ponds in India, using a Difference-in-Differences (DiD) approach combined with Propensity Score-based matching. We computed Average Treatment Effects (ATE) of farm ponds  on agricultural productivity (crop yield) and drought resilience at the Agro-ecological Zone level, leveraging satellite imagery (Landsat) to compute the outcomes, and additionally, geospatial datasets to compute the rich set of covariates selected for this study.

![Project](/assets/img/projects/project_1.png)

*Data processing in our DiD with Propensity-score Matching (PSM) based impact evaluation framework*

###### **Extending the DiD impact evaluation framework for MGNREGA checkdams**
We extended our DiD-based impact evaluation framework to evaluate the impact of MGNREGA check dams, with an additional model for Zone of Influence (ZoI) based on the soil moisture profile in a 1.5 kms radius around the checkdams. We consider the first minima in the satellite data-derived NDMI (Normalised Difference Moisture Index) profiles with distance to generate ground truth for ZoI, which is later used to build a ZoI model based on relevant features. 

###### **Estimating Heterogeneous Treatment Effects for MGNREGA farm ponds**
To uncover heterogeneity in farm pond impacts across sites, in this study, we worked towards estimating Individual Treatment Effects (ITE) or Conditional Average Treatment Effects (CATE) of farm ponds on agricultural productivity (crop yield). We employ a Causal Machine Learning approach based on the Double Machine Learning (DML) method. We also add a layer of explainable AI to our framework to explain the heterogeneity in treatment effects. Our framework can be used for retrospective analysis to answer: “What is the impact of a specific farm pond, and why did this impact occur?”, as well as for predictive analysis to answer: “What would be the impact of a farm pond constructed at this location?”

###### **Impact evaluation of waterbody rejuvenation efforts**
In this ongoing project, we evaluate the impact of waterbody rejuvenation efforts carried out by the ATE Chandra Foundation across India, as part of the Amrit Sarovar Mission under the Niti Aayog. As part of this project, the CoRE stack team has developed the Waterbody Rejuvenation - Impact Assessment Dashboard, to which my contributions include the design of methodology and data analysis. In terms of impact evaluation, we are currently working on implementing methods to compute both ATEs and ITEs of waterbody rejuvenation on surface water availability in the waterbody, and cropping intensity in its Zone of Influence, using both DiD and DML, among other methods. 

-------