# ElaraNet

Neural network for spacetime metric optimization, implemented with ~~Elara ML~~ TensorFlow (for now)

## Usage

Ensure you have SciPy, NumPy, TensorFlow, and Plotly installed. The Jupyter notebooks are organized as follows:

- To generate the dataset, use the [generator notebook](./ElaraNet Generator.ipynb)
- To train/use the NN, use the [model notebook](./ElaraNet Model.ipynb)

## Pre-generated data & models

A pre-generated dataset is available at [`sigma_data.csv`](./sigma_data.csv). This is meant to be used in conjunction with the model notebook; alternatively, `np.loadtxt()` can be used to load it as an array. The dataset consists of two arrays: one of $\sigma$ values, and one of associated energy requirement values.

A pre-generated model is also available in the `./saved_models` directory. It may be used in place of ElaraNet continaed in the model notebook in usage.
