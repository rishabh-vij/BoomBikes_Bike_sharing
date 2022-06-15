# Boom Bikes Bike Sharing demand analysis
> Using Linear Regression and EDA to undersatnd important features impcating demand



## General Information
- Background - A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.
- Problem Statement - A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. In such an attempt, BoomBikes aspires to understand the demand for shared bikes among the people after this ongoing quarantine situation ends across the nation due to Covid-19. They have planned this to prepare themselves to cater to the people's needs once the situation gets better all around and stand out from other service providers and make huge profits.


## Conclusions
#### From our analysis we can conclude that, the driving features that have most impcat on the bike rental demand are:
- weathersit_3 has the most impact on bike rentals. Bike rentals go down when it is weathersit_3
- We see an year-on-year growth of `1000` daily rental units
- increase in temperature positivily impacts bike rentals. wehereas increase in humidity and windspeed negatively impcats bike rentals
- Public holidays have a negative impcat on bike rentals
- We see a negative impcat on bike rentals in spring season and a positive impcat in summer and winter seasons


## Technologies Used
* **Python 3.9**
* Pandas 1.4.2
* Numpy 1.22.3
* Matplotlib 3.5.2
* seaborn 0.11.2
* dython 0.7.1.
* scikit-learn 1.1.1
* statsmodels 0.13.2

