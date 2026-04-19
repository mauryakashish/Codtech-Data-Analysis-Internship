#CODTECH DATA ANALYSIS INTERNSHIP#-
All 4 internship tasks submission

*COMPANY*: CODTECH IT SOLUTION

*NAME*: KASHISH DHYANCHANDRA MAURYA

*INTERN ID*: CTIS8000

*DOMAIN*: DATA ANALYTICS

*DURATION*: 6 WEEKS

*MENTOR*: NEELA SANTOSH
_______________________________________________________________________________________________________________________________________________________________
1) **TASK1- BIG DATA ANALYSIS:**

##DESCRIPTION OF THE TASK-

In this task, I carried out a big data analysis using PySpark, a highly efficient framework designed for processing and analyzing large-scale datasets. The primary aim of this activity was to gain hands-on experience with big data tools and understand how they function in real-world scenarios. For implementation, I used Google Colab as my development environment and installed PySpark to initialize a Spark session. This session enabled distributed data processing, which is one of the major advantages of PySpark compared to traditional data analysis tools. I worked with a restaurant tips dataset that contained information such as total bill, tip amount, gender, day, and other related attributes. While attempting to load the dataset directly through a URL, I initially encountered some issues. However, I resolved this by first loading the dataset using Pandas and then converting it into a PySpark DataFrame. This experience helped me understand practical challenges that can arise during data handling and how to effectively overcome them.

Once the dataset was successfully loaded into a PySpark DataFrame, I began by exploring its structure using the printSchema() function. This step was crucial because it provided a clear understanding of the data types of each column, including numerical and categorical variables. After that, I performed some basic analysis to get familiar with the dataset. I calculated the total number of records to understand the size of the data, which is an important step in big data processing. Additionally, I used aggregation functions to compute the average value of the total bill, which is a common operation in data analysis tasks. These initial steps helped me build a strong foundation and gave me confidence in working with PySpark. I also learned how PySpark operations differ from those in traditional Python libraries like Pandas, especially in terms of syntax and execution.

Moving forward, I performed grouping and aggregation operations to extract meaningful insights from the dataset. I grouped the data based on gender to examine differences in spending patterns and also grouped it by the day of the week to analyze how customer behavior changes over time. From the analysis, I observed that weekends, particularly Saturday and Sunday, showed higher average total bills compared to weekdays, indicating increased customer activity during those days. I also analyzed tipping patterns across different days to understand customer behavior more deeply. These insights can be very useful for businesses, especially in decision-making processes such as staffing, promotions, and resource allocation. Overall, this task provided me with valuable practical exposure to big data analysis using PySpark and enhanced my ability to efficiently handle and analyze datasets while deriving meaningful conclusions.

#OUTPUT-

<img width="583" height="508" alt="Image" src="https://github.com/user-attachments/assets/5008a8bc-bc23-4600-8431-cc169a1e1c29" />

___________________________________________________________________________________________________________________________________________________________________
2) **TASK2- PREDICTIVE ANALYSIS USING MACHINE LEARNING:**

##DESCRIPTION OF THE TASK-

In this task, I carried out predictive analysis using machine learning techniques with the help of PySpark in a Google Colab environment. The main objective was to build a regression model capable of predicting the tip amount based on the total bill using a real-world dataset. To start with, I set up the working environment by installing PySpark and initializing a Spark session, which is essential for performing distributed data processing. The dataset used for this task was the well-known “tips” dataset, which includes information such as total bill, tip amount, gender, smoking status, day, time, and group size. While working with PySpark, I learned that it does not directly support loading datasets from online URLs. To overcome this limitation, I first used the Pandas library to download and read the dataset, then saved it locally as a CSV file. Afterward, I loaded this file into a PySpark DataFrame with schema inference enabled, allowing PySpark to automatically identify the appropriate data types for each column. This step ensured that the dataset was ready for further processing and analysis.

