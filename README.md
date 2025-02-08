# FlyingWhale Airlines: A Business Intelligence Report

FlyingWhale Airline aims to improve customer experience by understanding travel patterns and maximizing the effectivness of its membership program. For the stated purpose a business intelligence report is generated in PowerBI that analyzes the flight booking patterns, effectiveness of the loyalty program as well as the customer demographics and retention and cacellation trends for those enrolled in the membership program.

![Dashboard1](https://github.com/user-attachments/assets/df7f7017-ade0-41b5-993f-12fe66ef7d2f)

![Dashboard2](https://github.com/user-attachments/assets/af807253-87d1-486a-a95d-9881fba21fef)

![Dashboard3](https://github.com/user-attachments/assets/c0de87c7-ffc0-4608-8f1e-887f3519a2df)

![Dashboard4](https://github.com/user-attachments/assets/48e07e37-9b3b-488c-8865-f5b5c6bb53a8)

![Dashboard5](https://github.com/user-attachments/assets/19445989-7f06-4566-a61a-69a952db6784)

## Methodology
- **Data Cleaning and Exploration**
  - Cleaning data i.e., ensuring correct data types, checking for errors, blanks and nulls in PowerQuery.
  - Normalizing calendar data for flight activity, enrollment and cancellation of membership program in PowerQuery.
  - Adding indexes to relate calendar tables to customer flight activity and customer loyalty history tables in PowerQuery.
  - Data Modeling in Model View.
  - Binning or discretization was done for Salary and Active/Inactive members.
  - Additional columns were created to calculate the duration of each member's enrollment
  - Additional table was created to segregate the cancellation data for more clarity.
 
- **Key Metrics and Loyalty Program Effectiveness**
  - Key Performance Metrics, such as active members, number of flights booked, distance traveled, points accumulated and redeemed were tracked over a period of 2017-18. A correlation between distance traveled and points rewarded was also established.
  - The effectiveness of loyalty cards Aurora, Nova, and Star was analyzed by examining factors such as the number of customers using each card, average customer lifetime value, enrollment trends, distance traveled, number of flights booked, and points redeemed by each card.
  - Customer demographics were established using factors such as gender, marital status, salary, education and region. Moreover, flight booking pattern for single or multiple tickets bought by each member was also analyzed.
  - Customer retention and cancellation trends are studied first over region and time and then over customer demographics.
 
## Key Insights
- The customer retention rate for loyalty programs has fallen from 89% to 87.6% in the year 2018.
- Over 2 million flights took off in the year 2017-18. Majority of these flights were recorded in the months of June, July, August and September. 490 million kilometers were covered in the time duration and 50.17 million points were awarded to the customers.A positive correlation between distance covered and the points awarded was recorded.
- Approximately 16 thousand people have enrolled in companie’s loyalty program since 2012. Overall retention rate of loyalty card memberships is 87.6%. The enrollment rate remains consistent throughout except for a sharp increase from Jan 2018 to April 2018.
- Customer Preference for loyalty cards has remained consistent from 2013 till 2017, however a sudden increase in membership is seen from year 2017-18. Nova Loyalty Card has outperformed the remaining cards and has seen an increase of 37% usage. Star Card holders remain the highest users of the airlines, with nova and aurora in second and third place respectively.
- Star Loyalty Card is significantly more in demand then Nova or Aurora making up almost half of the total clientele. However, the client lifetime value is lower for Star 26% compared to the Aurora and Nova with an average CLV of 42% and 32% respectively. Despite booking most flights the median distance travelled by the three loyalty card users does not vary significantly.
- The biggest perk offered by the loyalty program are the points awarded for each flight booked that can be redeemed for next journey with the airline. Despite earning a lot of points only 25% of them seem to get redeemed by the customer.
- Most loyalty card members belong to the city of Vancouver, Toronto & Montreal.
![CustomerBreakdown by Province City](https://github.com/user-attachments/assets/ed467879-4385-4ad7-924f-c55ccb1dc046)
- The cancellation of loyalty membership, even though seemingly insignificant, has been constantly rising. In contrast the enrollment trend has been consistent throughout with a sharp rise in April 2018 and then straightens out again. Interestingly April 2018, a significant number of loyalty memberships were taken out and in August 2018 highest cancellations to date were recorded. Since the beginning of 2018, retention rate of loyalty members has decreased from 89% to 87.6%.
- None of the trends regarding education, marital status, salary status or gender give a clear insight into the reason behind the cancellation. As the highest demographic in each category also shows a higher trend of cancellation.

## Actionable Recommendations
It has been observed that most customers do not redeem the points that are awarded to them. Following steps can be taken to educate them on the benefits:
  - Marketing campaigns especially during summer break and winter break to promote the usage of points.
  - Inquiring the customer if they want to use their previous points while the purchase of ticket.
  - A prompt window suggesting them to redeem their points before checkout for online ticket purchase.
All of the above, can help improve the customer experience and will be beneficial in retaining membership.
