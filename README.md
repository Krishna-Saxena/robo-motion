# robo-motion
Visualizations of OptimuS-VD Prime's timeseries data projected to lower dimensional space and transformed back to a timeseries.

From the data matrix $X \in \mathbb[R]^{15×11400}$, we first calculate the PCA of $\bar{X} := X-\vec{\mu}$, $\bar{X} = U \Sigma V^T$

- POD Modes: gifs of the first 5 POD modes
	1. [First POD Mode](https://github.com/Krishna-Saxena/robo-motion/blob/main/POD_Mode_1.gif)
	2. [Second POD Mode](https://github.com/Krishna-Saxena/robo-motion/blob/main/POD_Mode_2.gif)
	3. [Third POD Mode](https://github.com/Krishna-Saxena/robo-motion/blob/main/POD_Mode_3.gif)
	4. [Fourth POD Mode](https://github.com/Krishna-Saxena/robo-motion/blob/main/POD_Mode_4.gif)
	5. [Fifth POD Mode](https://github.com/Krishna-Saxena/robo-motion/blob/main/POD_Mode_5.gif)
- [Jumping Animation](https://github.com/Krishna-Saxena/robo-motion/blob/main/Low_Dim_Jumping.gif): a gif of the mean of jumping data projected onto 5 POD modes and transformed back to a timeseries
- [Running Animation](https://github.com/Krishna-Saxena/robo-motion/blob/main/Low_Dim_Running.gif): a gif of the mean of running data projected onto 5 POD modes and transformed back to a timeseries
- [Walking Animation](https://github.com/Krishna-Saxena/robo-motion/blob/main/Low_Dim_Walking.gif): a gif of the mean of walking data projected onto 5 POD modes and transformed back to a timeseries
