**Farmer John’s Farm**
<br>
[ Memory: 64 MB, CPU: 1 sec ]

Farmer John, in the attempt to create more revenue, has turned his farm into a brand new hit TV show called “Farmer John’s Farm”. To watch the show, customers must sign up for a paid subscription service that costs d+K dollars (1 <= K <= 1,000,000,000) to subscribe for d consecutive days (where K is some fixed cost). You can start or cancel the subscription whenever you want and as many times as you want.

Farmer John’s favorite customer, Bob, wants to watch the show on N distinct days in the future. Given the dates Bob wants to watch the show on, determine the minimum cost that Bob must pay to watch the show on all of his desired days.  

INPUT FORMAT

Line 1: Two integers: N, the number of days, and K, the fixed cost of subscription.

Line 2: N space separated integers: the dates that Bob wishes to watch Farmer John’s Farm in ascending order 1 <= d_1 < d_2 < … < d_N <= 10^14.

OUTPUT FORMAT

Output a single integer, representing the minimum amount of money Bob must pay to watch on all N days.

SAMPLE INPUT
    
    3 5
    2 4 7
SAMPLE OUTPUT
    
    11
In this case, it is best to subscribe to Farmer John’s Farm for 6 days starting on day 2, yielding a total cost of 5+6 =11.

SAMPLE INPUT

    4 3
    1 6 7 9
SAMPLE OUTPUT

    11
In this test case, the optimal choice is to subscribe for 1 day starting on day 1 (incurring a cost of 1+3=4) and to subscribe for 4 days starting on day 6 (incurring a cost of 4+3=7) for a total cost of 11 dollars.

SCORING:<br>
Inputs 3-5: N <= 10
Inputs 6-12: No additional constraints.
<br>
<br>
MODE: normal<br>
Language: cpp<br>
