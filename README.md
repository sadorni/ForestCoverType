<<<<<<< HEAD
# Predict Forest Cover type using cartographical data (Multi-class classification task)

The goal of the project is to predict seven different cover types in four different wilderness areas of the Roosevelt National Forest of Northern Colorado. 
Forest Cover type classification can be used to monitor the evolution of flora over the designated region of interest. 

## Dataset
The dataset can be found on the [UCI Machine Learning Repository](https://archive.ics.uci.edu/ml/datasets/Covertype)
The actual forest cover type for a given observation (30 x 30 meter cell) was determined from US Forest Service (USFS) Region 2 Resource Information 
System (RIS) data. Independent variables were derived from data originally obtained from US Geological Survey (USGS) and USFS data. Data is in raw form 
(not scaled) and contains binary (0 or 1) columns of data for qualitative independent variables (wilderness areas and soil types).
The features are: 
Name / Data Type / Measurement / Description 

* Elevation / quantitative /meters / Elevation in meters 
* Aspect / quantitative / azimuth / Aspect in degrees azimuth 
* Slope / quantitative / degrees / Slope in degrees 
* Horizontal_Distance_To_Hydrology / quantitative / meters / Horz Dist to nearest surface water features 
* Vertical_Distance_To_Hydrology / quantitative / meters / Vert Dist to nearest surface water features 
* Horizontal_Distance_To_Roadways / quantitative / meters / Horz Dist to nearest roadway 
* Hillshade_9am / quantitative / 0 to 255 index / Hillshade index at 9am, summer solstice 
* Hillshade_Noon / quantitative / 0 to 255 index / Hillshade index at noon, summer soltice 
* Hillshade_3pm / quantitative / 0 to 255 index / Hillshade index at 3pm, summer solstice 
* Horizontal_Distance_To_Fire_Points / quantitative / meters / Horz Dist to nearest wildfire ignition points 
* Wilderness_Area (4 binary columns) / qualitative / 0 (absence) or 1 (presence) / Wilderness area designation 
* Soil_Type (40 binary columns) / qualitative / 0 (absence) or 1 (presence) / Soil Type designation 
* Cover_Type (7 types) / integer / 1 to 7 / Forest Cover Type designation

## Method
* Data Visualisation and Exploration
* Data Preprocessing (Scaling and UnderSampling)
* Modelling and Evaluation
* Conclusions



=======
# ForestCoverType
>>>>>>> 2cb10b91dca75caf55e3669c80aaf7484701dc14
