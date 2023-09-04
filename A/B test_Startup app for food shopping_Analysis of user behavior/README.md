# Analytics of a startup that sells food products

## Project Objective: 
1. To study the sales funnel. Learn how users reach the point of purchase. 
2. Find out which font is better. (The designers wanted to change the fonts in the whole app)
   
## Skills and tools
- Python
- Pandas
- Matlolib
- SkiPy
- A/B testing
- Statistical hypothesis testing

# Conclusion

The sales funnel is as follows: 
1) the user sees the main screen of the site
2) the user goes to the product he likes
3) the user adds the product to the basket and goes to it
4) the user pays for the order

Additionally there is an event - training. Perhaps the user is taught to work with the site. But, judging by the share of this event, it is not mandatory on the site. And only 4% of users go to this page, so it is not part of the sales funnel.
It was calculated what percentage of users pass to each stage of the funnel from the previous step. The offer screen is passed to 62% of users who looked at the home screen. The shopping basket screen is navigated by 81% of users. The successful payment screen is navigated by 95% of users. 95% of users go to the payment screen from the previous step, but only 62% of users go to the offer screen. 48% of users go from the main screen to the payment screen.
Computer analyses are better for determining the level of significance. For an alpha of 0.1, the control group performed better than the test group for the shopping cart event. For the other events, there is no significant difference between the groups. When alpha decreases, there is no significant difference between groups for any events.
We can conclude that the text on the site does not need to be changed. At best, the conversion rate will not change. But the share of users who went to the shopping basket may drop.
