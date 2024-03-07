# Home_Sales_Big_Data_PySpark


Using PySpark to determine the average costs of homes based on factors sucn as number of rooms, view_rating and year_built 
Not only address the below questions but to compare the speed response when using partition and cache methods 

===============================

What is the average price for a four-bedroom house sold for each year?

+----+-------------+
|YEAR|Average_Price|
+----+-------------+
|2022|    296363.88|
|2021|    301819.44|
|2020|    298353.78|
|2019|     300263.7|
+----+-------------+


What is the average price of a home for each year the home was built, that has three bedrooms and three bathrooms? 

+----+-------------+
|YEAR|Average_Price|
+----+-------------+
|2017|    289100.17|
|2016|    289090.11|
|2015|     299517.5|
|2014|    289935.92|
|2013|    291870.89|
|2012|    289533.13|
|2011|    294656.14|
|2010|    287529.97|
+----+-------------+


What is the average price of a home for each year the home was built, that has three bedrooms, three bathrooms, two floors, and is greater than or equal to 2,000 square feet?

+----+-------------+
|YEAR|Average_Price|
+----+-------------+
|2017|    280317.58|
|2016|     293965.1|
|2015|    297609.97|
|2014|    298264.72|
|2013|    303676.79|
|2012|    307539.97|
|2011|    276553.81|
|2010|    285010.22|
+----+-------------+


What is the average price of a home per "view" rating having an average home price greater than or equal to $350,000? Determine runtime query.

+-----------+-------------+
|View_Rating|Average_Price|
+-----------+-------------+
|         99|   1061201.42|
|         98|   1053739.33|
|         97|   1129040.15|
|         96|   1017815.92|
|         95|    1054325.6|
|         94|    1033536.2|
|         93|   1026006.06|
|         92|    970402.55|
|         91|   1137372.73|
|         90|   1062654.16|
|         89|   1107839.15|
|         88|   1031719.35|
|         87|    1072285.2|
|         86|   1070444.25|
|         85|   1056336.74|
|         84|   1117233.13|
|         83|   1033965.93|
|         82|    1063498.0|
|         81|   1053472.79|
|         80|    991767.38|
+-----------+-------------+

Total Runtime in seconds: 

--- 1.107529878616333 seconds ---
