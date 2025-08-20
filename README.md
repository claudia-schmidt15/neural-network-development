# neural-network-development

**Neural Network Analysis of Glassy Particle Rearrangements**

Janurary 2023 to December 2023 – Sussman Lab, Emory University

Developed and optimized neural network models to classify particle rearrangements in simulated glassy materials across varying temperatures. The project applied multi-layer perceptron (MLP) architectures using scikit-learn to analyze datasets containing 100 radial distribution features per particle, labeled as rearranging or non-rearranging.

**Key Contributions:**

- Built and tuned neural networks (layers, widths, iterations, solvers, learning rates) to maximize classification accuracy on glassy particle datasets.
- Compared cross-temperature classification performance by training networks on one temperature set (e.g., 0.45 LJ units) and testing on others.
- Applied stochastic gradient descent, backpropagation, and loss curve analysis to diagnose overfitting and learning limitations.
- Implemented cross-validation to evaluate generalization, achieving improved architecture selection with reduced overfitting.
- Produced visual analyses of accuracy trends across temperatures, validating hypotheses about classification degradation with increased temperature.
- Skills & Tools: Python, scikit-learn, Neural Network Optimization, Data Visualization, Cross-Validation, Scientific Computing, Physics-Based Simulation Data

**Included Files**

**trainingNN.ipynb**

This notebook contains the initial implementation and training of a neural network. It sets up the model architecture, prepares the dataset, runs the training loop, and evaluates baseline performance. It serves as the foundation for understanding how the network performs before further optimization.

**improvingT045.ipynb**

This notebook builds on the initial training by experimenting with improvements to the model. It explores changes in architecture, tuning hyperparameters, and testing different training methods to enhance accuracy and efficiency. The goal is to analyze how these adjustments affect learning rate, convergence, and overall model output quality.
  
