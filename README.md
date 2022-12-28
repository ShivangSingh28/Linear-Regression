**Problem Statement:**
Congratulations! You just got some contract work with an Ecommerce company based in New York City that sells clothing online but they also have in-store style and clothing advice sessions. Customers come in to the store, have sessions/meetings with a personal stylist, then they can go home and order either on a mobile app or website for the clothes they want.
The company is trying to decide whether to focus their efforts on their mobile app experience or their website. They've hired you on contract to help them figure it out!

__Data Set__
csv file named Ecommerce Customers

__Libraries Used__
Numpy 
Pandas
Matplotlib
Seaborn 
Sklearn

**Solution**
We first explore the dataset by using info() and describe() method on the DataFrame.
We explore the relationships between columns using Seaborn Data Visualizations like jointplot and pairplot

After the Data Analysis we discover a good Linear Relationship between Yearly Amount Spent and Length of Membership.

Next we split the Data into Test Data and Train Data.
Dependant Variable- 'Yearly Amount Spent'
Independant Variables- 'Avg. Session Length', 'Time on App','Time on Website', 'Length of Membership' 

After Creating and Training the model, we predict the results.

Finally we evaluate our model by calculating the Mean Absolute Error, Mean Squared Error, and the Root Mean Squared Error.
Our Residuals show a normal distribtuion.

**Conclusion**
Time on App has a much greater affect on the Yearly Amount Spent as compared to Time on Website.
