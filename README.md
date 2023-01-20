# Forest-Biomass-Predictio

## Collaborators
Hanwen Guan, Yunning Liu, Shuhan Mao, Yi Sun, Runsheng Wang, Weijie Xia, Hongyan Zhou

## The problem we want to solve
We want to predict the forest biomass in China through linear rergession model based on the dataset from https://esajournals.onlinelibrary.wiley.com/doi/abs/10.1890/13-2089.1

## Brief Introduction
Forest biomass and its allocation have long been crucial factors in forest ecosystem structure and function. They can be useful in exploring many ecological questions such as forest community dynamics, life-history evolution, and terrestrial carbon cycling. To predict biomass level, both internal factors (e.g., forest types, or soil fertility), as well as external factors (e.g., geographical location, climate, or precipitation), should be taken into consideration.

In this study, we seek to explore and identify parameters that have a significant impact on Chinese forest biomass. After preprocessing the raw dataset (imputing missing data, doing transformations) and carrying out feature selection (LASSO & PCA), we mainly focus on building a multiple linear regression model to predict AGBt (total biomass of all aboveground tree components) using 6 features: MAP, Stand Age, PCA factor, Larix Forest, Other Forest Type, and P tabuliformis. The resulting model will be tested for model assumptions and its predictive power will be measured using the validation dataset. We seek to make better predictions for Chinese forest biomass, which would contribute to sustainable development both ecologically and economically.

## How to install and run the project
The code is run in R and the markdown file is provided in the repo. 
