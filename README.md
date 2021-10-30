# The-Big-Apple---Project-1-Group-3
-------------------------------------------------------------------------------
Analysis of NYC Airbnb listings
-------------------------------------------------------------------------------

Airbnb has grown not only in size or popularity, but in value as well. Assuming to be an investment firm, we are attempting to determine whether Airbnb would be a good option for investment, therefore, we decided to create an analysis of different variables to come to a decision regarding this manner. Throughout this project, the following relationships were observed: distribution of neighborhoods by boroughs, number of reviews for neighborhoods in each borough, prices by borough, correlation between number of reviews and prices for each room type, number of reviews by minimum nights, heatmaps for number of reviews by boroughs, and lastly, a map with subway stops to see the proximity of these Airbnb listings to the public transit option around the city. These relationships are questions that we wanted to answer, and visually see through diagrams to come to an accurate conclusion. 

We began by grouping the neighborhoods to their according boroughs. In New York City, there are 5 boroughs: Bronx, Brooklyn, Manhattan, Queens, and Staten Island. By doing this, the data became more readable, understandable, and appealing.  Once  these neighborhoods were in groups, we were able to compare the number of reviews that each borough had, thus, determining which borough was the most popular and busiest throughout the year. Pie charts and a bar graph was used to demonstrate the data.

The next relationship that was observed was the difference in price by boroughs. In doing this, we were able to see the price range for each borough, as well as any outliers by creating a box plot. Manhattan, out of the five, seemed to have the most properties with higher price, ranging from $100-$350 per night. Brooklyn, on the other hand, seemed to have the most properties for a price range between $50-$100. Histograms for each borough was created along with an outline of all of NYC data. This helps us see exactly how much each borough contributes to the data as a whole. Pictures have been uploaded for each borough.

After looking at the data by boroughs, we decided to see the data as a whole for NYC Airbnb's. Because most of the New York population lives in townhouses, condos, lofts, and studio apartments, we were curious to see whether the room type affected the number of reviews for these properties. A scatter plot was used to determine the correlation for each room type in Airbnb as well as a regression line to indicate the finding. We found that there was in fact, no correlation between these variables, however, the minimum nights that the hosts set for these properties do impact the number of reviews. Scatter plots and histograms were provided for this. 

Lastly, heat maps for each borough was created to show the frequency of the number of reviews for each of them. Like mentioned above, this helps us see which borough is the most and least popular. In addition, a separate file was attached to determine how close subway stops are to these properties. In NYC, public transit is the most popular way of travelling around the city, therefore, one would want to be close to these options. A map was provided to show which borough could potentially be the most convenient for people traveling by leisure or because of business. By using all of this information, a statistical analysis was created between Brooklyn and Manhattan. More specifically, an independent t-test was created between the two boroughs to determine the p-value significance in price. 
***********************************
Data Limitations
Dataset represents a snapshot of property listings
- Reservation history is not included. We can not identify volume over time using a snapshot of the NYC AirBnB dataset
- Revenue optimization strategies cannot be identified. i.e. If a property/host charges more on Friday / Saturday vs Monday-Thursday, this pricing strategy is not including in our data file.

