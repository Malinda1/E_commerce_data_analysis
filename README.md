 Setup instruction 

    01. data_gathering.ipynb :- This notebook use for data gathering used technique web scrapping via "www.amazon.com" website.

	02. data_analysis.ipynb :- This notebook use for data Preprocessing | Exploratory data analysis | data visualization | create of custom analytics features.



data_anlysis.ipynb notebook setup process

   Beginning step
     1. Executing imported library.
	 2. I imported dataset executing it "data = pd.read_csv(f'combined_dataset_01.csv')". 
   
   Data Preprocessing step
	 3. Then jump to the data Preprocessing step.
	 4. Firstly check null values and remove those from dataset.
	 5. After cleaning part done, save the celaning dataset another CSV file called cleaned_dataset.csv.
	 6. finally cleaned_dataset.csv file assign to the data02 variable Because it use for EDA process.

   Data Exploratory data analysis step
	 7. Then jump to the checking outlier part of EDA.
	 8. Afetr gone that step run it again.
	 9. Then go to the outlier remove step because in this step again assign the outlier dataset another variable called "cleaned_data"
	 10. After jump to the beginning of Explore EDA part after cleaning process and explore it.
	 11.then that dataset save the another CSV file called final_cleand_dataset.csv.

   Data visualization step
     12. Import dataset file and assign it variable called data03. "data03 = pd.read_csv(f'final_cleaned_dataset.csv')"
	 13. After done it. you can exploring all interactive visualization process.

   Custom analytics features step (All features Run on the GUI window)
     14. Firstly created this feature, A search function to display all purchases by a specific customer (This feature run on GUI window.)
	 15. Then created this feature, A filter function to find purchases within a specific date range or exceeding a given amount.
	 16. Thirdly created this feature, A feature to calculate the total revenue generated by a product category.
	 17. furthly created this feature, A summary report highlighting top-performing products with additional scraped data (e.g., price trends or average ratings).
	 18. finally created this feature, Include a feature to export the  summary report into an Excel file. 



	 Hint: 
	    I all stuff in detail explained document_report file So explore it. 


Simple summarization of this customer purchases data analysis project

Purpose of the Project:
The aim of the project was to analyze a dataset containing product details to uncover meaningful insights. The focus was on preparing the data, understanding patterns through analysis, visualizing trends, and providing actionable recommendations for business decisions.

What Happened in the Project:

1.	Data Cleaning and Preparation:
	•	Missing values in the dataset were handled.
	•	A new metric, total_spent (price × quantity), was created to understand customer spending better.

2.	Analysis Performed:
	•	Statistical summaries were calculated to understand product prices, ratings, and quantities sold.
	•	Relationships between variables (e.g., price and sales) were studied using visualizations like scatter plots and heatmaps.

3.	Insights and Findings:
	•	Products with higher ratings (4.4 and above) contributed significantly to revenue.
	•	Availability of products directly influenced their sales performance.
	•	High-revenue products were identified, along with outliers in pricing and quantity sold.