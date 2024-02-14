# Flow Matching for Generative Modeling
_notebook by Georges Le Bellier_  - [Twitter](https://twitter.com/_lebellig), [Website](https://gle-bellier.github.io)

⚠️ This is not the official implementation of the original paper.

This notebook centers around the **Flow Matching for Generative Modeling** article [1] and proposes an implementation of _Flow Matching_ in the case of _Optimal Transport conditional Vector Fields_. The implementation proposed in [2] was consulted and it inspired the use of the _Zuko_ [3] package for ODE solving and sampling. Moreover, this notebook adopts the notations of the original article and thus the numbers of the equations are the same as in the paper.

## References:

📄 [1] **Flow Matching for Generative Modeling** by Yaron Lipman, Ricky T. Q. Chen, Heli Ben-Hamu, Maximilian Nickel, Matt Le - [Article](https://arxiv.org/abs/2210.02747)

🐍 [2] **Flow Matching in 100 LOC** by François Rozet - [Implementation](https://gist.github.com/francois-rozet/fd6a820e052157f8ac6e2aa39e16c1aa)

🐍 [3] **Zuko** package - [Website](https://zuko.readthedocs.io/en/stable/index.html)
