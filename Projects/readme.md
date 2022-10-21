# Deep Reinforcement Learning Crash Course Projects 

In this directory, I try to share the projects I learned and implemented from [Nicholas Renotte](https://www.youtube.com/c/NicholasRenotte)'s crash course. I try to provide a brief description of each project in this section so that you can easily find the project you want.

## First session
**environment**:[`"CartPole-v0"`](https://github.com/openai/gym/wiki/CartPole-v0)

**Target**:Balance the  pole on the cart

**Reinforcement learning algorithm**: DQNAgent

**Further Details**:
Regarding the environment, I should say that An unactuated joint attaches a pole to a cart, which moves along a frictionless track. The pendulum starts upright, and the goal is to prevent it from falling over by increasing and reducing the cart's velocity.

**Observation**:
| **Num** |       **Action**       |       **Min**       |      **Max**      |
|:-------:|:----------------------:|:-------------------:|:-----------------:|
| 0       | Push cart to the left  | -2.4                | 2.4               |
| 1       | Push cart to the right | -Inf                | Inf               |
| 2       | Pole Angle             | ~ -0.418 rad (-24°) | ~ 0.418 rad (24°) |
| 3       | Pole Velocity At Tip   | -Inf                | Inf               |

**Actions**:
| **Num** |       **Action**       |
|:-------:|:----------------------:|
| 0       | Push cart to the left  |
| 1       | Push cart to the right |

## Second session

## Third session

This page is being edited...
