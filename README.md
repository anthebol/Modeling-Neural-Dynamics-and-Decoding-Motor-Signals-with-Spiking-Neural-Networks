# Modeling Neural Dynamics and Decoding Motor Signals with Spiking Neural Networks

This project explores the use of spiking neural networks (SNNs) for decoding motor signals from neural spike train data recorded from a primate motor cortex. The goal is to model neural activity using biologically inspired leaky integrate-and-fire (LIF) neurons and predict motor output, such as pointer movements on a screen, based on spike train input.

## Features

- **Synfire Chain Simulation**: Implements and evaluates a synfire chain model with spiking neural networks.  
- **Neural Decoding**: Predicts motor movements using SNNs trained on spike data and velocity information.  
- **Spiking vs. Non-Spiking Networks**: Compares the performance of networks with spiking hidden layers to those without.  
- **Brain-Machine Interface**: Demonstrates how spiking neuron outputs can predict actions performed on a screen.

## Key Tasks

1. **Synfire Chain Simulation**  
   - Built a simulator to model synfire chain propagation based on leaky integrate-and-fire neurons.
   - Implemented Poisson background noise and refractory periods for realistic neural activity.

2. **Data Preprocessing and Analysis**  
   - Processed neural spike data and velocity signals for training and validation.
   - Visualized data with raster plots, velocity trajectories, and firing rate histograms.

3. **Network Training and Evaluation**  
   - Trained spiking and non-spiking networks using surrogate gradient descent.  
   - Evaluated performance via loss curves, output plots, and statistical metrics.

4. **Longer-Length Decoding**  
   - Extended decoding to longer time windows by using final outputs of overlapping input segments.  

5. **Spiking vs. Non-Spiking Comparison**  
   - Assessed training and prediction accuracy with spiking hidden layers, highlighting trade-offs in computational complexity and performance.

## Results

- Demonstrated the ability of spiking neural networks to predict motor outputs from spike train data.
- Explored the trade-offs between spiking and non-spiking architectures in terms of accuracy and efficiency.
- Highlighted the potential for brain-machine interface applications using SNNs.

---

### Acknowledgments

This project is inspired by the methodologies in ["Machine Learning for Neural Decoding" (Glaser et al. 2020)](https://doi.org/10.1523/ENEURO.0506-19.2020) and incorporates concepts from brain-machine interface research.