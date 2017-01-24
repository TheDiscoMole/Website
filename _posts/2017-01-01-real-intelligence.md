---
layout: post
title:  "Real Intelligence"
date:   2017-01-01
excerpt: "My silly attempt at Consciousness."
project: true
tag:
- Artificial Intelligence 
- Neurogenesis
- Synaptogenesis
- Recursion
- Parallelism
comments: false
---

Micro Controllers, Monte Carlo, Random Forest and Data Science Graph Algorithms are all based on conceptual ideas that become increasingly disappointing the more one understands and learns to use them, and as the problems we try to tackle with computational power enter the space imposibility for expert systems the desire for real, human level, AI appears evident. The most promising potential in pattern deriving logic is of course the Neural Network with *some* genetic algorithms lagging behind as close second, but there are still a number of problems before human level cognition can be achieved. Some problems are arbitrary and will solve themselves over time, wheras others require intuitively creative, yet logically rigorous solutions.

------------------------------------------------------------

So what makes up a strong Neural Network?

* **Neurons** act as proxies for approximated real world concepts and are a mostly solved part of the problem. By summing the synaptic inputs and activating over a sigmoidal function a probabilistic, standard deviation-like behaviour emerges in each information processing step.

* **Synapses** represent how concepts relate to one another and are also pretty much completely understood. They take a Neural output and feed it into an output neural over multiplicative weight, simulating linear function over each data-point relationship.

* **Loss** is the error feedback over which the network learns and readjusts to state evaluations. Loss functions such as binary-cross-entropy for true false feedback and MSE for pretty much everything else are used to deduce error gradients against target data.

* **Neurogenesis**, the brains capability to grow and prune existing neural structures has had essentially no real break-throughs in AI programming appart from some [NEAT](https://en.wikipedia.org/wiki/Neuroevolution_of_augmenting_topologies) genetic algorithms which end up sacrificing gradient descent or not making it take part in the action.

* **Synaptogenesis** which allows our brain to relate previously unrelated conceptual knowledge by growing, pruning and updating synaptic connections is doing alright with the emergence of Gradient Descent which allows for very clean and computationally fast weight updates. But again, appart from some rough Genetic Algorithms, network rewiring isn't really going anywhere.

------------------------------------------------------------

Here is what I am working on:

* **Neurogenesis** & **Synaptogenesis**: Finishing Stages. My Neural Networks can grow, shrink, rewire themselves and update synaptic weights in one *relatively* clean parallel algorithm. Currently working on a scalable CUDA implementation that can learn from real data-streams in real-time. (unfortunately due to needed hardware functionality which not supported by current GPU & CPU technology, a lot of the growing and pruning has to be handled in Host)

* **Loss-less Net**: Prototyping stages. The Network will be able to learn without the **need** (having tagged data will always help) for training data or loss gradients. This currently works, but is not really at implementation stage for scalable code yet. It require restucturing the current design paradigm for my above-mentioned Neural Net quite a bit. 

* **Fractalisation**: Concept stages. Using inheritance, the network objects will ideally become completely self similar and allowing for growing, pruning and rewiring of entirely interconnected sub-graphs, and thus, higher level learning.

* **Distributability** Concept stages. By implementing several communication interfaces for Neurons (DMA & ZMQ), a network should become able to be hosted over different sets of hardware at all times.