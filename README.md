# Plant-Disease-Recognition-DL-CNN
A Deep Learning-based Convolutional Neural Network (CNN) model for accurate plant disease recognition from leaf images. Helps farmers and researchers detect and classify plant diseases efficiently, supporting sustainable agriculture and crop health management. This project helps **farmers, researchers, and agricultural experts** detect and classify plant diseases efficiently, supporting **sustainable agriculture** and **crop health management**.

## 🌱 Features
- **Automated Disease Detection** from leaf images.
- **High Accuracy** using CNN architecture.
- **User-Friendly** for integration into agricultural workflows.
- **Scalable Model** for multiple plant types and diseases.
- **Dockerized Deployment** for easy setup.

## 📂 Project Structure

 DockerFile                        # Docker setup for deployment
PlantdiseasepredictionCNN.ipynb  # Jupyter Notebook or training script
 main.py                            # Main application file
 README.md                          # Project documentation


## 🛠️ Technologies Used
- **Python 3**
- **TensorFlow / Keras**
- **OpenCV**
- **NumPy & Pandas**
- **Matplotlib & Seaborn**

## 📊 Dataset
- Publicly available **PlantVillage dataset** (or any custom dataset of leaf images).
- Images preprocessed (resized, normalized) before training.

## 🚀 How to Run
1. **Clone the Repository**
 
   git clone https://github.com/YourUsername/plant-disease-recognition-dl-cnn.git
   cd plant-disease-recognition-dl-cnn


2. **Install Dependencies**

  pip install -r requirements.txt

3. **Run the Application**

   python main.py

4. **Using Docker**

   
   docker build -t plant-disease-recognition .
   docker run -p 5000:5000 plant-disease-recognition
   ## 📈 Model Performance

* 📊 **Training Accuracy:** 80%
* ✅ **Validation Accuracy:** 89%
* 📉 **Loss:** Reduced significantly after data augmentation & tuning
  
## 📌 Future Enhancements

* Add **mobile application** interface for field usage.
* Integrate **real-time camera-based detection**.
* Expand to **more crops and diseases**.
* Include **explainable AI** for transparency.

## 🤝 Contributing

Contributions are welcome! Please fork this repo and submit a pull request.
