# 🔍 Zero-Day Exploit Detection Simulation using Machine Learning

This project simulates zero-day attack behavior using **synthetic dataset generation** and builds a **Machine Learning model** (Random Forest) to classify normal vs suspicious (zero-day like) data points.

---

## 📌 Project Features

- 🚨 **Synthetic Dataset Generation**:
  - Normal traffic
  - Simulated zero-day exploit traffic
- 🤖 **Machine Learning Classification**:
  - Random Forest Classifier
  - 80-20 Train/Test Split
  - Accuracy & Confusion Matrix evaluation
- 📊 **Data Visualization**:
  - Feature Distribution Plots
  - Correlation Heatmap
- 🛡️ Useful for Security Research, Anomaly Detection, and AI-based IDS Testing.

---

## 📝 Notebook Structure

1. **Dataset Generation**: Synthetic zero-day and normal traffic created using NumPy and Pandas.
2. **Preprocessing**: Feature scaling using StandardScaler.
3. **ML Model Building**: RandomForestClassifier.
4. **Evaluation**: Accuracy Score and Confusion Matrix.
5. **Visualization**: Seaborn & Matplotlib plots to show feature separation and importance.

---

## 🚀 How to Run

### 1. Clone this Repository:

```bash
git clone https://github.com/yourname/zero-day-exploit-simulation.git
cd zero-day-exploit-simulation
