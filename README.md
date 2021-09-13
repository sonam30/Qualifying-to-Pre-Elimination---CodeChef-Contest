# Qualifying-to-Pre-Elimination---CodeChef
Practice Contest on Codechef

<h2>Problem Statement</h2><br>
Snackdown 2019 is coming! There are two rounds (round A and round B) after the qualification round. From both of them, teams can qualify to the pre-elimination round. According to the rules, in each of these two rounds, teams are sorted in descending order by their score and each team with a score greater or equal to the score of the team at the K=1500-th place advances to the pre-elimination round (this means it is possible to have more than K qualified teams from each round in the case of one or more ties after the K-th place).

Today, the organizers ask you to count the number of teams which would qualify for the pre-elimination round from round A for a given value of K (possibly different from 1500). They provided the scores of all teams to you; you should ensure that all teams scoring at least as many points as the K-th team qualify.

<h3>Input</h3><br>
- The first line of the input contains a single integer T denoting the number of test cases. The description of T test cases follows.
- The first line of each test case contains two space-separated integers N and K.
- The second line contains N space-separated integers S1,S2,…,SN

<h3>Output</h3><br>
For each test case, print a single line containing one integer — the number of qualified teams.

<h3>Constraints</h3><br>
- 1≤T≤1,000
- 1≤K≤N≤105
- 1≤Si≤109 for each valid i
- the sum of N for all test cases does not exceed 10^{6} 

<h3>Example Input</h3><br>
2<br>
5 1<br>
3 5 2 4 5<br>
6 4<br>
6 5 4 3 2 1<br>


<h3>Example Output</h3><br>
2<br>
4
