# Waste-classification-model-cnn
Internship project: AICTE || SHELL || EDUNET FOUNDATION

# <a href="https://waste-classification-model-cnn.streamlit.app/" target="_blank">Live at Streamlit</a>

# 🌿 Waste Classification App  

[![Python](https://img.shields.io/badge/Python-3.12-blue.svg)](https://www.python.org/)  
[![Streamlit](https://img.shields.io/badge/Built%20With-Streamlit-brightgreen.svg)](https://streamlit.io/)  
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)  

An intuitive web-based application to classify waste into **Organic** or **Inorganic** categories, promoting sustainability and eco-friendly practices. The app leverages the power of **TensorFlow**, **OpenCV**, and **Streamlit** to deliver real-time predictions with an elegant user interface.

![Upload Image](https://github.com/CHINNU081004/Waste-Classification-System-Using-AI-ML-AICTE/blob/main/Streamlit%20-%20Google%20Chrome%2001-12-2024%203.52.45%20PM.png)

---

## 🌟 Features

- 📤 **Upload Image**: Upload an image of waste and get it classified.  
- 📸 **Capture Image**: Use your device's camera to classify waste on the spot.  
- 🎨 **Interactive UI**: Minimalistic and user-friendly design for smooth interaction.  
- 📊 **Real-time Predictions**: Classifies waste with confidence scores.  
- 📦 **Powered by AI**: Built using a custom-trained CNN model for accurate results.

---

## 🛠️ Technologies Used

| Technology  | Description                                                                 |
|-------------|-----------------------------------------------------------------------------|
| TensorFlow  | Deep Learning framework for training and inference of the waste classifier. |
| OpenCV      | Used for image preprocessing and overlaying bounding boxes.                 |
| Streamlit   | Simplified the creation of an interactive web app.                          |
| PIL         | Image manipulation library.                                                |

---

## 📚 How It Works

1. **Upload or Capture** an image of the waste.
2. The image is processed and resized to match the input requirements of the model.
3. A **Convolutional Neural Network (CNN)** predicts whether the waste is:
   - **Organic** (e.g., food scraps, plants).
   - **Inorganic** (e.g., plastics, metals).
4. The result is displayed along with a **bounding box** around the waste object and a **confidence score**.

---

## 🖼️ Screenshots

### Home Page
![Home Page](https://github.com/CHINNU081004/Waste-Classification-System-Using-AI-ML-AICTE/blob/main/Streamlit%20-%20Google%20Chrome%2001-12-2024%203.52.45%20PM.png)

### Demo
![Upload Image](https://github.com/CHINNU081004/Waste-Classification-System-Using-AI-ML-AICTE/blob/main/Streamlit%20-%20Google%20Chrome%202024-12-01%2016-08-38.mp4)

![Upload Image](https://github.com/CHINNU081004/Waste-Classification-System-Using-AI-ML-AICTE/blob/main/Streamlit%20-%20Google%20Chrome%202024-12-01%2016-09-02.mp4)

---

## 🤖 Model Details

### **Architecture**
- **Model Type**: Convolutional Neural Network (CNN)
- **Layers**: Multiple convolutional and pooling layers for feature extraction, followed by fully connected layers for classification.

### **Input Size**
- **Image Dimensions**: 150x150 pixels.

### **Output Classes**
- **Organic Waste (O)**
- **Inorganic Waste (R)**

### **Preprocessing**
- **Normalization**: Pixel values are normalized to a range of [0, 1].
- **Data Augmentation**: Techniques like rotation, zoom, and horizontal flip applied to increase dataset variability and model robustness. 

---

## 🌟 Project Highlights

- **Sustainability-Oriented**: Encourages proper waste segregation for a cleaner environment.  
- **Real-World Application**: Designed for use in homes, industries, and municipalities.  

---

## 🧑‍💻 Developed By  

**B Hemanth reddy**  
📧 [hemanthchinnu081004@gmail.com](mailto:hemanthchinnu081004@gmail.com)  
🌐 [LinkedIn](www.linkedin.com/in/hemanth-reddy-855712282/) | [GitHub](https://https://github.com/CHINNU081004)  

---

## 📝 License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.

---

## 🌍Acknowledgments

- **TensorFlow Community** for extensive documentation and support in building and training the model.
- **Streamlit Team** for providing a fantastic framework to develop and deploy web applications.
- **OpenCV** for offering efficient image processing tools to enhance data handling and manipulation.
