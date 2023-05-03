Download Link: https://assignmentchef.com/product/solved-cs2211a-assignment-3
<br>
<h1>Program 1 (35 marks)</h1>

<strong><em>Draw a flowchart</em></strong> and develop a C program that <strong><em>ask</em> </strong>the user to enter two integers. The first integer value represents a<em> time of day</em> on a 24-hour clock, e.g., 1345 represents quarter to two mid-day. The second integer represents <em>time duration</em> in a similar way, e.g., 345 represents 3 hours and 45 minutes. <u>Note that, 2520 and 2372</u> <u>are not valid <em>time of day</em></u>. <u>Note also that 2372 is not valid <em>time duration</em>, but 2520 is valid <em>time duration</em></u>. The time duration can be <em>positive</em> or <em>negative</em>. Your program should loop until getting a valid <em>time of day</em> and a <em>time duration</em>.

The program will add the <em>time duration</em> to the <em>time of day</em>, and the result is printed out in the same notation (<em><u>always as a valid 4 digit time</u></em>). For example, in the above case, the answer should be 1730, which is the time at 3 hours and 45 minutes after 1345. You should consider cases like: starting time is 2300 and duration is 200. In this case, the end time will be 0100, not 2500.

Add as many inline comments in your program as you can to make it well documented and easy to be understood by anyone who reads it.

Test your program using <em>at least</em> these cases (include the <em>actual</em> <em>sample outputs</em> in your submission)

<strong>456 -500 </strong>

<strong>1234 +3750 </strong>

<strong>1234 –3750 </strong>

<strong>1234 –1250 </strong>

<strong>123 +456 </strong>

<strong>3 +4 </strong>

<strong> </strong>

Show what will happen when you enter the following values as a time of a day:

<strong>6420  </strong>

<strong>2064 </strong>

<strong>-6420  </strong>

<strong>-2064 </strong>

<strong> </strong>

Show what will happen when you enter the following values as duration:

<strong>+2064 </strong>

<strong>-2064 </strong>

<h1>Program 2 (30 marks)</h1>

<strong><em>Draw a flowchart</em></strong> and develop a C program that calculates the remaining balance on a loan after each of the first <em>n</em> monthly payments. Your program should <strong><em>ask</em> </strong>the user to enter the <u>amount of loan</u>, the <u>yearly interest rate</u>, the <u>monthly payment</u>, and <em><u>n</u></em><u> (the number of monthly payments)</u>. Display each balance with <em><u>two digits</u></em> after the decimal point. <u>Your program should make sure that all entered numbers are positive and valid</u>. <u>Your program</u> <u>should loop until getting positive values.</u>

<strong><em>Do not use arrays in this program. </em></strong>

Hint: each month, the balance is increased by the current balance times the monthly interest rate, and then decreased by the amount of the payment. Assume that the monthly interest rate is just the yearly interest rate divided by 12.

For example, if the loan is $1000, the yearly interest rate is 12%, the monthly payment is $100, and <em>n</em> is 3, then the balance after the first month is $1000 + $1000 × 1% – $100 = $910.00, the balance after the second month is $910 + $910 × 1% – $100 = $819.10, and the balance after the third payment is $819.10 + $819.10 × 1% – $100  = $727.29.

Your program should deal with cases like payment of $800 for example. In this case, the balance after the first month is $1000 + $1000 × 1% – $800 = $210.00, the balance after the second month is $210 + $210 × 1% – $212.10 = $0.00 (<em>yes, this payment is just $212.10, not $800</em>), and there will be no more payments, as the balance reached $0.00. <u>In a case like that, you should report the amount of the last payment</u>.

Add as many inline comments in your program as you can to make it well documented and easy to be understood by anyone who reads it.

Use your program to print the balance after each of the first 15 payments of a $12345 loan if the yearly interest rate is %12, and the monthly payment is $1234. Include the <em>actual</em> <em>output.</em>

Use your program to print the balance after each of the first 15 payments of a $12345 loan if the yearly interest rate is %12, and the monthly payment is $543.21. Include the <em>actual</em> <em>output.</em>

Use your program to print the balance after each of the first 15 payments of a $54321 loan if the yearly interest rate is %12, and the monthly payment is $543.21. Include the <em>actual</em> <em>output.</em>

Use your program to print the balance after each of the first 15 payments of a $54321 loan if the yearly interest rate is %12, and the monthly payment is $321. Include the <em>actual</em> <em>output.</em>

<h1>Program 3 (35 marks)</h1>

The value of the mathematical constant <em>e, </em>which is 2.718281828459045<strong>,</strong> can be approximated as an infinite series as follow:

<em>e = 1 + 1/1! + 1/2! + 1/3! + ….,  </em>

where <em>n! = 1×2×3×4×….×n.</em>

<strong><em>Draw a flowchart</em></strong> and develop a C program that approximates the value of the constant <em>e</em>. Your program should keep adding terms until the value of the current term to be added becomes less than a small <em><u>positive</u></em> floating-point number <u>entered by the user</u>. Your program should make sure that all entered value is positive and valid. Your program should loop until getting a positive value.

<strong><em>Do not use recursive functions in this program. </em></strong>

Test your program using the following floating-point numbers <em>(include the input value and the actual output). </em>

0.01,

0.001,

0.0001,

0.00001,

0.000001,

0.0000001,

0.00000001,

0.000000001,

0.0000000001, and

0.00000000001

Your program should <em><u>print the approximated value of e to 15 digits after the decimal</u></em>, as well as <em><u>the number of</u> <u>terms required to generate this value</u></em>.

Add as many inline comments in your program as you can to make it well documented and easy to be understood by anyone who reads it.