# Data-Structure
#GoldMan Sachs Coding Problem---->

#Valid String--->

There is a town named Chefland where Chef lives. One can only enter the Chefland through visa which is granted by head Chef of the town named Chef Sanjeev Kapoor. Chef Sanjeev is very interested in the validation of string.
Hence he devised a test to get into the Chefland. Chef Sanjeev Kapoor considers a string to be valid if all characters of the string appear the same number of times. It is also valid if he can remove just 1 character at 1 index in the string, and the remaining characters will occur the same number of times. Given a string S, determine if it is valid. If so, return YES, otherwise return NO.
For example, if S="abc", it is a valid string because frequencies are {a:1, b:1,c:1}. So is S="abcc" because we can remove one c and have 1 of each character in the remaining string. If S="abccc" however, the string is not valid as we can only remove 1 occurrence of c. That would leave character frequencies of {a:1, b:1, c:2}.
Input Format:
A single string S.
Constraints:
1 ≤ |S| ≤ 100000
Each character s[i] belongs to [a-z]
Time limit = 1 sec
Output Format:
Print YES if string S is valid, otherwise, print NO. 
Sample Input 1:
aabbcd
Sample Output 1:
NO
Sample Input 2:
abcdefghhgfedecba
Sample Output 2:
YES
Explanation:
For testcase 2:
All characters occur twice except for e which occurs 3 times. We can delete one instance of e to have a valid string.
