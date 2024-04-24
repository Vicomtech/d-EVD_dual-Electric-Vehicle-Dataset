# d-EVD_dual-Electric-Vehicle-Dataset

<!-- PROJECT LOGO -->
<br />
<p align="center">
  <a href="https://github.com/Vicomtech/d-EVD_dual-Electric-Vehicle-Dataset">
    <img src="logo.png" alt="Logo" height="80">
  </a>    
</p>

This is a dual dataset of electric vehicle trips where battery, driving conditions and external conditions data is obtained. Electric car owners have the uncertainty of the battery range. SoC, speed, geo-position, traffic and weather are key parameters for analyzing battery consumption. The purpose of these datasets is to train models for an accurate battery range prediction. 

It is a dual dataset because there are two different datasets. One is formed by synthetic data from a wide range of simulations (DEVST), and the other by real trips carried out with two different vehicles (DEVRT).

In the next sections, the content and the way to access to the datasets is explained.


## DEVST (Dataset of Electric Vehicle Synthetic Trips)

Simulations have been done using SUMO (Simulation of Urban MObility) software. Data consists of 21 different routes and for each route, 5 cars, 3 driving styles, 3 confort cases, 5 occupancy cases, 3 wind cases and 3 traffic situations have been combined. The cases are the following:

* Driving style: agressive, moderate, defensive.
* Confort: high, medium, low.
* Occupancy: 1, 2, 3, 4, 5.
* Traffic: high, medium, low.
* Wind: high, medium, low.

The combination of all these cases gives a total of 42525 trips.

To gain access to the dataset, please fill the form in the following [link](https://opendatasets.vicomtech.org/di23-devst-dataset-of-electric-vehicle-simulated-trips/d913b9ff).

To know more about the process of getting data and building the dataset, refer to the following paper: [Electric vehicle battery consumption estimation model based on simulated environments](https://www.vicomtech.org/en) (in publication process).

## DEVRT (Dataset of Electric Vehicle Real Trips)

For the real trips dataset, many routes have been done, some more than one time, with two electric vehciles. A Dacia Spring and a Nissan Leaf. One is more intended to be used in urban trips and the other in medium and large trips. For obtaining vehicle battery data, an OBD-II device has been used. For obtaining the rest of the data, two external APIs have been used: 
* [Weatherapi](https://www.weatherapi.com/) for weather data.
* [Open data euskadi](https://opendata.euskadi.eus/) for traffic data.

As a result, during 5 consecutive days 29 urban/non-urban trips have been carried out with each vehicle, which gives a total of 58 trips.


To gain access to the dataset, please fill the form in the following [link](https://opendatasets.vicomtech.org/di23-devrt-dataset-of-electric-vehicle-real-trips/85b07c75).

<!--To know more about the process of getting data and building the dataset, refer to the following [paper](https://www.vicomtech.org/en). -->

## License
For both datasets:

The dataset is developed by Vicomtech and is made avaliable under a Creative Commons Attribution-NonCommercial-ShareAlike 4.0 International ([CC BY-NC-SA 4.0](https://creativecommons.org/licenses/by-nc-sa/4.0/deed.es)).

This license requires that reusers give credit to the creator. It allows reusers to distribute, remix, adapt, and build upon the material in any medium or format, for noncommercial purposes only. If others modify or adapt the material, they must license the modified material under identical terms.

## Contact

If you have any question or suggestion, do not hesitate to contact us at the following addresses:

* Eider Irigoyen: eirigoyen@vicomtech.org
* Iñaki Cejudo: icejudo@vicomtech.org
* Harbil Arregui: harregui@vicomtech.org
* Estíbaliz Loyo: eloyo@vicomtech.org 
