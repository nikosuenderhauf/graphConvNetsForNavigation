# Where are the Keys? - Learning Object-Centric Navigation Policies on Semantic Maps with Graph Convolutional Networks

Code accompanying our paper http://arxiv.org/abs/1909.07376 will appear soon, by early October 2019.

Emerging object-based SLAM algorithms can build a graph representation of an environment comprising nodes for robot poses and object landmarks. However, while this map will contain static objects such as furniture or appliances, many moveable objects (e.g. the car keys, the glasses, or a magazine), are not suitable as landmarks and will not be part of the map due to their non-static nature. 

We show that Graph Convolutional Networks can learn navigation policies to find such unmapped objects by learning to exploit the hidden probabilistic model that governs where these objects appear in the environment. The learned policies can generalise to object classes unseen during training by using word vectors that express semantic similarity as representations for object nodes in the graph. Furthermore, we show that the policies generalise to unseen environments with only minimal loss of performance. We demonstrate that pre-training the policy network with a proxy task can significantly speed up learning, improving sample efficiency.
