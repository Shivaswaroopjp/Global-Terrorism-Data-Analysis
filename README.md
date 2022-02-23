# Global-Terrorism-Data-Analysis

## About the dataset:
The Global Terrorism Database (GTD) is an open-source database including information on terrorist attacks around the world from 1970 through 2017. The GTD includes systematic data on domestic as well as international terrorist incidents that have occurred during this time period and now includes more than 180,000 attacks. The database is maintained by researchers at the National Consortium for the Study of Terrorism and Responses to Terrorism (START)

## Execution: 

For the First step, the data is imported from a csv file and converted to a  panda’s DataFrame . Pandas is inbuilt library in python that is used in handling and manipulating Dataframes. Dataframe is basically collection of Rows and Columns. 


Consequently, the Data is trimmed of all the columns that contain either null values or which are irrelevant to our analysis. 
Once the data is clean, we check for the statistics of the cleaned data. The statistics of the data tells us the mean, median and the distribution of the data and some more info. 

## Visualizations: 

After the data is cleaned, Visualizations can be done on the data and inferences can be done from the visualizations. 
One such visualization is to find which year has the most number of terrorist attacks, and we find out that 2014 was the year where most of the number attacks with over 20,000 attacks that year. 


Another such visualizations is to find out that the top 5 countries that were attacked most and we find out that Iraq, Pakistan, Afghanistan, India and Columbia are the top 5 attacked countries with almost 25000 attacks in Iraq.


Similarly, we can plot the frequency of attacks according to their months and found that there is no correlation or relation in between the months and attacks. 
Also, we plotted the equipment’s that were most used by the Terrorists in their attacks and found that Bombing/Explosion was the most used weapon/Equipment in the attacks.
At last, by plotting the various targets on which the terrorist attack, we find that Private People and private property are the most attacked targets which was obvious as they are unarmed and most susceptible and last on their targets is Hijacking/Kidnapping. 

## Conclusion:

In the end, It was a good Experience working on the terrorist Data, But one downside with exploring these datasets is, the reason why these attacks happen are mostly political and neither can be explained nor be predicted by the most of Machine learning Algorithms but to some extent can certainly be used to reduce the number of attacks happening.


### Credits and References: 
  1. https://www.start.umd.edu/gtd/
