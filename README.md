<p align="center">
<img width="127" alt="Screenshot 2023-04-18 at 8 09 09 PM" src="https://user-images.githubusercontent.com/77115883/232812001-469af381-e224-4ab0-91c4-8db57353697e.png">
</p>



<h1 align="center">PedalPal</h3>

*<h3 align="center">Pedal for the planet!</h3>*



## Background

The e-bike startup industry has been growing rapidly in recent years, with companies focused on developing new technologies and designs to improve the performance and convenience of e-bikes. Some startups are creating e-bikes specifically for commuting or delivery services, while others are developing innovative battery and motor technologies to increase range and power. The industry is attracting significant investment from venture capital firms and other investors looking to capitalize on the growth potential of e-bikes.

## Problem Statement

- Vir Bike plans to develop a No-Code website that provides users with information about e-bikes, such as battery needs and environmental impact. 
- Users will enter their travel details, and the website will calculate battery power needed, pedalling required, and real-time tracking. 
- No Code tools like Thunkable, Glide, and Webflow will be used to create the website. 
- The goal is to encourage e-bike adoption for a more sustainable future.
- Vir Bike hopes to inspire a greater adoption of e-bikes, which will cut carbon emissions and contribute to a more environmentally friendly future. 

<img width="1001" alt="Screenshot 2023-04-18 at 8 07 21 PM" src="https://user-images.githubusercontent.com/77115883/232811479-dd131e62-7d05-4cc5-b6f4-80bdc5a4eeac.png">


## What it does

- PedalPal is your companion for exploring and understanding e-bikes. 
- The personalized battery requirements, gamification, interactive maps, social sharing, rewards based on achievements, and customizable dashboards are all quintessential to the app.
- The integration with fitness trackers is a great way to help users track their health and improve their overall wellness. 
- Adding a chatbot assistance feature will assist users in navigating the no code mobile app and make it easier to find the information they need.

<p align"center">
<img width="1484" alt="Screenshot 2023-04-18 at 8 19 17 PM" src="https://user-images.githubusercontent.com/77115883/232814850-2b993340-fb5e-4922-af6d-9d8b94f39d87.png">
</p>


## Features

**Personalised battery optimization**

The Battery capacity is calculated from the weight of the rider, the inclination of the road, and the distance to be traveled. 

These are calculated using the following formula:

```
Battery Capacity (in Wh) = (Rider Weight in kg x Distance in km x Gradient Percent x 10 x 0.9) / (System Efficiency x Desired Range)
```
Here we are assuming system efficiency to be 80% and the desired range to be 96 km. These variables depend on the specific e-bike being used. 


**Eco-friendly insights**

Based on our research it was observed that the use of E-bikes significantly impacted the following Ecofriendly Insights:
- CO2 Emissions
- Energy Consumption
CO2 Emissions: It was easily deduced that the CO2 emissions would decrease for every person using E-bikes. But we were able to calculate the amount of carbon emissions reduced using the following formula:

```
CO2 Emissions = Battery Capacity (in kWh) x Electricity Grid Emissions Factor (kg CO2/kWh)
```
It was found that energy consumption lowered and energy savings grew in the households which used E-Bikes regularly.

```
Energy Savings = Battery Capacity (in kWh) x Average E-Bike Efficiency (Wh/km) x 1000 / Distance (in km)
```


**A gamified user experience**

- It was observed that the customer's market was always slow to adopt E-bikes and  to counteract this and build a gamified UX which would incentivize the customers to use the app more. 
- This would further create a habit which would benefit the users in the long run.
- Here every time the user uses the app to make a journey a certain reward rank is given to the user. These reward ranks can be redeemed to provide coupons, and discounts on E-Bike related accessories.
- Further more, the amount of reward ranks you have, puts you on a leaderboard with other users in your vicinity. The more reward rank you have the higher your ranking on the leader board.

**Chatbot assistance**

- Upon studying the market, we found that people are hesitant to use e-bikes due to concerns regarding safety and convenience. 
- Making people aware about the benefits and catering to their concerns is an important step in marketing e-bikes as a valuable product.
- A interactive chatbot is the perfect tool for simplifying user experience and making our customers aware.
- We have a implemented a self-learning conversational bot that will keep growing as the questions explode, providing guidance to novel users.

