Download Link: https://assignmentchef.com/product/solved-blg335e-homework-1-quicksort
<br>
<h2>Part 1. Implementation</h2>

You are given a dataset where the global sales of different products are reported. There are following attributes in dataset:

Country: Country that sells the product                                   Units Sold: Number of units that is sold

Item Type: Type of the product                                               Total Profit: Profit obtained from order

Order ID: Unique ID for each order

You are supposed to sort the orders in alphabetical order in terms of the name of country. For the orders that have the same country name you should sort them in descending order of total profits. You must use regular Quicksort as the sorting algorithm.

Your code must run with the following command:                       ./a.out N

N: number of the sales to be sorted (You can just take the first N entries from the file)

After the execution, a message including the elapsed time of execution should be printed out and you should write the sales in sorted order into sorted.txt file with the same format.

<h2>Part 2. Report</h2>

<ol>

 <li>Write down the asymptotic upper bound for the Quicksort for best case, worst case and average case. Prove them solving the recurrence equations.</li>

 <li> In implementation, we wanted to sort the sales by alphabetical order of country names and then by their total profits. Let’s assume that we are having this kind of method:

  <ul>

   <li>Sort the sales.txt data by the total profits and write it into sorted_by_profits.txt</li>

   <li>Sort the sorted_by_profits.txt data according to country names using QuickSort</li>

  </ul></li>

</ol>

Does this solution give us the desired output for all cases?

<ol>

 <li>Explain why or why not and give a simulation on a small fraction from the dataset (you may modify the results if necessary).</li>

 <li>Give 3 examples for the sorting algorithms that give the desired output.</li>

 <li>(15 points) Run the algorithm for different N values {10, 100, 1000, 10K, 100K, 500K, 1M} on sales.txt data and calculate the average time of running. (Run the algorithm 10 times for each N value and take the average execution time for each N value). Report the average execution times in a table and prepare an Excel plot which shows the N – runtime relation. Comment on the results considering the asymptotic bound that you have found in (a). (3-4 sentences)</li>

</ol>

Note: You can use the clock() function under ctime library for calculating time of execution for the search functions. Refer to http://www.cplusplus.com/reference/clibrary/ctime/clock for more details.

<ol>

 <li>) Run the algorithm for different N values {10, 100, 1000, 10K, 100K, 500K, 1M} on sorted.txt data and calculate the average time of running as you have done in (c). Report the results in a table and plot them similarly.</li>

 <li>Compare the results with the results you have obtained at (c) and explain the difference in detail referring the equations you have given in (a). (4-5 sentences)</li>

 <li>Which other input cases would give us the similar results? (1 sentence)</li>

 <li>Propose a solution to this case. (1 sentence)</li>

</ol>