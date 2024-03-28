# Bike_Share_Case_study_2023_data
This is my case study for the goggle analytics certificate 

## Objective

- To find how members and casual riders use bikes from the company Cyclistic differently

## Tools Used
 - SQL
 - Google Sheets
 - Tableau
 - Google maps

## Company Goal

- To convert casual riders into annual members

- To maximize the number of annual members for the future growth

## About the Company

- Cyclistic is a bike share company based in Chicago started in 2016. They have more than 5800 bicycles and 600 doc stations. Until recently Cyclistic’s marketing strategy has been on building general awareness and appealing to broad consumer segments. They are looking at new marketing strategies after Cyclistic’s finance analysts had concluded that annual members are much more profitable than casual riders. They have flexible pricing plans but want to find ways to increase the number of riders to purchase a membership.

# The ASK phase
## Question
- How do annual members and casual riders use Cyclistic bikes differently?

## Business Task
- Analyze  the Cyclistic historical bike trip data to identify trends

## Key Stakeholders
- Lily Morena: The director of marketing and manager
- Cyclistic marketing analytic team: Responsible for collecting, analyzing,and reporting data that guides Cyclistic marketing strategy
- Cyclistic detail-oriented executive team: To approve the recommended marketing program

## Key Question
- How to change casual users to an annual subscription?

# The Prepare Phase

## Data Credibility

- Cyclistic historical trip data is public data and is provided by Motivate International Inc. The data is of 12 months from 2023 and is in csv format the data sourse can be found here [https://divvy-tripdata.s3.amazonaws.com/index.html]

## Data Integrity

- Sorting and Organizing Data
- Binding all the datasets together in a single dataset with proper naming convention for easier analysis
- The focus is on the 2023 bike data With information including trip duration, start time, end time, start station, end station,bike type and user type

## Keytasks

- Download data and store it appropriately 
- Identify how it's organized

  
# Process Phase
- Clean the data and document changes( documentation of changes can be found here[
- I have decided due to this being a made up senerio that deleting the null values would be the best case for this scenerio. in a real world scenerio I would ask about the null values and determine if they need to be deleted, left in, or if we can figure out what those null values are.
 
# Analize and Share 

- After looking into the number of members and the number of casual users we can see that there are more members then casual users

![Member vs Casual Users](https://github.com/WellerAmber/Bike_Share_Case_study_2023_data/assets/164393629/4f9b55ab-e08c-40c5-8263-a4d4d5bf1444)

- After looking into the number of rides per month we can see that users are more active during the summer months and the most popular months are from May through September
![Rides Per Month](https://github.com/WellerAmber/Bike_Share_Case_study_2023_data/assets/164393629/f3f5b130-ef77-403c-b804-19d473717dd5)

- After looking at the number of rides each user type does during the week we can see that Members use the bikes more during the week and Casual riders use the bikes more during the weekend

![Sheet 1 (1)](https://github.com/WellerAmber/Bike_Share_Case_study_2023_data/assets/164393629/f6aa94fa-edd9-4550-add8-ad2e6dcdc293)


-After looking into what type of bike is used the most we find that classic bikes are used most frequently 
![Bike types](https://github.com/WellerAmber/Bike_Share_Case_study_2023_data/assets/164393629/08d90c06-884a-431c-a503-19242f46fdf8)

-After looking into the top 10 start stations for casual users and doing a map search of these areas we can see that the bike stations that are near turist attrations are used the most for causal users

![Top stations for casual riders ](https://github.com/WellerAmber/Bike_Share_Case_study_2023_data/assets/164393629/a476088a-e3d6-4b90-88bd-a739aa387822)




# Act Phase
Summary of data collected 
- Casual users rides mostly during the weekends where Members users ride mostly during the week
- Casual users ride longer duration but less frequently where members ride shorter duration but more frequently
- Classic bikes are the most used bikes compared to electric and docked bikes
- Most active months for users are from May though September
- The most active areas for casual riders seems to be near popular turist attractions 
Recomendations: Consider adding perks/discount for members during the weekend
                Consider adding perks/discount for summer months
                Consider adding advertisments around popular turist areas
                consider adding more adds during spring and summer months about membership
                

