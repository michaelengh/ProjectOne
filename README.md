# Sales Project - Preview and predictions

## This was a project made to analyze the data in order to determine steps that can be made in increase the product sales of items in store. 

Author: Michael Engh

### Business Problem:
We have recorded data of item sales for each business location and would like to analyze the data to see where they can improve certain store criterias to increase the sales of items. also included is a prediction mothod so we can test the items data to roughly predict what the sale of the item will be for that location with the changing criterias. 

### Methods:
* I created a couple charts for simplistic understanding of the used data points like the Outlet data, sales data amd item visibility within each location. 
* With looking at the data i neded to modify some datapoints with either scaling the data of one hot encoding for processing the data further. character columns needed to be changed to integers so the models could use the data for predictions
* I also took the given data to create a a couple prediction models on future item outlet sales.


### Data:
When looking at the data the items seem be be sold in more volume at the Super Market Type Three locations and I also noticed that the visibility of the item seemed to have a negative coorelation with the items sales based off the data set.
![Store Sales](https://github.com/michaelengh/ProjectOne/blob/main/salesbar.png)
![Visibility](https://github.com/michaelengh/ProjectOne/blob/main/salesvisplot.png)

### Findings/Recommendations:
Based of some of the data I would look into how the Outlet types are different and why one sells more items in total compared to the others. it appears that Supermarket Type 3 has a large boost compared to the other location on number of items sold. Also, I looked at it seems that Items visibility may have something to do with quantity of items sold, so prioritizing the visual needs of items may boost sales for the some items.

### Next Steps:
I fell that next steps would be to get more data on the stores themselves to see how each of them differ from eachother. maybe some of the options like visibilty is due to one location having more floor space then the others, or what the difference is in physical location of the sites. also maybe getting some data points on how many customers come into each store and test that against number of items sold, to see what the percentage of people coming into the store and buying items is. 
