#Pikes Peak Marathon 

## Data Visualization With Tableau

<h3>An exploration of age and running potential at the Pike's Peak Marathon</h3>

<a href="https://public.tableau.com/profile/publish/PikesPeakMarathonStoryBoard/PikesPeakStory#!/publish-confirm"> Final Version: Tableau Public Story Board</a>


<h2 id="Summary"> Summary </h2>
The data I chose comes from race participant information from the Pike's Peak Marathon.  The data consists of year, runner name, age, ascent time and descent time.  The data was scraped from the various results pages on  <a href="http://www.pikespeakmarathon.org">http://www.pikespeakmarathon.org</a> and then cleaned and manipulated using Python in a Jupyter Notebook (<a href="./PP_Wrangling.html">html </a>, <a href="./PP_Wrangling.ipynb">ipynb</a>).   

<h2 id="Design_Feedback"> Design / Feedback</h2>
Initially I was considering how the age group average finish times varied by year using a simple line plot conditioned on year. (see: <a href="https://public.tableau.com/profile/art3000#!/vizhome/PikesPeak/Sheet2">Initial Visualization</a>)  The feedback I received was that the plot was confusing as there were so many years displayed at once and the intended goal of showing how age and finish time changed over the years was lost in the plot.  
	
I added several plots and controls that would help to clarify the intent of the displays to the reader.  A scatterplot of median age vs median finish time shows a clear trend in the data and allows the user to select a data point to filter the remaining plots by year.  Furthermore, it was brainstormed that the use of average finish time might not be the best way to measure the potential ability of a generic person of a certain age.  Thus a plot of min finish time for each age group was added to the dashboard in an attempt to capture how potential changes with age.  Also included is an important plot that allows the user to see how the age distribution of runners varies over the years.

<h2 id="Resources"> Resources </h2>

<a href="http://www.pikespeakmarathon.org">http://www.pikespeakmarathon.org</a> 

<h2 id="DataFiles">Data Files</h2>


Data File: <a href="all_data.csv">all_data.csv</a>

Python Code: <a href="./PP_Wrangling.html">html </a>, <a href="./PP_Wrangling.ipynb">ipynb</a>



