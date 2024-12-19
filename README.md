# 👕 Fashion MNIST Classification with PyTorch

A deep learning project implementing a Convolutional Neural Network (CNN) to classify fashion items from the Fashion MNIST dataset. The model achieves **91.8% accuracy** on the test set.

## 📊 Dataset

The [Fashion MNIST](https://github.com/zalandoresearch/fashion-mnist) dataset consists of:
- 60,000 training images
- 10,000 test images
- 28x28 grayscale images
- 10 categories of clothing items

Classes:
1. T-shirt/top
2. Trouser
3. Pullover
4. Dress
5. Coat
6. Sandal
7. Shirt
8. Sneaker
9. Bag
10. Ankle boot

## 🏗️ Model Architecture

The implemented CNN includes:
- 2 Convolutional layers
- Max pooling layers
- Dropout regularization (0.25)
- 2 Fully connected layers
- ReLU activation functions

## 🎯 Results

- Test Accuracy: **91.8%**
- Training completed in 10 epochs
- Batch size: 64
- Optimizer: Adam (lr=0.001)

## 🛠️ Requirements

```
torch
torchvision
matplotlib
numpy
```

## 🚀 Getting Started

1. Clone this repository:
```bash
git clone https://github.com/yourusername/fashion-mnist-classification.git
```

2. Install required packages:
```bash
pip install -r requirements.txt
```

3. Run the training script:
```bash
python train.py
```

## 📈 Training Process

The model is trained using:
- Cross-Entropy Loss
- Adam optimizer
- Learning rate: 0.001
- Data augmentation: Normalization

## 🤝 Contributing

Feel free to open issues and pull requests! We welcome contributions from the community.

## 📝 License

This project is licensed under the MIT License - see the LICENSE file for details.

## 🙏 Acknowledgments

- Fashion MNIST dataset creators
- PyTorch team for the excellent deep learning framework

---
Made with ❤️ and 🧠
