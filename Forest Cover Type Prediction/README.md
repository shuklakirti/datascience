# Kaggle Competition
This repository contains a proposed solution to the Kaggle competition mentioned below
https://www.kaggle.com/c/forest-cover-type-prediction#evaluation

# Abstract
In this Kaggle competition we're predicting the forest cover type (the predominant kind of tree cover) from strictly cartographic variables (as opposed to remotely sensed data). The actual forest cover type for a given 30 x 30 meter cell was determined from US Forest Service (USFS) Region 2 Resource Information System data. Independent variables were then derived from data obtained from the US Geological Survey and USFS. The data is in raw form (not scaled) and contains binary columns of data for qualitative independent variables such as wilderness areas and soil type.

This study area includes four wilderness areas located in the Roosevelt National Forest of northern Colorado. These areas represent forests with minimal human-caused disturbances, so that existing forest cover types are more a result of ecological processes rather than forest management practices.

Each observation is a 30m x 30m patch. You are asked to predict an integer classification for the forest cover type. The seven types are:

   - Spruce/Fir
   - Lodgepole Pine
   - Ponderosa Pine
   - Cottonwood/Willow
   - Aspen
   - Douglas-fir
   - Krummholz

The training set (15120 observations) contains both features and the Cover_Type. The test set contains only the features. You must predict the Cover_Type for every row in the test set (565892 observations).

# Result
Ranked 78 in the kaggle competition on submission of the test csv as on March 2, 2019