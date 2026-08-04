// LeetCode <NUMBER> — <Problem Title>
// https://leetcode.com/problems/<slug>/
//

// Pattern:  <must match a filename in notes/ exactly, e.g. "sliding window">
// Key Idea:  <the one fact about this problem that makes a faster/simpler solution possible>
// Approach:  <the concrete steps that turn the Key Idea into working code>

// Pitfalls:  <the thing that broke the first time you ran it due to mistakes in logic / approach>
// Traps:     <mistakes baited by language / system >

// Time:     O(?)      Space: O(?)
// Execution Time: <Execution Time>

// v1 - solveBrute - description
// Time: O(?) Space: O(?)
// Verdict: Time Limit Exceeded past
// Execution Time: <Execution Time>

// v2 - solve - description
// Time: O(?) Space: O(?)
// Verdict: accepted
// Execution Time: <Execution Time>


// Solved:   <YYYY-MM-DD> | <minutes> min | hint needed: <yes/no> - retired (if Next is blank)
// Next:     <YYYY-MM-DD>

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

// Rename this class to match the filename (e.g. TwoSum.java -> public class TwoSum).
public class Template {

    // ---------- solution ----------

    static int solve(int[] nums) {
        // your code
        return 0;
    }

    // ---------- local tests ----------
    // Helper to print expected vs actual for easy visual diffs.
    // Uses deepEquals/deepToString so it works correctly for arrays too,
    // not just scalars (Objects.equals on int[] compares references).
    static void expect(String label, Object actual, Object expected) {
        boolean ok = Arrays.deepEquals(new Object[]{actual}, new Object[]{expected});
        System.out.printf("%s: actual=%s | expected=%s -> %s%n",
            label, str(actual), str(expected), ok ? "OK" : "FAIL");
    }

    static String str(Object o) {
        String s = Arrays.deepToString(new Object[]{o});
        return s.substring(1, s.length() - 1);
    }

    public static void main(String[] args) {
        // TODO: replace these with this problem's own examples and edge cases —
        // the calls below exercise the unfinished stub above, not a real solution.
        expect("Example1", solve(new int[]{1, 2, 3}), /* expected */ 6);
        expect("Empty", solve(new int[]{}), /* expected */ 0);         // edge case
        expect("SingleNeg", solve(new int[]{-5}), /* expected */ -5);  // edge case
    }
}
