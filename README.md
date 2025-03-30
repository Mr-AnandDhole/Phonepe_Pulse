# Phonepe Pulse Data Visualization and Exploration

# What is PhonePe Pulse?
The PhonePe Pulse website showcases more than 2000+ Crore transactions by consumers on an interactive map of India. With over 45% market share, PhonePe's data is representative of the country's digital payment habits. The insights on the website and in the report have been drawn from two key sources - the entirety of PhonePe's transaction data combined with merchant and customer interviews. The report is available as a free download on the PhonePe Pulse website and GitHub.

# Libraries used for the project

1. Pandas - (To Create a DataFrame with the scraped data)
2. mysql Workbench - (To store and retrieve the data)
3. json - (To load the json files)
4. git.repo.base - (To clone the GitHub repository)

# Project Workflow 

**Importing the Libraries:**

First we have to import all those libraries. If the libraries are not installed already use the below piece of code to install.
pip install + "Namee for librarie"

**Data extraction:**

Clone the Github using scripting to fetch the data from the Phonepe pulse Github repository and store it in a suitable format such as JSON. Use the below syntax to clone the phonepe github repository into your local drive.

**Data transformation:**

In this step the JSON files that are available in the folders are converted into the readeable and understandable DataFrame format by using the for loop and iterating file by file and then finally the DataFrame is created. In order to perform this step I've used os, json and pandas packages. And finally converted the dataframe into CSV file and storing in the local drive.

**Database insertion:**

To insert the datadrame into SQL first I've created a new database and tables using "mysql-connector-python" library in Python to connect to a MySQL database and insert the transformed data using SQL commands.

**Data retrieval:**

Finally if needed Using the "mysql-connector-python" library to connect to the MySQL database and fetch the data into a Pandas dataframe.




