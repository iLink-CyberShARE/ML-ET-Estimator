# ML-ETo-Estimator
Reference Evapotranspiration (ETo) models' analysis for outdoor irrigation to support water and vegetation management in semi-arid urban households.
Includes the evaluation of the following data driven algorithms: Linear Regression, XGBRegressor, Support Vector Regressor, Random Forest Regressor,  MLP, GRU, LSTM and Conv-LSTM to estimate reference evapotranspiration (ETo) from weather station data. 
Includes computations with physical ETo models: Penman-Monteith, Priestley-Taylor and Hargraves

# Data Source
Chihuahua Central Board of Water and Sanitation (JCAS)    
Data derived from 33 Davis Vantage Pro II model ground weather stations publicly available online. 
Data covers several regions in the state of Chihuahuahua, Mexico.   
[http://proyectojcas.uacj.mx/clima/public/maps/google/estacion](http://proyectojcas.uacj.mx/clima/public/maps/google/estacion)

# Links to Google Colab Notebooks  
+ Data consolidation and Curation: [https://purl.org/swim/etcode4](https://purl.org/swim/etcode4)      
+ ETo Regression and ML Models, Data statistics and SHAP analysis: [https://purl.org/swim/etcode1](https://purl.org/swim/etcode1)      
+ CovLSTM model and evaluation: [https://purl.org/swim/etcode3](https://purl.org/swim/etcode3)         
+ GRU and LSTM models and evaluation - [https://purl.org/swim/etcode2](https://purl.org/swim/etcode2)      

# How to Run

The application code is made available as a python notebook that can be executed online with Google Colab.    
Note that shared notebooks have been pre-executed, runtime outputs are shown accordingly.   

To run from scratch:   
1. Open link to the target notebook.
2. Generate a dataset following the instructions on Data consolidation and Curation notebook.
3. To run model noebooks: import the input dataset file (All-state8.xlsx) generated from the previous notebook.
4. To execute the notebook go to Runtime->Run all. Each code section can also be executed individually.

# Participating Institutions
The University of Texas at El Paso (UTEP)  
Universidad Autonoma de Chihuahua (UACH)   

# Contributors
Damian Gallegos Espinoza - UTEP   
Luis A Garnica Chavira - UTEP  
Natalia Villanueva Rosales - UTEP  
Juan Manuel Rodriguez Gaeta - UACH  
Carmen Julia Navarro - UACH   

# Acknowledgements  
This work was supported by Microsoft (UTEP team). This work used publicly available data provided by La Junta Central de Agua y Saneamiento (JCAS) of the state of Chihuahua, Mexico. 

# License
This software code is licensed under the [GNU GENERAL PUBLIC LICENSE v3.0](./LICENSE) and uses third party libraries that are distributed under their own terms (see [LICENSE-3RD-PARTY.md](./LICENSE-3RD-PARTY.md)).

## Citation  
Towards Estimating Water Consumption in Semi-Arid Urban Landscaping: A Data-Driven and Machine Learning Approach (In Press)   
Damian Gallegos Espinoza, Luis A Garnica Chavira, Natalia Villanueva-Rosales, Juan Manuel Rodríguez Gaeta and Carmen Julia Navarro Gómez    
23rd Mexican International Conference on Artificial Intelligence, INAOE, Tonantzintla, Puebla, México, October 21st - 25th, 2024 

First published in [Volumee page number, year] by Springer Nature”. - Pending Publication

