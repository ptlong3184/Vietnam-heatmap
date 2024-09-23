# VietNam_temperature_heatmap
This project shows how i use python and its libraries: numpy, pandas, shapefile, matplotlib, seaborn to create a heatmap base on the current temperature of every provinces in Viet Nam. 
I pulled API for the current temperature data on Openweathermap site. 
File data.zip contains all the data needed for shapefile to create the map of Viet Nam and specify borders of the provinces. 
Disclaimer!: Some provinces temperature data can not be pulled due to its name can not be identified on the API, for example: Dak Lak, Dak Nong, Ba Ria-Vung Tau,.. which counts up to 9 provinces. All of these missing information are replaced by 0 for the sake of simplicity. 
