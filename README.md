# CPEN 400Q Project
## Code Running Instructions
Both of the `.ipynb` files under the software directory can be run by opening them in Google Colab, and running all cells. `bQCNN-TensorflowQuantum.ipynb` includes all of the source code for our main software implementation with TensorFlow Quantum. `bQCNN-Qiskit.ipynb` includes the source code for our attempt to implement the circuit with Qiskit. The Qiskit code does not include a full implementation of the original paper, but does detail our attempts to reproduce the original results.
## Individual Contributions
A majority of the software implementation was completed through pair programming. However, the general individual contributions are as follows:
- Rain Zhang: 
    - Created the Qiskit notebook
    - Developed the Qiskit functionality for creating the convolution layer to reflect the original paper's convolution layer architecture
- Amir Barkam: 
    - Developed the Qiskit functionality for including branching in the pooling layers and performing mid-circuit measurements on a subset of qubits in the pooling layers
- Arnold Ying:
    - Developed the TensorFlow Quantum functionality for implementing the convolution layers to reflect the original paper's implementation
    - Developed the TensorFlow Quantum code for branching in the architecture's pooling layers
- Stella Wang:
    - Developed the TensorFlow Quantum functionality for generating random excitations of the cluster state and random 4-pixel images
    - Developed the Tensorflow Quantum functionality for running gradient descent on the bQCNN