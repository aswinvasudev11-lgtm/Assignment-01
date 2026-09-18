# Assignment-01
Data Exploration 
Total Price of the product==SUM(G2:G35)
count of the product==COUNT(I2:I35)
average price==AVERAGE(G2:G35)
minimum price==MIN(G2:G35)
maximum price==MAX(G2:G35)
Using an IF function, create a new column named Price Range to categorize products with a price greater than or equal to $500 as 'High Price' and others as 'Standard Price'.==IF(G2>=500,"High Sale","Standard Sale") and drag to all
The total price for products in the 'Electronics' category using the SUMIF function==SUMIF(J2:J35,"Electronics",G2:G35)
Determine the count of products with a price less than $100 using the COUNTIF function==+COUNTIF(G2:G35,"< 100")
 Create a new column named Day with the first 2 characters of each 'Product ID' using the LEFT function==LEFT(A2,2) & drag to end
 Create a new column named Country Code by extracting the last 2 characters from the 'Product ID' column using the RIGHT function==RIGHT(A2,2)&drag to end
 Create a new column named Month by extracting 4th to 6th characters from the 'Product ID' column using the MID function==MID(A2,4,3)& drag to end
