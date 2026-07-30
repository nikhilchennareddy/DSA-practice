// LeetCode <NUMBER> — <Problem Title>
// https://leetcode.com/problems/<slug>/
//
// Difficulty: <Easy/Medium/Hard>
// Pattern / Topic:  <must match a filename in notes/ exactly, e.g. "sliding window">
// Tags: <e.g. two-pointers, DP, graph, heap, binary-search>
// Summary: <1-2 sentence problem summary in your own words>
// Constraints: <n range, value ranges — important for complexity and choice of approach>
// Examples:
//   Input: <…>  Output: <…>  Explanation: <short>
//   Input: <…>  Output: <…>  Explanation: <short>
//
// Approach: <one or two lines — what the algorithm actually does (high-level)>
// Pseudocode / Steps:
//   1. ...
//   2. ...
//
// Time:     O(?)      Space: O(?)
// Complexity reasoning: <why time/space are as stated — mention dominating operations>
//
// Insight:  <why the naive approach is wasteful and what this exploits>
// Pitfalls: <the thing(s) that broke the first time you ran it (off-by-one, overflow, null, etc.)>
// Variants / Follow-ups: <related variants worth practicing>
// Related problems: <list of problem numbers/titles>
//
// Solved:   <YYYY-MM-DD> | <minutes> min | hint needed: <yes/no>
// Next:     <YYYY-MM-DD>   <- set from the table below; delete this line on a third clean run
// References: <links / discussion / solution posts>
//
// Review schedule (set Next: from how THIS attempt went):
//   How the last attempt went        Next in
//   Needed a hint                    3 days
//   Clean but slow or shaky          1 week
//   Clean and comfortable            3 weeks
//   Third clean run                  Retire — delete the Next: line

import java.util.*;

/* ---------- helper types (paste or refer as needed) ----------
class ListNode {
    int val; ListNode next;
    ListNode(int x) { val = x; }
}
class TreeNode {
    int val; TreeNode left, right;
    TreeNode(int x) { val = x; }
}
--------------------------------------------------------------- */

public class LeetCodeTemplate {

    // ---------- solution ----------
    // Rename method and signature to match problem if helpful.
    static int solve(int[] nums) {
        // Implementation
        return 0;
    }

    // If the problem returns a complex type, add overloaded helper methods
    // or sample converters (e.g., build ListNode from array).

    // ---------- tests / local harness ----------
    // Helper to print expected vs actual for easy visual diffs
    static void expect(String label, Object actual, Object expected) {
        System.out.printf("%s: actual=%s | expected=%s -> %s%n",
            label,
            String.valueOf(actual),
            String.valueOf(expected),
            Objects.equals(actual, expected) ? "OK" : "FAIL");
    }

    public static void main(String[] args) {
        // basic tests
        expect("Example1", solve(new int[]{1,2,3}), /* expected */ 6);
        // edge cases
        expect("Empty", solve(new int[]{}), /* expected */ 0);
        expect("SingleNeg", solve(new int[]{-5}), /* expected */ -5);
        // larger / stress case (optional)
        // expect("Large", solve(largeInput), /* expected */ ???);
    }
}
