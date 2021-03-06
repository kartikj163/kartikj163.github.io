<h1> Final Project </h1>

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/kartikj163/kartikj163.github.io/master?labpath=Jadhav-Kartik-Final-Project-Part2.ipynb)
<h2> TITLE: Public opinions and perspectives on Global Warming. </h2>
<h2> AUTHOR: KARTIK JADHAV </h2> 

<h3>MOTIVATION:</h3>
Many people feel that global warming is a hoax and that it is not a major problem. We need to educate people about global warming in order to have a meaningful impact on it.

<h3>DATA SOURCE:</h3>
1. Data from a survey conducted by Yale University on global warming at the state and county levels. https://climatecommunication.yale.edu/ , SIZE = (4563, 64) . As mentioned on the link provided above this dataset can be utilized solely for - research, scholarly or academic purposes.
<br />2. County level Election data: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/VOQCHQ , size = (31578, 13) . This is the community of Harvard and worldwide researchers who share data in the Harvard Dataverse Repository, and is an open source, that allows other users free access to the data and utilize the same to derive some meaningful insights based on their individual study / research.
<br />3. Net Generation of Electricity by State and Type of Energy Produced by Energy Source data from 1990 to 2020, which includes the type of energy source generated for each state. The dataset can be downloaded from: https://www.eia.gov/electricity/data/state/ , SIZE = (52296, 6). This datasource is given by the United States Energy Information Administration and is open to anyone who wants to conduct research on energy consumption. This is an open data source, meaning you can download, modify, and reuse it for free.
<br />4. Harvard dataverse dataset, which contains data on the number of votes each presidential candidate earned in each state from 1976 to 2020.The dataset can be downloaded from: https://dataverse.harvard.edu/dataset.xhtml?persistentId=doi:10.7910/DVN/42MVDX , SIZE = (4287, 15) . This was found on Harvard Dataverse Repository, and is an open data meaning it is available for anyone and everyone for access, modification, and reuse.

<h4> I'll be answering the following key questions through my visualizations - </h4>
1. Comparison of different states in terms of the percentage of people who oppose the idea of combating global warming in various categories.   
<br />2. Comparing several citizen viewpoints in a given state against one another to determine what percentage of people in that state oppose one viewpoint over another when it comes to addressing global warming.  
<br />3. Which were the top 10 winning Republican / Democrat states?
<br />4. Do Republican voters believe or support the idea that global warming should be a key priority for the next president and Congress, and that citizens and local governments should do more to combat it?
<br />5. What percentage of Democratic and Republican voters oppose a certain global warming viewpoint?
<br />6. Will there be an impact on actions that prioritize, address, and improve accountability for global warming if the number of Republican voters in the state rises?
<br />7. Which states are in the top N in terms of renewable energy consumption? In this case, N might be any number that the user wishes to see.
<br />8. Which Republican and Democratic states consume the most renewable energy?
<br />9. Have the republican leaning states reduced the usage of renewable resources as a percentage of their total power consumption?
<br />10. What year did most states see a major growth in the use of renewable energy, and what could be the cause of this increase?
<h4> SOME OF MY KEY VISUALIZATIONS </H4>
<h4> CONTEXTUAL VISUALIZATION 1 </H4>

![PLOT1](https://user-images.githubusercontent.com/17830967/144704306-c06154bb-2c3a-4211-bf01-fa05d68d5662.PNG)   


The map essentially depicts the aggregate value for a certain property by state. For a state with a high count, a darker tint is used. The map plot is useful for comparing values and displaying categories across regions. A bar chart depicting the comparison of the top 20 states backs up this claim. The bar chart can be used to compare values in different subsets of your data.

<h4> CONTEXTUAL VISUALIZATION 2 </H4>

![plot2](https://user-images.githubusercontent.com/17830967/144704368-4d5a2dc6-5f66-4331-9ea5-53e7a7d3b682.PNG)

Based on the graphs above, we may deduce that as the number of republican voters rises, fewer people believe that global warming should be a key priority for the next president and Congress, and that citizens and local governments should do more to combat it.

![plot3](https://user-images.githubusercontent.com/17830967/144704405-668aa865-dfb8-4001-94f1-5133d53e42f0.PNG)


As seen in the graph above, as the number of Republican voters in a county rises, it's possible that a higher percentage of poll respondents in that county reject measures that prioritize, address, and improve responsibility for global warming
<h4> CONTEXTUAL VISUALIZATION 3 </H4>
Which Republican and Democratic states consume the most renewable energy?


![plot4](https://user-images.githubusercontent.com/17830967/144704448-2cf99797-bca8-4a17-9234-5d9bb3a74b82.PNG)

<H4> CENTRAL VISUALIZATION </H4>
The states that are leading in Republican and Democratic party votes are shown on the map. The graphic allows the user to choose a state and see the trend line between different parties' votes.

![plot5](https://user-images.githubusercontent.com/17830967/144704493-1dfc61ce-1da5-4de8-9997-97045a55cf8d.PNG)

The graph below depicts how each state has fared in terms of using renewable energy to tackle the global warming crisis throughout time. After 2010, the use of renewable energy increased significantly in most states, as shown in the graph. This might be attributed to President Barack Obama's Clean Energy and Recovery Act of 2009, which has been dubbed the "biggest energy law in history."

![plot6](https://user-images.githubusercontent.com/17830967/144704561-7118b127-c6cb-4633-8ef6-312037ebaa40.PNG)

CONCLUSION:

1. Data source 1 was climate data, which included state and county-level records as well as various factors such as the percentage of locals who support or oppose the idea of combating global warming, and data source 2 was a presedential election dataset that contained information on how many votes a particular political party (democrat or republican) received, and from this I was able to deduce that the Republican party tends to oppose the idea that global warming is a problem. Finally, the study indicates that when the number of Republican voters in a county increases, it's probable that a bigger percentage of poll respondents in that county will reject initiatives that prioritize, address, and improve global warming responsibility.

2. I was able to obtain State-by-State data for the mean proportion of renewable energy used in dataset 3 (Net Generation of Electricity by State and Type of Energy Produced by Energy Source data from 1990 to 2020). From 1976 until 2020, dataset 4 (the Harvard dataverse dataset) contained data on the number of votes each presidential candidate received in each state. I wanted to see, since Republican States oppose the idea of mitigating global warming, did these states reduced their use of renewable resources as a percentage of overall electricity consumption. According to the findings of the preceding analysis, both Democrat and Republican states did equally well in adopting renewable energy to meet their complete consumption demands.

SOURCE:

https://coderzcolumn.com/tutorials/data-science/interactive-plotting-in-python-jupyter-notebook-using-bqplot
<br />https://geopandas.org/en/stable/docs/user_guide/mapping.html
<br />https://stackoverflow.com/questions/69235532/add-dropdown-button-to-plotly-express-choropleth-map
<br />https://swdevnotes.com/python/2021/interactive-charts-with-ipywidgets-matplotlib/
<br />https://www.geeksforgeeks.org/grouped-barplots-in-python-with-seaborn/
<br />https://seaborn.pydata.org/examples/index.html
<br />https://pandas.pydata.org/docs/reference/api/pandas.DataFrame.rename.html
<br />https://seaborn.pydata.org/generated/seaborn.lineplot.html
<br />https://plotly.com/python/bar-charts/
<br />https://bqplot.readthedocs.io/en/latest/_generate/bqplot.marks.Bars.html
<br />https://python-visualization.github.io/folium/quickstart.html




