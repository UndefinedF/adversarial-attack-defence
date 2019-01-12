# Adversarial attack & defence

We try adversarial attack & defence in this example.

implement the following functions on MNIST dataset:

1. Generate adversarial examples (Fast gradient sign method)
2. Try targeted-attack / non-targeted attack on MNIST
3. Denoising the adversarial examples (Denoise autocoder/autocoder)

## Setup 

1. Clone the repository

```
git clone https://github.com/UndefinedF/adversarial-attack-defence.git
```

2. Make sure that you have Jupyter Notebook and tensorflow installed

## 

## Running

Here is the guidance:

1. Train the CNN in FGSM.ipynb on MNIST dataset
2. Try targeted-attack / non-targeted attack in FGSM.ipynb
3. Generate adversarial examples on the test_set of MNIST in FGSM.ipynb
4. Train DAE in DAE.ipynb / Train AE in AE.ipynb using the adversarial expamles
5. Test the performance of DAE/AE in FGSM.ipynb



## Reference

 [Intriguing Properties of Neural Networks](http://arxiv.org/abs/1312.6199)

[Explaining and Harnessing Adversarial Examples](https://arxiv.org/abs/1412.6572)

https://github.com/divyam3897/adversarial-examples