Once the dataset was successfully loaded, I proceeded with data preparation, which is a crucial step in any machine learning workflow. In PySpark, machine learning algorithms require input features to be assembled into a single vector column rather than using individual columns directly. To achieve this, I used the VectorAssembler tool to transform the data into the required format. In this task, I selected the “total_bill” column as the input feature and the “tip” column as the target variable. The assembler created a new column called “features,” which stored the input values in vector form. This transformation is necessary because PySpark’s MLlib models operate only on vectorized inputs. After completing feature engineering, I implemented a Linear Regression model, which is commonly used for predicting continuous numerical values. I configured the model by specifying the features column and the label column, and then trained it using the prepared dataset. During training, the model learned the underlying relationship between the total bill and the tip amount, enabling it to make predictions on new or unseen data.

In the final stage, I evaluated the performance of the trained model by generating predictions and analyzing the output. I used the transform() function to apply the model to the dataset, which produced a new DataFrame containing a “prediction” column along with the original values. This allowed me to compare the actual tip values with the predicted ones and assess the model’s accuracy. The results showed that the predicted values were quite close to the actual values, indicating that the model performed well and successfully captured the relationship between the variables. I also examined the model’s coefficient and intercept, which provided deeper insights into its behavior. The coefficient revealed a positive relationship between the total bill and the tip amount, meaning that higher bills generally result in higher tips. Overall, this task gave me a complete understanding of building a machine learning model using PySpark, including data loading, preprocessing, feature engineering, model training, prediction, and evaluation, and highlighted the importance of predictive analytics in extracting valuable insights from data.

#OUTPUT-

<img width="345" height="528" alt="Image" src="https://github.com/user-attachments/assets/74e4da03-b30a-494e-94dc-5e913dc4b0b4" />

___________________________________________________________________________________________________________________________________________________________________
3) **TASK3- DASHBOARD DEVELOPMENT:**

##DESCRIPTION OF THE TASK-

In this task, I designed and developed an interactive dashboard using Microsoft Power BI to effectively visualize and analyze a dataset. The main objective of this task was to convert raw data into meaningful visual insights that can support better understanding and decision-making. The dataset used for this project was the widely used “tips” dataset, which includes details about restaurant transactions such as total bill amount, tip, gender, smoking status, day, time, and group size. To begin the process, I imported the dataset into Power BI using the “Get Data” option and selected the CSV file format. Once the dataset was loaded, I carefully explored the data fields to understand the structure and ensured that each column had the correct data type assigned, such as numerical or categorical. This step was important because accurate data types are necessary for proper visualization and analysis in Power BI.

After preparing the dataset, I moved on to creating different visualizations that would present the data in an interactive and easy-to-understand manner. The first visualization I created was a bar chart that showed the average total bill amount for each day of the week. This visualization helped in identifying spending patterns among customers. From the chart, it was clear that weekends, particularly Saturday and Sunday, had higher average total bill values compared to weekdays. This suggests that customer activity and spending are generally higher during weekends, which can be valuable information for business planning. The second visualization I developed was a pie chart representing the distribution of customers based on gender. This chart showed that male customers made up a larger portion of the dataset compared to female customers, offering insights into the demographic composition of the restaurant’s customers.

In addition to these visuals, I created a line chart to analyze the trend of tip amounts across different days of the week. This chart allowed me to observe how tipping behavior changes over time and across different days. The analysis indicated that tip amounts were generally higher on weekends, which aligns with the earlier observation of increased total bill amounts during those days. This suggests a positive relationship between how much customers spend and how much they tip. Finally, I organized all the visual elements into a clean and structured dashboard layout and added an appropriate title to make the dashboard look professional and user-friendly. The final dashboard provides valuable insights such as peak business days, customer demographics, and tipping behavior trends. Overall, this task highlighted the importance of data visualization in simplifying complex data and demonstrated how Power BI can be used as an effective tool to create interactive dashboards that deliver clear and actionable insights.

#OUTPUT-









