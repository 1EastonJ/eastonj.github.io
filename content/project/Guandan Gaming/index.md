---
title: Nash Equilibrium Guandan
---

**May 2024 - Sept. 2024**  
**Advisor:** Prof. Kani Chen (Financial Mathematics, HKUST)
<!--more-->
- Worked under Professor Ka-Ni Chan at the Hong Kong University of Science and Technology to develop an AI agent for the card game “Guandan.” Our goal was to create a platform that combined Guandan teaching with gameplay.  
- Used the DMC (Deep Monte Carlo) model for a foundation, and worked to incorporate additional rules in hopes that the AI agent would surpass human-level gameplay. However, the final model achieved a win rate of only 70%. 
- Experimented with using MCTS (Monte Carlo Tree Search) to find the optimal strategy for the Jianzi game, but the method proved to be limited due to the large variety of card types and the high-dimensional action space.   

**Contributions:**
1. Adjusted the penalty for playing a bomb at the beginning of the game: reduced the penalty for strong hands and increased it for weak hands.  
2. Differentiated the penalty for straight flush (同花顺) and normal bombs, as their rankings differ significantly.  
3. Added a function to play counter cards (压牌) to prevent the opponent from sneaking away too many single cards or sequences straight.  
4. Noticed that the agent had an excessive tendency to play single cards, so I wrote a function to adjust this tendency.


<!--more-->
### Video Demo
Below is our Demo -- Playing Guandan on terminal:

<video width="640" height="380" controls>
  <source src="/uploads/guandan.mov" type="video/mp4">
  Your browser does not support the video tag.
</video>

