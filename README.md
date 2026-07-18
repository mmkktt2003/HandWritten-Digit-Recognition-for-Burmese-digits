# Burmese Handwritten Digit Recognition

A convolutional neural network that recognises handwritten Burmese digits (0-9), trained on the [BHDD dataset](https://github.com/baseresearch/BHDD), which is the Burmese counterpart to MNIST. Includes an interactive Tkinter app where you can draw a digit and get a instant prediction.

## How to run it

```bash
git clone https://github.com/mmkktt2003/HandWritten-Digit-Recognition-for-Burmese-digits.git
cd HandWritten-Digit-Recognition-for-Burmese-digits
pip install -r requirements.txt
jupyter notebook source.ipynb
```

Run all cells top to bottom. Training may take a few minutes on CPU. The final cell launches the interactive drawing app.
S
## Dataset & licence

This project uses the **Burmese Handwritten Digit Dataset (BHDD)** created by Base Technology / Expa.ai, released under CC BY-SA 4.0:

> Swan Htet Aung et al., *BHDD: A Burmese Handwritten Digit Dataset* — https://github.com/baseresearch/BHDD

The dataset files in `Resources/` are redistributed under the terms of that licence with attribution to the original authors.
