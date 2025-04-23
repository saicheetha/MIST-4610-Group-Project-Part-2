# MIST-4610-Group-Project-Part-2
MIST 4610

## Team Name: 
71552 Group 8

## Team Members:
1.Alt, Jared [@jaralt](https://github.com/jaralt/Mist-4610-Group-Project-Part-2)

2.Cheetha Rajesh, Sai [@saicheetha](https://github.com/saicheetha/MIST-4610-Group-Project-Part-2)

3.Gregg, Stephen [@SGREGG-4](https://github.com/SGREGG-4/Group-Project-2)

4.Lutz, Nic [@niclutz3](https://github.com/niclutz3/MIST-4610-Group-Project-Part-2)

5.Tanti, Dev [@DevTanti](https://github.com/DevTanti/MIST-4610-Group-Project-Part-2/tree/main)

## Dataset Overview

We chose the dataset, titled "Electric Vehicle Population Data," which was obtained from data.gov,
a government website that provides public access to government datasets. It contains information
about electric and plug-in hybrid vehicles registered in the United States. 

Columns/Data Types
- VIN (1-10): The first ten characters of the Vehicle Identification Number. This
serves as a partial unique identifier for each vehicle.
- County: The name of the county where the vehicle is registered.
- City: The name of the city where the vehicle is registered.
- State: The US state where the vehicle is registered.
- Postal Code: The zip code of the vehicle's registered address.
- Model Year: The year the vehicle was manufactured.
- Make: The manufacturer of the vehicle.
- Model: The specific model of the vehicle.
- Electric Vehicle Type: Categorizes the vehicle as either "Battery Electric Vehicle
(BEV)" or "Plug-in Hybrid Electric Vehicle (PHEV)".
- Clean Alternative Fuel Vehicle Eligibility: Indicates whether the vehicle
meets the criteria to be classified as a Clean Alternative Fuel Vehicle. The specific
eligibility criteria can vary by state and may consider factors like electric range. 
- Electric Range: The estimated range the vehicle can travel on a single
electric charge, measured in miles. 
- Base MSRP: The Manufacturer's Suggested Retail Price of the vehicle at the
time of its release, in US dollars.
- Legislative District: The legislative district where the vehicle is registered.
The level and numbering of these districts will vary by state.
- DOL Vehicle ID: A unique identification number assigned to the vehicle by the
Department of Licensing in the respective state.
- Vehicle Location: A geographic representation of the vehicle's approximate location,
often provided as a geographic coordinate (latitude and longitude) in a point format,
sometimes accompanied by a nearby landmark or city name.
- Electric Utility: The name of the electric utility provider that serves the registered
address of the vehicle owner. This will vary significantly by location.
- 2020 Census Tract: The census tract, based on the 2020 US Census, where
the vehicle is registered. This provides a more granular geographic identifier.

## Question 1
What are the top 5 electric car manufacturers in the USA?

![image](https://github.com/user-attachments/assets/62e2e37f-367d-41a1-ba5c-ba4178ba7abb)

We chose to represent this question in a bar graph format. Each bar graph includes the different manufacturers and the total number of cars that they have manufactured in the US over the years.

This is an important question as it highlights the best manufacturer in the electric car industry. The main reason is because different auto manufacturers would want to see how their competitors are performing and take key measures to improve their own operations. This way, they can stay on pace with others in the market. For example, in our data set, Tesla was the best manufacturer. However, let's say Kia and Ford wanted to improve their cars. They can see, based on our bar graph, that Tesla is the best, and they can do research and conduct operations analysis to see where they can improve to compete with Tesla’s numbers. Whether it’s through battery technology or providing a larger charging network, they can isolate the discrepancies between their product and Tesla’s. In addition, some manufacturers can also use this from a sales perspective. Let's say Kia wants to improve their sales, but maybe they can’t figure out why it’s not selling as well as Tesla. It could be due to pricing, product availability, etc. If it was related to pricing, they could compare the price of an electric Kia to an electric Tesla. If the price of a Kia is too high, that might lead to an increase in sales for different manufacturers, such as Tesla. Kia could lower their prices and offer incentives such as EV tax credits to help improve sales of their electric vehicles and compete with Tesla.  

This question is interesting because it illustrates the competition in the market for electric vehicles. In our dataset, Tesla was the winner. This bar graph can also help determine if manufacturers should merge and how to build better products. If Ford and Kia started keeping track of Tesla, they could take notes and see where they need to improve, and potentially see an increase in production for their electric cars. Auto manufacturers are a huge business in the US. Because of such a big market, lots of technological improvements and new products are released every few years. So, to become dominant in the EV market, it's important to keep up with the new technology coming out frequently so that you can be the best of the best on the market.   

## Question 2
Which county has the most electric cars in California?

![image](https://github.com/user-attachments/assets/281156ef-797c-4d3c-af5a-d2f375775bbc)

For our second question, we decided to use a map to display how many electric cars are in each county in California. The map highlights each county that has electric cars, and displays the number of electric cars in that county. The map also has a heat map, meaning that the more cars the county has, the darker the county is highlighted. 

This is particularly important to manufacturers of electric cars because California has the most electric cars of any state, meaning that the residents there closely align with the target market of electric car manufacturers. So, looking at California’s counties individually is important because there could be areas that have potential to have more electric car owners. The reason California should be such a big target is due to many factors, such as mandates for zero emission vehicles by 2035, financial incentives, and just an overall big emphasis on environmental protection by California in general. This map is very interesting because very populated areas, such as the San Francisco area, have a shockingly low amount of electric cars, but areas like San Diego have the most electric vehicles of any part of the state. If electric car manufacturers could capture these other highly populated areas, then there is a chance for them to increase their margins and capture a greater market share.

## Manipulations

For Question 1, we applied a filter to the Make field to show the top 5 manufacturers in the country. We did this as they represent a large majority of the EV market and including more would make the data more cluttered. 

For Question 2, we applied a filter to the State field, focusing solely on California, to show ownership by counties within the state. We did this because California is by far the largest market for EVs and it creates a much more interesting visualization.

## Analysis and Results

For the first question, we created a bar graph in Tableau to visualize the top five electric car manufacturers in the United States based on the total number of electric vehicles they have manufactured over the years. The data shows that Tesla leads the pack, as it has five times more production than its closest competitors. Kia, Ford, Chevrolet, and Nissan are among the top five; however, they do not match Tesla's output. In terms of real-world implications, other leading EV manufacturers must analyze this data to determine what separates Tesla from its competitors. By identifying this distinction, they can aspire to match Tesla’s output or even surpass it over time. Additionally, this kind of performance data could influence strategic decisions such as partnerships, mergers, or R&D investments to enhance product offerings. Ultimately, while the graph shows the top competitors and who is leading in EV manufacturing, it also highlights areas for growth and opportunity within the sector. 

To address the second question, we created a heat map in Tableau to pinpoint California counties with the highest concentration of electric vehicles. Counties are shaded according to their registered EV numbers, with deeper shades representing larger quantities. This analysis is intriguing, as most would assume the San Francisco Bay has the most EV concentration; however, San Diego has the highest concentration in the state. Through this graphic, we see there are opportunities in many areas of untapped potential, such as San Francisco, Kern, Placer, and many more. This data can be of great value for EV car manufacturers as they plan how to pivot their markets to different counties and even to different states or regions as time advances. By boosting EV adoption in underperforming counties with large populations, companies can significantly grow their market share and enhance shareholder margins. 

## Sources

https://catalog.data.gov/dataset/electric-vehicle-population-data
