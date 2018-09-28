# DSP1


Unit 5.2: JSON exercise

Exercice:


You can find the dataset @world_bank_projects.json and the questions/instructions @sliderule_dsi_json_exercise.ipynb


Solution:


My solution was updated @sliderule_dsi_json_solution.ipynb


Section: 

Data Wrangling

Questions:

Using data in file 'data/world_bank_projects.json' and the techniques demonstrated above,
1. Find the 10 countries with most projects
2. Find the top 10 major project themes (using column 'mjtheme_namecode')
3. In 2. above you will notice that some entries have only the code and the name is missing. Create a dataframe with the missing names filled in.

Tips:

1. 

1.1 Load the Json file into a Pandas DataFrame

1.2 Select relevent columns from the DataFrame 

1.3 Use value_counts to answer the question



2. 

2.1 Load the column 'mjtheme_namecode' into a Pandas Series 

2.2 Create an empty DataFrame that will contain each row of the Pandas Series 

2.3 Use value_counts to answer the question



3. 

3.1 Create two separate Pandas DataFrames (one for the missing data and one for the non-missing data)
