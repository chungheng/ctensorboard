# A C++ wrapper for visualizing data in Tensorboard

This package aims to leverage the visualization tool
[Tensorboard](https://www.tensorflow.org/programmers_guide/summaries_and_tensorboard)
for monitoring iterative procedures, such as update step in machine learning algorithm.
The package provides C++ APIs to log data as Tensorflow
[tf.Summary](https://www.tensorflow.org/api_docs/python/tf/summary) objects into `Tensorflow` event files. The event files can be visualized in `Tensorboard`.

Note this package **DOES NOT** support visualization of the network graph.

## Acknowledgements

Based on the [answer](https://stackoverflow.com/a/48702823) by the stack
overflow user [Patwie](https://stackoverflow.com/users/7443104/patwie).
