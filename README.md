# Reinforcement-Learning

Restored pretrained model (Cornell Movie Script Model) that converged at 56 Epochs and preformed 8 tests for 3 batch lengths resulting in 24 simulations.

Parameters
Trained at 5, 6, 25, 26 & 50 Epochs
Trained with Batch sizes of 1 and 10
Trained with learning rate of 0.01 and 0.0001

Evaluation
The tests will be evaluated by surveying 5 individuals and having them score each of the bots responses, we will call this score comprehension. A short script of 12 messages from the Dark Knight movie are used as the input. The entire scripts scores are averaged to get a final score for each test.

Each response with get one of the following
0 for not making any sense
0.5 for making some sense
1 for responding appropriately
