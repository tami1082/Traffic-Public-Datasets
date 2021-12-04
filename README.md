# Contact Me
if you have any questions, please contact me. I can aslo provide **Baidu Netdisk**. Expect us to communicate about the processing of spatio-temporal data.

yudou.tian@outlook.com

# Datasets
it is a detail of public datasets.

https://drive.google.com/drive/folders/1xZifYuEtunwiKt4RA5bnnI1ex46OBWFO?usp=sharing 

that is my google drive, including **Los and sz, Pems3478, Pems7M, Pems-bay, metra-la, Pems-sf, Seattle_loop**.

<p align="middle">
  <img src="Images/content.png" width="308" height="450" />  
</p>  

# Run
https://colab.research.google.com/drive/1QOu-thJL2fo-P6O6QeS96weAcmae2hay?usp=sharing

that is a **colab version**, that can run the datasets.

## Pems-SF
http://www.timeseriesclassification.com/description.php?Dataset=PEMS-SF

https://archive.ics.uci.edu/ml/datasets/PEMS-SF

<p align="middle">
  <img src="Images/PEMS-FS.png" width="878" height="102" />  
</p>  


 ## Pems-03
The flow data is aggregated to 5 mins, which means there are 12 points in the flow data for each hour

<p align="middle">
  <img src="Images/PEMSD-3.png" width="537" height="248" />  
  <img src="Images/PEMSD-3-data.png" width="172" height="218" />  
</p>  

 
 ## Pems-04
The flow data is aggregated to 5 mins, which means there are 12 points in the flow data for each hour. It contains 3848 detectors on 29 roads. The time span of this dataset is from January to February in 2018.

Each npz file contains one key, named "data", the shape is (sequence_length, num_of_vertices, num_of_features).

<p align="middle">
  <img src="Images/PEMSD-4.png" width="590" height="285" />  
  <img src="Images/PEMSD-4-data.png" width="360" height="238" />  
</p>   

 
 ## Pems-07
The flow data is aggregated to 5 mins, which means there are 12 points in the flow data foe each hour. This folder should contain two csv files. One file contains the distances(km) between each pair of vertices, it has n rows and n columns, where n is the number of vertices. The other csv file contains n columns and lots of rows, each row represents a time step, each column represents the time series of a vertice.

<p align="middle">
  <img src="Images/PEMSD-7.png" width="539" height="246" />  
  <img src="Images/PEMSD-7-data.png" width="269" height="249" />  
</p>  

 ## Pems-07M
PeMSD7 was collected from Caltrans Performance Measurement System (PeMS) in real-time by over 39, 000 sensor stations, deployed across the major metropolitan areas of California state highway system. The dataset is also aggregated into 5-minute interval from 30-second data samples. We randomly select a medium and a large scale among the District 7 of California containing 228 and 1, 026 stations, labeled as PeMSD7(M) and PeMSD7(L), respectively, as data sources. The time range of PeMSD7 dataset is in the weekdays of May and June of 2012. We select the first month of historical speed records as training set, and the rest serves as validation and test set respectively.
 
 ## Pems-08
The flow data is aggregated to 5 mins, which means there are 12 points in the flow data foe each hour. It contains 1979 detectors on 8 roads. The time span of this dataset is from July to August in 2016.

Each npz file contains one key, named "data", the shape is (sequence_length, num_of_vertices, num_of_features).

There are three kinds of traffic measurements considered in our experiments, including total flow, average speed, and average occupancy. PeMS-04 and PeMS-08 are preprocessed to ensure the distance between any adjacent detector in datasets is longer than 3.5 miles. Finally, there are 307 detectors in the PeMSD4 and 170 detectors in the PeMSD8. The traffic data are aggregated every 5 minutes, so each detector contains 288 data points per day.

<p align="middle">
  <img src="Images/PEMSD-8.png" width="500" height="265" />  
  <img src="Images/PEMSD-8-data.png" width="460" height="194" />  
</p>   
 
 ## BAY-METR-LA
 https://github.com/liyaguang/DCRNN
 
(1) METR-LA This traffic dataset contains traffic information collected from loop detectors in the highway of Los Angeles County (Jagadish et al., 2014). We select 207 sensors and collect 4 months of data ranging from Mar 1st 2012 to Jun 30th 2012 for the experiment. 

(2) PEMS-BAY This traffic dataset is collected by California Transportation Agencies (CalTrans) Performance Measurement System (PeMS). We select 325 sensors in the Bay Area and collect 6 months of data ranging from Jan 1st 2017 to May 31th 2017 for the experiment.

 ## Los-loop-sz
Los-This data set is collected in real time on the highway in Los Angeles County by the loop detector. It includes 207 sensors and its traffic speed is collected from 3/1/2012 to 3/7/2012. These traffic speed data are aggregated every 5 minutes.

Sz-This is the trajectory of taxis in Shenzhen from January 1 to January 31, 2015, including 156 main roads in Luohu District as the study area. The traffic speed on each road is calculated every 15 minutes.

Only use the two files load-adj/speed.
 
 ## Seattle_Loop_Dataset
 https://github.com/zhiyongc/Seattle-Loop-Data
