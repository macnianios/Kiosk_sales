# Kiosk_Sales

Objectives:
	The goal was to analyze sales data from a kiosk for products with different VAT (Value Added Tax) rates over the course of one year.
 

#Running the Notebook in Google Colab
  1.	Open Google Colab: Go to https://colab.research.google.com/.
  2.	Upload the Notebook:
  3.	Click on "File" -> "Upload notebook" and select "Kiosk_Sales.ipynb" from your local machine.
  4.	Alternatively, you can upload the entire project directory (including "Kiosk_Sales.ipynb") to your Google Drive and open the notebook directly from there.

#Methods Used

    •	Data Manipulation (pandas,numpy)  
    •	Data Visualization(seaborn,matplotlib)
 


#DATA

  •	data collected by me

	•Month: Represents the month of the year in which the transactions occur (e.g., January, February, etc.).
	•VAT %(Value Added Tax Percentage): The percentage rate of VAT applicable to the Selling Price. This is a regulatory tax applied to the sale of goods or services.
	•Selling Price (Gross Price): The total amount received from customers for each item sold, including VAT.
	•Quantity Sold: The total number of items sold during the specified month.
	•Net Selling Price (Excluding VAT): The portion of the Selling Price that excludes VAT. This is the true revenue from selling the items before tax obligations.
	•Formula: Net Selling Price = Selling Price/(1+VAT/100)
	•Sales Tax : The tax amount derived from the Selling Price, representing the VAT portion.
	•Formula: Sales Tax= Selling Price - Net Selling Price


	•VAT 0%: Cigarettes and smoking-related items
	•VAT 6%: Personal protective equipment during COVID-19
	•VAT 13%: Water and non-alcoholic beverages such as juices, sodas, and energy drinks
	•VAT 24%: Alcoholic drinks, snacks, and ice cream

#Results

  • This analysis explores VAT categories and sales trends for a local kiosk in Greece, providing insights into seasonal and event-driven variations:

  •VAT 6%: Sales of COVID-19 personal protective equipment remained minimal throughout the year, reflecting reduced demand after 2022.

  •VAT 13%: Sales of water and non-alcoholic beverages increased significantly, driven by warm weather and a local festival in August, which caused a noticeable spike.

  •VAT 24%: Sales rose moderately, with higher demand for ice cream but a decline in temperature-sensitive products like chocolates.

  •Key Trends: Cigarettes and smoking-related items dominated sales year-round, exceeding 50% of revenue except in July and August. During these months, water and non-alcoholic beverages peaked at over 33% of sales. Snacks and COVID-19 protective equipment showed minimal variability throughout the year.
