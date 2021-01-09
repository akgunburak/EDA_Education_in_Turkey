# Exploratory Data Analysis on Turkey's Educational Data
&nbsp;&nbsp;&nbsp;&nbsp; In this project, I applied exploratory data analysis on various education data of Turkey that I've obtained from Turkstat. I used the R language and several libraries related to data manipulation and data visualization. One who is interested in to see population, income, and happiness status of different education levels visually, or curious about which city is more well-educated in Turkey can click [**here**](https://akgunburak.github.io/EDA_Education_in_Turkey/) and review full code & graphics.

&nbsp;
&nbsp;
&nbsp;

## Technologies Used
* **Language and version:** R - 4.0.3 
* **Packages:** Tidyverse, Dplyr, Reshape2, Readxl, Sf, Ggplot2, Gganimate, Plotly, Qdap, Ggthemes

&nbsp;
&nbsp;
&nbsp;

## Data
* **Population, happiness, income, expenditure and cities data:** https://data.tuik.gov.tr

Original datasets can be found by searching following statements at Turkstat website;

    - Population: Population by attained education level and sex
    - Happiness: Level of happiness by educational level
    - Income: Mean annual income at main job by level of education
    - Expenditure: Education expenditure per student by level of education
    - Cities: Attained education level by provinces

* **Spatial data of Turkey:** https://data.humdata.org/dataset/turkey-administrative-boundaries-levels-0-1-2

&nbsp;
&nbsp;
&nbsp;

## Data Manipulation
&nbsp;&nbsp;&nbsp;&nbsp; Although the datasets have a well-organized structure, they have needed to be manipulated a little. The manipulation oparations include;

* Removing rows and columns which contain NA
* Dropping columns that contain male and female information, if they exist
* Renaming columns/cleaning Turkish phrases
* Changing data types
* Melting
* Transposing
* Joining dataframes

&nbsp;
&nbsp;
&nbsp;

## Graphics
&nbsp;&nbsp;&nbsp;&nbsp; Different types of charts have used to show the data's characteristics properly. All of them can be found by clicking the link in the introduction section. Nevertheless, a couple of example of charts;

* Pie chart of the population by education levels (This is a screenshot, again, interactive version is in the link in the introduction section)

![alt text](https://github.com/akgunburak/EDA_Education_in_Turkey/blob/main/data/pie.JPG)

&nbsp;

* Bar chart of happiness levels

![alt text](https://github.com/akgunburak/EDA_Education_in_Turkey/blob/main/data/bar.JPG)

&nbsp;

* Change of income over years line plot

![alt text](https://github.com/akgunburak/EDA_Education_in_Turkey/blob/main/data/income_line.JPG)

&nbsp;

* Choropleth map of provinces in Turkey by education level

![alt text](https://github.com/akgunburak/EDA_Education_in_Turkey/blob/main/data/map.JPG)

