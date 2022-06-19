# IGR204_mini_project_1
Mini-project: Baby Names

The 3 "Tableau" visualisations can be accessed by downloading the "Data_vis.twbx" file and opening it via "Tableau Desktop 2022.1.1".
The file is composed of several dashboards and sheets, organized by a color code.
  * green : the 3 dashboards, in which there are a main visualization and its associated filters
  * blue : the sheets used to generate the dashboards
  * pink : other ideas

The sketches are in the folder : https://github.com/nicolasgallay/IGR204_mini_project_1/tree/main/Sketches

Hereunder, the description of why we believe these visualisation answer the questions of the project.

## Visualization 1  
How do baby names evolve over time? Are there names that have consistently remained popular or unpopular? Are there some that have were suddenly or briefly popular or unpopular? Are there trends in time?

The first visualisation allow the user to visualise baby names popularity evolution in percentage over the years. As there are to many different names given every year, the visualisation does not allow the extraction of clear information to answer the questions. Therefore, it has been decided to had 3 filters : 
 * total_names : allows to filter on the names based of a the number of times they were given during the observed period. For example, the user can choose to observe the evolution of the names that have only been given between 20 and a 1000 times.
 * name : allows the user to highlight the evolution of a name
 * histogram : allows to visualize the evolution of the number of births but also to study names popularity evolution on specific years or periods


## Visualization 2
Is there a regional effect in the data? Are some names more popular in some regions? Are popular names generally popular across the whole country?

This visualisation is a map of France departments on which are displayed the most popular name for a given year for each department. In order to allow a deeper analysis of names popularity geographical evolution accros France and answer the questions, 3 filters have been added.
 * Year Selection : to visualize the regional effect over time. In our opinion, the questions can only be answered if the regonal effect is studied over time.
 * Gender Selector : to analyse the phenomena by gender.
 * Most pop name : to accelerate the visualization of the departments where a name is popular


## Visualization 3
Are there gender effects in the data? Does popularity of names given to both sexes evolve consistently? (Note: this data set treats sex as binary; this is a simplification that carries into this assignment but does not generally hold.)

This visualisation present the evolution of unisex and not unisex names popularity over the years and answers both questions at the same time. The user can compare the gender effect in volume and name diversity.
