# Timbre Recognition: A Computer Vision Perspective

This project is a part of the **AAI-521 course** in the Applied Artificial Intelligence Program at the University of San Diego (USD).  
**Project Status**: [Completed]

---

## Installation

To access and run this project: [GitHub Repository](https://github.com/bpayton0101/AAI-521-Final-Project)

1. Navigate to the GitHub repository: **AAI-521-Final-Project**.
2. Open the notebook file (`AAI-521_Grp8_NSynth.ipynb`) in **Google Colab** or your local **Jupyter Notebook** environment. 
3. Install the necessary Python dependencies by running the `!pip install` commands in the first code cell of the notebook.
4. Load Dataset: Download from [NSynth Dataset](https://magenta.tensorflow.org/datasets/nsynth) OR authenticate via **Google Cloud Storage (GCS)** access. Follow the instructions provided in the notebook. 
5. Follow the steps in the notebook to execute data preprocessing, visualization, and model training.

---

## Project Intro/Objective

The main objective of this project is to explore **timbre recognition** in audio using **computer vision techniques** combined with **deep learning**. Specifically, the goal is to classify and analyze the **timbral qualities** of sound, identify **instrument families**, and differentiate between **acoustic**, **electronic**, and **synthetic** sound sources.

This project demonstrates potential applications in **music information retrieval**, **sound design**, and **interactive audio technologies**. By employing advanced machine learning techniques, it aims to push the boundaries of how complex timbral qualities can be understood and recognized with **computer vision** and **deep learning**.

---

## Partner(s)/Contributor(s)  

- Brett Payton  
- Kevin Pooler  

---

## Methods Used

- **Deep Learning**: Multi-task learning for instrument classification, timbral qualities detection, and source type classification.  
- **Computer Vision**: Spectrogram and MFCC visualization for audio feature representation.  
- **Data Visualization**: Exploratory data analysis through plots like histograms, heatmaps, and radar charts.  
- **Data Manipulation**: Preprocessing and organizing datasets with pandas and NumPy for feature extraction.  
- **Cloud Computing**: Integration with Google Cloud Storage for dataset hosting and retrieval.  
- **Audio Analysis**: Feature extraction techniques such as Mel-spectrograms, MFCCs, and spectral contrast using Librosa.  

---

## Technologies

- **Python**: Primary programming language for data handling, modeling, and visualization.  
- **TensorFlow/Keras**: Deep learning framework for building and training the multi-task learning model.  
- **Librosa**: Library for advanced audio analysis and feature extraction.  
- **Matplotlib/Seaborn**: Libraries for creating insightful visualizations.  
- **Google Cloud Storage (GCS)**: For hosting and accessing the NSynth dataset.  
- **OpenCV**: Image processing for resizing and normalizing spectrograms and MFCCs.  
- **Jupyter Notebook**: Environment for developing and documenting the project.  

---

## Project Description

This project explores the application of **computer vision (CV)** and **deep learning** to classify and analyze **musical timbre**, **instrument families**, and **sound sources**. By leveraging the **NSynth Super Dataset** from Google, which contains **305,979 audio files** paired with detailed labels for **pitch**, **timbral qualities**, and **instrument classifications**, we implemented a **multi-task learning model** using **Convolutional Neural Networks (CNNs)**.

The dataset includes audio samples for **1,006 instruments** across three sound source categories: **acoustic**, **electronic**, and **synthetic**. Each audio file is represented visually through **spectrograms** and **Mel-Frequency Cepstral Coefficients (MFCCs)**, transforming audio analysis into a visual task.

### Key Questions and Hypotheses
1. Can visual representations of sound effectively capture complex timbral attributes?  
2. Can a unified CNN architecture handle multi-task classification across diverse musical features?  

### Tasks
1. **Instrument Classification**: Predicting **11 instrument families** (e.g., guitar, keyboard, brass).  
2. **Timbral Quality Detection**: Multi-label classification of **10 timbral attributes** (e.g., bright, dark, reverb).  
3. **Source Classification**: Identifying the sound source as **acoustic**, **electronic**, or **synthetic**.  

### Challenges
- **Overfitting** in the instrument classification task.  
- Imbalanced data distributions.  
- Variability in model performance across timbral attributes like “reverb.”  
- Limited dataset usage (only 10% of NSynth).  

Despite these challenges, the project demonstrates the potential of CV techniques and CNNs in transforming audio signal analysis, paving the way for more robust timbre research and real-world applications.

---

## License

This project is licensed under the **MIT License**, which allows for reuse, modification, and distribution with attribution. Please ensure proper citation and credit when using or adapting this project.

---

## Acknowledgments

We would like to express our gratitude to our Professors for their guidance and support throughout the course of this project. Additionally, we thank the University of San Diego’s **Applied Artificial Intelligence** program for providing the resources and framework to explore this exciting area of research.  

Special thanks to the Google NSynth Team for creating and sharing the **NSynth Super Dataset**, which was instrumental in our study. We also acknowledge the creators of **Librosa**, **TensorFlow**, and other open-source libraries that made this project possible. Finally, we extend our appreciation to our peers and collaborators for their insightful feedback and encouragement.  