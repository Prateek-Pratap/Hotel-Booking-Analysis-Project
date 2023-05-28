
# EDA - Hotel Booking Analysis







## Introduction

The provided data set encompasses booking details for both a city hotel and a resort hotel. It comprises various information points, including the booking date, duration of stay, the count of adults, children, and babies, as well as the number of available parking spaces, among other relevant factors. Importantly, all personally identifying information has been anonymized, ensuring privacy protection. The aim of conducting exploratory analysis on this data set is to uncover valuable insights that can be utilized to enhance the business operations and overall performance of the hotels.
## Problem Statements

This project analyzes booking behavior in hotels to address key challenges. It covers areas such as hotel preference, customer type distribution, guest origination, monthly booking patterns, arrivals count by year and month, preferred room types, trusted agent analysis, segment-wise room booking, booking cancellation patterns, guest stay duration, ADR vs. stay analysis, special requests, parking analysis, percentage of repeated guests, meal pattern analysis, deposit type distribution, lead time analysis, and customer retention based on hotel type. The project aims to provide valuable insights for informed decision-making and positive business outcomes in the hotel industry.
## Tools and Libraries

We used python as language and following Libraries of python

1. Numpy
2. Pandas
3. Matplotlib
4. Seaborne
## Business Objective

The business objective of hotel booking analysis could be to gain insights and make informed decisions to enhance the overall performance and profitability of the hotel. By analyzing the type of hotels preferred by guests, customer distribution, guest origination, booking patterns, room preferences, agent trustworthiness, cancellation patterns, duration of stay, customer retention, and other factors.

The objective is to optimize operations, improve customer satisfaction, increase occupancy rates, target marketing efforts effectively, streamline inventory and manpower management, and ultimately drive revenue growth for the hotel.
## Solution to Business Objective

To achieve the business objective, the client can consider the following suggestions:

**Maximizing bookings :** Since the City Hotel consistently had higher bookings than the Resort Hotel, the client can focus on strategies to further increase bookings for both hotels. This can include targeted marketing campaigns, promotional offers, and partnerships with online travel agents (OTAs) to attract more customers.

**Targeting peak periods** : As the year 2016 had the highest number of bookings for both hotels, the client can analyze the factors that contributed to this peak period and implement strategies to replicate or exceed those results. This can involve optimizing pricing, enhancing services, and leveraging market trends during that specific time frame.

**Customer segmentation:** Understanding the distribution of customer types can help the client tailor their services and marketing efforts accordingly. Prioritizing the needs and preferences of transient and transient-party customers, who form the majority, can lead to higher customer satisfaction and repeat bookings. Offering special packages or incentives to contract and group customers can also attract their business.

**Targeting popular countries:** The insights on the distribution of guests across different countries highlight the countries with the highest number of guests. The client can focus on targeted marketing and promotional campaigns in those countries to attract more guests. Strengthening relationships with travel agencies and tour operators in those countries can also help drive bookings.

**Optimizing booking patterns:** Analyzing the seasonal patterns and yearly variations in bookings can assist the client in optimizing their revenue management strategies. They can identify peak months and plan resources and staffing accordingly. Understanding the fluctuating months can help the client implement targeted marketing campaigns or special offers during slower periods to drive bookings.

**Enhancing customer experience:** The insights on room types, special requests, and parking spaces can guide the client in improving their offerings. Ensuring a sufficient number of preferred room types (such as type A), efficiently managing special requests, and providing adequate parking spaces can enhance the overall customer experience and satisfaction.

**Prioritizing agent partnerships:** Identifying the top-performing agents and focusing on building strong partnerships with them can lead to increased bookings. The client can collaborate closely with these agents, offer exclusive deals, and provide them with the necessary support and resources to drive more bookings through their channels.

**Market segment targeting:** Understanding the distribution of bookings across different market segments can help the client refine their marketing strategies. They can allocate resources to target the segments with higher booking counts, such as online travel agents (OTAs) and offline travel agents/tour operators. Customized marketing messages and promotions can be tailored to specific segments, increasing the chances of conversions.

**Reducing cancellations:** To minimize booking cancellations, the client can focus on factors that show negative correlations with cancellations. This includes fulfilling special requests, providing a seamless booking experience, and addressing any concerns related to room allocation. Offering flexible cancellation policies or incentives for non-cancellation can also help in reducing cancellations.

**Optimizing pricing:** Analyzing the relationship between Average Daily Rate (ADR) and other variables, such as the number of adults, can help the client optimize their pricing strategies. They can consider dynamic pricing models, adjust rates based on demand patterns, and offer attractive packages or discounts to maximize revenue while meeting customer expectations.

**Pre-planning and lead time:** Recognizing that guests tend to pre-plan their stays around 20-60 days can help the client optimize their inventory management and marketing efforts. They can ensure availability and promotional campaigns during those lead time ranges, increasing the chances of capturing bookings from customers who prefer to plan ahead.

**Focus on customer preferences:** Taking into account the preferences and needs of guests, such as the popularity of meal types like Bed and Breakfast (BB), Half Board (HB), and Self Catering (SC), can help the client tailor their offerings. They can optimize their menu options, food services, and meal packages to align with customer preferences, enhancing the overall guest experience.

Overall, a combination of targeted marketing, optimized pricing, enhanced customer experience, and strategic partnerships can help the client achieve their business objective of increasing bookings, maximizing revenue, and improving customer satisfaction.
## Conclusion

1. City Hotel had higher bookings than Resort Hotel in all three years, with the highest number of bookings occurring in 2016.

2. The majority of customers fall under the "Transient" category, accounting for approximately 75.06% of the total, followed by the "Transient-Party" category with 21.04% of the total.

3. Portugal (PRT) had the highest number of guests, followed by the United Kingdom (GBR), France (FRA), Spain (ESP), and Germany (DEU).

4. August had the highest count of arrivals, while February, November, December, and January had lower arrival counts.

5. May 2017 had the highest count of bookings, while January 2016 had the lowest count.

6. Room type "A" was the most common reserved room type.

7. Agent 9.0 had the highest number of bookings, followed by Agent 240.0 and Agent 1.0.

8. The "Online TA" segment had the highest number of bookings, followed by the "Offline TA/TO" segment.

9. The City Hotel had a booking cancellation rate of approximately 42%, while the Resort Hotel had a cancellation rate of approximately 28%.

10. The majority of guests preferred stays of 1 to 4 days.

11. There were positive correlations between lead time and booking cancellation, the number of weekend nights stayed and the number of weekday nights stayed, and the average daily rate and the number of adults in the booking.

12. The City Hotel received more special requests compared to the Resort Hotel.

13. The majority of entries did not require any car parking spaces.

14. 96.8% of bookings were from non-repeated guests.

15. Bed and Breakfast (BB) was the most popular meal type.

16. The majority of bookings did not require a deposit.

17. Most guests preferred to pre-plan their stay around 20-60 days.

18. There were various correlations between different variables, such as lead time, special requests, previous cancellations, and booking cancellation.

19. There is a positive correlation between lead time and the likelihood of booking cancellation (0.293123). The number of weekend nights stayed shows a moderate positive correlation with the number of weekday nights stayed (0.498968818). The average daily rate (ADR) has a moderate positive correlation with the number of adults in the booking (0.230641216).Bookings with a higher number of special requests show a negative correlation with cancellations (-0.234658).

20. Adults and average daily rate were major factors contributing to the special requests.
