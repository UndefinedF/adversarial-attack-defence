Adversarial attack & defense

This example is about adversarial attack & defense.

implement the following functions on MNIST dataset:

1. Generate adversarial examples (Fast gradient sign method)
2. Try targeted-attack / non-targeted attack on MNIST
3. Denoise the adversarial examples (Denoise autocoder/autocoder)

Setup 

1. Clone the repository

    git clone https://github.com/UndefinedF/adversarial-attack-defense.git

1. Make sure that you have Jupyter Notebook and tensorflow installed

 

Running

Here is the guidance:

1. Train the CNN in FGSM.ipynb on MNIST dataset
2. Try targeted-attack / non-targeted attack in FGSM.ipynb
3. Generate adversarial examples on the test_set of MNIST in FGSM.ipynb
4. Train DAE in DAE.ipynb / Train AE in AE.ipynb using the adversarial expamles
5. Test the performance of DAE/AE in FGSM.ipynb



Reference

 Intriguing Properties of Neural Networks

Explaining and Harnessing Adversarial Examples

https://github.com/divyam3897/adversarial-examples
