# Artifical-Inteligence-Step-2-Deep-learning-with-Keras📜 About This Repository
This repository contains a collection of Jupyter Notebooks, each corresponding to a key module or project within the course. My goal was not just to complete the assignments, but to deeply understand the "why" and "how" behind every line of code—from the mathematics of backpropagation to the architecture of modern Transformers.
Each notebook serves as a practical implementation of a core deep learning concept.
notebooks: A Journey Through Core Concepts
Here is a breakdown of the projects and concepts explored in this repository:
🧠 1. The Building Blocks of Neural Networks
These notebooks explore the fundamental mechanics of how neural networks learn.
Forward_Propagation_A_small_neural_network.ipynb
Concept: The initial "guess" phase of a neural network. This notebook implements the step-by-step process of passing input data through layers to get an initial prediction.
Skills Demonstrated: Understanding of weights, biases, and activation functions in a simple, manual context.
Back_Propagation_Neural_Network.ipynb
Concept: The "learning" phase. This notebook dives into the core algorithm of deep learning, demonstrating how a network calculates its error and adjusts its weights to improve.
Skills Demonstrated: Manual implementation of the chain rule (calculus) to compute gradients and update parameters.
Activation_Function_and_Vanishing_Gradient.ipynb
Concept: Explores the "switches" of a neural network (Activation Functions like ReLU) and a critical problem in training deep networks—the Vanishing Gradient problem.
Skills Demonstrated: Understanding the role of activation functions and the challenges of training deep architectures.
🚀 2. Practical Implementation with Keras
These notebooks transition from manual calculations to using Keras, a powerful, high-level API for building and training models efficiently.
Regression_with_Keras_in_DL.ipynb
Concept: Building a neural network to predict a continuous value (e.g., a price or a temperature).
Skills Demonstrated: Using Keras's Sequential API, Dense layers, and compiling a model with appropriate loss functions (MSE) and optimizers (Adam).
Classification_with_Keras_on_digital_writen.ipynb
Concept: Building a neural network to classify data into distinct categories. This notebook likely tackles the famous MNIST dataset of handwritten digits.
Skills Demonstrated: Implementing a multi-class classification model, using softmax activation, and evaluating performance with accuracy.
Transformer_with_Keras.ipynb
Concept: An introduction to the state-of-the-art architecture that powers models like GPT and BERT. This notebook implements the core components of a Transformer, such as the self-attention mechanism.
Skills Demonstrated: Understanding and implementing Query (Q), Key (K), and Value (V) vectors, and building a custom attention layer in Keras.
🏆 3. Final Capstone Project
This is the culminating project for the course, combining multiple skills into a single, powerful application.
Final_Project_Classification_and_Captioning.ipynb
Concept: A multi-modal AI project that performs two distinct tasks:
Image Classification: Using a pre-trained model (like VGG16) with Transfer Learning to classify images.
Image Captioning: Using a pre-trained, Transformer-based model (like BLIP) to generate descriptive text for an image.
Skills Demonstrated:
Transfer Learning: Leveraging the knowledge of large, pre-trained models.
Computer Vision: Classifying visual data.
Natural Language Processing (NLP): Generating human-readable text.
Model Integration: Combining two different AI models to create a single, feature-rich application.
🛠️ Technologies & Libraries Used
Frameworks: Keras, TensorFlow
Libraries: NumPy, Pandas, Matplotlib, Scikit-learn, Pillow, Transformers (Hugging Face)
Concepts: Neural Networks, Backpropagation, Gradient Descent, CNNs, Transformers, Self-Attention, Transfer Learning, Image Classification, Image Captioning.
🌟 My Learning Philosophy
My approach throughout this course was to build a first-principles understanding. I strived to look inside the "black box" of every function and architecture, connecting the high-level Keras code to the underlying mathematical operations. This repository is a testament to that journey.
Thank you for visiting! Feel free to explore the notebooks and reach out with any questions or feedback. On to the next 11 courses! 🚀
