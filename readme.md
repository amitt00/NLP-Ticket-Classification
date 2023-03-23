# Environment: 
A financial company wants to automate its customer support tickets system. 
As a financial company, the firm has many products and services such as credit cards, banking and mortgages/loans. 

# Buisness Objective: 
To build a model that is able to classify customer complaints based on the products/services that the ticket mentions.
By doing so, one can segregate these tickets into their relevant categories and, 
therefore, help in the quick resolution of the issue.

# Opted Methodology : 
           1) Apply NMF to analyse patterns and classify tickets into clusters based on their products/services.
           2) Coherence Model for optimum topics/clusters->(5)
           3) Map each ticket onto its respective department/category.
           4) Use this data to train supervised model( Naive Bayes/logistic regression/decision tree/random forest)
           5) Using trained model, classify new customer complaint support ticket into its relevant department.

# Result: Optimum result using Logistic Regression
      
| Topic                            | Precision | Recall | F1-score | Support |
| -------------------------------- | --------- | ------ | -------- | ------- |
| Bank Account services            | 0.93      | 0.95   | 0.94     | 1303    |
| Credit card or prepaid card      | 0.94      | 0.93   | 0.93     | 1290    |
| Mortgage/Loan                    | 0.95      | 0.89   | 0.92     | 548     |
| Theft Reporting                  | 0.91      | 0.90   | 0.91     | 1204    |
| Others                           | 0.93      | 0.95   | 0.94     | 923     |
|                                  |           |        |          |         |
| Accuracy                         |           |        | 0.93     | 5268    |
| Macro average                    | 0.93      | 0.92   | 0.93     | 5268    |
| Weighted average                 | 0.93      | 0.93   | 0.93     | 5268    |

