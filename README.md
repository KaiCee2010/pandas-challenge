# pandas-challenge
This repository contains the files and folders for the panda-challenge homework. The repository contains a HeroesOfPymoli jupyter notebook and a Resources folder.  The Resources folder contains the purchase_data.csv.

This jupyter notebook contains:
* Player Count
* Purchasing Analysis (Total)
* Gender Demographics
* Purchasing Analysis (Gender)
* Age Demographics
* Purchasing Analysis (Age)
* Top Spenders
* Most Popular Items
* Most Profitable Items

## [Player Count](HeroesOfPymoli/Images/player_count.png)
 This dataframe contains the Total Players.  This dataframe was created by:
* Saving the "SN" column unique count to a variable
* Creating a dataframe using the variable



## [Purchasing Analysis (Total)](HeroesOfPymoli/Images/purchasinganalysistotal.png)
The final dataframe for the Purchasing Analysis (Total) contains the following information:
* Number of Unique Items
* Average Purchase Price
* Total Number of Purchases
* Total Revenue

This dataframe was created by:
* Saving the "Item Name" unique count to a variable
* Saving the "Price" mean to a variable
* Saving the "Purchase ID" count to a variable
* Saving the "Price" sum to a variable
* Creating a dataframe from the four variables
* Formatting the columns
* Displaying the dataframe

## [Gender Demographics](HeroesOfPymoli/Images/gender_demograhics.png)
The final dataframe for Gender Demographics contains:
* Percentage and Count of Male Players
* Percentage and Count of Female Players
* Percentage and Count of Other / Non-Disclosed

The dataframe was created by:
* Saving the "SN" and "Gender" columns to a new dataframe variable
* Removing duplicates
* Grabbing the count of players
* Sending the gender value counts to a frame
* Calculating values 
* Formatting the data
* Displaying the dataframe

## [Purchasing Analysis (Gender)](HeroesOfPymoli/Images/purchasing_analysis_gender.png)
The final dataframe for Purchasing Analysis (Gender) contains:
* Purchase Count
* Average Purchase Price
* Total Purchase Value
* Average Purchase Total per Person

This dataframe was created by:
* Creating the group dataframe
* Creating the statistics of the price column
* Creating a new dataframe with count and mean
* Creating a total value column by calculating the count by mean
* Creating an aggregate of the unique "SN" values
* Creating a average total purchase by dividing total purchase value by unique total gender
* Deleting unique total gender column
* Renaming the count and mean columns
* Formatting the columns
* Displaying the dataframe

## [Age Demographics](HeroesOfPymoli/Images/age_demographics.png)
The final dataframe for Age Demographics contains:
* Purchase Count
* Average Purchase Price
* Total Purchase Value
* Average Purchase Total per Person

This dataframe was created by:
* Creating an age bin
* Creating an age label
* Cutting the dataframe by bin and label
* Creating the groupby dataframe
* Saving the "Total Count" sum to a variable
* Creating a percentage of player column by dividing total count by the "Total Count" variable
* Formatting the columns
* Displaying the dataframe 

## [Purchasing Analysis (Age)](HeroesOfPymoli/Images/purchasing_analysis_age.png)
The final dataframe for Purchasing Analysis (Age) contains:
* Purchase Count
* Average Purchase Price
* Total Purchase Value
* Average Purchase Total per Person

This dataframe was created by:
* Creating an age bin
* Creating an age label
* Cutting the dataframe by bin and label
* Creating the group dataframe
* Creating the statistics of the price column
* Creating a new dataframe with count and mean
* Creating a total purchase value column by multiplying the count by mean
* Creating an aggregate of the unique "SN" values
* Creating a average total purchase by dividing total purchase value by unique total age
* Deleting unique total age column
* Renaming the count and mean columns
* Formatting the columns
* Displaying the dataframe

## [Top Spenders](HeroesOfPymoli/Images/top_spending.png)
The final dataframe for Top Spenders contains:
* SN
* Purchase Count
* Average Purchase Price
* Total Purchase Value

This dataframe was created by:
* Creating the group dataframe
* Creating the statistics of the price column
* Creating a new dataframe with count and mean
* Sorting the dataframe by total purchase value
* Renaming the count and mean columns
* Formatting the columns
* Displaying the dataframe

## [Most Popular Items](HeroesOfPymoli/Images/most_popular_items.png)
The final dataframe for Most Popular Items contains:
* Item ID
* Item Name
* Purchase Count
* Item Price
* Total Purchase Value

This dataframe was created by:
* Creating the group dataframe
* Creating the statistics of the price column
* Creating a new dataframe with count and mean
* Renaming the count and mean columns
* Sorting the dataframe by purchase count
* Formatting the columns
* Displaying the dataframe

## [Most Profitable Items](HeroesOfPymoli/Images/purchasing_analysis_age.png)
The final dataframe for Most Profitable Items contains:
* Item ID
* Item Name
* Purchase Count
* Item Price
* Total Purchase Value

This dataframe was created by:
* Sorting the dataframe by total purchase value
* Formatting the columns
* Displaying the dataframe