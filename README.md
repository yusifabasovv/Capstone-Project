# Capstone Project - The Battle of Neighborhoods
# This is the final assignment of the Applied Data Science Capstone Course by IBM on Coursera 

###### The project will focus on to find an optimal location for a **restaurant** in **Baku** . Specifically, this report will be targeted to stakeholders interested in opening a restaurant in Baku , Azerbaijan.


## Introduction - Restaurant Business in Baku

  Baku is the capital and largest city of Azerbaijan, as well as the largest city on the Caspian Sea and of the Caucasus region. Baku lies on the southern shore of the Absheron Peninsula, alongside the Bay of Baku about 25% of all inhabitants of the country live in Baku's metropolitan area. Since, it is capital and largest city in the country there are lots of restaurants in Baku and  we will try to detect locations that are not already crowded with restaurants. We would also prefer locations as close to city center as possible.

## Data 
 Based on our model , the factors that would affect a restautant business are :
- The number of existing restaurants in the city.
- Other competitors ,such as **Fast-food restaurants** or **cafes** that sell foods .

For the locations of restaurants near to the city center, we will use **Foursquare Api** which is quite useful to handle locations all over the world.

## Methodology
- First , data which contains restaurants location near to the city center - **Nizami street** will be collected from **Foursquare** database and cleaned and transfromed into a Dataframe
- Then, The same process will be apply to the **competitors** data which mentioned above.
- Finally, data will be visually assested by Python's **Folium** and **HeatMap** libraries

## Conclusion
What is/are  the best location(s) for the new restaurant in Baku ? The **HeatMap** will help us define it and final decison for the best place will be explored by business owners/stakeholders


###### For better view of interactive libraries in the code cells ,which is unseen in Github , use this link : https://nbviewer.jupyter.org/github/yusifabasovv/Capstone-Project/blob/main/Final%20Capstone%20Project%20.ipynb
