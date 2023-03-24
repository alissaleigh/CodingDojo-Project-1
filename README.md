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

-Decision Tree Regressor Model (Testing Set):

Model Training RMSE: 1082.6553744791681;
Model Testing RMSE: 1057.4530115283153

Model Training R2: 0.6039330279227338;
Model Testing R2 0.595560043215285

#### Why I Think The Decision Tree Is The Better Option
When looking at the overall score I think the decision tree shows better overall results that can be brought to a stakeholder to explain why the sales are what they are. I think it looks better as well and short of know the shareholders would perfer a specific metric over another, going with the the one that looks the nicest makes the most sense to me.

### For further information


For any additional questions, please contact alissaleigh19@gmail.com
