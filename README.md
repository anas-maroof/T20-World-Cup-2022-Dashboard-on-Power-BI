# T20-World-Cup-2022-Dashboard-on-Power-BI

# Overview 
This project showcases a comprehensive Power BI dashboard for the T20 World Cup 2022, offering in-depth player analyses across five distinct categories. Each category encompasses a top 5 player selection based on specific conditions, accompanied by detailed visualizations and interactive features.

# Dashboard Categories



# Power Hitter/Opener: 
* Conditions: 
          Batting average > 30, Strike rate > 140, Boundary % > 50%.
* Visualizations: 
          Line charts for batting average, strike rate, average balls faced, boundary % vs. days, and a scatter plot of               strike rate vs. batting average.


          
# Anchors/Middle Order:
* Conditions: 
          Batting average > 40, Strike rate > 125, Average balls faced > 20.
* Visualizations: 
          Line charts for batting average, strike rate, average balls faced, boundary % vs. days, and a scatter plot of               strike rate vs. batting average.



          
# Finisher:
* Conditions: 
          Batting average > 25, Strike rate > 135, Average balls faced > 13.
* Visualizations: 
          Line charts for batting average, strike rate, average balls faced, boundary % vs. days, and a scatter plot of               strike rate vs. batting average.



          
# All Rounder:
* Conditions: 
          Batting average > 15, Strike rate > 140, Economy < 7, Bowling strike rate < 20.
* Visualizations: 
          Line charts for batting average, strike rate, economy, bowling strike rate vs. days, and a scatter plot of                  economy vs. bowling strike rate.




          
# Fast Bowler:
* Conditions: 
          Bowling average < 20, Economy < 7, Dot ball % > 40%.
* Visualizations: 
          Line charts for bowling average, bowling strike rate, economy, dot balls % vs. days, and a scatter plot of                  economy vs. bowling strike rate.
          
# Player Selection Dashboard
* Select your final 11 players via checkboxes, with all player names available.
* Player profiles with images and detailed batting/bowling statistics appear on hover.


# Project Development Steps
* Data Scraping:
      Utilized JavaScript logic on Bright Data Site to scrape data from ESPNcricinfo, obtaining a JSON format.
  
* Data Preprocessing:
      Converted JSON to CSV using pandas and Python.  
      Performed data preprocessing, including removing unwanted columns, adding match ID columns for data linkage, and            converting text columns to numeric.
  
* Power BI Visualization:
      Leveraged Power BI to create visualizations.
      Implemented key measures such as batting and bowling strike rates, and economy calculations.

  
# Usage
* Clone the repository to your local machine.
* Open the Power BI project file to explore the T20 World Cup 2022 dashboard.

  
Feel free to contribute, provide feedback, or customize the dashboard to suit your needs. Enjoy exploring the exciting world of T20 cricket through data visualization!
