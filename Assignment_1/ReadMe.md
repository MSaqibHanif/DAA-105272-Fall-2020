## N Queen Problem using Brute-force

Brute-force algorithms are also known as exhaustive algorithms, they consist of testing all possibilities with 8 (or more) queens on a chessboard like that for the first one:

In this case a limit of 8 queens is set to end the test and rollback the last placed queen, the next posibility tested will be:

It is clear that this algorithm is uneficient because the second placed queen is already invalid and next positionned and tested queens are just a waste of time. No solution can be found with 2 queens on the 2 first positions for example.






