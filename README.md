
# Investment Advisor for Stock Recommendation

Based on expenses of a particular person, analysis was done on where they were spending their money and based on the money remaining, what stocck and/or sector to invest in.

Taking into account several financial key parameters, certain stocks and sectors were concluded best to invest in for future investments as well.


## Data Description 


The data available was a persons expenses across a month and where exactly they were spending that money and was present in Google Sheet. Our objective was to dynamically update this Google Sheet with an Excel sheet using an API everytime changes were made on the Google Sheet. 

Apart from this, we also had to update where exactly the money was being spent andd this was done using SQL to group the different spending groups. 

Data related to the BSE was also available where all the stock data present in the BSE and their company details were given. We were to study these details thoroughly and find out which company and stock would be ideal to invest in.

One of the major limitations that we stumbled upon were that the numbers in the data weren't in the int format and hence, we had to convert them from string to int. Another difficulty faced was finding out what exact stock would be ideal based on financials, certain stock research and studies were done to find the same outcome. 

## Methodology

First, a Google API was created in order to link the Google sheet with the Excel sheet in order to dynamically make changes to the Excel sheet. 

Soon after this was done, calculations were made as to where the persons money was being spent and using SQL, we were able to distinguish them into different categories. This was dynamically updated on the Excel Sheet using the API. Once this was finished, we had to find out how much money was remaining for investments and this was done by simply subtracting income and the expenses of the person.

The final part of the project was to study the BSE data and find out optimal statistics to conclude as to which sector would be the best to invest in for the future. It was also required to find out which 5 stocks would be the best for the person to invest in based on the money remaining.

A dashboard was created using the KPIs to determine the stock data.

## Summary

![Screenshot (5)](https://github.com/PranavPramod18/Investment-Advisor/assets/132399432/cbd56128-f8c3-4d37-bd77-bd5fce3de226)

In the above image, you can see the analysis done on companies and their stocks which show a positive and negative 3Yr Return. It also shows which sector/industry would be the best to invest in based on the same.

![Screenshot (6)](https://github.com/PranavPramod18/Investment-Advisor/assets/132399432/ec793a7f-f676-48ad-b404-42022091aa22)

Analysis done on Median of the Enterprise Value (in Cr) and which Sector has the highest and lowest.

![Screenshot (7)](https://github.com/PranavPramod18/Investment-Advisor/assets/132399432/6f0d5945-9bb5-48a5-9724-6bdeb1cc428a)

Key parameters based on which the stock is studied tpo find out which would be the most ideal.

![Screenshot (8)](https://github.com/PranavPramod18/Investment-Advisor/assets/132399432/014725bb-2641-4824-b85f-6649f7ce0c03)

Dashboard that uses certain KPIs to indicate best stock to invest in.

![Screenshot (9)](https://github.com/PranavPramod18/Investment-Advisor/assets/132399432/54bf76b8-ce37-4dd4-b071-c1aea99837ed)

Analysis on Expenses of the person and where they are spending the money. Also shows which stock they must invest on based on the money available and, how risky said investment would be.









## Results/Insights

We were able to conclude that that the Pharma and the IT sector was the best sector to invest in for good future gains while the Adani stocks were the best stock to invest in based on Money to Book ratio, 5Y Returns, 10Y Returns and other important KPIs. 

We were also able to find out which stock is less risky and which is the most risky as well taking into account various KPIs

