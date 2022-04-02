# When to use narrow AI or heuristic to solve a problem?

Briefly:

    An AI solution is preferred to problems which are hard to be distilled mathematically
        Although the pursuit of AI is to solve any problem (i.e. domain generalization), a simple heuristic can sometimes be more time and memory efficient than an AI solution.
        The more you understand the problem, the less likely it's to be solved using an AI algorithm.
        Example: The Tower of Hanoi puzzle is a problem that can be solved using a reinforcement learning agent, but it's better solved through a recursive algorithm.
    An AI solution is preferred when the variables involved in the problem (input features predicting an output) don't follow a monotonic relationship and/or can't be linearised
        An AI solution is preferred for a task when a model has to capture the non-linear, non-monotonic relationship between input features and output.
        Models where there exists a linear or monotonic relationship between input features and output usually focus on their parameters' interpretability and explainability, while those that don't have such linear relationships care more about the accuracy of the models' predictions and optimal performance in a task.
        Input features that usually bear no relationship with the output usually correspond to unstructured data, while those which do display some sort of monotonic relationship are carefully-processed data, which may have research backing then up.
        Example: The task of cat image recognition based on input features consisting of pixels is better solved using an AI algorithm like deep learning. The task of coronary artery disease (CAD) detection based on known physiological features like age, gender or cholesterol levels are better solved using logistic regression.
    A symbiosis rather than zero-sum choice
        A purely AI solution may optimally solve a task and can generalize to different environments, but it may be time-consuming. A pure non-AI, heuristic solution may require too much understanding of a problem beforehand and can't be generalized. A mix of both strategies, such as what AlphaGo does by mixing reinforcement learning paradigm of environment interaction based on a tree-search heuristic can be better at solving a task. Albeit the creativity that is required to extrapolate the advantages of both the AI and non-AI paradigm may also be challenging.
    NP problems, Artificial General Intelligence and quantum computing
        It seems as though heuristics are preferred for polynomially-solvable problems since they aren't as cumbersome and time-consuming as AI-based solutions. What about NP problems?
        Will the above recommendations still be useful once we achieve Artificial General Intelligence?
        NP problems have the quality of being non-polynomial due to the fundamental, discrete, binary nature of computation. If quantum computing, which proposes that a state can be evaluated to different values at the same time, can simplify NP problems to P, then will all problems be solved through a simple, AI-General heuristic?

[^1]: I have to add "2022" because the pace in which AI algorithms and models are developing is exponentially fast (see The Singularity is Near, by Ray Kurzweil) to the point that by next year, or next 5 years, we just might witness an "Universal Algorithm" which allows a model to solve any kind of task and the whole argument of when to use AI to solve a problem is pointless.

In the notebook we distill each point in more detail and run few lines of code exploring this dichotomy
