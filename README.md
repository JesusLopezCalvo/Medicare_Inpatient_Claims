# Medicare_Inpatient_Claims

A summary of calendar year Medicare inpatient hospital fee-for-service claims data.

![image of CMS](https://www.aha.org/sites/default/files/styles/900x400/public/2019-12/CMSlogo.jpg?itok=i_M4u9Qc)
Mcostello_drupal. (2022). American Hospital Association. AHA News.

## **Purpose of this project**

* Analyze Medicare inpatient hospital fee-for-service claims from the state of Kentucky
* Create a spatial visualization of Medicare providers based on the zip code of their Medicare CCN number
* Create different graphs to visualize what areas within the state of Kentucky consume more Medicare monetary resources 

## **Tools used**
* I used the following Python libraries:
    * Pandas - To create dataframes and manipulate the data
    * Matplotlib - To create graphs and visualizations
    * Plotly - To create an interactive map 

## **Features used**
* **Import and read data**
    * I used pandas.read_excel to read in data from two different local excel file
    * One xls file provided the data set for Medicare inpatient claims
    * The other xlsx file provided the latitudes and longitudes of each zip code of Kentucky
* **Manipulation and cleaning of the data**
    * I used built-in pandas to manipulate and clean data from the dataframes.
    * I removed all the columns from the dataframes that I did not need for this project 
    * I merged different dataframes to create a new one with information regarding the latitudes and longitudes coordinates of the different zip codes of the state of Kentucky
* **Analysis and visualization of the data**
    * I used Plotly library to create spatial visualizations of the different zip codes
    * I merged and created new dataframes incorporating additional information to provide the spatial visualizations
* **Best practices**
    * I created a virtual environment
    * I added a README file with instructions of how setup the project
    * I added a requirements.txt with all the needed libraries to run this project
* **Interpretation of the data**
    * I used Markdown cells in the Jupyter Lab notebook explaining the process and code interpretation of the data’s output

## **Resources used for Data sets**

* [Fee-for-Service Claims](https://data.cms.gov/provider-summary-by-type-of-service/medicare-inpatient-hospitals/hospital-service-area)
* [US zip codes' latitudes and longitudes](https://simplemaps.com/data/us-zips)


## **Setup**

* **Requirements**
    * Git Bash
        * To clone the project
        * [Git Bash Link](https://git-scm.com/downloads)
    * Anaconda Navigator
        * This project is run using Anaconda
        * Other GUI or editors can be used instead
        * [Anaconda Link](https://www.anaconda.com/)

* **Clone the project**
    * Open Git Bash
    * Clone the project in the desired folder by typing:
        * Git clone https://github.com/JesusLopezCalvo/Medicare_Inpatient_Claims.git
    
* **Create a virtual environment**
    * Open Anaconda Navigator
    * Launch CMD.exe Prompt
    * Select the path directory where the project is installed
    * Create a virtual environment by typing:
        * conda env create -f environment.yml
    * Activate virtual environment by typing:
        * Activate Medicare
        
* **Run the notebook**
    * Launch jupyter lab
        * With the virtual environment activated launch jupyter lab
        * Type in the prompt "jupyter lab"
    * A web browser will automatically open with jupyter lab
        * Open Medicare.ipynb in the file explorer
        * Run the project by clickin on the double arrow (Restart Kernerl and Run all cells)


## Badges 
### 1. GitHub Stats
![Your Repository's Stats](https://github-readme-stats.vercel.app/api?username=JesusLopezCalvo&show_icons=true)
### 2. Most Used Languages
![Your Repository's Stats](https://github-readme-stats.vercel.app/api/top-langs/?username=JesusLopezCalvo&theme=blue-green)
### 3. Contributors Badge
![Your Repository's Stats](https://contrib.rocks/image?repo=JesusLopezCalvo/Medicare_Inpatient_Claims)
### 4. Random Joke Generator
![Jokes Card](https://readme-jokes.vercel.app/api)
### 5. Profile View Counter
![Profile View Counter](https://komarev.com/ghpvc/?username=JesusLopezCalvo)