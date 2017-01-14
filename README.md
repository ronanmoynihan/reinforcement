### Model-Based RL 
Adapting the [cartpole tutorial](https://medium.com/@awjuliani/simple-reinforcement-learning-with-tensorflow-part-3-model-based-rl-9a6fe0cce99#.azb6u5164) to work with [Flappy Bird](https://gym.openai.com/envs/FlappyBird-v0).  

### Install
- https://github.com/lusob/gym-ple

### Game State
The cartpole state consists of 4 continous features. Flappy Bird currently uses 5.

- player y position / 512
- players velocity / 10
- next pipe distance to player / 288
- next pipe top y position / 512
- next pipe bottom y position / 512

(Screen size - 512 x 288)