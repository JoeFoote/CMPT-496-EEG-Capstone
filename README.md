# CMPT-496-EEG-Capstone
This repository includes notebooks of the EEG and music autoencoders built for the Fall 2025 Capstone under the supervision of Dana Cobzas at Grant MacEwan University. 
## Requirements
Both notebooks require data to be mounted onto a google drive if used in google collab.
## Notes
The notebooks contain code which can be used to process data with desired parameters.
## Results
Example of EEG signal reconstructions from the EEG autoencoder:
![EEG_reconstructions](https://github.com/user-attachments/assets/e1225ca7-d2d9-476f-9527-af26201fdefa)

Example of music reconstruction from the music autoencoder (files will download when clicked):  
[smooth criminal.wav](https://github.com/user-attachments/files/26254252/smooth.criminal.wav)
[reconstructed_smooth criminal (2).wav](https://github.com/user-attachments/files/26254260/reconstructed_smooth.criminal.2.wav)

## Credits
The models were trained using the [Song Familiarity Dataset](https://openneuro.org/datasets/ds005876/versions/1.0.1) gathered by Dr. Cameron Hassal of the Psychology Department at Grant MacEwan University.
The EEG autoencoder arcitecture was inspired by tweaking and repurposing [EEGnet](https://arxiv.org/abs/1611.08024).
