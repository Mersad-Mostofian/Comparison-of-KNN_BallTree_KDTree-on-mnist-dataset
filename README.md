🔥 KNN with Ball Tree and KD-Tree from Scratch 🚀

This repository contains an efficient implementation of K-Nearest Neighbors (KNN) using Ball Tree and KD-Tree, achieving 97.19% accuracy on the MNIST dataset. The implementation is done from scratch without relying on built-in scikit-learn functions for these structures.

✨ Features

⚡ Custom KNN implementation without scikit-learn's built-in KNN.

🌲 Ball Tree and KD-Tree optimization for faster nearest neighbor searches.

🚀 Significantly improved speed compared to brute-force KNN.

🧪 Tested on MNIST dataset, achieving high accuracy.

📊 Performance Comparison

Method

🎯 Accuracy

⏳ Time (for 14,000 test samples)

Brute-force KNN

96.68%

~2 Houes and 4 minutes

KD-Tree KNN

80.18%

< 1 second

Ball Tree KNN

96.93%

~1 Hour and 25 minutes

📝 Dataset

The MNIST dataset is used for evaluation. It consists of handwritten digit images (0-9), each represented as a 784-dimensional vector (28x28 pixels flattened).

📈 Results

⚡ KD-Tree: Extremely fast but slightly lower accuracy.

🌲 Ball Tree: Slower than KD-Tree but achieves higher accuracy.

🏆 Brute-force KNN: Most accurate but computationally expensive.
