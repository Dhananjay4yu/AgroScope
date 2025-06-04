<!DOCTYPE html>
<html lang="en">
<head>
  <meta charset="UTF-8">
  <title>Plant Disease Detection using CNN</title>
</head>
<body style="font-family: Arial, sans-serif; line-height: 1.6; margin: 40px;">

  <h1>🌿 Plant Disease Detection using CNN</h1>
  <p>
    A deep learning-based system for detecting and classifying plant leaf diseases using image data. Built using Convolutional Neural Networks (CNN), this model helps in early and accurate identification of common plant diseases, supporting farmers and agricultural researchers.
  </p>

  <h2>Features</h2>
  <ul>
    <li>Detects and classifies multiple plant diseases from leaf images.</li>
    <li>Built using Convolutional Neural Networks (CNN).</li>
    <li>Trained on a dataset of 600,000+ images.</li>
    <li>Implemented in TensorFlow/Keras.</li>
    <li>Addresses real-world agricultural challenges.</li>
    <li>Includes training metrics and result visualizations.</li>
    <li>Optionally deployable as a Streamlit web app.</li>
  </ul>

  <h2>Model Architecture</h2>
  <ul>
    <li>Input: RGB leaf images</li>
    <li>Layers: Conv2D, MaxPooling, Dropout</li>
    <li>Output: Softmax layer with disease classes</li>
    <li>Loss: Categorical Crossentropy</li>
    <li>Optimizer: Adam</li>
  </ul>

  <h2>🔧 How to Run</h2>
  <ol>
    <li>Clone the repository:
      <pre><code>git clone https://github.com/yourusername/PlantDiseaseDetection.git</code></pre>
    </li>
    <li>Create a virtual environment and install dependencies:
      <pre><code>
python -m venv venv
source venv/bin/activate  # Windows: venv\Scripts\activate
pip install -r requirements.txt
      </code></pre>
    </li>
    <li>Place the <code>best_epoch_weights.h5</code> file in the <code>model/</code> folder.</li>
    <li>Run prediction:
      <pre><code>python predict.py --image path/to/image.jpg</code></pre>
    </li>
    <li>(Optional) Launch Streamlit app:
      <pre><code>streamlit run app.py</code></pre>
    </li>
  </ol>

  <h2>Sample Results</h2>
  <table border="1" cellpadding="5">
    <tr><th>Input Image</th><th>Prediction</th><th>Confidence</th></tr>
    <tr><td>Leaf1.jpg</td><td>Powdery Mildew</td><td>97.3%</td></tr>
    <tr><td>Leaf2.jpg</td><td>Bacterial Spot</td><td>94.8%</td></tr>
  </table>

  <h2>Technologies Used</h2>
  <ul>
    <li>Python</li>
    <li>TensorFlow / Keras</li>
    <li>OpenCV</li>
    <li>NumPy / Pandas</li>
    <li>Matplotlib / Seaborn</li>
    <li>Streamlit</li>
  </ul>

  <h2>What I Learned</h2>
  <ul>
    <li>Working with large-scale image datasets.</li>
    <li>Building and training CNNs.</li>
    <li>Model evaluation and performance tuning.</li>
    <li>Saving/loading models using HDF5.</li>
    <li>Deploying AI apps using Streamlit.</li>
  </ul>

  <h2>Future Improvements</h2>
  <ul>
    <li>Mobile app with TensorFlow Lite</li>
    <li>Live deployment on Hugging Face Spaces</li>
    <li>Further fine-tuning with advanced techniques</li>
    <li>Add model explainability (e.g., Grad-CAM)</li>
  </ul>

  <h2>Acknowledgements</h2>
  <p>
    Based on the <a href="https://www.kaggle.com/emmarex/plantdisease">PlantVillage dataset</a>.<br>
    Special thanks to Atria Institute of Technology for mentorship and resources.
  </p>

  <h2>Contact</h2>
  <p>
    Made with 💚 by <a href="https://github.com/Dhananjay4yu">Dhananjay Kumar</a><br>
    Feel free to connect, open issues, or contribute!
  </p>

</body>
</html>

