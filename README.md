# kth from the end of a Linked List
A method added to our Linked List Class.

## Challenge
Write a method for our Linked List Class that takes in a number (k) and returns the value of the node that is (k) nodes from the tail of the list.

## Approach & Efficiency
With the help of TA Brea, Nikki and I worked together on this problem.  We went with the most efficient way whcih was to have the current value which holds the calue of the heads, the forward value which moves ahead once every time that 'k' is not equal to null.  The runner goes along one behind the current value which we take forward untiil it hits null, and then the counter is pointing at the value we want and thus we return counter.
## Solution
![whiteboard](./assets/)07codeChallenge.png)