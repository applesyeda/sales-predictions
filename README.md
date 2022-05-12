# Title that recommends an action
## Subtitle describing the analysis 

**Author**: 

### Business problem:

Here is where you state the business problem you were trying to solve


### Data:
My goal is to access a variety of variables, from fat content to outlet size, on how they may be able to predict greater sales in grocery stores. 


## Methods

I consider variables such as an item's fat content and see if that could predict sales revenue because there may be some people are are more inclined to buy foods if it is labeled as being low in fat. If I'm able to see a trend in this, I can work with other manufacturing companies as well as other grocery stores about how to market items as healthy as their consumers may be attracted to health-consious advertising.  

I also explore variables considering item size and weight because people may also be more likely to buy foods if it's easier to access or carry. Smaller items are generally more compact and easier to travel with, meaning that a packet of 10 protein bars may contribute to a greater number in sales compared to buying it in bulk. If a trend is found between item size and sales, this may also change the way products are manufactured and sold in the future. 

As I prepare to analyze the data, I make sure there are no missing variables as well as duplicate columns. I also make sure all variables are organized and the values of those variables are correct. 

## Results

I created a machine learning model to see if there were variables in my dataset that could predict sales revenue of grocery stores. My R^2 value of my training and test data was .56. This means that the model I created to make sales preductions was not "overfit," which is good news because it means that it will still be able to adjust and makes sales predictions, even with new data being added. 

However, the square-root of the average errors in the model did show that there was high variance, suggesting there could be error in those analyses, maybe even more so if new data is introduced. 

I also created a Decision Tree Regression. That also showed me that my model was overfit as my R^2 was a 1 for my training data and much smallar, .15, for my testing data. Also, the RMSE on the training data was much higher on the testing data.  

I would ultimately implement the linear regression, rather than the deciscion tree regression, because there was a better R^2 value of .56 for both of my training and testing data. This meant that it would make better predictions. 



#### Reflection: Sales Predictions and Low-fat Items 


I first created the below graph because I would like to see if there's a difference in sales between low fat items and regular items. Just by eye-balling it, the medians look about the same. There seems to be a slightly greater range (including outliers) with low fat items compared to regular. I think asssessing for this is important because if there were changes, I could investigate further if those were significant, and that may change the way retailers advertise their products. For instance, if it's found that customers tend to choose the lower fat option, retailers could advertise their lower caloried or health-consious items more to further appeal to those people and drive sales.

![download](https://user-images.githubusercontent.com/101068535/167980577-6563db81-0aba-41e2-9eba-1000b0c0fe27.png)



#### Reflection: Outlet Type and Sales 

I would also like to look into outlet types and sales. This is important because it could be that larger stores may lead to more customers with more options, resulting in a greater number of sales. It could then be effective to assess for calculations on how much a retailer invests in a store type and it's proportions to sales revenue. In the below graph, I can see Supermarket Type 3 has the highest in sales compared to all other outlet types. This may influence how future stores are developed as retailers may be better off creating and investing resources in large supermarkets, rather then grocery stores.

![download](https://user-images.githubusercontent.com/101068535/167980689-c6b6a2a2-1041-4efa-996f-c18a528cecbd.png)

#### Reflection: Outlet Type and Sales

Lastly, I have created a heat wave to assess for correlations in my data set. There are no correlations that stand out, except for a moderate correlation between Item Outlet Sales and Item MRP. This is interesting because even though correlation doesn't equal causation, this finding could inspire further research in how materials used when making an item (MRP) could be associated with sales revenue. If there are any causal findings in further research, this may change the relatioshhip retailers have with vendors as they might change the type of material they'd request or products depending on it's association to sales revenue.

![download](https://user-images.githubusercontent.com/101068535/167980854-b14eea25-6ab5-4a28-82ba-ab66e365a8aa.png)



## Recommendations:

Again, I would implement the linear regression because there was a moderate R^2 of .56 for both the training and testing data. This model was not as overfit, as opposed to the regression tree model.

I also believe further analyses should be done to see if changes in marketing, such as marketing products as health-consious or low fat, would make an impact in sales depending on geographical region. Therefore, further exploration of what different variables interact would be an interesting pursuit in the future as there may be many different variables that contribute to the sales revenue in different ways. 

## Limitations & Next Steps

My analyses was limitted to the variables in my dataset. Because location of the outlets weren't taken into account in the dataset, there is still a question of whether the findings from this dataset would be consistent across all grocery store outlets. However, this leaves more room for exploration that inspires a greater need for data collection and analyzation in the future. 


For any additional questions, please contact **meryum.syeda01@gmail.com**