Customer review detail is not included in analyses
![image](https://user-images.githubusercontent.com/88281736/139542870-ea55512f-fd3c-406b-9f1d-283b4d06bc13.png)

***********************************

***********************************
Pricing Analyses
Price outliers are removed from all Pricing Analyses using the Inter Quartile bounds. 

For each Borough, a box plot is plotted to identify inconsistencies / correlations , at a high level , between Boroughs.

To supplement this analysis, a histogram is used to overlay Borough price compared to All NYC price and understand distribution by price. 
***********************************

=======

***********************************
Analysis Ideas
***********************************
•	Box & Whisker Plot boroughs/price - AG

•	“Rooms by” analysis - PM

•	Pie Charts by neighborhood - CB

•	Review & Price scatter plots 

•	Heat map for rentals - AP


API Links:
https://github.com/mimouncadosch/MTA-API

##Similar project to ours(our original data?)
https://www.kaggle.com/geowiz34/maps-of-nyc-airbnbs-with-python

#MTA NYC Transit - updated 7/30/2021 -static data subway stop coordinate
https://atisdata.s3.amazonaws.com/Station/Stations.csv
>>>>>>> 926e1![Slide1](https://user-images.githubusercontent.com/88807979/139542598-20db282e-377b-4a61-899e-85b17922855e.PNG)
4214c27b3317056c0037c1ec579c9ca2aaa
>>>>>>> 
![Slide2](https://user-images.githubusercontent.com/88807979/139542622-7e98ce89-bc0d-4247-a226-77d9b498668d.PNG)

![Slide3](https://user-images.githubusercontent.com/88807979/139542644-6b4a7775-3052-40da-9959-b542be1cfa7c.PNG)

![Slide4](https://user-images.githubusercontent.com/88807979/139542651-9c29e6c5-f1a8-40bc-a49a-7a4e6d4ce793.PNG)
![Slide5](https://user-images.githubusercontent.com/88807979/139542654-c945c7f5-cd3b-4d1d-8130-e74c34a07ffe.PNG)
![Slide6](https://user-images.githubusercontent.com/88807979/139542657-7f427fb1-64d6-423c-aa44-aed2f997bb5f.PNG)
![Slide7](https://user-images.githubusercontent.com/88807979/139542660-7a772712-c7b6-46ac-87d1-21dee390d808.PNG)
![Slide8](https://user-images.githubusercontent.com/88807979/139542664-3c97ec96-4424-44c6-99b9-945da9025fb8.PNG)
![Slide9](https://user-images.githubusercontent.com/88807979/139542670-8c65bde4-cde3-4a1e-aeb2-99332dcbb690.PNG)
![Slide10](https://user-images.githubusercontent.com/88807979/139542673-6d44a331-f790-4a48-9565-bf7ac912666b.PNG)
![Slide11](https://user-images.githubusercontent.com/88807979/139542698-27ab7ff3-b257-41be-92f8-4ff9ba46f4ab.PNG)

![Slide12](https://user-images.githubusercontent.com/88807979/139542705-af821e08-dcf1-45a3-b52e-704bc1dd26d2.PNG)
![Slide13](https://user-images.githubusercontent.com/88807979/139542712-c2b776c9-1530-4a55-9d30-d166f9d1e1bd.PNG)
![Slide14](https://user-images.githubusercontent.com/88807979/139542715-367e09d6-4943-4b50-9093-f3f356bcdf93.PNG)
![Slide15](https://user-images.githubusercontent.com/88807979/139542717-8a5698f4-da1f-4704-8ff8-7d29be18cecb.PNG)
![Slide16](https://user-images.githubusercontent.com/88807979/139542719-fae3f6db-fe8f-4d69-8bab-f910a6809b21.PNG)
![Slide17](https://user-images.githubusercontent.com/88807979/139542724-3489a844-96d4-4eef-9ea8-45a18f8bff93.PNG)
![Slide18](https://user-images.githubusercontent.com/88807979/139542767-4cb40d94-672c-4b00-9270-474bc3e232e2.PNG)

![Slide19](https://user-images.githubusercontent.com/88807979/139542734-f4318e38-0492-4046-991a-f73ec0376380.PNG)
![Slide20](https://user-images.githubusercontent.com/88807979/139542736-dec939bf-f49a-42d5-a95a-e43bed4ca03d.PNG)
![Slide21](https://user-images.githubusercontent.com/88807979/139542737-2624d1de-f82b-49bb-9549-fe5900d6a4a9.PNG)
![Slide22](https://user-images.githubusercontent.com/88807979/139542738-702cf5c2-d2aa-4bd6-86af-4b058b7a2cb5.PNG)
![Slide23](https://user-images.githubusercontent.com/88807979/139542740-93cb4129-905c-486f-832d-5f09cff1ca58.PNG)
![Slide24](https://user-images.githubusercontent.com/88807979/139542741-d426fb35-0e10-4e4e-8f59-b7250df13e8d.PNG)
![Slide25](https://user-images.githubusercontent.com/88807979/139542744-087a9b26-549d-4183-ae94-7c118ee5cf37.PNG)
![Slide26](https://user-images.githubusercontent.com/88807979/139542746-c31e30fe-5e60-4b7e-8cf4-215f68fe6c2c.PNG)
![Slide27](https://user-images.githubusercontent.com/88807979/139542747-8d65f3b5-c37a-455d-a5dd-316e94c4f0da.PNG)
![Slide28](https://user-images.githubusercontent.com/88807979/139542749-d2dd4741-0f1e-48f1-abd9-a0c089b1f95c.PNG)
![Slide29](https://user-images.githubusercontent.com/88807979/139542750-4b53e184-1a35-4c80-8e57-b9d75a74c145.PNG)
![Slide30](https://user-images.githubusercontent.com/88807979/139542751-108ed5ca-6893-4bb8-be45-01b9fbc34d90.PNG)
![Slide31](https://user-images.githubusercontent.com/88807979/139542753-480318f7-c386-4487-8874-29994df6eddc.PNG)

