Practical 5: Sequence Analysis


Aim: Implement Longest Common Subsequence (LCS) algorithm to find the length and LCS
for DNA sequences.


Task 1: Similarity between two sequences (LCS)

Objective:
Determine the Longest Common Subsequence (LCS) between two given sequences.

Description:

A subsequence is a sequence derived from another sequence by deleting some elements without changing the order of the remaining elements.

A common subsequence is a subsequence present in both sequences.

The LCS is the longest sequence that appears in both sequences.

Given:

X = AGCCCTAAGGGCTACCTAGCTT
Y = GACAGCCTACAAGCGTTAGCTTG


Expected Outcomes:

A cost matrix showing the LCS computation process, including directions.

The final cost, i.e., the length of the LCS.

The LCS string itself.

Task 2: Longest Repeating Subsequence (LRS)

Objective:
Find the Longest Repeating Subsequence (LRS) in a single string.

Description:

The LRS is a subsequence that appears at least twice in the string without overlapping the same character index.

It is a variation of the LCS problem where the string is compared with itself.

Example:

S = AABCBDC
LRS = ABC or ABD


Expected Outcomes:

Identification of the longest repeating subsequence.

Explanation of the subsequence and its length.

Key Concepts

Subsequence: Elements of a sequence selected without changing their relative order.

Common Subsequence: Subsequence present in two or more sequences.

LCS: Longest sequence present in both sequences.

LRS: Longest sequence repeating within the same string.
