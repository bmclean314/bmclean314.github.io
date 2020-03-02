#Assignment 4 - Remix

For this assignment, I chose to remix a visualization that I used for my week 7 reflection. The original visualization is shown here:

![origvis](img/<origvis.>)

The vis uses a bar and pie chart to show the most common causes of accidental death in England and Wales in 2008.
The original creater of the vis used Microsoft Excel and photoshop to make it. I thought it would be interesting to remix this vis
and make it interactive so you could easily see what categories of the pie chart match to the bars of the bar chart. My remix is shown below: 

![myvis](img/<myvis.>)

I changed the vis so when you mouseover a slice of the pie chart, all the bars of the bar chart belonging to that category get highlighted.
I also did it the other way around, so when the user hovers over a bar, the corresponding slice highlights. 

I included 3 CSV/xlsx files in this assignment. Mortality,England&Wales.xlsx is the original data set. The file contains multiple
sheets of information, but I specifically used the 2008 data from the "Accidents and Others" sheet. To make it easier to read the file
in with d3, I put the accident name, total deaths per accident, and accident type into a csv called accidentdeaths.csv to create the 
bar chart. To make the pie chart, I put the accident type along with the total deaths per accident type in another csv called typetotals.csv.

#Design Achievements
I chose to change the colors that the original vis used. For my vis, I chose colors from the d3.schemeTableau10 color scheme. 
I know these colors were specially chosen to be effective in portraying categorical data, as I do in my visualization. For this reason,
I chose these colors for my vis. 

#Technical Achievements
For this assignment, I decided to make my vis interactive by highlighting elements that the user hovers over with their mouse. The visuals
are linked so highlighting elements of one chart will highlight other elements of the other chart. 
