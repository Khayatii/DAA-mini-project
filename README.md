# DAA-mini-project
## Project Title - DNA Sequence Matching

The problem of DNA sequence matching involves identifying similarities between two or more DNA sequences. This is an important problem in genetics and bioinformatics, as it helps researchers understand the relationship between different organisms and the function of specific genes.One popular algorithm for solving this problem is the Longest Common Subsequence (LCS) algorithm, which identifies the longest subsequence that is common to two or more sequences. The LCS algorithm can be implemented using both dynamic and recursive approaches.In the dynamic approach, we use a two-dimensional array to store the lengths of the LCS between all possible pairs of prefixes of the input sequences. We then use this array to construct the LCS by backtracking from the bottom-right corner to the top-left corner.In the recursive approach, we define a recursive function that computes the LCS of two sequences by breaking the sequences into smaller and smaller subproblems. We then memoize the results of these subproblems to avoid redundant computation.
