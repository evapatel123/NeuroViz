# 🧠 NeuroViz — 3D AI & Machine Learning Visualizer

**An interactive 3D environment for exploring how machine learning models learn, make predictions, and change over time.**

NeuroViz turns concepts such as neural networks, activations, weights, gradients, training, and decision boundaries into an interactive visual experience.

Instead of only reading about how a neural network works, you can **see the network process information in 3D.**

---

## ✨ Features

### 🧠 Interactive 3D Neural Networks

Explore a visual feed-forward neural network with:

* Input, hidden, and output layers
* Adjustable hidden-layer sizes
* Adjustable number of neurons
* Dynamic neuron activations
* Animated forward propagation
* Interactive 3D camera controls
* Clickable neuron inspection

### 🔗 Dynamic Weight Connections

Connections between neurons visually represent model weights.

* 🔵 Positive weights
* 🔴 Negative weights
* Variable connection intensity
* Animated data propagation
* Visual changes during training

### 📈 Training Visualization

Watch a model train through an interactive interface.

Adjust:

* Learning rate
* Number of epochs
* Hidden neurons
* Number of hidden layers
* Activation function

Monitor:

* Loss
* Accuracy
* Epoch progression
* Prediction behavior
* Training curves

### 🌐 Decision Boundary Visualization

NeuroViz includes an interactive 3D decision-boundary visualization that changes as the model learns.

This provides an intuitive way to understand how a machine learning model separates different regions of a dataset.

### ⚡ Neuron Activation Effects

Neurons respond visually as information moves through the network.

During propagation and training, neurons can:

* Glow
* Pulse
* Scale dynamically
* Change visual intensity

### 🎯 Dataset Scenarios

Experiment with different dataset configurations, including:

* Balanced Classification
* XOR
* Concentric Rings
* Spiral Dataset
* Overfitting Demo
* Underfitting Demo

These examples make it easier to explore how architecture and training parameters affect model behavior.

### 🏗️ Multiple Model Architectures

NeuroViz supports several conceptual architectures:

**Classification**

A network designed to separate data into classes.

**Regression**

A network designed to predict continuous values.

**Autoencoder**

A network containing a bottleneck representation for exploring encoder/decoder architectures.

### 🔍 Neuron Inspection

Select individual neurons to inspect their internal state, including:

* Bias
* Gradient
* Activation
* Current state

This makes otherwise abstract mathematical concepts easier to explore visually.

### 🎥 Camera Presets

Quickly explore the network using:

* Top View
* Output Node Focus
* Cinematic Orbit

The camera transitions smoothly between perspectives.

### 🌓 Dark & Light Modes

Switch between two visual themes:

* ☀️ Light Mode
* 🌙 Dark Mode

The dark interface uses a futuristic glassmorphism-inspired visual style designed for an immersive machine-learning visualization experience.

---

## 🛠️ Technologies

NeuroViz is built primarily with:

* HTML5
* CSS3
* JavaScript
* Three.js
* WebGL
* HTML Canvas
* Local browser storage

The project is designed as a standalone web experience and can be deployed through **GitHub Pages**.

---

## 🚀 Running Locally

Clone the repository:

```bash
git clone https://github.com/YOUR-USERNAME/YOUR-REPOSITORY.git
```

Navigate into the project:

```bash
cd YOUR-REPOSITORY
```

Then open the main HTML file in a modern browser.

No backend server is required for the core visualization.

---

## 🌎 GitHub Pages

NeuroViz can be deployed as a static website using GitHub Pages.

After enabling GitHub Pages for the repository, the project can be accessed through your GitHub Pages URL.

---

## 🎮 How to Use

### 1. Choose an Architecture

Select:

* Classification
* Regression
* Autoencoder

### 2. Configure the Model

Experiment with:

* Learning rate
* Epochs
* Hidden neurons
* Hidden layers
* Activation function

### 3. Select a Dataset

Load one of the available example scenarios.

### 4. Train the Model

Press **Train Model** and observe the network as it processes information.

Watch the:

* neurons
* connections
* activations
* decision surface
* metrics
* training curve

change throughout the process.

### 5. Inspect Neurons

Click a neuron to examine its current mathematical state.

### 6. Explore the 3D Environment

Drag to rotate the scene and scroll to zoom.

Try the camera presets for different perspectives.

---

## 🎓 Educational Purpose

NeuroViz was designed to make machine learning concepts more intuitive and visually accessible.

It can be used to explore concepts such as:

* Neural networks
* Forward propagation
* Activation functions
* Model training
* Learning rates
* Epochs
* Weights
* Biases
* Gradients
* Classification
* Regression
* Autoencoders
* Decision boundaries
* Overfitting
* Underfitting

The project is intended as an **educational visualization**, not as a replacement for a production machine-learning framework.

---

## 👩‍💻 Programmer

**Eva J Patel**

NeuroViz was designed and developed as an interactive educational project exploring the visualization of artificial intelligence and machine learning concepts.

---

## 📄 License

**Copyright © 2026 Eva J Patel. All Rights Reserved.**

This repository is publicly available for viewing through GitHub, but the source code is **not open source** and is not licensed for copying, modification, redistribution, publication, or reuse without explicit written permission from the copyright holder.

See the [`LICENSE`](LICENSE) file for the complete terms.

---

## ⚠️ Third-Party Dependencies

NeuroViz may load third-party libraries such as Three.js through external CDNs.

Those dependencies remain subject to their respective licenses and terms.

This repository's custom source code is separately protected by its copyright and license terms.

---

## ⭐ Project

NeuroViz is an exploration of how interactive 3D graphics can make artificial intelligence and machine learning concepts easier to understand.

**Happy Learning!**
