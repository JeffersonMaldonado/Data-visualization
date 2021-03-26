# Visualization of Prosper's financial data to complete the last Udacity project

To complete the last project I decided to explore Prosper's loan data. The data set has 113,937 records and 81 columns, however I summarized the data for analysis in 8 columns. My target variable is ProsperRatingAlpha, and which features affect each rating. I chose to work with Term, employment status, loan amount, APR rate, IsBorrowerHomeowner and CurrentCreditLines.

In my exploration, the number of borrowers who do or do not have a mortgage in their name is very similar. The most common APR rate in Prosper's loan amounts is 35%, but with a large volume between 15% and 25%. There are clearly more frequent loan amounts, 20k, 25k and 30k and open credit lines with an average of 9 accounts per borrower. Employment data is also relevant, with overwhelming employee status, however if the borrower is in the best alpha ratings, he may be approved.

By exploring the data, I was able to identify the concentration of borrowers' data in relation to the loan values and APR rate, the closer to HR the higher the rate, and the closer to AA the lower the rate, making clear a downward trend. It is also important to note that the higher the loan amount requested, the lower the APR rate. That said, I was able to verify the loan values of HR, E and D are on average from 5k to 15k, respectively. And from C to AA from 5k to 35k. During the exploration of the data I was able to understand that the more borrowers have open lines of credit, the higher the loan values. This goes for any alpha rating, what defines in fact is the cut-off of the values, clearly an upward trend. In other words, the closer to HR the lower the loan amount will be, and the opposite holds true for ratings close to AA, with a range between 5k to 35k. The most used loan terms offered by Prosper are 36 months, followed by 60 months. It is interesting to note that the HR rating is only offered in terms of 36 months. For the E, D and C ratings the rates are lower for the longer terms on average. However, for the B, A and AA ratings the rates are higher for longer terms. Probably due to the range of available values greater than the worst ratings.

## Requiriments

### Python

- pandas==0.24.2
- numpy==1.20.0
- matplotlib==3.3.3
- seaborn 0.11.1
