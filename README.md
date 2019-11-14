# lift-performance-with-learning-rate-schedule

Some of the tips and care I need to take when using learning rate schedule

**incease the initial learning rate:** Because the learning rate will decrease, start with a larger value to decrease from. A larger learning rate will result in a lot larger changes to the weights, at least in the beginning, allowing you to beneﬁt from ﬁne tuning later.  

**Use a large momentum:** Using a larger momentum value will help the optimization algorithm to continue to make updates in the right direction when your learning rate shrinks to small values. 

**Experiment with different schedules:** It will not be clear which learning rate schedule to use so try a few with diﬀerent conﬁguration options and see what works best on your problem. Also try schedules that change exponentially and even schedules that respond to the accuracy of your model on the training or test datasets.
