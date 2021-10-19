# Amazon_Vine_Analysis
# Overview of the analysis:
In this project I have picked a data set from amazon reviews regarding video games and used Pyspark to perform the ETL process by extracting the data, transforming the data and connecting to the database that was generated for me through the AWS webserver. With the reviews my goal is to try and determine if there is favorable review bias from the Vine members of our data set.
# Results:

## How many Vine reviews and non-Vine reviews were there?

There were a total of of 4,291 vine reviews in our dataset, and 40,471 non-vine reviews in the complete dataset.

![image](https://user-images.githubusercontent.com/86137857/137833382-caca0fdb-2451-4dbc-9d38-7063cdcb35da.png)

## How many Vine reviews were 5 stars? How many non-Vine reviews were 5 stars?

In the data set their was a total of 15,711 5-star reviews
15,663 of the 5-star reviews were non-vine

## What percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?

38.2% of the five_star reviews were vine
38.9% of the five_star reviews were non-vine

![image](https://user-images.githubusercontent.com/86137857/137833650-b7f560f5-b654-4c1d-a9e7-b3d46ce6385d.png)

# Summary:
After I had come up with my analysis there does not appear to be any sort of positivity bias because the percentages shown above are very similar at 38%. To conclude the analysis the vine program does not show any bias.
