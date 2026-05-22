<h1 align="center"> Food Classification Using Deep Learning</h1>

<p align="center">
  <img src="https://img.shields.io/badge/Python-3.10-blue?style=for-the-badge&logo=python">
  <img src="https://img.shields.io/badge/TensorFlow-DeepLearning-orange?style=for-the-badge&logo=tensorflow">
  <img src="https://img.shields.io/badge/Flask-black?style=for-the-badge&logo=flask">
  <img src="https://img.shields.io/badge/CNN-ComputerVision-green?style=for-the-badge">
</p>

<hr>

<h2> Project Overview</h2>

<p>
This project is a <b>Food Classification Web Application</b> developed using
<b>Deep Learning</b> and <b>Computer Vision</b>.
The system predicts food categories from uploaded images using:
</p>

<ul>
  <li> Custom CNN</li>
  <li> ResNet50</li>
  <li> VGG16</li>
</ul>

<p>
The application is built with <b>Flask</b> and provides nutritional information
for predicted food items.
</p>

<p>
Food image classification is one of the major applications of Artificial Intelligence and Machine Learning in the healthcare and food industry.
This project helps users identify food categories automatically using advanced Deep Learning techniques.
</p>

<hr>

<h2> Objectives</h2>

<ul>
  <li>Detect food categories from uploaded images</li>
  <li>Compare performance of multiple CNN architectures</li>
  <li>Provide nutritional information</li>
  <li>Create a responsive web application using Flask</li>
  <li>Improve prediction accuracy using transfer learning</li>
  <li>Develop an intelligent image classification system</li>
</ul>

<hr>

<h2> Features</h2>

<ul>
  <li> Upload Food Images</li>
  <li> Predict Food Category</li>
  <li> Multiple Deep Learning Models</li>
  <li> Nutrition Information Display</li>
  <li> Responsive User Interface</li>
  <li> Fast Prediction System</li>
  <li> Supports Different Image Formats</li>
  <li> Real-time Prediction Workflow</li>
</ul>

<hr>

<h2> Technologies Used</h2>

<table border="1" cellpadding="10">
<tr>
<th>Technology</th>
<th>Purpose</th>
</tr>

<tr>
<td>Python</td>
<td>Programming Language</td>
</tr>

<tr>
<td>TensorFlow</td>
<td>Deep Learning Framework</td>
</tr>

<tr>
<td>Keras</td>
<td>Model Building</td>
</tr>

<tr>
<td>Flask</td>
<td>Backend Web Framework</td>
</tr>

<tr>
<td>HTML/CSS</td>
<td>Frontend Development</td>
</tr>

<tr>
<td>Tailwind CSS</td>
<td>UI Styling</td>
</tr>

<tr>
<td>OpenCV</td>
<td>Image Processing</td>
</tr>

<tr>
<td>NumPy</td>
<td>Numerical Computation</td>
</tr>

<tr>
<td>Matplotlib</td>
<td>Visualization</td>
</tr>

</table>

<hr>

<h2> Deep Learning Concepts Used</h2>

<h3>1️. Convolutional Neural Network (CNN)</h3>

<p>
CNN is a Deep Learning algorithm mainly used for image classification and computer vision applications.
It automatically extracts image features such as edges, shapes, colors, and textures.
CNN models reduce manual feature extraction and improve prediction accuracy.
</p>

<h3>2️. Transfer Learning</h3>

<p>
Transfer Learning is a technique where pretrained models are reused for new tasks.
Models like ResNet50 and VGG16 are already trained on large datasets like ImageNet.
This reduces training time and improves model performance.
</p>

<h3>3️. Image Preprocessing</h3>

<p>
Before prediction, images are resized, normalized, and converted into numerical arrays.
Image preprocessing improves model accuracy and consistency.
</p>

<h3>4️. Feature Extraction</h3>

<p>
Feature extraction is the process of identifying important patterns from images.
Deep Learning models automatically learn useful features during training.
</p>

<h3>5️. Pooling Layer</h3>

<p>
Pooling layers reduce image dimensions while preserving important information.
This decreases computation and helps prevent overfitting.
</p>

<h3> 6. Activation Function</h3>

<p>
Activation functions introduce non-linearity into neural networks.
Common activation functions used in CNNs include ReLU and Softmax.
</p>

<hr>

<h2> Deep Learning Models</h2>

<table border="1" cellpadding="10">

<tr>
<th>Model</th>
<th>Description</th>
</tr>

<tr>
<td>Custom CNN</td>
<td>

Built from scratch using convolution and pooling layers.

<br><br>

<b>Definition:</b><br>
Custom CNN is a manually designed Convolutional Neural Network architecture used for image classification tasks.
It learns image patterns directly from datasets.

<br><br>

