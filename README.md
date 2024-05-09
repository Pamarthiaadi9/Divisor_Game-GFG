# Divisor_Game-GFG
Alice and Bob take turns playing a game, with Alice starting first.
Initially, there is a number n on the chalkboard. On each player's turn, that player makes a move consisting of:

Choosing any x with 0 < x < n  and n % x == 0.
Replacing the number n on the chalkboard with n - x.
Also, if a player cannot make a move, they lose the game.
Return true if and only if Alice wins the game, assuming both players play optimally.
![image](https://github.com/Pamarthiaadi9/Divisor_Game-GFG/assets/105631285/fcebdd92-c1dc-47e0-8790-fb4f131e3542)

Your Task:
You don't need to read input or print anything. Your task is to complete the function divisorGame() which takes an integer n as a parameter and returns true if Alice wins the game.

Expected Time Complexity: O(1)
Expected Auxiliary Space: O(1)

Constraints:
1 ≤ n ≤ 103

