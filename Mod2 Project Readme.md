This readme contains a regression analysis project. I approached situation from a new construction perspective. I wanted to know what type of houses I should build. How much living space should the house have? How many bathrooms and bedrooms I should have? What grade of construction should I pursue? What price range should I consider? I want to build based on what has been selling reviewing the data that I have. I used kc_house_data.csv for my project. My data set has 21,600 lines

I examined the Square feet Living to Price through a visual. Please see 'pricetosqftliving.png' in the images folder. My next step was to find out the bedroom distribution in the house sales and how did the bedrooms relate to price of the house. I looked at the visuals pricetobedrooms.png and bedroomscount.png graph in the visuals section below or in the images folder. I reviewed to see if the number of bathrooms and house price has any linear relationship, but once again the variance is not explained by the number of bathrooms. Bathrooms have a slightly better relationship than with the bedrooms. Please see pricetobathrooms.png and bathroomscount.png. Grade has a better relationship with price compared to bathrooms. For grading visuals, please see Gradecount.png and pricetograde.png. Finally, I wanted to see what Frequency distribution of the house sales on a price range basis to see what price range sells the most.

In my base model, I included all the variable except Id, zipcode, and date. What I missed during my EDA was the number of floors influence on the price. My R2 for this base model is .638.

In my second model, I included same as the first model, but I created an additional column for Square_feet_Living/Bedrooms. My R2 for this model was 
.647.

In my third model, I included same as the first, but I created an additional column for Square_feet_Living/Bathrooms. My R2 for this model was .641.
In my 4th model, I included the sames as the first model but ran a polynomial to the second degree and my R2 is .705.

In conclusion, I want to include the features that sell the houses quickly and provide a good profit. I want to build houses in the 2500 to 3000 Square feet which includes 1-2 floors, 2+ bathrooms and 3-4 bedrooms in the  350,000𝑡𝑜 650,000 range with a grade of 7 throug 9.
Due to the limitation of the data from the kitchen, family room, and open lots availability. I would like to do more research in the area based on those factors and house price sales around the open lots and fine tune my recommendations accordingly.