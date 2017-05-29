#Pikes Peak Marathon 

## Data Visualization With Tableau

<h3>An exploration of age and running potential at the Pike's Peak Marathon</h3>



<h2 id="Summary"> Summary </h2>
<p> The data I chose came from race participant information from the Pike's Peak Marathon.  The data consists of year, runner name, age, ascent time and descent time.  The data was scraped from the various results pages on  <a href="http://www.pikespeakmarathon.org">http://www.pikespeakmarathon.org</a> and then cleaned and manipulated using Python in a Jupyter Notebook (<a href="./PP_Webscrape.html">html </a>, <a href="./PP_Webscrape.ipynb">ipynb</a>).   </p>

<h2 id="Design_Feedback"> Design / Feedback</h2>
<p> 	Initially I was considering how the age group average finish times varied by year using a simple line plot conditioned on year. So I made a simple plot of age group and average finish time.  The color was conditioned on year so that a chronological progression could be seen by the reader.  (see: <a href="https://public.tableau.com/profile/art3000#!/vizhome/PikesPeak/Sheet2">Initial Visualization</a>)  The feedback I received was that the plot was confusing as there were so many years displayed at once and the intended goal of showing how age and finish time changed over the years was lost in the plot.  </p>

<p>
For an initial Tableau story board I added several plots and controls that would help to clarify the intent of the displays to the reader.  A scatterplot of median age vs median finish time shows a clear trend in the data and allows the user to select a data point to filter the remaining plots by year.  Furthermore, it was brainstormed that the use of average finish time might not be the best way to measure the potential ability of a generic person of a certain age.  Thus a plot of min finish time for each age group was added to the dashboard in an attempt to capture how potential changes with age.  Also included is an important plot that allows the user to see how the age distribution of runners varies over the years. See the initial visualization at <a href="https://public.tableau.com/profile/art3000#!/vizhome/PikesPeakMarathonStoryBoard/PikesPeakStory">initial version</a>.</p>


<p>
The feedback I received on this iteration included several suggestions for improvements.  The age distribution should be a histogram not a bar chart which was quickly changed.  Also, on the same chart, the dynamic scaling of the axis made it hard for the reader to use position to see how the distribution shape was changing. Position, being a high factor in understanding relations, was crucial to allow the reader to easily see the changing distribution of ages.  The axis were both set statically and an improvement is quickly noted.

What was also noted in conversation was that the dashboard was too crowded.  Agreeing with the observation, I removed the least helpful /most redundant plot and reduced the dashboard to just the key visualizations.  Furthermore, in discussion, and wondering if there were other factors that could be leading to the increase in median finish times besides increasing median age, a break down of median finish time by age group over the years was created.  And, interestingly enough, the observation can then be made that even within each age group, the median times generally increase over time from 1976 to 2016.  See the final version at <a href ="https://public.tableau.com/profile/publish/PikesPeakMarathonStoryBoard_v2/PikesPeakStory#!/publish-confirm">Final Story</a>.
</p>

<p>
I am quite pleased with this data exploration and story. It highlights two main factors that I have also noted in the running community: running marathons and beyond has gained popularity in the main stream and casual athletes, and a notable increase the the number of older runners among the masters groups and beyond.  Even at one of the most difficult marathons that can be run, these trends are still present.

</p>
<h2 id="Resources"> Resources </h2>

<a href="http://www.pikespeakmarathon.org">http://www.pikespeakmarathon.org</a> 

<h2 id="DataFiles">Data Files</h2>


Data File: <a href="all_data.csv">all_data.csv</a>

Python Code: <a href="./PP_Webscrape.html">html </a>, <a href="./PP_Webscrape.ipynb">ipynb</a>



