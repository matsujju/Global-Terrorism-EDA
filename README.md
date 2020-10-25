# Global Terrorism (Exploratory Data Analysis)
  This repository contains files for Global Terrorism Exploratory Data Analysis.

## Overview -
  - This Project is exploratory data analysis of [Global Terrorism Database](https://www.kaggle.com/START-UMD/gtd) (GTD) and more about the [data](https://www.start.umd.edu/gtd/), it's collection methodology, definitions, and coding schema can be found [here](https://start.umd.edu/gtd/downloads/Codebook.pdf).
  - Here I tried to find out Is the definiton of Terrorism is relevant to this data? I tried to gain understanding of how terrorism spread across globe, it's relevant details, though knowing philosophical thought behind these incident would not be possible without domain expertise.
  - This project has also been converted to [Dashboard](https://terrorismglobal.herokuapp.com/) for users to interact and compare the results and it's repository can be found [here](https://github.com/matsujju/Global-Terrorism-Dashboard) for more details.
  
## Data Set Information -
  * Geography: Worldwide
  * Time period: 1970-2017, except 1993
  * Unit of analysis: Attacks and Casualities
  * Variables: >100 variables on location, tactics, perpetrators, targets, and outcomes but used around <ins>30 parameters as most of them has more than *80% missing values*</ins>.
  * Sources: Unclassified media articles (<ins>Note: Please interpret changes over time with caution. Global patterns are driven by diverse trends in particular regions, and data collection is influenced by fluctuations in access to media coverage over both time and place.</ins>)
  
## Some Explortory Data Analysis Results -
  - Most affected Countries:
    ![Image](https://github.com/matsujju/Global-Terrorism-EDA/blob/master/images/Most%20Affected%20countries.png)
   
  - Ratio of Terror Attacks and People Killed:
    ![Image](https://github.com/matsujju/Global-Terrorism-EDA/blob/master/images/Attack%20Vs%20killed.png)
    
  - How the casualities look over the Map of Iraq?
    ![Image](https://github.com/matsujju/Global-Terrorism-EDA/blob/master/images/Satellite%20overview%20of%20Iraq.png)
  
  - More Details about Iraq:
    ![Image](https://github.com/matsujju/Global-Terrorism-EDA/blob/master/images/Country%20Analysis%20of%20Iraq.png)
    
  - How different Regions are affected over the years?
    ![Image](https://github.com/matsujju/Global-Terrorism-EDA/blob/master/images/How%20Regions%20are%20affected.png)
    
  - Weapons used in different regions:
    ![Image](https://github.com/matsujju/Global-Terrorism-EDA/blob/master/images/Weapons%20used%20in%20Regions.png)
    
  - Word Cloud for Motivation behind these Attacks:
    ![Image](https://github.com/matsujju/Global-Terrorism-EDA/blob/master/images/terror_word_cloud.png)

## Libraries used -
  - [Pandas](https://pandas.pydata.org/) : Used for exploring and manipulating dataset
  - [Numpy](https://numpy.org/doc/stable/reference/index.html) : Working with arrays
  - [Seaborn](https://seaborn.pydata.org/) and [Matplotlib](https://matplotlib.org/) : Visualization library for plotting graphs (2-D static plots)
  - [Plotly](https://plotly.com/python/) : Interactive visualization library for Graphs 
 

