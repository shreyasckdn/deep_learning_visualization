# deep_learning_visualization
Visualization of data passed through non linearities and neural netowrks

The following notebook helps to visualize what happens to points as they pass non linearities and a neural network. The analysis is done step by step. The main reason for the development of this notebook is that 02-space_stretching.ipynb lets you just see what happens after 1 linear transformation and 1 non linear transformation in 2D. This notebook helps you to see what happens after each step of a full neural network with hidden layers in 3D. There is also a part dedicated to 1D transformation at the end of this notebook.

You can choose whether your input points should be a 2-D Mesh Grid or a 2-D Gaussian Cloud. You can choose a non linearity: TanH or ReLU.

The code runs the input through two networks

1. A 2 Layered Network (Linear Layer, NL, Linear Layer)
2. A 3 Layered Network (Linear Layer, NL, Linear Layer, NL, Linear Layer)
You can also optionally initialize the weights of the neural network yourself. Initializing weights to different scale of values will enable you to make visualizations similar to 02-space_stretching.ipynb
