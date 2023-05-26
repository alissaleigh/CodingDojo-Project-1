# Food Sales Predictions
## An Analyzation of Our Existing Sales To Help Predict Our Future

**Alissa Butler**: 

### Business problem:

When it comes to sales it's imporant to know what is more or less likely to sale, so that we can ensure the most bang for our buck


### Data:
Data source : https://docs.google.com/spreadsheets/d/1IDsDWMeUS4JZrwIVfoO-yRPmHxd9uVKtIjzjBo9vOfM/edit?usp=sharing

The above data goes over the sales for out diffrent stoes and the diffrent asspects of a prodcut might effect it's ablity to sale


## Methods
- We did a data clean to ensure we the data could be worked with and was consistant
- We also created a hisagraph and a heatmap to look at the corelations

## Results

#### The Item Types to The Total Number of Sales
![download](https://user-images.githubusercontent.com/118623787/224366814-1fb67c25-ca78-4d60-85c4-2928f862f41d.png)
> The above boxplot shows the volume of each item type that as sold. It lets us know what item types we're overal selling the most

#### Sales Based On Outlet Opening Year
![download](https://user-images.githubusercontent.com/118623787/224367703-86838924-91c1-4118-8a5b-3f7ceeeb1113.png)
>The above graft shows how the opening year of a store can effect slaes 

## Models Evaluated & Results
When we ran the data through macine learning and a couple of modles, here are the results

-Linear Regression Model (Testing Set):

Model Training RMSE: 1208.2986676127668;
Model Testing RMSE: 1162.7949404772457

Model Training R2: 0.5066708827837141;
Model Testing R2 0.5104451944264382

-Tree Regressor Model (Testing Set):

Model Training RMSE: 1082.6553744791681;
Model Testing RMSE: 1057.4530115283153

Model Training R2: 0.6039330279227338;
Model Testing R2 0.595560043215285

## Linear Regression Coefficients
![download](https://github.com/alissaleigh/food-sales-predictions/assets/118623787/3e7eeae6-bce3-4ff6-8c2e-3c1e21cf5615)
>Looking at the data we can see that the type of Outlet has some of the bigest impacts within our data

## Important Features
![download](https://github.com/alissaleigh/food-sales-predictions/assets/118623787/3f3223a8-c015-4fc2-bfd3-381b222f51c7)
>Looking at our features the fat content seems to be one of the best features as well as the item type of each sold item.

## A Summary Dot-Plot 
![download](https://github.com/alissaleigh/food-sales-predictions/assets/118623787/9bc86d5b-23f6-457a-ba15-b946d451108d)
>Looking at the dot summary we can see that the item MRP has the highest impact on our modle

## Examing Two Rows To Compare Data

Both rows that where chosen was due to them being diffrent Outlet Types and have very diffrent MRP

### Row 28
![image](https://github.com/alissaleigh/food-sales-predictions/assets/118623787/6d6b235f-27fa-4c22-b5e7-33aa35e7dace)
![image](https://github.com/alissaleigh/food-sales-predictions/assets/118623787/524e2ef3-b367-4ea6-ae72-65fe6be9b6e7)
>Looking at the dot summary we can see that the item MRP has the highest impact on our modle

### Row 70
![image](https://github.com/alissaleigh/food-sales-predictions/assets/118623787/89e714c8-3309-419b-b9c8-bf49e2b5f5bd)
![image](https://github.com/alissaleigh/food-sales-predictions/assets/118623787/175f182c-8705-4fe5-b319-ee77713664ac)
>Looking at the dot summary we can see that the item MRP has the highest impact on our modle

### For further information

For any additional questions, please contact alissaleigh19@gmail.com
