# hackathon

The data is about direct marketing campaigns (phone calls) of a Portuguese banking institution from May 2008 to November 2010. The clients were contacted more than once in order to access if the product (bank term deposit) would be (‘yes’) or not (‘no’) subscribed.
The goal is to predict whether the client will subscribe (yes/no) to a term deposit. Key Process Owners can use the output of this prediction to improve the stragegy for the next market campaign.

Data Dictionary:

1.bank client data
* Age (numeric)
* Job : type of job
* Marital : marital status
* Education
* Default: has credit in default? (“yes”,“no”)
* Balance: average yearly balance, in euros
* Housing: has housing loan? (“yes”,“no”)
* Loan: has personal loan? “yes”,“no”)

2.last contact of the current campaign
* Contact: contact communication type
* Day: last contact day of the month
* Month: last contact month of year
* Duration: last contact duration, in seconds (numeric)

3.other variables
* Campaign: number of contacts performed during this campaign and for this client
* Pdays: number of days that passed by after the client was last contacted from a previous campaign (-1 means - client was not previously contacted)
* Previous: number of contacts performed before this campaign and for this client
* Poutcome: outcome of the previous marketing campaign
