# Cambridge_Real_Estate_Analysis
This Project was carried out by me for satisfying requirements of Udacity Data Scientist Nanodegree program.

**Back Ground:**

Cambridge is a centre of innovation in Greated boston area. Many Enterpreuners have made this are home to their successfull businesses and Technology companies 
and start ups are thriving in this area. Partly because of the availability of high skilled labor and aspiring new grads entering work force in greater boston area. 
Cambridge is also home to thousands of families living in this neighborhood for decades and centuries. 

Here is an Analysis of Real estate data for Cambridge Massachussets area, present the analysis findings and also use the Data to build a Linear regresssion model that can be used to predict the future sale prices of the properties in this area. The Data was downloaded from opendata platform,a public Data repository hosted by "City of Cambridge"

This project aims to analyse the Real estate in Cambridge MA and answer below questions - 
1. How does the Property Value distribution look like in Cambridge for different property types. 
2. What was the sales volume in this area in last 10 years for different property types. 
3. Distribution of gap between sale price and assessed value for different property types in last 10 years sales.
4. Develop and evaluate a Machine learning model to predict future property sale prices in cambridge area.


**Contents:**

CambridgeHomePricesAnalysis.ipynb - Python Notebook which contains the technical implementation of the project.

README.md - This file contains the detailed description of the project.

fy2019_propDB.xlsx - Cambridge housing data for 2019. Sample Data for reference.

property_database_2015_metadata.xlsx - Data dictionary containing the description of each column in the dataset.



**Libraries:**

The following Python libraries used for Analysis and modelling.

Numpy
Pandas
Matplotlib
Seaborn
sklearn

**Summary of Analysis:**

1. Educational institutions have a high distrubution of assessed property value. 
The mean for a Business premise was 21MM and for condominiums the mean was 735k USD.
Also notably depending on the premium property features sometimes may cost upto 2MM USD 
more than mean price for condominiums in Cambridge area as std for condominiums is 2.2 MM!

![AssessedValueDistPlot](https://user-images.githubusercontent.com/52425499/127932879-6d7b3e59-5dd3-4f98-9d6b-14d4d12d1278.jpg)


2. In the last 10 years condiminum properties have been outselling Family homes and other business premises in Cambridge area.

![SalesVolume](https://user-images.githubusercontent.com/52425499/127932922-a23690d1-9546-48c9-9ab5-cb3131a0bb70.png)


3. Family Homes, Business premises, Piece of Land and Educational properties have sold for much more than the last assessed value.

![PriceGapPlot](https://user-images.githubusercontent.com/52425499/127932944-d6f30166-4f09-424f-83d2-96c87086dc90.png)


**Conclusion** - Investment in a good property with nicer features 
in cambridge area whether in Housing project, Business Premises or Piece of Land may be a wise decision for Future Financial Prosperity!

**Blog Post**

The Analysis was presented in my medium blog post.

https://medium.com/@sudee.gm/cambridge-real-estate-analysis-a12d27ec9032

**Aknowledgements:**

City of Cambridge - OpenData platform

Scikit Learn


