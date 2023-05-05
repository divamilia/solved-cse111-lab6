Download Link: https://assignmentchef.com/product/solved-cse111-lab6
<br>
<strong>DATABASESYSTEMS</strong>




In this lab session you have to write 15 SQL queries for the TPCH database created and populated in the previous labs. The queries are the following (1 point per query):

<ol>

 <li>Find the total quantity (l quantity) of line items shipped per month (l shipdate) in 1995. Hint: check function strftime to extract the month/year from a date.</li>

 <li>Find the number of customers who had at least three orders in November 1995 (o orderdate).</li>

 <li>Find how many parts are supplied by exactly two suppliers from UNITED STATES.</li>

 <li>Find how many suppliers from UNITED STATES supply more than 40 different parts.</li>

 <li>Find how many suppliers supply the most expensive part (p retailprice).</li>

 <li>Find the supplier-customer pair(s) with the least expensive (o totalprice) order(s) completed (F in o orderstatus). Print the supplier name, the customer name, and the total price.</li>

 <li>Find how many suppliers have less than 50 distinct orders from customers in GERMANY and FRANCE</li>

 <li>Find how many distinct customers have at least one order supplied exclusively by suppliers fromAMERICA.</li>

 <li>Find the distinct parts (p name) ordered by customers from AMERICA that are supplied by exactly 3 suppliers from ASIA.</li>

 <li>Find the region where customers spend the smallest amount of money (l extendedprice) buying items from suppliers in the same region.</li>

 <li>Find the nation(s) with the smallest number of customers.</li>

 <li>Find the nation(s) having customers that spend the smallest amount of money (o totalprice).</li>

 <li>Find the nation(s) with the most developed industry, i.e., selling items totaling the largest amount ofmoney (l extendedprice) in 1994 (l shipdate).</li>

 <li>Compute, for every country, the value of economic exchange, i.e., the difference between the numberof items from suppliers in that country sold to customers in other countries and the number of items bought by local customers from foreign suppliers in 1994 (l shipdate).</li>

 <li>Compute the change in the economic exchange for every country between 1994 and 1996. There should be two columns in the output for every country: 1995 and 1996. Hint: use CASE to select the values in the result.</li>

</ol>

In order to complete the lab you have to perform the following tasks:

<ol>

 <li>Write the SQL statement corresponding to every query in the file test/x.sql, where x is the number of the query above. Every query goes into its separate file. These are the only files you have to modify and submit in this assignment.</li>

 <li>You can check the correctness of your queries by executing the command ./test.sh in the terminal. You have to be in the main lab folder. The expected output is available in results/x.res, where x is the number of the query. The output produced by your code is available in output/x.out. They have to match for every query, e.g., res has to match with 1.out.</li>

 <li>In case there are any errors, repeat the process from step 1 for the incorrect queries.</li>

 <li>The submission consists of a compressed zip file that contains the files in the test The name of the file has to be lab-6.zip. When you create the file, include the folder test into the compression, not every file test/x.sql separately.</li>

</ol>

<em>Lab 6                                                                                                                                                                                                   </em>2