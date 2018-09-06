# Mekktronics-Sales-Forecasting-using-Random-Forest-H2o-

Dataset Description:

Sales Data was spread across country levels. (Daily Basis) 
Holiday information was given 
Promotional Expense details were given (Weekly Level)

Task:
Forecasting at Monthly Level



Data Preparation Steps Taken
1.  holidays date conversion into proper format( date standardization)
2.  Sales Currency standardization ( Scaled to one currency)
3.  Promotional Currency standardization ( Scaled to one currency)
4. Data Aggregation at Monthly Level
5. Feature Engg ( Finding region wise:  number of holidays in a month)


Model Building Stage
1. Did EDA to find exactly number of bins for random forest model
2. Used H20 model with n.trees =100 as aggregated data was less.
3. Train-Test split gave results of Symmetric mean absolute percentage error as 0.12

 

“What we know now – is that Pricing includes not just Dollars – but looks at the 3 C s, the various entities : Product, Brand, Stock, Volume commitment etc.
We saw the logistic Win-Loss curve , the linear contribution Function and the differential that allowed us to reach the optimal point!

Here is the data – lets begin: 

Problem statement: This is a diagnostic pricing problem – and we want to optimize the margin for our CoP Client. Here is the data we have – from Jan 2017 – Aug 2018. (Hint: The yellow marked columns will most likely be mandatorily used in any kind of analysis you d do. While some of the white & blue ones will help to enhance the idea better!)

For the win-loss – or as we called it in our CoP session – ‘How many customers we would lose if we reduce the discounts – the Low/Medium/High risk customers; we would share the competitor data by Thursday. 

The data dictionary also has hints section”
