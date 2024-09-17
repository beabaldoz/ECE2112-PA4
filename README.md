# ECE2112-PA4
# September 17, 2024

## import pandas as pd 
## boards = pd.read_csv('board2.csv') - to read the given csv file.
## matplotlib.pyplot - to be used for the graphs.

# PROBLEM 1 #
## Create the following data frames based on the format provided:
### Example: Vis = [“Name”, “Gender”, “Track”, “Math<70”]; hometown is constant as Visayas
### a. Filename: Instru = [“Name”, “GEAS”, “Electronics >70”]; where track is constant as Instrumentation and hometown Luzon
## To get certain elements from the given data, I used the function .loc.

### b. Filename: Mindy = [ “Name”, “Track”, “Electronics”, “Average >=55”]; where hometown is constant as Mindanao and gender Female
## Since this problem requires the average, I first got the average of the students in their subjects.
## I then used .loc function to locate the elements that is being asked for this problem.

# PROBLEM 2#
## Create a visualization that shows how the different features contributes to average grade. Does chosen track in college, gender, or hometown contributes to a higher average score?
## In this problem, I used different graphs for the visualization to show the different features that somehow affects the average grades of the students.
## In the first graph, I experimented with the boxplot graph. I used this graph to show how the 'Track' of the students affects their average.
## In the second and third graphs, I used bar graphs because it is easier to understand and easier to code as well. In these bar graphs, I showed how the Hometown and Gender of a student affects their average. 
