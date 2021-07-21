<h2 align="center">Analysis-of-Charging-Schedules-of-Electric-Vehicles-Considering-End-User-Inputs</h2>


<h3 align="left">Introduction
  
 <h4 align="left"> This section includes the analysis of the EV Charging data which provide by Schneider Electric from the year 2017 to 2020. Feature Engineering selection was applied such as Correlation test and PCA. After that cleaned data was analyzed based on various aspects to deduce the problems within the grid and to provide a suitable solution. For the ease of data analysis, the power consumption of the vehicle in a charging station is evenly distributed along the total time that the EV took for charging...</h4>

<p align="center">
  <img width="500" src="https://user-images.githubusercontent.com/74568334/126491250-f65550ba-674a-4707-8296-7321756e17c3.jpg">
</p> 

## 🔑 Results 
  <h3 align="left"> 1. Analysis of Year-Wise Power Consumption from 2017 to 2020</h3>
  <h4 align="left"> The analysis done  on the variation of power consumption in kilo-Watthour(kWh) against Time for all stations under analysis from 2017 to 2020. There were eleven stations involved in the analysis and further details are shown in Section III. The power consumption from 2017 has been increasing until 2019 and it saw a steady decline in the year 2020. The peak power consumption of the year 2019 and 2020 are 3090.991 kWh and 1128.401 kWh, respectively. </h4>
  <p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/74568334/126492077-1de6b55f-aa43-4426-bfce-9cdaf1c8d3c9.jpeg">
</p> 
  
<h4 align="left"> Discussions</h4> 
  
<h4 align="left">'
  
*	From 2017, there was a steady growth in the number of electric vehicles this resulted in more power consumption in 2019.
  
*	2020 power consumption was drastically low because of the travel regulation imposed due to Corona pandemic. 
  
*	The power consumption peaks range between 8 am and 4 pm, this might be because of working hours.
  
*	The power consumption is minimal for the time range, from 12 am to 7 am and from 4 pm to 11 pm reason might be, because of a smaller number of vehicles being charged in those time range. </h4> 
  
<h3 align="left"> 2. Analysis of Power Consumption for Each Day</h3>
  <h4 align="left"> The following graph is plotted on the variation of total power consumption (sum of power consumption of all the charging stations under analysis) in kilo-Watthour(kWh) against Time for each day from 2017 to 2020. </h4>
  <p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/74568334/126493282-27421381-411f-4f01-8926-530bd8ac73f6.png">
</p> 
  
<h4 align="left"> Discussions</h4> 
  
<h4 align="left">  
  
* The power consumption is generally found to be high during the weekdays and significantly low during the weekends. Further, Monday and Friday have relatively higher power consumption among the rest of the weekdays. The peak power consumption(total) for Monday and Friday are 1128.88 kWh and 1011.32 kWh, respectively. 

* The power consumption in the working days is significantly higher than the weekends, this might be due to lack of usage of EVs on the weekends.
  
* The power consumption on Mondays is found to be greater than that of any other day as there might be higher travelling on the weekends.
  
*	Similarly, the Friday power consumption might correspond to the higher travelling requirement on the weekends.
  
*	The rest of the working days (i.e., Tuesday till Thursday) the power consumption is similar and comparatively lesser than that of Monday and Friday, as these days do not succeed or precede by any other day with higher travelling requirements.</h4> 
  
<h3 align="left"> 3. Analysis of Power Consumption for Each Charging Station in 2020</h3>
	
  <h4 align="left"> The following graph is plotted on the variation of power consumption in kilo-Watthour(kWh) against Time for each station under analysis in 2020. 
The stations under analysis were named as follows:
	  
DE*I2G*ESO0003*001: DE3001
	  
DE*I2G*ESO0005*002: DE5002
	  
BESUCHER E5.12: E12
	  
BESUCHER E3.3: E3
	  
DE*I2G*ESO0003*002: DE3002
	  
DE*I2G*E00009*8F*1: DEF1
	  
BESUCHER E5.13: E13
	  
BESUCHER E3.4: E4
	  
DE*I2G*ESO0005*001: DE5001
BESUCHER E5.11: E11 
	  
BESUCHER E5.14: E14</h4>
	
  <p align="center">
  <img width="700" src="https://user-images.githubusercontent.com/74568334/126493282-27421381-411f-4f01-8926-530bd8ac73f6.png">
</p> 
  
<h4 align="left"> Discussions</h4> 
  
<h4 align="left">  
  
* The power consumption is generally found to be high during the weekdays and significantly low during the weekends. Further, Monday and Friday have relatively higher power consumption among the rest of the weekdays. The peak power consumption(total) for Monday and Friday are 1128.88 kWh and 1011.32 kWh, respectively. 

* The power consumption in the working days is significantly higher than the weekends, this might be due to lack of usage of EVs on the weekends.
  
* The power consumption on Mondays is found to be greater than that of any other day as there might be higher travelling on the weekends.
  
*	Similarly, the Friday power consumption might correspond to the higher travelling requirement on the weekends.
  
*	The rest of the working days (i.e., Tuesday till Thursday) the power consumption is similar and comparatively lesser than that of Monday and Friday, as these days do not succeed or precede by any other day with higher travelling requirements.</h4> 
