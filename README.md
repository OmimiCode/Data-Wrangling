# Data-Wrangling :: EU Road Safety Facts and Figure (Web Scrapping)
An Open Project containing python script to get normalized CSV data file of Road Safety Facts and Figures in the EU via web scrapping

Click this https://hackmd.io/@datopian/junior-software-engineer-challenge to access project overview.
>> You can also access the Wikipedia documentation on the subject [here](https://en.wikipedia.org/wiki/Road_safety_in_Europe)

           
# Preparation
You will need 
  1. `Python 3.6` or `greater`, 
  2. a `virtual environment`
  3. the underlisted `library` or `packages` to run the python script script (*all of which can be found in the requirement.txt file in the project directory.*)
> #### beautifulsoup4 == 4.10.0  || run "pip install beautifulsoup4"
> #### pip install pandas || run "pandas == 1.4.1"
> #### pip install requests || run "requests == 2.27.1"
> #### pip install lxml || run "lxml == 4.8.0"
> #### pip install matplotlib || run "matplotlib === 3.5.1 "


# Project Structure
```
Data-Wrangling:
├───alt_code:
|   └───Data_Wrangling_Challenge_.ipynb
├───data:
|   └───EU_ROAD_SAFETY_data_curated.csv
├───datapackage.json
├───data_dir_test:
|   └───EU_ROAD_SAFETY_data_curated.csv
├───LICENSE
├───README.md
├───requirements.txt
├───script.py
├───venv:
└───visual_plots_test:
    └───EU_Road-Death-Rate.jpg
```


## Run the script
``python Data-Wrangling/script.py``

# Results and Visualization

Having nornamlized and pre-processed the dataset by the python script, The data was sorted by “Road deaths per Million Inhabitants” column.
Consequently, a bar chart was generated to get visual cue about the Road death per million inhabitant against the Country. 
`See image below : `

![bar cart](https://github.com/OmimiCode/Data-Wrangling/blob/main/visual_plots_test/EU_Road%20Death%20Rate.jpg)

## Deduced statistics
    ```
    ### 5 Lowest Road deaths per Million Inhabitants by Country
    
    United Kingdom::28
    Denmark::30
    Netherlands::31
    Ireland::31
    Sweden::32
    
    ```
   ### it can be deduced from this class that `United Kingdom` has the `lowest` Road deaths per Million Inhabitants of `28`
   
       ```
    ### 5 Highest Road deaths per Million Inhabitants by Country
    
    Poland::76
    Croatia::77
    Latvia::78
    Bulgaria::88
    Romania::96
    ```
   ### it can be deduced from this class that `Romania` has the `Highest` Road deaths per Million Inhabitants of `96`
   
   

## Author
![avatar](https://avatars.githubusercontent.com/u/69190825?s=400&u=0153b80ec358c574751303b63e6e8e3753e44e34&v=4)

#### Name: Barnabas Oretan 
#### Title: Software Engineer
#### Email: barnabas.oretan@gmail.com
#### Url: [github.com/omimiCode](http://www.github.com/omimiCode) 

## TODO

```
Secure the job and upadate project
Consider more meanmingful data interpretation
License instead of MIT 
```
