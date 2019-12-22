# The “blocks” behindblockbusters
Examining metadata on 5,000 movie releases
Ryan Fitzpatrick 
MSDS 696

# Summary
As a long time movie buff, I’ve always been interested in the finer, more granular details behind films like: who was in charge of stage design for “Saving Private Ryan?”, what genre would “The Big Short” fall under, a comedy or a drama? What did “Avatar” end up grossing at the box office?.  Thousands of google searches later, my insatiable appetite for movie related facts and statistics has not waned.  That said, I want to take my curiosity one step further by attempting to understand what movie factors (e.g. cast, director, budget etc…) impact a film’s success at the box office and among critics. In addition to answering this foundational question, this project will ask additional questions of the data including (but not limited to): 

Do specific movie genres have more weight/predictive power

Are directorial debuts less likely to be critically received (popularity score)? How do budgets compare?

Which genres have the highest average revenue, highest budget, longest duration (runtime)?

How has genre popularity changed within the last ~15 years?

How many movies have the highest paid actors/actresses appeared in over the last ~15 years?

How do increases/decrease in numerical variables like budget, popularity, vote counts impact revenue (regression)


In terms of methodology and scope, this project will leverage a variety of data science techniques including but not limited:
•	Supervised Learning
o	  Linear regression - modeling relationship between budget, rating and other variables scalar response (revenue)
o	  Random forest decision trees – evaluate feature importance on revenue/critical reception e.g. voting score
•	Data visualization – EDA and statistical tests
•	Feature engineering – create dummy variables for movie genres, binary variables for highest paid actors, etc…
•	Text analytics for creating word clouds by genre


Data: 
This project will be using film and data fields from The Movie Database (TMDb) collected by Kaggle through its use of TMDb’s open API. In total, the data set includes roughly 5000 records with 24 fields, the majority manually entered by users. 


