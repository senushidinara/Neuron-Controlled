# Neuron-Controlled
+-----------------+                  +------------------+
|  Environment    |                  |   Neuron Model   |
|                 |                  |                  |
|  - State Space  | <--------------> |  - Firing Rate   |
|  - Action Space |                  |  - Activation     |
|                 |                  |  - Synaptic Weights|
+-----------------+                  +------------------+
        |                                   |
        |                                   |
        +-------------+---------------------+
                      |
                      v
              +------------------+
              |   Reinforcement   |
              |   Learning Agent  |
              +------------------+
                      |
                      v
              +------------------+
              |   Visualization   |
              |     & Learning    |
              |      Feedback      |
              +------------------+
