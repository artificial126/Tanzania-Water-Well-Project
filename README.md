# Tanzania-Water-Well-Project

## Overview 

Tanzania is in the midst of a water crisis: some of the people in the country do not have access to a source of safe water, and most of the people lack access to improved sanitation.Peoples in Tanzania lives in poverty for reaching safe water which is human body's basic need. They are sometimes making significant traveling with long time distances to reach water.

The objective of this project is to use a powerful ensemble method to perform a **classification** of the functionality of the water wells in Tanzania.


## Business Problems

Almost half the population of Tanzania is without basic access to safe water. Although there are many waterpoints already established in the country, a lot of them are in need of repair while others have failed altogether. 

In this model, aim is the predict **functionality** of water points. This will help Tanzania Government for future work.
If a water point needs repair or why is not functional and what features affect functionality. With this model, we can help the Tanzanian authorities how to use water sources in a productive way.

## Dataset

The dataset provided on https://www.drivendata.org by **Taarifa** and the **Tanzanian Ministry of Water**.
Dataset has 59,400 entries and 40 columns and after preparing data to modeling we have 168 features.

    We have data from 1960 to 2013 with different funders at 21 different regions in Tanzania. 

    Also it has water quality as ; soft and bad with waterpoint type as; communal pipe, hand pump etc.    

    We have the quantity of the water source as enough, insufficient,dry and seasonal,

    with source type as spring, shallow well, etc.
    
## Exploratory Data Analysis(EDA)

Our target variable(status_group)'s frequency is ;

    functional                 0.54304
    non functional             0.38429
    functional needs repair    0.07267

## Features 

### Quality
![Water Quality with Functionality](./images/water_quality.jpg)

As we processed our water quality values as soft(convenient) and bad(not usable). It seems convenient water quality points needs improvement, because there is a big portion of non-functional water points. 

### Quantity

![Water Point Type](./images/quantity.jpg)

Communal standpipe and hand pump mostly preferred.

Communal standpipes with multiple types and others(dam,cattle trough) have mostly non-functional water points.


### Regions 

![Regions](./images/regions.jpg)

We can easily see the region which has mostly functional water points has the highest number of water point.

On the other hand less water point regions have mostly non-functinoal water points.


### Findings

![Findings](./images/findings.jpg)
