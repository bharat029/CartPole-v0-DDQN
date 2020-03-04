# CartPole-v0 Solution

CartPole-v0 is an environment from OpenAI Gym. This is a simple Cart Pole problem, wehre the task is to keep a pole from falling. You get rewarded based on how long you can balance it.

I have used **Double Deep Q Networks (DDQN)** with the **Expected Sarsa** Update. As for Policy I used a **Softmax Policy** with temperature decay.

## Highlights
- Average reward of **200.0** (200 is the max possible reward in this environment) over 100 episodes.
- Trained on **100** episodes.