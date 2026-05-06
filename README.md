# Deep_Learning_Assignment-
## 🧠 Simple Neural Network for Regression

## 📌 Overview

This project demonstrates a basic implementation of a **Neural Network from scratch** using Python.
The model learns the relationship between input features and output using **forward propagation** and **backpropagation**.

---

## 🎯 Objective

The objective of this project is to build a simple neural network model that:

* Takes two inputs (**x1** and **x2**)
* Learns their relationship with the output (**y**)
* Minimizes prediction error using training

---

## 🧪 Input Data

The model is trained on sample data:

* `x1 = 3`
* `x2 = 2`
* `y_actual = 17`

---

## ⚙️ Methodology

### 🔹 1. Weight Initialization

Weights are initialized randomly:

```python
w1 = np.random.randn()
w2 = np.random.randn()
```

---

### 🔹 2. Forward Propagation

The predicted output is calculated as:
[
y_{pred} = x_1 \cdot w_1 + x_2 \cdot w_2
]

---

### 🔹 3. Error Calculation

Squared error is used:
[
Error = (y_{actual} - y_{pred})^2
]

---

### 🔹 4. Backpropagation

Weights are updated using gradient descent:
[
w = w - \alpha \cdot gradient
]

---

### 🔹 5. Training

* The model is trained for **20 epochs**
* Error is minimized over iterations

---

## 📊 Visualization

The project includes a graph showing:

* **Error vs Epochs**
* Demonstrates how the model improves over time

---

## 🚀 Technologies Used

* Python
* NumPy
* Matplotlib

---

## ▶️ How to Run

1. Clone the repository:

```bash
git clone https://github.com/your-username/your-repo-name.git
```

2. Navigate to the folder:

```bash
cd your-repo-name
```

3. Run the script:

```bash
python your_script_name.py
```

---

## 📈 Expected Output

* Error decreases over time
* Final prediction becomes close to actual value (17)
* Graph shows downward trend

---

## 🏁 Conclusion

This project demonstrates how a simple neural network can learn patterns from data using basic machine learning concepts like forward propagation and backpropagation.

---

## 📌 Future Improvements

* Add multiple neurons (hidden layer)
* Use real datasets
* Implement using deep learning frameworks like TensorFlow or PyTorch

---

## 🙌 Author

**Sanket Tippe**

---

⭐ If you like this project, consider giving it a star!
