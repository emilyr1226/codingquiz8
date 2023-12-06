# codingquiz8
Staircase:
The time complexity of staircase is O(n). This is because we have constant initalization of variables. Then, we have a for-loop with constant work inside, which is linear. Thus, the time complexity is linear.
The space complexity of staircase is O(1). This is because we do not use any more space than the input.

Alternating Characters:
The recursive definition for alternating characters is if the string is less than 2 characters, then return 0 since it not possible for 2 of the same letters to be adjacent to one another in this case and this means we are done traversing the string. However, otherwise, if the last two letters are the same, then increase the counter (number of deletions needed). If the last two letters are not the same, then do not increase the counter. The time complexity of alternating characters would be O(2^n) since we have n length of our input string and there are 2 recursive calls that are happening (one if the two letters are the same and one if not). The space complexity of alternating characters would also be O(2^n) because of our recursive calls.
