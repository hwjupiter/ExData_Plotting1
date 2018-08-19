This is an updated readme file for the R scripts contained in this repository.

The scripts will plot data from a household energy consumption dataset. The load_data.R script should be run first.
This will download the dataset, unzip the folder and subset the data so that only the data between the stipulated
dates are used. The dates are from 01-02-2007 to 02-02-2007. Using a separate script to read in and tidy up the data
means this function is only performed once, instead of every time a new plot needs to be generated.

The plot1.R script generates a histogram of the global active power. The output is shown in the plot1.png file.

The plot2.R script generates a line graph of the global active power over the course of the two day period. The 
output is shown in the plot2.png file.

The plot3.R script genetes a line graph of the three sub metering readings over the course of the two day period.
The three sub metering readings are shown on the same graph. The output is shown in the plot3.png file.

The plot4.R script. generates 4 graphs in a single png file. These are replicas of the second and third plots, as 
well as a plot of the voltage over the two day period, and a plot of the global reactive power over the two day period.