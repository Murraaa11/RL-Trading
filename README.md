# Self-adapting Trading Systems Based on Reinforcement Learning

The project aimed to build self-adapting trading systems using reinforcement learning techniques in order
to maximize the profit. I constructed these trading systems by different settings (discounted setting and
average-reward setting), control algorithms (SARSA and Q-Learning), reward functions (daily return and
Differential Sharpe Ratio) and state spaces. The project assumed the trader can only take short or long position by
a fixed magnitude for the action space. All the systems were simulated on two stock return series and one
index return series, and some metrics were used to evaluate their performance in terms of profit and risk.
I also set two simple baseline strategies for comparison. Results showed that these trading systems
could provide satisfactory profit for regular time series of return, while for irregular and volatile ones they
performed poorly most of the time.

