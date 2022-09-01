# MDP
<sub> Submitted on September 1, 2022 </sub>
--------------------------
## Scenario number 1
Create an MDP. Remember to describe the states, actions and rewards. Make sure your three MDPs are different from each other.

  - **MDP**: Simplified version of Frozen Lake: The goal of this game is to go from start state (S) to goal state (G) and avoid the hole (H) by just walking on the frozen tiles (F).

  - **State**: In this game, there is a 4 x 4 grid marked with numbers 0 to 15. This number represents the location of the agent. The game ends when the agent is placed on the G or H houses (episodic).

  - **Actions**: The action space of the agent is specified by the numbers 0 to 3. 0 is considered for moving the agent up, 1 for moving the agent to the left, 2 for moving the agent down, and 3 for moving the agent to the right. (If the agent is in a place that is unable to move left (for example) movement and is ordered to go left, the agent will remain in the previous location without moving.)

  - **Reward**: The agent gets -1 point as a reward by going to the places labeled with the letter H, which represent holes, and +1 point by going to the house marked with the letter G. Moving on frozen areas (F) has no particular points for the agent.
--------------------------
## Scenario number 2
Create an MDP. Remember to describe the states, actions and rewards. Make sure your three MDPs are different from each other.

   - **MDP**: A pole is connected by a non-actuated joint to a cart that moves along a frictionless track. The pendulum starts vertically, and the goal is to prevent it from falling by increasing and decreasing the trolley's speed. (episodic)

   - **State**: The state space is specified as a table, as shown below. 
      | Num | Observation          | Min                 | Max               |
      |-----|----------------------|---------------------|-------------------|
      | 0   | Cart Position        | -2.4                | 2.4               |
      | 1   | Cart Velocity        | -Inf                | Inf               |
      | 2   | Pole Angle           | ~ -0.418 rad (-24°) | ~ 0.418 rad (24°) |
      | 3   | Pole Velocity At Tip | -Inf                | Inf               |
      
     The game will finish when the Pole Angle is not in the range of min and max written in the above table.

   - **Actions**: The action space is minimal and actually has only two members. The numbers 0 and 1 are members of this space. 0 for the pushing cart to the left and 1 for pushing the cart to the right

   - **Reward**: Reward is 1 for every step, including the termination step. The threshold is 475 for v1.

--------------------------
## Scenario number 3
Create an MDP. Remember to describe the states, actions and rewards. Make sure your three MDPs are different from each other.

   - **MDP**: Chess game with all rules. It can be an example of an episodic MDP.

   - **State**: The position of the pieces on the chess board clearly tells the state.

   - **Actions**: Each piece in a chess game can take several moves regardless of its position. A set that includes all these movements will be the action space. But in each state, the available actions are part of this space of actions.

   - **Reward**: The game ends with three modes. A win in chess gets +1 point. A loss gets -1 point, and a tie receives no points.
