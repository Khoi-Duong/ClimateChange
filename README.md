# Project Overview
For this project, you will work  to solve, analyze, or visualize a problem using machine learning (ML) with the other technologies  learned. Here are the specific requirements:

1. Find a problem worth solving, analyzing, or visualizing.

2. Use machine learning (ML) with the technologies we’ve learned.

3. You must use Scikit-learn and/or another machine learning library.

4. Your project must be powered by a dataset with at least 100 records.

5. You must use at least two of the following:
    * Python Pandas
    * Python Matplotlib
    * HTML/CSS/Bootstrap
    * JavaScript Plotly
    * JavaScript Leaflet
    * SQL Database
    * MongoDB Database
    * Google Cloud SQL
    * Amazon AWS
    * Tableau

For this project, you can focus your efforts within a specific industry, as detailed in the following examples.

### Finance
* Create an algorithm that analyzes credit scores and predicts consumer personal-loan eligibility.

* Using natural language processing, create a chatbot to perform simple tasks and help users find information.

* Train an algorithm to analyze consumer spending and predict trends.

* Train an image classifier to assess property value, which could then be used to calculate insurance quotes.

### Healthcare
* Train an algorithm to recognize disease symptoms and predict if a patient is at risk.

* Train an image classifier to recognize anomalies, such as suspicious vs healthy areas of skin.

* Using natural language processing, create a chatbot that will help connect patients with doctors.

* Create an algorithm to analyze patient history and predict the likelihood of inherited illness.

### Custom
We’ve only specified healthcare and finance, but any industry can benefit from machine learning. Consider preparing a 15-minute data deep dive or infrastructure review that shows machine learning in the context of what we’ve already learned.

* Create a front-end interface that maps to an API to “smarten” the algorithm.

* Perform a deep dive on existing data using machine learning.

* Create a visualization that continues to learn where clusters lie based on ML (use Leaflet or Plotly to change the visualization).

* Create an idea using mock data, and simulate how machine learning might be used.

* Create an analysis of existing data to make a prediction, classification, or regression.

### Considerations
* Remember to closely monitor any AWS resources that you choose to use. It’s crucial that you clean up and stop, or shut down any AWS resources to avoid accruing additional costs.

    * AWS Billing Guide (https://static.bc-edx.com/data/dl-1-2/m23/supplemental/AWS_check_billing.pdf)

### Project Proposal
Before you start writing any code, your group should outline the scope and purpose of your project. This will help provide direction and safeguard against **scope creep** (the tendency for projects to become more complex after work begins).

The proposal is essentially a brief summary of your interests and intent. Be sure to include the following details:

* The kind of data you’d like to work with and the field you’re interested in (finance, healthcare surveys, etc.)

* The questions you’ll ask of the data

* Possible source for the data

Use the following example for guidance:

The aim of our project is to uncover patterns in credit card fraud. We’ll examine relationships between transaction types and location, purchase prices and times of day, purchase trends over the course of a year, and other related relationships derived from the data.

### Finding Data
Once your group has written a proposal, it’s time to start searching for data. We recommend the following curated sources of high-quality data:

* data.world (https://www.data.world/)

* Kaggle (https://www.kaggle.com/)

* Data.gov (https://www.data.gov/)

* Awesome Public Datasets (https://github.com/awesomedata/awesome-public-datasets)

* Public-APIs (https://github.com/n0shake/Public-APIs)

* Awesome API (https://github.com/Kikobeats/awesome-api)

* Medium API List (https://benjamin-libor.medium.com/a-curated-collection-of-over-150-apis-to-build-great-products-fdcfa0f361bc)


**IMPORTANT:**

Whenever you use a dataset or create a new dataset based on other sources (such as existing datasets or information scraped from websites), make sure to use the following guidelines:

1. Check for copyright protections, and make sure that the way you plan to use this dataset is within the bounds of fair use.

2. Document how you intend to use this dataset now and in the future. Find any licenses or terms of use associated with the dataset, and review them to confirm that your intended use is in compliance.

3. Investigate how the dataset was collected. Identify any indicators that the data was obtained from a source that the compilers were not authorized to access.

You’ll likely have to adjust your project plan as you explore the available data. That’s okay! This is all part of the process. Just make sure that everyone in the group is aligned on the project’s goals as you make changes.

Make sure that your datasets are not too large for your personal computer. Big datasets are difficult to manage locally, so consider using data subsets or different datasets altogether.

### Data Cleanup and Analysis
Now that you’ve picked your data, it’s time to tackle development and analysis. This is where the fun starts!

The analysis process can be broken into two broad phases: (1) exploration and cleanup, and (2) analysis.

As you’ve learned, you’ll need to explore, clean, and reformat your data before you can begin answering your research questions. We recommend keeping track of these exploration and cleanup steps in a dedicated Jupyter notebook to keep you organized and make it easier to present your work later.

After you’ve cleaned your data and are ready to start crunching numbers, you should track your work in a Jupyter notebook dedicated specifically to analysis. We recommend focusing your analysis on multiple techniques, such as aggregation, correlation, comparison, summary statistics, sentiment analysis, and time-series analysis. Don’t forget to include plots during both the exploration and analysis phases. Creating plots along the way can reveal insights and interesting trends in the data that you might not notice.

# Climate Change
1. Project Title: 
* Machine Learning To Predict Annual CO2 Emissions

2. Project Description/Outline:
* According to the Paris Climate Agreement of 2015, the global goal is to limit the overall increase in global temperature by 1.5℃ or less from the average prior to pre-industrial times. Determining how to calculate the starting temperature is controversial, but for the sake of argument, we took the average temperature in our dataset for 1850, which was around 14.87℃ or 58.76℉. An increase of 1.5℃ would be 16.37℃ or 61.47℉.

3. Research Questions to Answer
* When will the temperature rise to a dangerous level of 16.37 𝇈C /61.47𝇈F?
* When will Earth reach the concerning temperature?

4. Datasets to Be Used 
* Data Sources:

      * https://www.kaggle.com/berkeleyearth/climate-change-earth-surface-temperature-data#GlobalTemperatures.csv

      * https://sealevel.nasa.gov/understanding-sea-level/key-indicators/global-mean-sea-level/

      * https://population.un.org/wpp/Download/Files/1_Indicators%20(Standard)/EXCEL_FILES/1_Population/WPP2019_POP_F01_1_TOTAL_POPULATION_BOTH_SEXES.xlsx

      * https://ourworldindata.org/grapher/co-emissions-per-capita?tab=chart&country=AUS+CAN+USA+OWID_WRL

      * https://ourworldindata.org/co2-and-other-greenhouse-gas-emissions

5. Rough Breakdown of Tasks 
* Compared data on temperature, sea level, CO2 emissions, and population from 1993-2015. 
* Create analysis explaining trends of population, CO2 emissions, temperature, and global mean sea level. 
* Leverage machine learning to create a forecast.
* Used sklearn and Prophet along with visualizations.

