# DQN on Breakout

This project takes a simple DQN model and adapts it from *Pong* to *Breakout* using Gymnasium and ALE. The goal wasn’t to build a perfect agent, but to show how the agent’s behavior improves after a little training.

## What I Did

- **Environment Switch**: Changed from *Pong* (ALE/Pong-v5) to *Breakout* (ALE/Breakout-v5)
- **Model**: Kept the same DQN model, replay buffer, training loop, and wrappers
- **Training**: Ran a short training session to learn basic paddle control and handle longer rallies
- **Gameplay Clips**: Recorded two short clips to show progress

## Videos

- **Before Training**:  
  (https://github.com/suryaharshith-ship-it/DQN-on-New-Atari-Domains/blob/main/early.mp4)
  
- **After Training**:  
  (https://github.com/suryaharshith-ship-it/DQN-on-New-Atari-Domains/blob/main/later.mp4)


## Notes

- Breakout episodes end quickly early on, so even short clips show clear differences in paddle behavior.
- The goal was to show progress, not to build a perfect agent.
- Used epsilon-greedy exploration, frame stacking, and a standard DQN CNN for training.
