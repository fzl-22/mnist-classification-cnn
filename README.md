# Handwritten Digits (MNIST) Classification using CNN

This project uses a Convolutional Neural Network (CNN) in PyTorch to classify handwritten digits (0-9) from the MNIST dataset. The model is trained to recognize patterns in 28x28 grayscale images, achieving high accuracy in digit classification (98.1%).

To create the predefined virtual environment, run this command.

```bash
conda env create -f environment.yml -p ./venv
```

Then activate it with the following command.

```bash
conda activate ./venv
```

If you are using CUDA instead of Apple's Metal, modify all occurences of `torch.mps.is_available` to `torch.cuda.is_available`.
