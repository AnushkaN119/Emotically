# Emotically- Emotion-Based Music Recommendation System 🎶

This project is a real-time music recommendation system that curates playlists based on the user's facial emotions. Using a Convolutional Neural Network (CNN) for emotion detection and transfer learning with ResNet-18, it classifies user emotions based on the Valence-Arousal-Dominance (VAD) model and suggests music accordingly.

## Key Features
- **Real-Time Emotion Detection:** Uses CNN to analyze facial expressions and predict user mood.
- **Transfer Learning:** Achieved 55%+ accuracy in VAD emotion classification with ResNet-18 using the EMOTIC dataset.
- **Music Recommendation:** Curates playlists dynamically based on user mood.
- **Multimodal Inputs:** Integrates various inputs for emotion detection to enhance accuracy.
- **Optimized Training Speed:** Focused on reducing training time for efficient real-time use.

## Technologies Used
- **Python**: Core programming language for development.
- **Machine Learning**: CNN for facial emotion recognition.
- **Transfer Learning**: ResNet-18 architecture for emotion classification.
- **Data Science**: Data manipulation and analysis.
- **EMOTIC Dataset**: Used for training the emotion recognition model.

## Dataset
The model uses the **EMOTIC dataset** for training, focusing on emotions classified into Valence, Arousal, and Dominance categories.

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/emotion-music-recommendation.git
   ```

2. Navigate to the project directory:
   ```bash
   cd emotion-music-recommendation
   ```

3. Install required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Usage

1. **Run the system**:
   ```bash
   python main.py
   ```

2. Allow the system to access your camera for real-time facial emotion detection.

3. Based on the detected emotion, a playlist will be suggested and displayed.

## Model Performance
- **Accuracy**: Achieved 55%+ accuracy in emotion classification using VAD categories.
- **Optimization**: Model training optimized for faster inference in real-time applications.

## Future Improvements
- Increasing emotion classification accuracy with additional datasets.
- Enhancing the playlist recommendation engine by integrating music metadata and user preferences.
- Incorporating more modalities (e.g., voice or text input) to improve emotion detection.

## Contributing
Feel free to fork this repository, create a feature branch, and submit a pull request.

## License
This project is licensed under the MIT License.

