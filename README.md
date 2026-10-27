# 🌿 Plant Disease Detection System

A deep learning project that uses a Convolutional Neural Network (CNN) to identify plant diseases from leaf images.

## 🚀 Features
- Detects plant diseases from leaf images.
- Uses a CNN model trained on the PlantVillage dataset.
- Provides predictions through a simple web interface.
- Built with Flask for web integration.

## 🛠️ Tech Stack
- **Language:** Python
- **Machine Learning:** TensorFlow, Keras, CNN
- **Dataset:** PlantVillage
- **Backend:** Flask
- **Frontend:** HTML, CSS, JavaScript

## 📂 Project Structure

```text
plant-disease-detection/
├── app.py
├── plant_model.h5
├── templates/
│   ├── index.html
│   └── result.html
├── static/
│   └── style.css
├── requirements.txt
└── README.md
```

*The structure above is an example; adjust it to match your actual files.*

## ⚙️ Installation and Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/YOUR-USERNAME/plant-disease-detection.git
   cd plant-disease-detection
   ```

2. Create and activate a virtual environment:

   ```bash
   python -m venv venv
   ```

   Windows:

   ```bash
   venv\Scripts\activate
   ```

3. Install dependencies:

   ```bash
   pip install -r requirements.txt
   ```

4. Run the application:

   ```bash
   python app.py
   ```

5. Open the local URL shown in your terminal, usually `http://127.0.0.1:5000/`.

## 🧠 How It Works

1. The user uploads a plant leaf image.
2. The image is preprocessed to match the model's input requirements.
3. The trained CNN model predicts the corresponding class.
4. The application displays the prediction on the web page.

## 📊 Dataset

This project uses the [PlantVillage dataset](https://www.kaggle.com/datasets/emmarex/plantdisease), which contains labeled images of healthy and diseased plant leaves.

## 🔮 Future Improvements
- Improve prediction accuracy with more diverse images.
- Add more plant species and disease categories.
- Enhance the user interface and prediction results.
- Evaluate performance on real-world leaf images.

## ⚠️ Disclaimer

This project is intended for educational purposes. Predictions may not always be accurate and should not replace expert agricultural advice.

## 👨‍💻 Author

**Sujal**

[GitHub Profile](https://github.com/SujalSP)
