
# 🔢 MNIST Digit Recognition using Convolutional Neural Networks (CNNs)

This project, developed by **Chanikya Kothi**, implements a Convolutional Neural Network (CNN) for handwritten digit classification using the **MNIST dataset**.  
The goal is to demonstrate the effectiveness of deep learning architectures for image recognition tasks.

---

## 🎯 Project Overview

The MNIST dataset consists of 70,000 grayscale images (28x28 pixels) of handwritten digits (0–9):  
- 60,000 training images  
- 10,000 test images

This project achieves high accuracy through a carefully designed CNN architecture and effective regularization techniques.

---

## 🧠 Model Architecture

The CNN is structured as follows:

- 🔹 Convolutional layer: 32 filters, 3x3 kernel, ReLU activation  
- 🔹 Max pooling layer: 2x2 pool size  
- 🔹 Dropout: 25% rate  
- 🔹 Convolutional layer: 64 filters, 3x3 kernel, ReLU activation  
- 🔹 Max pooling layer: 2x2 pool size  
- 🔹 Dropout: 25% rate  
- 🔹 Flatten layer  
- 🔹 Dense layer: 128 units, ReLU activation  
- 🔹 Dropout: 50% rate  
- 🔹 Output layer: 10 units, softmax activation (for 10 digit classes)

The model is compiled with **categorical cross-entropy loss** and optimized using **Adam optimizer**.

---

## 📊 Results

✅ The model achieved a **test accuracy of 99.31% after 20 epochs** of training.  
Throughout training and validation, loss and accuracy were monitored, and no signs of overfitting were observed.

---

## 📈 Conclusion

This project demonstrates that a relatively simple CNN can deliver **excellent performance on the MNIST digit classification task**.  
With further tuning and experimentation (e.g., deeper networks, learning rate schedules), even greater performance may be possible.

---

## 🖥️ Technologies & Libraries

- Python, Jupyter Notebook  
- TensorFlow / Keras  
- pandas, numpy  
- matplotlib, seaborn

---

## 👤 Author

**Chanikya Kothi** — Data Science & Deep Learning Enthusiast

⭐ If you find this project useful, feel free to ⭐ star the repository or reach out for collaboration!
