## **Innocent Gad -183419**

**Question 1**

The big O notation is used to describe the complexity or the performance of an algorithm. The main rules are as follows;

1. **Dropping constants**

The Big O notation ignores constant factors  since they don’t necessarily affect the the  growth rate .for example if an algorithm has  a time complexity of 2n + 5n , the constants that is 2 and 5 are dropped  this is because as n grows large they become negligible.

2. **Keeping the Dominant terms**

Here only the term that grows the fastest as n increases is kept for example  for a time  complexity of n2 +3n + 2, the dominant term here is n2  hence the Big O is O (n2) since n2 grows faster than 3n  and 2 as n increases.

3. **Ignoring lower order terms**

Lower order terms are dropped  for simplicity and since they have less impact as n becomes very large for example  an algorithm complexity n3 + n2 simplifies to O(n3) the n2 term is ignored since it grows slower than n3.

4 **Analyzing Loops**

for eg;   

for(int i= o ;i<n; i++) { } here the loop runs n times hence time complexity is O(n)

5. **Worst case matters**

The Big O focuses on the worst case scenario for example ;

in a linear search of an array with n elements , the worst case happens when the desired element is at the very end or  not found , hence making the time complexity O(n).
