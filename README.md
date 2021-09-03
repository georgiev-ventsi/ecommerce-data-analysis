Data Set Information:
This is a transnational data set which contains all the transactions occurring between 01/12/2010 and 09/12/2011 for a UK-based and registered non-store online retail.The company mainly sells unique all-occasion gifts. Many customers of the company are wholesalers.

Online Retail Data Set: https://archive.ics.uci.edu/ml/datasets/online%2Bretail#

Attribute Information of the provided data:
InvoiceNo : Invoice number. Nominal, a 6-digit integral number uniquely assigned to each transaction. If this code starts with letter 'c', it indicates a cancellation.
StockCode: Product (item) code. Nominal, a 5-digit integral number uniquely assigned to each distinct product.
Description: Product (item) name. Nominal.
Quantity: The quantities of each product (item) per transaction. Numeric.
InvoiceDate: Invice Date and time. Numeric, the day and time when each transaction was generated.
UnitPrice: Unit price. Numeric, Product price per unit in sterling.
CustomerID: Customer number. Nominal, a 5-digit integral number uniquely assigned to each customer.
Country: Country name. Nominal, the name of the country where each customer resides.
Source:
Dr Daqing Chen, Director: Public Analytics group. chend '@' lsbu.ac.uk, School of Engineering, London South Bank University, London SE1 0AA, UK.

Relevant Papers:
The evolution of direct, data and digital marketing, Richard Webber, Journal of Direct, Data and Digital Marketing Practice (2013) 14, 291â€“309. Clustering Experiments on Big Transaction Data for Market Segmentation, Ashishkumar Singh, Grace Rumantir, Annie South, Blair Bethwaite, Proceedings of the 2014 International Conference on Big Data Science and Computing. A decision-making framework for precision marketing, Zhen You, Yain-Whar Si, Defu Zhang, XiangXiang Zeng, Stephen C.H. Leung c, Tao Li, Expert Systems with Applications, 42 (2015) 3357â€“3367.

Citation Request:
Daqing Chen, Sai Liang Sain, and Kun Guo, Data mining for the online retail industry: A case study of RFM model-based customer segmentation using data mining, Journal of Database Marketing and Customer Strategy Management, Vol. 19, No. 3, pp. 197â€“208, 2012 (Published online before print: 27 August 2012. doi: 10.1057/dbm.2012.17).

List of required analyzes:
1. What is the number of canceled orders during 2011? Visualize the results as a percentage ratio.

2. Extract to a separate Excel file the orders for 2011 only. The file name should be "Orders_in_2011.xlsx"

3. Compare the orders in the first half with the second half of 2011. Do not take into account whether the order was rejected or fulfilled if the canceled orders for the whole year are below 2%. Visualize the results.

4. Find the top 20 best products to prepare a marketing campaign.  Visualize the results.

5. Are the sales of these 20 most sold products depending on the price of the product?

6.* Find the countries with the most sales that you would recommend starting an online marketing campaign. Use the sales for 2011.

7.* What was the best month for sales? How moch was earned that month? Plot the ortders per month.

8.* What time should we display advertisments to maximize likelihood of customer's buying products?

9.* Find the Key Clients to send them gifts, promotional materials and contract for distribution

* Let the analysis be reusable with a different datasets or a different number of products, if possible.