<b>Uses:</b>

<ul>
<li>Food Classification</li>
<li>Object Detection</li>
<li>Face Recognition</li>
<li>Medical Image Analysis</li>
<li>Digit Recognition</li>
</ul>

</td>
</tr>

<tr>
<td>ResNet50</td>
<td>

Transfer learning model with residual connections.

<br><br>

<b>Definition:</b><br>
ResNet50 is a pretrained Deep Learning architecture with 50 layers.
It uses skip connections to solve the vanishing gradient problem and improve learning efficiency.

<br><br>

<b>Uses:</b>

<ul>
<li>Food Recognition Systems</li>
<li>Autonomous Vehicles</li>
<li>Medical Diagnosis</li>
<li>Satellite Image Analysis</li>
<li>Security Systems</li>
</ul>

</td>
</tr>

<tr>
<td>VGG16</td>
<td>

Pretrained deep CNN architecture for image classification.

<br><br>

<b>Definition:</b><br>
VGG16 is a popular pretrained CNN architecture developed by Oxford University's Visual Geometry Group.
It contains 16 deep layers and provides excellent image feature extraction.

<br><br>

<b>Uses:</b>

<ul>
<li>Image Classification</li>
<li>Food Detection</li>
<li>Disease Detection</li>
<li>Video Analysis</li>
<li>Computer Vision Applications</li>
</ul>

</td>
</tr>

</table>

<hr>

<h2> Dataset Information</h2>

<p>
The dataset contains multiple food categories used for training, validation, and testing.
Each category contains different food images for model learning.
</p>

<h3>Dataset Structure</h3>

<pre>
dataset/
│
├── train/
├── validation/
└── test/
</pre>

<ul>
<li><b>Training Data:</b> Used for model learning</li>
<li><b>Validation Data:</b> Used for performance evaluation</li>
<li><b>Testing Data:</b> Used for final prediction testing</li>
</ul>

<hr>

<h2> Project Structure</h2>

<pre>
food_classification_project/
│
├── app.py
├── requirements.txt
├── README.md
│
├── models/
│   ├── custom_cnn.keras
│   ├── resnet50_model.keras
│   └── vgg16_model.keras
│
├── static/
│   ├── uploads/
│   └── styles.css
│
├── templates/
│   └── index.html
│
├── dataset/
│   ├── train/
│   ├── validation/
│   └── test/
│
├── train_custom_cnn.py
├── train_resnet50.py
└── train_vgg16.py
</pre>

<hr>

<h2> Application Workflow</h2>

<ol>
  <li>User uploads food image</li>
  <li>Selects deep learning model</li>
  <li>Image preprocessing is performed</li>
  <li>Selected model extracts image features</li>
  <li>Food category is predicted</li>
  <li>Prediction and nutrition details are displayed</li>
</ol>

<hr>

<h2> Installation</h2>

<pre>
pip install -r requirements.txt
</pre>

<hr>

<h2> Run Application</h2>

<pre>
python app.py
</pre>

<hr>

<h2> Train Models</h2>

<h3>Custom CNN</h3>

<pre>
python train_custom_cnn.py
</pre>

<h3>ResNet50</h3>

<pre>
python train_resnet50.py
</pre>

<h3>VGG16</h3>

<pre>
python train_vgg16.py
</pre>

<hr>

<h2> Output</h2>

<ul>
  <li> Food Prediction</li>
  <li> Uploaded Image Preview</li>
  <li> Nutrition Details</li>
  <li> Multiple Model Comparison</li>
</ul>

<hr>

<h2> Advantages</h2>

<ul>
  <li>High accuracy food prediction</li>
  <li>Easy-to-use web interface</li>
  <li>Supports multiple CNN architectures</li>
  <li>Fast image classification</li>
  <li>Uses advanced transfer learning models</li>
  <li>Efficient feature extraction</li>
</ul>

<hr>

<h2> Limitations</h2>

<ul>
<li>Requires quality datasets for better accuracy</li>
<li>Training deep models requires high computational power</li>
<li>Prediction accuracy may decrease for blurry images</li>
</ul>

<hr>

<h2>Future Enhancements</h2>

<ul>
  <li> Real-time camera prediction</li>
  <li> Mobile application support</li>
  <li> More food categories</li>
  <li> Cloud deployment</li>
  <li>AI-based diet recommendation system</li>
</ul>

<hr>

<h2> Conclusion</h2>

<p>
This project successfully demonstrates the implementation of Deep Learning techniques for food image classification.
Using Custom CNN, ResNet50, and VGG16 models, the system achieves efficient and accurate food prediction.
</p>

<p>
The project highlights the importance of Artificial Intelligence, Computer Vision, and Transfer Learning in solving real-world image classification problems.
</p>
