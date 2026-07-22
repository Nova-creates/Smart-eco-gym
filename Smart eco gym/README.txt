The Smart Eco Gym

	The Smart Eco Gym is the idea mixing both the electrical and mechanical mini challenges and combined them to solve a new compounded solution. The problem that this solves is keeping circulation good through efficient designs, and to analyze the usage and generation of electricity within the gym to know where can be optimized. This is intended for gym managers who want to have eco friendly gym and make profit. Through the several files such as the following: 
equipment_power_consumption.mat
facility_energy_meters.mat
fan_air_velocity.mat
fan_power_consumption.mat
renewable_generation.mat
Through these files the metrics calculated was air change per hour, net electricity, energy generation, energy usage, and fan efficiency. There was a mix of averaging to remove the outliers and the "smoothdata()" function to get better results and consistant readings. To interact with the GUI you could either click on the graph or on the button. and it will give all of the information that can be offered through the app. There are graphs showing how the metrics change over time such as energy usage and pie graphs showing the percentage of each usage.

How to use:
Download the folder from GitHub.
Find "Smart_Eco_Gym.mlapp"
Click and interact with the app.

There are some assumptions that are made in this and some things that it does not count for in terms of. In the calculation for ACH there is an assumption that there is an area of the door which the air escapes. This was made by an average door size that was researched. the amount of watts used and power used by fans did not account for the the pressure changed which is how fans are calculated for efficiency. There are some errors with the graphing for one of the wattages as it seems that there are two values at seemingly the same time. These are the biggest glaring issues with this app.