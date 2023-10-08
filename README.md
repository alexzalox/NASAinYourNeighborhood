# [Top 20 countries with the highest cumulative pm2.5 from 1980 to 2022](https://www.youtube.com/watch?v=Uv0lIyd7y8w) 


# Name and Summary
## Project Name :
- A Global Ranking Observation on Cumulative PM2.5 Level

## Summary :
- We use Python to generate a bar chart race of accumulated PM2.5 in each country from 1980 to 2022. By taking reference of this data, the United Nations and NASA can enact international conventions to regulate PM2.5 emissions, which is important because the particles are smaller than a hair grain so that they can pass through the alveoli and circulate the human body via blood flow. The impact of PM2.5 on physical health and ecology systems is nontrivial.

# Project Links
## Project Demo
- https://youtu.be/Vi2HLlf15gQ

## Final Project
- https://github.com/alexzalox/NASAinYourNeighborhood


# Project Information
## Project Details
- What exactly does it do? 
    -  Observes the cumulative ranking of PM2.5 using each country’s data.

- How does it work?
   - `Top 20 countries with the highest cumulative PM2.5 from 1980 to 2022`
        - Runs Data_Processing.ipynb on Colab
        - Data processing :
            - Converts date string to datetime object
            - Creates a cumulative dataframe
            - Removes the underscores in country names
        - Removes countries that never ranked in the top 20
        - Makes a racing bar chart

- What do you hope to achieve? 
    - We hope to raise global awareness about PM2.5, which are invisible killers damaging our lungs.
    - Through this project, we call on the United Nations to pay greater attention to the issue of air pollution.


- What tools, coding languages, hardware, or software did you use to develop your project?
    - Tools:
        - github
        - colab
        - jupyter notebook
        - youtube
    - Coding languages
        - python : pandas, ipython-autotime, bar_chart_race


- What is the significance of NASA data?
    - Using the MERRA PM2.5 data from NASA GES DISC, we take a data science approach to observe the emissions of each country, and hope to provide adaptable references for international standards, and finally a positive contribution to global environment.


- What is PM2.5?
    - There are many polutions in the air, one of them is dust-like, granular substances known as particular matters (PM). PMs differ in diameters; for those smaller than 2.5 micrometers (μm) are known as PM2.5, which is measured in μg/m3.

    - PM2.5 is thinner than a hair grain, and can pass through the alveoli in our lungs and enter our blood flow. Therefore, the impact of PM2.5 on physical health and the ecology systems is nontrivial.

## Use of Artificial Intelligence
- we used [ChatGPT](https://chat.openai.com/) to write code, translate and generate technical documentation.

## Space Agency Data
- goldsmr4.gesdisc.eosdis.nasa.gov : [MERRA-2 instM_2d_gas_Nx: 2d,Monthly mean,Instantaneous,Single-Level,Assimilation,Aerosol Optical Depth Analysis 0.625 x 0.5 degree V5.12.4 (M2IMNXGAS) at GES DISC](https://search.earthdata.nasa.gov/search/granules?p=C1276812824-GES_DISC&pg[0][v]=f&pg[0][gsk]=-start_date&q=M2IMNXGAS&tl=1696671844.396!3!!)

- disc.gsfc.nasa.gov : [MERRA-2 instM_2d_gas_Nx: 2d,Monthly mean,Instantaneous,Single-Level,Assimilation,Aerosol Optical Depth Analysis V5.12.4 (M2IMNXGAS)](https://disc.gsfc.nasa.gov/datasets/M2IMNXGAS_5.12.4/summary)

- goldsmr4.gesdisc.eosdis.nasa.gov : [MERRA2.avgM_2d_pm25_admin0x.v01.19800101-20221231.csv](https://goldsmr4.gesdisc.eosdis.nasa.gov/data/MERRA2_CLIM/M2_TMAX_PM25.1/1980/MERRA2.avgM_2d_pm25_admin0x.v01.19800101-20221231.csv)


## References
- disc.gsfc.nasa.gov : [How to remotely access MERRA-2 with Python3 and calculate monthly average surface PM2.5 for world countries](https://disc.gsfc.nasa.gov/information/howto?title=How%20to%20remotely%20access%20MERRA-2%20with%20Python3%20and%20calculate%20monthly%20average%20surface%20PM2.5%20for%20world%20countries)


- goldsmr4.gesdisc.eosdis.nasa.gov : [README Document for
MERRA-2 Country-Level Surface PM2.5
Monthly Mean Products - Version 1](https://goldsmr4.gesdisc.eosdis.nasa.gov/data/MERRA2_CLIM/M2_TMAX_PM25.1/doc/README_M2PM25.pdf)

- towardsdatascience.com : [A Single Python Function Generating A Gorgeous Bar Chart Race Video](https://towardsdatascience.com/a-single-python-function-generating-a-gorgeous-bar-chart-race-video-dd6410b8aed)

- earthdata-cloud-cookbook : [Read Data
netCDF](https://nasa-openscapes.github.io/earthdata-cloud-cookbook/how-tos/read_data.html)

- haqast.org : [How To Download NASA Data](https://haqast.org/wp-content/uploads/sites/91/2018/01/How-To-Download-NASA-Data-Tutorial2.pdf)

- Youtube : [How to make a Racing Bar Chart using Python | Diazonic Labs | Useful Python Libraries](https://www.youtube.com/watch?v=HrhPnFS25OU)