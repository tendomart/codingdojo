# Alcohol-Related Disease Impact (ARDI) Prediction
DATASET SOURCE : https://catalog.data.gov/dataset/alcohol-related-disease-impact-ardi-application-alcohol-attributable-fractions



#  Brief description of the data

Alcohol-Related Disease Impact (ARDI) Application - Alcohol-Attributable Fractions

ARDI is an online application that provides national and state estimates of alcohol-related health impacts, including deaths and years of potential life lost (YPLL). These estimates are calculated for 58 acute and chronic causes using alcohol-attributable fractions, and are reported by age and sex for 2015-2019. This dataset provides estimates of the proportion of deaths from various causes that are attributable to alcohol.


# Abstract

Alcohol-Related Disease Impact (ARDI) Software has been developed for the Centers for Disease Control (CDC) to allow States to calculate mortality, years of potential life lost (YPLL), direct health-care costs, indirect morbidity and mortality costs, and nonhealth-sector costs associated with alcohol use and misuse. The mortality related measures--mortality, YPLL, and indirect mortality costs--are computed for 35 diagnoses related to alcohol use and misuse. A review of clinical research studies and injury surveillance studies was conducted to produce estimates of the alcohol-attributable fraction (AAF) for each diagnosis. For these measures, age-specific and age-adjusted rates are also calculated. Health care costs, morbidity costs, and nonhealth-sector costs are prorated from national studies to the State or locality. This multiple-measure approach to quantifying a health problem is termed "disease impact estimation." National estimates of the disease impact of alcohol use and misuse have been produced using ARDI software and State-specific estimates are in preparation. Designed to CDC specifications, ARDI is completely menu-driven and operates within Lotus 1-2-3 software as a set of linked spreadsheets. ARDI adapts national epidemiologic and health economics methods for use by State and local health agencies. ARDI produces data on the health consequences of alcohol use and misuse for use by locally based policymakers, public health professionals, and researchers, while permitting comparison and compilation of these data across jurisdictions.

Source https://pubmed.ncbi.nlm.nih.gov/1652146/


# Why we're working with this dataset

 1. Identify the problem as either one that requires supervized or unsupervized machine learning algorithms
 2. To Identify the target variable for predictions if any ?
 3. Identify features which aid in predicting the target

# STEPS PERFORMED DURING PREPARATION 
1. Explolatory Data Analysis (EDA)
2. Explanatory Data analysis
3. Pre-processing in preparation for machine learning model training
4. The several models (Linear, Bagging and Tree Regressors) are then fit on the Pre-processed data 
5. The models are then used to predict The Cause of Alcohol Related Deaths 
6. Models are then Evaluated using various Metrics and the best performer is then selected and recommended for production


