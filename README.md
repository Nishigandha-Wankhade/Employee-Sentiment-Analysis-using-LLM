# Employee-Sentiment-Analysis-using-LLM
This project involves analyzing an unlabeled dataset (test.csv) of employee messages to assess sentiment and engagement with insights such as sentiment labeling, exploratory data analysis, employee score and ranking, flight risk detection, and predictive modeling using natural language processing (NLP) and statistical analysis techniques. 

### RESULTS

### Overall Top Three Positive and Negative Employees:
#### •	Top Positive Employees 
            Rank	        Employee	            Total Sentiment Score
              1	    johnny.palmer@enron.com             	55
              2	    eric.bass@enron.com                         52
              3	    lydia.delgado@enron.com             	52

#### •	Top Negative Employees  
            Rank	        Employee	            Total Sentiment Score
              1	    rhonda.denton@enron.com	                26
              2	    don.baughman@enron.com               	29
              3	    kayne.coulter@enron.com             	32


### Monthly Top Three Positive and Negative Employees:
#### •	Top Positive Employees for January 2010:
            Rank	        Employee	            Monthly Sentiment Score
              1	    eric.bass@enron.com                 	3
              2	    patti.thompson@enron.com             	3
              3	    don.baughman@enron.com              	2

#### •	Top Negative Employees for January 2010:
            Rank	        Employee	            Total Sentiment Score
              1	    sally.beck@enron.com                	-1
              2	    bobette.riner@ipgdirect.com                  0
              3	    john.ernold@enron.com             	         0

### Employees Flagged as Flight Risks:
Based on the overall analysis done, no employees met all three risk criteria-
  -	Score Slope < 0 (decline in sentiment over time)
  -	Negative-to-Positive Ratio > 1
  -	Engagement Slope < 0 (declining engagement)
There appears to be no immediate flight risk within this group; however, employees showing negative sentiment scores or declining engagement trends should be closely monitored.

### Key Insights:
•	Around 80% of the initial assumptions made via Excel pivot table analysis were validated by advanced NLP and machine learning models.
•	Feature engineering significantly improved model performance - linear regression achieved R² = 1.00 post-feature enhancements.
•	Message counts and sentiment class counts (positive, negative, neutral) are strong indicators of employee sentiment and risk.

### Recommendations:
1.	Implement Ongoing Sentiment Monitoring: Automate sentiment tracking to proactively identify shifts in morale.
2.	Early Intervention Strategy: Use the flight risk model to alert HR when sentiment declines sharply.
3.	Employee Engagement Programs: Focus on employees showing early signs of disengagement (high neutral or low message count). Schedule monthly pulse checks or informal 1:1s with employees at the bottom of the sentiment list to uncover underlying issues.
4.	Employee Award Programs: Continue to recognize and reward top positive contributors to reinforce a positive communication culture.
5.	Validation of Models on Unseen Data: To ensure robustness, validate models with new datasets to avoid overfitting.

