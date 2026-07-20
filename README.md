# Longest Valid Parentheses

## Problem Statement:
Given a string containing only '(' and ')', return the length of the longest valid parentheses substring.

## Approach:
I used a stack-based approach.
- Initialize the stack with -1.
- Traverse the string.
- Push the index of every '('.
- For every ')', pop one index.
- If the stack becomes empty, push the current index as a new boundary.
- Otherwise calculate the current valid substring length.
- Keep track of the maximum length.

## Algorithm:
1. Initialize stack = [-1]
2. Traverse the string.
3. Push index of '('.
4. Pop for ')'.
5. If stack is empty, push current index.
6. Else update maximum length.
7. Return maximum length.

## Time Complexity:
O(n)

## Space Complexity:
O(n)
