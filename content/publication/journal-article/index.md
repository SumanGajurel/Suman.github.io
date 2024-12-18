---
title: "Performance comparision of Machine Learning models"
authors:
- admin
- Yunru Lai
- Keith Pembleton
author_notes: ""
date: "2024-09-01T00:00:00Z"
doi: ""

# Schedule page publish date (NOT publication's date).
publishDate: "2024-01-01T00:00:00Z"

# Publication type.
# Accepts a single type but formatted as a YAML list (for Hugo requirements).
# Enter a publication type from the CSL standard.
publication_types: ["article-journal"]

# Publication name and optional abbreviated publication name.
publication: ""
publication_short: ""

abstract: Soil chemical properties are crucial indicators of the capacity of soils to support plant growth. Soil chemical properties such as exchangeable sodium percentage (ESP), along with chloride (Cl), boron (B), and aluminium (Al) concentrations are important indicators for soil sodicity and elemental toxicities common in Australia. Information on these soil properties is available only for some regions of Australia or not available at all. Direct measurement of soil chemical properties can be challenging due to associated costs and complexities. Machine learning models provide promising approaches for timely and cost-effective prediction of soil properties. However, identifying the most suitable model to predict soil properties from particular datasets is challenging due to the variability in soil characteristics, the complexity of the data, and the need for models to generalize well across different conditions. We combined data from two Australian national databases [the National Paddock Survey (NPS) and Soil Data Federator (SDF)] and evaluated the ability of five machine learning models including random forest (RF), cubist (CU), extreme gradient boosting (XGB), support vector machine (SVM) and k nearest neighbour (kNN) in modelling Al, B, Cl concentrations and ESP.  Our results indicate that the CU performed best for Al, ESP, and Cl, while RF performed best for B in the training dataset. The prediction accuracy of RF models was slightly better for all the soil properties within the validation dataset. Measured soil properties such as electrical conductivity (EC) and pH were identified as the most critical variables for predicting ESP, B and Cl. The prediction interval coverage probability (PICP) result indicates that the RF model shows low prediction uncertainty for Al and B, and SVM model shows low prediction uncertainty for Cl and ESP.  The predictive models for soil chemical properties offer a cost-effective and reliable method for assessing soil quality. By enabling accurate predictions, these models can enhance farm management decisions, leading to optimized resource use for better production. 

# Summary. An optional shortened abstract.
summary: This study leverages machine learning models to predict critical soil chemical properties, such as exchangeable sodium percentage (ESP), chloride (Cl), boron (B), and aluminium (Al), essential for assessing soil health in Australia. Using data from two national databases, it evaluates five models—random forest (RF), cubist (CU), extreme gradient boosting (XGB), support vector machine (SVM), and k-nearest neighbor (kNN)for predictive accuracy. Cubist performed best for Al, ESP, and Cl, while RF excelled for B and overall validation accuracy. These models provide a cost-effective approach for assessing soil quality, supporting more informed farm management.

tags:
- Soil chemical properties
- Machine learning
- Soil constraints
featured: true

# links:
# - name: ""
#   url: ""
url_pdf: ""


# Featured image
# To use, add an image named `featured.jpg/png` to your page's folder. 
image:
  caption: 'Image credit: [**Unsplash**](https://unsplash.com/photos/jdD8gXaTZsc)'
  focal_point: ""
  preview_only: false

---

