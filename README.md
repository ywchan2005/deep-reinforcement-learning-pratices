# Deep Reinforcement Learning Pratices

## Imitation Learning

### Results
Task: Ant-v1

![Ant-v1](https://github.com/ywchan2005/deep-reinforcement-learning-pratices/raw/master/imitation-learning/Ant-v1.gif)

Task: Humanoid-v1

![Humanoid-v1](https://github.com/ywchan2005/deep-reinforcement-learning-pratices/raw/master/imitation-learning/Humanoid-v1.gif)

Task: Hopper-v1

![Hopper-v1](https://github.com/ywchan2005/deep-reinforcement-learning-pratices/raw/master/imitation-learning/Hopper-v1.gif)

Task: HalfCheetah-v1

![HalfCheetah-v1](https://github.com/ywchan2005/deep-reinforcement-learning-pratices/raw/master/imitation-learning/HalfCheetah-v1.gif)

### Network Architecture Comparison
A number of network architectures are compared according to its losses and similiarity of distribution against the true values. All networks contain a single hidden layer, either fully connected with all inptus/outputs or connected to each output dimension separately and concatenated afterwards.

| | Standardized input | Number of Parameters | Loss (Training/Validation) | Similarity |
| - | :-: | :-: | :-: | :-: |
| Fully-connected | ✗ | 6,893,585 | .0412/.0369 | .0351 |
| Fully-connected | ✓ | 6,893,585 | .0350/.0385 | .0373 |
| Concatenated | ✓ | 413,457 | **.0056**/**.0069** | **.0129** |
| Concatenated | ✓ | 6,615,057 | .0091/.0113 | .0216 |

### License
MIT

