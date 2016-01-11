# 2014 Public University President Pay

Scripts and data used for [analysis on the 'competitiveness' of university 
president pay](https://neilbedi.com/posts/college-president-pay).

## About the analysis and data

Competitiveness in this scope is defined as the difference between a president's 
base salary and the salary average of the nearest 5 percent of neighbors.

Neighbors were selected using the [scikit-learn implementation of the nearest 
neighbor algorithm](http://scikit-learn.org/stable/modules/neighbors.html).

The university data – 2014 revenue, tuition and enrollment – comes from the 
[US Department of Education's Institute of Educational 
Service](https://nces.ed.gov/ipeds/datacenter/InstitutionByName.aspx).

The initial 2014 president data comes from the [the Chronicle of Higher Education](http://chronicle.com/interactives/executive-compensation#id=table_public_2014). 
After removing executives leading entire university systems, 147 presidents were 
left. 

Five additional presidents were removed because their universities used 
[FASB accounting standards instead of GASB 
standards](https://nces.ed.gov/ipeds/factsheets/fct_ipeds_finance_1.asp) for 
reporting revenue. Those universities are Pennsylvania State University at 
University Park, University of Delaware, University of Pittsburgh main campus 
and Temple University.
