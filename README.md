** AI-Based-Rock-Paper-Scissors-Game **
implementation of an AI-based RPS game that attempts to predict human behavior by adapting to the player's moves.
The AI system picks up a pattern of previously played rounds to make a prediction on the next move the player will make. 
By factoring in patterns, and focusing on the most recent rounds played, the AI maximizes the opportunity to win. 
The success of this game lends credibility to the notion that even simple prediction algorithms can enable the design of games that are far more interesting to-and competitive with-players.


Examples of Prediction 
Case 1: Repetition

The user consistently chooses Scissors (S) in every round.
The AI’s prediction system learns that the user has frequently used Scissors in the past few rounds, and based on this pattern, it predicts that the user will continue choosing Scissors.
As a counter, the AI selects Rock, which beats Scissors, leading to multiple consecutive wins for the AI.



![image](https://github.com/user-attachments/assets/c29cfef9-bda5-4954-9be4-e5e28edb7e09)




Case 2: Aggressive Switching

In Round 3, the user plays Rock (R), and the AI predicts that the user will choose Rock. However, the AI plays Paper and wins.
In Rounds 4, 5, and 6, the AI’s predictions appear to be correct, but the outcomes result in draws because both the AI and the user played the same move (e.g., the AI predicted Scissors (S) and played Scissors when the user also chose Scissors).

![image](https://github.com/user-attachments/assets/f45b1450-fb30-478a-a610-9db9ea06dae3)




Case 3: Cycle Pattern
![image](https://github.com/user-attachments/assets/427d8b4b-7fa3-4523-b233-8ec3edaf95d2)


User Strategy: The user is cycling between Rock (R), Paper (P), and Scissors (S) in a consistent pattern.
Expected AI Behavior: The AI should start recognizing this pattern after a few rounds and adjust its predictions accordingly to counter the user’s move.
Round 1:The AI incorrectly predicts Paper for our move, but we chose Rock, so the AI's counter (Scissors) loses.
Round 2:The AI predicted Rock, but we played Paper. The AI also chose Paper, resulting in a draw.
Round 3:The AI predicted Scissors, and we played Scissors. The AI correctly countered by playing Rock and won this round.
Round 4:The AI predicted Rock and countered correctly by playing Paper, resulting in another win for the AI.
Round 5:The AI predicted Paper and countered with Scissors, leading to another win for the AI.
Round 6: The AI again predicts correctly that we will choose Scissors, and counters with Rock for another win.
Analysis:
After the first couple of rounds, the AI starts detecting your cycle pattern (Rock→Paper→Scissors) and successfully predicts your moves.
By Round 3, the AI correctly predicts your choice of Scissors and plays Rock to win.
From Round 3 onward, the AI consistently predicts your next move based on the pattern and counters it effectively.



Results
The artificial intelligence performed under these conditions when the participant utilized a constant, repetitive, or cyclical strategy. AI predictively made the players' next move with high accuracy and was more likely to win. In fact, there were participants who would simply use one move, Scissors continuously, and adapt it by using the Rock against them. If the player progresses through a rotation pattern, the AI adjusts its tactic by predicting the next action in the cycle.
The game history feature allowed for reviewing previous rounds, showing how the AI’s predictions evolved over time. By focusing on recent moves, the AI became more competitive, offering a greater challenge to the player.





