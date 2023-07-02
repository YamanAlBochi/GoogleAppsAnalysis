Google Play-Store Applications Data Analysis Project:

1. Importing all the necessary Libararies: 
There are more than 3.04 million apps found on Google Play Store. In this project I analyzed various apps found on the play store with the help of different python libraries...........................

2. Data Exploration:
After loading the dataset, we look for the exploration, we need to check and see that the dataset is ready for performing several exploration operations or not, so I look at the Data structure and the manner in which the data is organized. To figure out if we have any missing value or NaN value in our Dataset, I used the isnull() function.

3. Data Preparation and Cleaning:
Data preparation and Cleaning; is the process of cleaning and transforming raw data prior to processing and analysis. It is an important step prior to processing and often involves reformatting data, making corrections to data, and the combining of data sets to enrich data. The dataset contained many Null or missing values. The column Rating, Type , Content Rating , Current Ver , and Android Ver contains 1474, 1, 1, 8, and 3 missing values respectively.
I encountered useful information about the dataset. i.e., the missing number of values of any attribute, its unique count, and its respective data types. Row 10472 has missing data for the Category column and all the prevailing column values are being replaced with its previous column. I dropped this row from our data frame. so all my  columns had the null_count as zero, which indicates that now the data frame doesn’t contain any missing values.
After I did my Data Preparation and Cleaning. I saw that  original dataset contained 10841 Rows and 13 Columns. It contained App, Category, Rating, Reviews, Size, Installs, Type, Price, Content Rating, Genres, Last Updated, Curernt Ver, and Android VerColumns. But after cleansing the dataset and dropping the unwanted rows and columns having Null Values and Garbage data from the data frame, we are left with 8434 Rows and 10 Columns.

4. Exploratory Analysis and Visualization: 
Exploratory data analysis is an approach to analyzing data sets to summarize their main characteristics, often with visual methods. A statistical model can be used or not, but primarily EDA is for seeing what the data can tell us beyond the formal modeling or hypothesis testing task. Data visualization is the graphic representation of data. It involves producing images that communicate relationships among the represented data to viewers of the images. This communication is achieved through the use of a systematic mapping between graphic marks and data values in the creation of the visualization. This mapping establishes how data values will be represented visually, determining how and to what extent the property of a graphic mark, such as size or colour, will change to reflect changes in the value of a datum. There are all total of 33 categories in the dataset from the above output we can come to the conclusion that in the play store most of the apps are under Family & Game category and least are of Beauty & Comics Category.
