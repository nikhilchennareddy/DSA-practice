// LeetCode <NUMBER> — <Problem Title>
// https://leetcode.com/problems/<slug>/
//
// Pattern:  <must match a filename in notes/ exactly, e.g. "sliding window">
// Approach: <one or two lines — what the algorithm actually does>
// Time:     O(?)      Space: O(?)
//
// Insight:  <why the naive approach is wasteful and what this exploits>
// Gotcha:   <the thing that broke the first time you ran it>
// Solved:   <YYYY-MM-DD> | <minutes> min | hint needed: <yes/no>

import java.util.*;

public class Template {

    // ---------- solution ----------

    static int solve(int[] nums) {
        // your code
        return 0;
    }

    // ---------- local tests ----------
    // Expected value in a trailing comment, so a wrong answer is obvious
    // without reading back through the problem statement.

    public static void main(String[] args) {
        System.out.println(solve(new int[]{1, 2, 3}));   // expected: 6
        System.out.println(solve(new int[]{}));          // expected: 0   <- edge case
        System.out.println(solve(new int[]{-5}));        // expected: -5  <- edge case
    }
}
