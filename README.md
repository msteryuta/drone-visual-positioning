# drone-visual-positioning
Assessing the Impact of Seasonal Lighting Variations on Drone Visual Positioning
Authors: Che-Cheng Chang, Po-Ting Wu, Bo-Yu Liu, Bo-Ren Chen
Published by: IEEE

Summary:
This study explores the challenges of drone visual positioning under varying seasonal lighting conditions. While Global Positioning Systems (GPS) are commonly used for drone navigation, their accuracy is often compromised in specific scenarios. To address these limitations, the authors propose a Convolutional Neural Network (CNN)-based architecture designed to overcome the effects of seasonal lighting variations.

Key contributions include:

Vision-Based Positioning: Utilizing orthophotomaps and CNNs to position drones accurately, even under diverse lighting conditions caused by seasonal changes.
Data Augmentation: Introducing lighting variations into the training dataset using solar radiation models specific to Taiwan, enhancing the generalizability of the model.
Experimental Design: Conducting tests across 16 sub-areas and four seasons using a CNN architecture with residual blocks for improved accuracy and stability.
Findings: The model demonstrates strong performance in most scenarios but experiences reduced accuracy in low-light conditions (e.g., winter). This highlights the importance of addressing low-light environments in drone positioning systems.
Future Work
The paper suggests exploring additional environmental factors, improving low-light performance, and scaling the implementation to larger datasets to enhance real-world applicability.

Acknowledgment
The research is supported by the National Science and Technology Council, Taiwan, and the orthophotomap data provided by SINJIE INSTRUMENT CO., LTD.

Keywords
Drone Positioning, Convolutional Neural Network (CNN), Lighting Variations

