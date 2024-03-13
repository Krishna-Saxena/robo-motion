# robo-motion
Visualizations of OptimuS-VD Prime's timeseries data projected to lower dimensional space and transformed back to a timeseries.

From the data matrix $X \in \mathbb[R]^{15×11400}$, we first calculate the PCA of $\bar{X} := X-\vec{\mu}$, $\bar{X} = U \Sigma V^T$

- [Jumping Animation](https://github.com/Krishna-Saxena/robo-motion/blob/main/Low_Dim_Jumping.gif): a gif of the mean of jumping data projected onto 8 dimensions and reprojected
- [Running Animation](https://github.com/Krishna-Saxena/robo-motion/blob/main/Low_Dim_Running.gif): a gif of the mean of running data projected onto 8 dimensions and reprojected
- [Walking Animation](https://github.com/Krishna-Saxena/robo-motion/blob/main/Low_Dim_Walking.gif): a gif of the mean of running data projected onto 8 dimensions and reprojected
