# 📈 Linear Regression from Scratch

This project demonstrates how **Linear Regression** works under the hood by implementing it from scratch in Python using only basic libraries like NumPy and Matplotlib as well as using Scikit Learn.

---

## 🧠 What I Learned

- The mathematics behind linear regression  
- Cost function (Mean Squared Error)  
- Gradient Descent optimization  
- Visualizing the best-fit line  

---

## ⚙️ How It Works

1. Initialize weights and bias  
2. Use the cost function:
   \[
   J = \frac{1}{n} \sum_{i=1}^{n} (y_i - (mx_i + b))^2
   \]
3. Update weights using Gradient Descent:
   \[
   m = m - \alpha \cdot \frac{\partial J}{\partial m}, \quad b = b - \alpha \cdot \frac{\partial J}{\partial b}
   \]
4. Stop when convergence is achieved  
5. Plot predictions vs original data

---

## 📌 How to Run

```bash
# Clone this repo
git clone https://github.com/VaibhavKhangale/Machine-Learning.git

# Navigate to this project
cd Machine-Learning/Linear Regression

# open notebook
# jupyter notebook FILENAME.ipynb
