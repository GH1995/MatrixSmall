# MatrixSmall - Deep Learning Framework in Python


MatrixSlow keep core


### Characteristics

- Based on computational graphs, can be used to build most machine learning models.
- Support for automatic derivation.
- Supports stochastic gradient descent optimization algorithm and several of its important variants (e.g., RMSProp, ADAGrad, ADAM, etc.).
- Support for common model evaluation algorithms.
- Support for model saving and loading.
- Support PS and Ring AllReduce distributed training.
- Support for model serving.

### Dependencies

Core：
```
- python 3.7 or above
- numpy
```
Distributed training：
```
- protobuf
- grpc
```
Example：
```
- pandas
```

### Codes
```
.
├── README.md
├── benchmark
├── example
├── matrixsmall
└── matrixsmall_serving
```
- matrixsmall: The core code section, including computational graphs, auto-derivation and optimization algorithms, model saving loading, and distributed training. matrixsmall_serving: A generic model inference service, similar to tensorflow serving.
- matrixsmall_serving: Generic model inference service, similar to tensorflow serving.
- example: ch05 introduces how to build and train multi-layer fully connected neural networks with matrixsmall, and ch11 demonstrates how to run distributed training.
