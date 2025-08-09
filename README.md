# Handwritten Digit Recognition API

This project is an implementation of a Handwritten Digit Recognition system using the MNIST dataset. The model currently uses a simple **fully connected neural network**, but I plan to upgrade it to **Convolutional Neural Networks (CNNs)** to improve performance and accuracy.

The final goal is to deploy this as a **Flask API** where users can upload their own digit images and receive predictions in real-time.

---

## 🚀 Features

- Train a neural network to recognize handwritten digits (0–9) from the MNIST dataset.
- Evaluate model accuracy and performance.
- Save and load trained models for reuse.
- Planned deployment as a **Flask REST API** for easy integration.

---

## 🛠️ Tech Stack

- **Python**
- **TensorFlow / Keras**
- **Flask** (planned deployment)
- **NumPy**, **Matplotlib** for data processing and visualization.

---

## 📈 Current Status

✅ Model trained using a basic neural network.  
🔄 Plan to experiment with **CNNs** for better accuracy and generalization.  
🚧 API implementation using Flask is in progress.

---

## 📂 Project Structure

```
.
├── MNIST_notebook.ipynb     # Jupyter notebook for model training and evaluation
├── saved_model/             # Directory to store trained model files
├── README.md                # Project documentation
└── requirements.txt         # Python dependencies
```

---

## 📌 Next Steps

1. Improve performance by switching from a dense neural net to a **CNN architecture**.
2. Implement **Flask API** for digit image upload and classification.
3. Enhance preprocessing to handle user-uploaded images in different formats.
4. Deploy API to a cloud platform for public use.

---

## 📦 Installation & Usage

### 1️⃣ Clone the repository
```bash
git clone https://github.com/your-username/handwritten-digit-recognition.git
cd handwritten-digit-recognition
```

### 2️⃣ Install dependencies
```bash
pip install -r requirements.txt
```

### 3️⃣ Train the model
```bash
jupyter notebook MNIST_notebook.ipynb
```

### 4️⃣ (Planned) Run Flask API
```bash
python app.py
```

---

## 📊 Example Predictions

Once deployed, the API will accept image uploads and return a JSON response like:
```json
{
    "prediction": 7,
    "confidence": 0.98
}
```

---

## 📜 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
