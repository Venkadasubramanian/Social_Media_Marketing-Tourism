## DSBA-Capstone
### PGP - DSBA Final Capstone Project on Social Media - Tourism
### Business Objective:
An aviation company that provides domestic as well as international trips to the customers now wants to apply a targeted approach instead of reaching out to each of the customers. This time they want to do it digitally instead of tele calling. Hence they have collaborated with a social networking platform, so they can learn the digital and social behaviour of the customers and provide the digital advertisement on the user page of the targeted customers who have a high propensity to take up the product.

Propensity of buying tickets is different for different login devices. Hence, you have to create 2 models separately for Laptop and Mobile. [Anything which is not a laptop can be considered as mobile phone usage.]

The advertisements on the digital platform are a bit expensive; hence, you need to be very accurate while creating the models.
### Variable Description
- UserID  : Unique ID of user
- Buy_ticket  : Buy ticket in next month
- Yearly_avg_view_on_travel_page  : Average yearly views on any travel related page by user
- preferred_device  :  Through which device user preferred to do login
- total_likes_on_outstation_checkin_given : Total number of likes given by a user on out of station checkings in last year
- yearly_avg_Outstation_checkins  : Average number of out of station check-in done by user
- member_in_family  : Total number of relationship mentioned by user in the account
- preferred_location_type : Preferred type of the location for travelling of user
- Yearly_avg_comment_on_travel_page : Average yearly comments on any travel related page by user
- total_likes_on_outofstation_checkin_received  : Total number of likes received by a user on out of station checkings in last year
- week_since_last_outstation_checkin  : Number of weeks since last out of station check-in update by user
- following_company_page  : Weather the customer is following company page (Yes or No)
- montly_avg_comment_on_company_page  : Average monthly comments on company page by user
- working_flag  : Weather the customer is working or not
- travelling_network_rating : Does user have close friends who also like travelling. 1 is highs and 4 is lowest
- Adult_flag  : Weather the customer is adult or not
- Daily_Avg_mins_spend_on_traveling_page  : Average time spend on the company page by user on daily basis
