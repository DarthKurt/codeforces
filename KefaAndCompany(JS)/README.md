# Kefa and Company

##### **Source**: https://codeforces.com

Kefa wants to celebrate his first big salary by going to restaurant. However, he needs company.

Kefa has n friends, each friend will agree to go to the restaurant if Kefa asks. Each friend is characterized by the amount of money he has and the friendship factor in respect to Kefa. The parrot doesn't want any friend to feel poor compared to somebody else in the company (Kefa doesn't count). A friend feels poor if in the company there is someone who has at least d units of money more than he does. Also, Kefa wants the total friendship factor of the members of the company to be maximum. Help him invite an optimal company!

##### **Input**
The first line of the input contains two space-separated integers, n and d (1 ≤ n ≤ 10^5, 1 ≤ d ≤ 10^9 ) — the number of Kefa's friends and the minimum difference between the amount of money in order to feel poor, respectively.

Next n lines contain the descriptions of Kefa's friends, the (i + 1)-th line contains the description of the i-th friend of type mi, si (0 ≤ mi, si ≤ 10^9) — the amount of money and the friendship factor, respectively.

##### **Output**
Print the maximum total friendship factir that can be reached.