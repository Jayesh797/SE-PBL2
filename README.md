<h1 style="text-align: center;">Child Speech Emotion Recognition using Deep Learning</h1>

<p>This project predicts emotions from child speech using machine learning and deep learning techniques. The model is trained on various datasets like TESS, SAVEE, RAVDESS, BESD, and CREMAD, commonly used for emotion recognition tasks.</p>

<h2>Datasets Used</h2>
<ul>
  <li>CREMA-D</li>
  <li>RAVDESS</li>
  <li>SAVEE</li>
  <li>TESS</li>
</ul>

<h2>Project Workflow</h2>
    <ul>
        <li>
            <strong>1. Importing Libraries</strong>
            <p>The following libraries are used: <code>pandas</code>, <code>numpy</code>, <code>librosa</code>, <code>keras</code>, <code>scikit-learn</code>, <code>matplotlib</code>, and <code>seaborn</code>.</p>
        </li>
        <li>
            <strong>2. Data Preparation</strong>
            <p>Data from multiple datasets is merged into a dataframe, storing emotion labels and file paths. This dataframe is then used to extract features for training the model.</p>
        </li>
        <img style="text-align: center;" src="images/model_emotions_final.png" alt="Alt text" width="500" height="400">
        <p style="text-align: center;">Fig-Combined Emotions from Different Datasets</p>
        <li>
            <strong>3. Data Visualization and Exploration</strong>
            <p>Visualize the distribution of emotions using bar charts. Waveplots and Spectrograms are also used to analyze audio signals:</p>
            <ul>
                <li><strong>Waveplots:</strong> Show loudness over time.</li>
                <li><strong>Spectrograms:</strong> Represent the frequency spectrum over time.</li>
            </ul>
        </li>
        <li>
            <strong>4. Data Augmentation</strong>
            <p>Augmentation techniques to enhance generalization include:</p>
            <ul>
                <li>Noise Injection</li>
                <li>Time Shifting</li>
                <li>Pitch Alteration</li>
                <li>Speed Changes</li>
            </ul>
        </li>
        <li>
            <strong>5. Feature Extraction</strong>
            <p>The audio features extracted include:</p>
            <ul>
                <li>Zero Crossing Rate</li>
                <li>Chroma_STFT</li>
                <li>MFCC (Mel-frequency cepstral coefficients)</li>
                <li>RMS (Root Mean Square)</li>
                <li>MelSpectrogram</li>
            </ul>
        </li>
        <li>
            <strong>6. Data Preparation</strong>
            <p>Features are normalized and split into training and testing sets.</p>
        </li>
        <li>
            <strong>7. Model Architecture</strong>
            <p>A CNN (Convolutional Neural Network) is built to classify emotions from speech.</p>
        </li>
    </ul>

<div>
    <h2>Future Scope</h2>
    <p>Future improvements and explorations for this project may include:</p>
    <ul>
        <li>Exploring additional datasets to enhance model accuracy.</li>
        <li>Implementing more advanced feature extraction techniques.</li>
        <li>Testing various architectures of deep learning models to improve classification performance.</li>
        <li>Integrating real-time emotion detection in applications such as educational tools and therapy.</li>
        <li>Conducting user studies to assess the practical applications and effectiveness of the model.</li>
    </ul>
</div>
<hr>
