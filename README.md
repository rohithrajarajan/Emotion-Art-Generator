## Real-Time Emotion-to-Art GAN Generator

This project explores the intersection of affective computing and generative art. It provides a pipeline to:

1.  Capture live video frames from a user's webcam (using Google Colab's interface).
2.  Detect faces within the frame using OpenCV's Haar Cascades.
3.  Analyze the detected face using the DeepFace library to determine the user's dominant facial emotion.
4.  Map the identified emotion (e.g., 'happy', 'sad', 'neutral') to a specific region within the latent input space of a Generative Adversarial Network (GAN).
5.  Feed this emotion-specific latent vector into a pre-trained Deep Convolutional GAN (DCGAN) built with PyTorch.
6.  Generate and display a novel, abstract image intended to reflect the user's detected emotion.

The goal is to create an interactive experience where generative art dynamically responds to the user's affective state.

**Technologies:** Python, PyTorch, OpenCV, DeepFace, Matplotlib, Google Colab.
