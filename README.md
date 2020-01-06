# Increasing SAT Participation Rates 

### Overview

Our task at hand is to offer recommendations to executives at the College Board on how to increase SAT participation rates. The two college admissions exams that currently exist are the SAT and ACT. The overall ACT participation rate is currently higher than that of the SAT. The executives want to know where they should start spending money to change this. 

We have access to the following information 

| Feature | Type   | Dataset| Description  |
|------|------|------|------|
|   state  | object|   SAT  | State that data comes from|
|------|------|------|------|
|   sat_2017_participation_rates  | float|   SAT  | The participation rate for the SAT |
|------|------|------|------|
|  sat_2017_reading_and_writing_score  | int|   SAT  | The average reading and writing score|
|------|------|------|------|
|   sat_2017_math_score  | int|   SAT  | The average math score|
|------|------|------|------|
|  sat_2017_total_score  | int|   SAT  |  The average total score|
|------|------|------|------|
|  state  | object|   ACT  |  State that data comes from|
|------|------|------|------|
|  act_2017_participation_rates | float|   ACT  |  The participation rate for the ACT|
|------|------|------|------|
|  act_2017_english_score | float|   ACT  |  The average english score|
|------|------|------|------|
| act_2017_math_score | float|   ACT  |  The average math score|
|------|------|------|------|
| act_2017_reading_score | float|   ACT  |  The average reading score|
|------|------|------|------|
| act_2017_science_score | float|   ACT  |  The average science score|
|------|------|------|------|
| act_2017_composite_score | float|   ACT  |  The average composite score|


We can analyze this data to look at trends such as: 

- Is there a correlation between ACT and SAT scores? 
- What states are we most successful in? 
- What states are we least successful in? 
- Is there a correlation between participation rates and scores in both tests? 

By answering the questions above, in addition to conducting outside research on what we might have done differently in states with high SAT participation rates vs low SAT pariticipation rates, we will be able to make recommendations to the College Board excecutives. 

### Findings 

- Is there a correlation between ACT and SAT scores? 
There is a strong negative correlation between ACT and SAT scores; states that have high ACT participation rates tend to have low SAT participation rates 

- What states are we most successful in? 
We are most successful in the following states (2018): Colorado, Connecticut, Deleware, Michigan, and Idaho all have 100% participation rates for the 2018 SAT. We found that states we are most successful in require all public high school students to take the SAT (https://blog.prepscholar.com/which-states-require-the-sat).   

- What states are we least successful in? 
We are least successful in North Dakota. North Dakota requires all public high school students to take the ACT. 

- Is there a correlation between participation rates and scores in both tests? 
The higher the participation rate, the lower the average test scores. 


### Conclusions and Recommendations 

After analyzing the data and looking at state requirements and current events, there are three factors that stand out as being important to students when deciding to take the test: 

1. Whether or not the state requires the exam: states that require the SAT had extremely high participation rates   
2. Cost: Of the states that require the exam, many of them choose to cover the cost. This could be a deciding factor. 
3. Student confidence in exam: When the state does not require it and cost is not an issue, students tend to take the test they think they will perform well on (www.usnews.com/education/best-colleges/articles/act-vs-sat-how-to-decide-which-test-to-take)

Initially, I noticed a significant drop in participation rates for the SAT in Florida; from 83% in 2017 to 56% in 2018. I wanted to understand why this change occured in Florida, since the state doesn't require either test and the SAT had a decent overall participation rate in 2017. I thought this could also be a good opportunity to get our participation rates up again in the state. After not being able to find anything that could explain this decrease, I discovered that the data in the file was incorrect. Florida actually had a 97% participation rate. 

I decided to instead focus on Oregon. Oregon does not require the SAT or ACT;  this makes for a good opportunity for us!  Oregon also has under 50% participation in both exams, which indicates that there is no strong preference for one exam or the other, and room for us to dominate the state. Oregon also ranks high in most educated states (http://worldpopulationreview.com/states/most-educated-states/). 

In conclusion, I recommend the following we explore the following to increase partiicpation rates in Oregon: 

-Data: Put time into making sure data we are working with is correct, given that the Florida participation rates were wrong. 

-Market Research: Invest in market research. What drives states to require college admission exams? What makes states decide one exam over the other?  What is the current state of education in Oregon? Using this, we could try to understand how to frame the SAT as being a good test to require in the state.  

-Marketing:  To increase student confidence in exam: offer webinars and free online resources via social media platforms for targeted audience.

-Discounted price for the exam: Test whether or not this increases participation.  


