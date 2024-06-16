Tech Used: Jupyter Notebook, Python, MatPlotLib, Pandas, BeautifulSoup, Splinter

Credits:
- Xpert Learning Assistant was used to identify code needed to extract data from all cells rather than only the first cell of a row - row_data = [cell.text for cell in row.find_all('td')]
- Worked with AskBCS Learning Assistant, Deborah Aina, to identify error with MatPlotLib. Error could not be resolved so I used Pands plot instead.

Data Analysis:

1) How many months exist on Mars?
2) How many Martian (and not Earth) days worth of data exist in the scraped dataset?
3) What are the coldest and the warmest months on Mars (at the location of Curiosity)? To answer this question:
4) Find the average the minimum daily temperature for all of the months.
5) Plot the results as a bar chart.
Which months have the lowest and the highest atmospheric pressure on Mars? To answer this question:
Find the average the daily atmospheric pressure of all the months.
Plot the results as a bar chart.
About how many terrestrial (Earth) days exist in a Martian year? To answer this question:
Consider how many days elapse on Earth in the time that Mars circles the Sun once.
Visually estimate the result by plotting the daily minimum temperature.