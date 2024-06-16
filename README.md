# Intelligent System for Monitoring National Heritage Sites

## Overview
This project focuses on developing an intelligent system to detect and deter inappropriate behavior, such as smoking and spitting, at national heritage sites. The system utilizes deep learning models, particularly the DenseNet architecture, to analyze images and identify these behaviors.

## Features
- Detection of smoking and spitting behaviors using computer vision.
- Integration of pre-trained DenseNet architecture for image understanding.
- Dynamic fine-tuning approach during training for optimizing model performance.
- UI powered by Gradio for interactive usage.

## Dataset
- Collected datasets:
  - Smoking and normal behavior images from Kaggle.
  - Spitting behavior images from various online sources.

## Technologies Used
- Python
- TensorFlow
- Gradio
- OpenCV
- Pandas, NumPy, Matplotlib for data handling and visualization

## Model Architecture
The system employs a modified DenseNet architecture:
- Additional dense layers for enhancing pattern recognition.
- Techniques to prevent overfitting and optimize learning.

## Training
- Training involved:
  - Determining optimal batch size and number of epochs.
  - Monitoring model performance and making adjustments as needed.
  - Achieved accuracy:
    - DenseNet: 99% (resource-intensive)
    - MobileNetV2: 98% (less resource-intensive)

## Usage
To use the system:
1. Clone the repository:
```bash
git clone https://github.com/codesmith25103/HumanAbnomalBehaviourAtHeritageSites.git
cd HumanAbnomalBehaviourAtHeritageSites
```

3. Open App.ipynb
   
4. Run Cell (Need to Install Gradio Library first)
"Note: There is no need to retrain the model since the .h5 file already contains all the weights and structure of the model."

UI:
![image](https://github.com/codesmith25103/HumanAbnomalBehaviourAtHeritageSites/assets/102778847/fd94b3da-f59b-44c2-9a65-62dd0790d400)

Open your web browser and navigate to `http://localhost:5000` to interact with the UI powered by Gradio.

## Contributors
- [Sankalp](https://github.com/codesmith25103)


## Acknowledgments
We would like to thank experts in heritage site management for their valuable insights and feedback.

## License
This project is licensed under the [MIT License](LICENSE).






