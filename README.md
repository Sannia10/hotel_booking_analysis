# Overview
 Using Power BI and Python, this analysis aims to understand the price movement as the booking date approaches the check-in date and identify business opportunity on its basis.

# Tools Used
Power BI has been used in this case study to visualise the data, establish relationships between different variables, view trends and facilitate overall understanding of the data.
Python has been used to run some statistical tests such as Pearson correlation. 

# Major Insights
1. 68.6% bookings take place within 3 days prior to check in. 
2. 29% of the total revenue of the business is recorded within 3 days to check-in date.
3. As the difference b/w booking date and check in date increases,the average daily revenue (ADR) also increases.
4. For high grossing months; Oct ,Nov and Dec, total revenue drops when the days to check-in increase.  However, this trend does not hold for August and September. 
5. In August, total revenue increases if people book 1 or 2 months prior to their trip. That is because people pay high on average/booking. This opens up a business opportunity.
6.If you get more people to make early bookings, the total revenue is likely to increase.


# Analysis
1. The Power BI dashboard also compares the revenue across different cities and how the average revenue changes as booking date approaches for each city.
2. The different types of accomodations are also compared. It shows that as days to check in increase, ADR for chain hotels rises more rapidly than non-chain hotels. Marketing partnerships with chain hotels can result in increased bookings and total revenue.
3. The accomodation ratings are also taken into account. Accommodation which is highly rated has higher ADR as the days to check-in increase.Promotion partnerships with high rating accommodation can help increase the bookings and increase overall revenue.
4. Pearson correlation shows a weak correlation between average daily rate and days to check-in. This is also primarily because there are several other factors influencing price such as demand and supply, seasonality factors, occupancy rate and economic and political factors.

# Limitations of Analysis
1. This analysis can not be generalized for all locations and accommodation types. The data set only contains records for 5 cities. Price variations within and across different geographical locations can be massive. Different regions will have to be analyzed separately.
2. Year round data required to validate the analysis. Current data set only includes data for 5 months.
3. In the current data set the duration of stay is only between 1-3 days. It can be assumed that this data is for short duration bookings only. Data regarding long term stays will be needed to see if the given analysis holds for them or not.
4. Multiple years need to be analysed to interpret and account for seasonal trends. 

# Implementation and Way Forward
1. Check booking abandonment rate -> check where people drop in the funnel and then re-target them. For example, if they drop off at giving card info, allow them to save progress and come back.
2. Pop ups/ Notifications which instill " Fear of Missing out on a limited time offer". Mention how many places have been booked in past hour. Award points for early bookings which can be redeemed.
3. If a person sends an x amount of time looking at a place or marks it as a favorite, send constant reminders via push notifications to complete booking process. Reinforcement leads to action.
4. In the deals section, similar to unlocking discounts for first booking etc, introduce streaks for early bookings and a chance to get cash backs.
5. When a user shows interest in a particular place, start marketing the location via push notifications e.g. fun facts about the location, how popular the place is, how frequently it is booked etc.

