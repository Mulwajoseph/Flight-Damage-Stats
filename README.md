# Flight-Damage-Stats
 
 <img src="Images/image.jpg" alt="Plane Image" width="900"/>

 
  ### Introduction
As part of our company's strategic expansion into new industries, we are venturing into the aviation sector, aiming to acquire and operate aircraft for both commercial and private purposes. However, understanding the risks associated with different aircraft types is crucial for making informed purchasing decisions.

The Flight-Damage-Stats project addresses this challenge by analyzing historical data on airplane damage to identify which aircraft types represent the lowest risk. By leveraging data visualization and statistical analysis, this project aims to provide actionable insights that will guide our new aviation division in selecting the safest and most reliable aircraft for our business.

### Business Problem
To investigate the risks involved in the Aviation Industry and come up with an informed decision. We have to investigate the risks associated with the Industry  based on historical damage data, which will make us with our business goal.

### Project Objective
1. Analyze the Given data
2. Create a storyline by visualization from the Data provided.
3. Come up with an analysis to come up with data-based decision for our aviation division

   ## Set Up Installation

   #### 1.Clone the Repository 
   To Install the project on your local machine, first clone the repository using your terminal <br/>
  a.Open your terminal and run </br>
           git clone https://github.com/Mulwajoseph/Flight-Damage-Stats.git <br/>

  b.Navigate to your project Directory  <br/>

            cd project 1 

  c.Set up the environment<br/> 

  Create a virtual environment using Conda(Recommended):<br/>

           conda create --name myenv python=3.11.5  
           
           conda activate myenv

 d.Install Dependencies;This will install all necessary libraries<br/>

           pip install -r requirements.txt 
 
 # <u> Data Understanding </u>

## Data Source 
  ([Data Source](https://www.kaggle.com/datasets/khsamaha/aviation-accident-database-synopses))

## Description of Data 
I have thoroughly processed the dataset mentioned above, which involved an extensive data cleaning phase to ensure accuracy and consistency. Following this meticulous cleaning process, I performed various visualizations to extract and present meaningful insights from the data. These visualizations help to better understand the underlying patterns and trends, facilitating informed decision-making.

[Data cleaning % Visualization Process](joseph.ipynb)

## Data Visualization 
 A presentation of All Accidents and their occurrence on Monthy Basis .

 ![Data Visualization](Images/Snips/Time_series_Injuries.JPG)

 A presentation of Purpose of flight vs Make

 ![Flight vs Make](Images/Snips/Purpose_vs_Injuries.JPG)
 

 Line  graph presentation of the total Injuries and Year vs the make of plane 

 ![Month vs Total Injuries](Images/Snips/Injuries_vs_Make.JPG)

###  <u> Conclusion </u>

1.Engine type Impacts on accidents  <br>

2.Prioritize operational focus on flight purposes with fewer recorded accidents or ensure stricter safety regulations for flight purposes that have higher accident rates, reducing overall risk.<br>

3.Its necessary to avoid investing in the Amateur built planes<br>

4.Prioritize aircraft with a lower likelihood of significant damage during accidents. This can reduce long-term costs related to repairs, downtime, and replacements.<br>


 