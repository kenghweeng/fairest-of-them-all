# Who's the fairest of them all?

 
This repository provides a logistic regression implementation in Python for the fair classification mechanisms introduced in the <a href="http://arxiv.org/abs/1507.05259" target="_blank">AISTATS'17</a>, <a href="https://arxiv.org/abs/1610.08452" target="_blank">WWW'17</a> and <a href="https://arxiv.org/abs/1707.00010" target="_blank">NIPS'17</a> papers.

#### References
1. <a href="http://arxiv.org/abs/1507.05259" target="_blank">Fairness Constraints: Mechanisms for Fair Classification</a> <br>
Muhammad Bilal Zafar, Isabel Valera, Manuel Gomez Rodriguez, Krishna P. Gummadi. <br>
20th International Conference on Artificial Intelligence and Statistics (AISTATS), Fort Lauderdale, FL, April 2017.
 
 
2. <a href="https://arxiv.org/abs/1610.08452" target="_blank">Fairness Beyond Disparate Treatment & Disparate Impact: Learning Classification without Disparate Mistreatment</a> <br>
Muhammad Bilal Zafar, Isabel Valera, Manuel Gomez Rodriguez, Krishna P. Gummadi. <br>
26th International World Wide Web Conference (WWW), Perth, Australia, April 2017.


3. <a href="https://arxiv.org/abs/1707.00010" target="_blank">From Parity to Preference-based Notions of Fairness in Classification</a> <br>
Muhammad Bilal Zafar, Isabel Valera, Manuel Gomez Rodriguez, Krishna P. Gummadi, Adrian Weller. <br>
31st Conference on Neural Information Processing Systems (NIPS), Long Beach, CA, December 2017.

#### Dependencies 
1. [numpy, scipy](https://www.scipy.org/scipylib/download.html) and [matplotlib](http://matplotlib.org/) if you are only using the mechanisms introduced in [1].
2. Additionally, if you are using the mechanisms introduced in [2] and [3], then you also need to install [CVXPY](https://github.com/cvxgrp/cvxpy) and [DCCP](https://github.com/cvxgrp/dccp).

#### Using the code

1. If you want to learn more about impact parity as described in [1], please navigate to the directory "disparate_impact".
2. If you want to learn more about mistreatment parity as described in [2], please navigate to the directory "disparate_mistreatment".
2. If you want to learn more about group-based, Pareto-optimal classifiers as described in [3], please navigate to the directory "preferential_fairness".

Please cite the corresponding paper when using the code.
