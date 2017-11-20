# Combinations-Once-Again

Combinations, Once Again

Description

Given n objects you'd have to tell how many different groups can be chosen if r objects are taken at a time.
Input

Input consists of less than 100 test cases. Each test case begins with two integers n (0 < n <= 50), m (0 <= m <= n). The next line will contain the labels (numbers in the range 1 to n) of the n objects you are to choose from. Two objects with the same label are considered equivalent. Then in the last line for that test case, you'd have m values for r. There will be a single space separating two consecutive numbers in a line. Input is terminated by a test case where n=0, you must not process this test case.
Output

For each test case, print the test case number. And for each query number r, print the number of different groups that can be formed if r objects are taken from the given n objects. You can assume that for all input cases, the output will always fit in a 64-bit unsigned integer and (0<=r<=n).

Sample Input

5 2
1 2 3 4 5
2 1

4 1
1 2 3 4 
2

0 0

Sample Output

Case 1:
10
5
Case 2:
6
