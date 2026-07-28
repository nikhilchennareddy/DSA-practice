/**

LeetCode 121 - Best Time To Buy and Sell Stock
https://leetcode.com/problems/best-time-to-buy-and-sell-stock/

Pattern: running minimum, single pass

v1 - solveBrute - compare every pair (i, j) where j > i
Time: O(n^2) Space: O(1)
Verdict: Time Limit Exceeded past ~10^4 elements

v2 - solve - track the lowest price seen so far; profit = price - minSoFar
Time: O(n) Space: O(1)
Verdict: accepted


Insight: you never need to look backwards - the cheapest price so far is all the history that matters
Gotcha: compute profit BEFORE updating minSoFar, or you sell on the same day
Solved: 2026-07-28 | 30 mins | hint needed: no

**/
