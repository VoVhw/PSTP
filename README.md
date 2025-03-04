# PSTP
literature data for survey paper

raw data is literature data from web of science with the searching query: 
"TS=(("Environmental Big Data" OR "Big Data" OR "Big Data Analytics" OR "Environmental Informatics" OR "Data-driven Environmental Monitoring" OR "Environmental Data Integration" OR "Remote Sensing" OR "Satellite Data" OR "Geographic Information System" OR "GIS")
AND ("Pollution" OR "Air Pollution" OR "Water Pollution" OR "Contaminant" OR "Emission" OR "Contamination")
AND ("Source Tracking" OR "Source Apportionment" OR "Source Identification" OR "Monitoring" OR "Tracing" OR "Dispersion" OR "Diffusion")
AND ("Prediction" OR "Forecasting" OR "Predictive Modeling" OR "Machine Learning" OR "Deep Learning" OR "Artificial Intelligence" OR "Data Fusion" OR "Hybrid Model"))
AND (PY=2015 OR PY=2016 OR PY=2017 OR PY=2018 OR PY=2019 OR PY=2020 OR PY=2021 OR PY=2022 OR PY=2023 OR PY=2024)
"

map.txt and network.txt are generated VOSviewer results using the following method:
1. create map based on map on text data
2. read data from bibliographic database files
3. using binary counting
4. minimun number of occurrences of a term is 12
5. manually unselect words that are too general like "challenge", "detection", "estimate" etc...
