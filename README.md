# constraint-pure-exploration

Code for Pure-Exploration in Bandits with linear constraints accepted to AISTATS 2024 [link to paper](https://arxiv.org/abs/2306.12774). 

Cite as:


@InProceedings{pmlr-v238-carlsson24a,
  title = 	 { Pure Exploration in Bandits with Linear Constraints },
  author =       {Carlsson, Emil and Basu, Debabrota and Johansson, Fredrik and Dubhashi, Devdatt},
  booktitle = 	 {Proceedings of The 27th International Conference on Artificial Intelligence and Statistics},
  pages = 	 {334--342},
  year = 	 {2024},
  editor = 	 {Dasgupta, Sanjoy and Mandt, Stephan and Li, Yingzhen},
  volume = 	 {238},
  series = 	 {Proceedings of Machine Learning Research},
  month = 	 {May},
  publisher =    {PMLR},
  abstract = 	 { We address the problem of identifying the optimal policy with a fixed confidence level in a multi-armed bandit setup, when \emph{the arms are subject to linear constraints}. Unlike the standard best-arm identification problem which is well studied, the optimal policy in this case may not be deterministic and could mix between several arms. This changes the geometry of the problem which we characterize via an information-theoretic lower bound. We introduce two asymptotically optimal algorithms for this setting, one based on the Track-and-Stop method and the other based on a game-theoretic approach. Both these algorithms try to track an optimal allocation based on the lower bound and computed by a weighted projection onto the boundary of a normal cone. Finally, we provide empirical results that validate our bounds and visualize how constraints change the hardness of the problem. }
}
