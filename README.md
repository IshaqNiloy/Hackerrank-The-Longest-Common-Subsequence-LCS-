# Hackerrank-The-Longest-Common-Subsequence-LCS-
A subsequence is a sequence that can be derived from another sequence by deleting some elements without changing the order of the remaining elements. Longest common subsequence (LCS) of 2 sequences is a subsequence, with maximal length, which is common to both the sequences.

Given two sequence of integers,  and , find any one longest common subsequence.

In case multiple solutions exist, print any of them. It is guaranteed that at least one non-empty common subsequence will exist.

Input Format

First line contains two space separated integers,  and , where  is the size of sequence , while  is size of sequence . In next line there are  space separated integers representing sequence , and in third line there are  space separated integers representing sequence .

n m
A1 A2 … An 
B1 B2 … Bm  
Constraints





Output Format

Print the longest common subsequence and each element should be separated by at least one white-space. In case of multiple answers, print any one of them.

Sample Input

5 6
1 2 3 4 1
3 4 1 2 1 3
Sample Output

1 2 3
Explanation

There is no common subsequence with length larger than 3. And "1 2 3", "1 2 1", "3 4 1" are all correct answers.
