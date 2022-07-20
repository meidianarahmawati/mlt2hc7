# ProA Machine Learning with Tensorflow Batch 2 - Kelompok Healthcare 7
Dataset yang digunakan adalah dataset Disease Symptom Prediction. Dataset tersebut berisi penyakit dan gejalanya sehingga dapat dibuat menjadi sistem penentuan diagnosis penyakit berdasarkan gejala yang muncul. Dataset tersebut juga disertai master data penyakit yang berisi deskripsi penyakit, tidakan pencegahan yang bisa dilakukan, dan tingkat keparahan gejala. Saat sistem penentuan diagnosis menerima input berupa gejala tertentu, output berupa diagnosis penyakit juga bisa dilengkapi dengan deskripsi dan tindakan pencegahan dari master data tersebut. 

Penyiapan data yang dilakukan pada dataset ini diantaranya: mengubah bentuk data menjadi feature vector gejala, memberikan label encoder pada variabel penyakit, dan membagi data menjadi training data dan testing data. Selanjutnya, akan dilakukan perbandingan klasifikasi dengan model Neural Network dan Random Forest.

Referensi: 
- preprocessing
  - https://www.kaggle.com/code/ronikdedhia/disease-sympton-prediction
- RandomForestModel
  - https://blog.tensorflow.org/2021/05/introducing-tensorflow-decision-forests.html
  - https://www.tensorflow.org/decision_forests/tutorials/beginner_colab
  - https://www.kaggle.com/code/carlmcbrideellis/classification-using-tensorflow-decision-forests/notebook
- Ensemble Model Neural Network dan RandomForest
  - https://www.tensorflow.org/decision_forests/tutorials/model_composition_colab
