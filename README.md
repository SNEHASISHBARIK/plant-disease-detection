# 🌿 AI-Based Plant Disease Detection System

This project is a **Deep Learning-based web application** that detects plant diseases from leaf images using a Convolutional Neural Network (CNN). It helps farmers and users identify diseases quickly and take preventive action.

---

## 🚀 Features

* 📷 Upload plant leaf images
* 🤖 Detect disease using CNN model
* 📊 Show prediction with confidence
* 🌐 Simple web interface using Flask

---

## 🧠 Technologies Used

* Python
* TensorFlow / Keras
* Flask
* OpenCV
* HTML, CSS

---

## 📁 Project Structure

```
plant-disease-detection/
│
├── app.py                # Flask web app
├── train.py              # Model training script
├── requirements.txt      # Dependencies
│
├── templates/            # HTML files
│   ├── index.html
│   └── result.html
│
├── static/               # CSS & assets
│   └── style.css
│
├── dataset/              # (Not included - large size)
├── model/                # (Not included - large size)
```

---

## 📸 Output Screenshots

### Home Page

![Home](images/home.png)

### Result Page

![Result](images/result.png)

---

## 📊 Dataset

PlantVillage Dataset (Kaggle):
https://www.kaggle.com/datasets/emmarex/plantdisease

---

## ▶️ How to Run the Project

1. Clone the repository:

```
git clone https://github.com/SNEHASISHBARIK/plant-disease-detection.git
cd plant-disease-detection
```

2. Install dependencies:

```
pip install -r requirements.txt
```

3. Train the model (optional):

```
python train.py
```

4. Run the application:

```
python app.py
```

5. Open browser:

```
http://127.0.0.1:5000
```

---

## ⚠️ Note

* Dataset and trained model are not included due to large file size.
* Please download the dataset from Kaggle and train the model locally.

---

## 🎯 Future Improvements

* 📱 Mobile app integration
* 🌐 Deploy on cloud (AWS/Render)
* 🧠 Improve model accuracy
* 📊 Add analytics dashboard

---

## 👨‍💻 Author

**Snehasish Barik**
GitHub: https://github.com/SNEHASISHBARIK

---

## ⭐ If you like this project

Give it a ⭐ on GitHub!
