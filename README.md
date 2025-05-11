# Hand_Gesture_Recognition
AI-powered Real-Time Hand Gesture Recognition System using CNN, OpenCV, and MediaPipe — bridging the communication gap for the speech and hearing impaired.

# 🤟 Hand Gesture Recognition Using CNN

This project implements real-time sign language recognition using deep learning and computer vision techniques.

## 🚀 Features

- 🔍 Real-time hand gesture detection via webcam
- 🧠 Trained using CNN architecture (MobileNetV2)
- 🖐️ Recognizes 6 American Sign Language (ASL) gestures:
  - Hello 👋
  - Bye 👋🏻
  - Yes 👍
  - No 👎
  - Perfect 👌
  - Thank You 🙏
- ⚙️ Integrated with OpenCV & MediaPipe
- 📈 Achieved 94.24% train and 87.42% test accuracy


## 🧰 Technologies Used


- Jupyter Notebook
- Python 🐍  
- TensorFlow / Keras  
- OpenCV  
- MediaPipe  
- NumPy  
- Scikit-learn  
- Matplotlib  

## 🧠 Model Architecture

- Pretrained CNN (MobileNetV2)  
- Transfer learning + Dense layers  
- Optimized using Adam optimizer and categorical cross-entropy  


## 📂 Project Structure
``` 📦hand-gesture-recognition
┣ 📜train.ipynb # Model training notebook
┣ 📜test.ipynb # Model evaluation notebook
┣ 📜dataset_info.ipynb # Dataset overview
┣ 📜gesture_model_v2.h5 # Trained CNN model
┣ 📜label_mapping.npy # Class label encoding
┣ 📜requirements.txt # Python dependencies
┣ 📜README.md # Project documentation
```
---

## 📊 Results

| Metric           | Value     |
|------------------|-----------|
| Train Accuracy   | 94.24%    |
| Test Accuracy    | 87.42%    |
| Real-time FPS    | 20–30     |

---

## 🧪 How to Use

### 1. Install Requirements

```
pip install -r requirements.txt
jupyter notebook train.ipynb
jupyter notebook test.ipynb

```


---

## 🧾 Dataset

- Source: Preprocessed gesture image dataset from [ComputerVision.Zone](https://www.computervision.zone/projects)  
- Size: 2400+ labeled images across 6 gesture classes  

---


## Contributing
Contributions are welcome! Please fork the repository and create a pull request with your changes. 
Make sure to follow the existing code style and include tests for any new features.

---

## License
This project is licensed under the MIT License. See the [LICENSE](https://github.com/SoumiliPal3//blob/main/LICENSE) file for more details.

## Contact
For any questions or inquiries, please reach out to Soumili Pal at [sou.enquiry@gmail.com](#sou.enquiry@gmail.com) .

Please do ⭐ the repository, if it helped you in anyway.

<a href="#top">Back to top</a>


