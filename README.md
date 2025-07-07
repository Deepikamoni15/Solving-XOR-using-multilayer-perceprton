# Solving-XOR-using-multilayer-perceprton
# XOR Neural Network with Keras

This project implements a simple neural network using **TensorFlow Keras** to solve the classic **XOR problem** — a fundamental example of a non-linearly separable problem.

---

## 🔧 Technologies Used

- Python 🐍
- NumPy
- TensorFlow (Keras API)

---

## 🧠 Problem Statement

The XOR truth table:

| Input A | Input B | Output (A XOR B) |
|---------|---------|------------------|
| 0       | 0       | 0                |
| 0       | 1       | 1                |
| 1       | 0       | 1                |
| 1       | 1       | 0                |

---

## 📌 How It Works

1. **Prepare Data**:
   - Inputs `X` are all 2-bit combinations.
   - Outputs `y` are the XOR results.

2. **Model Architecture**:
   - 1 hidden layer with 4 neurons (`sigmoid` activation)
   - 1 output neuron (`sigmoid` activation)

3. **Compilation**:
   - Loss function: `binary_crossentropy`
   - Optimizer: `adam`

4. **Training**:
   - Trained for `10,000` epochs

5. **Testing**:
   - Prints XOR predictions (rounded to 0 or 1)

---

## 📈 Example Output

```python
Predictions for XOR inputs:
[[0.]
 [1.]
 [1.]
 [0.]]
