# CMPT-496-EEG-Capstone
This repository includes notebooks of the EEG and music autoencoders built for the Fall 2025 Capstone under the supervision of Dana Cobzas at Grant MacEwan University. 
## Requirements
Both notebooks can be run locally or on google collab. The autoencoders were implemented with the latest iteration of tensorflow.
## Notes
The EEG autoencoder was created by Joseph and the music autoencoder by Francis. 
## Results
Example of EEG signal reconstructions from the EEG autoencoder:
![EEG_reconstructions](https://github.com/user-attachments/assets/e1225ca7-d2d9-476f-9527-af26201fdefa)

Example of music reconstruction from the music autoencoder (files will download when clicked):  
[smooth criminal.wav](https://github.com/user-attachments/files/26254252/smooth.criminal.wav)
[reconstructed_smooth criminal (2).wav](https://github.com/user-attachments/files/26254260/reconstructed_smooth.criminal.2.wav)

## Future work
The EEG autoencoder may be overfitting and requires a deep analysis of its functionality. PCA of the latent space would be a good place to start. As for the music autoencoder, it will require a refurbishing to become a VAE. Once those tasks are done it should be possible to link the two networks togther to create music from EEG signals.
## Credits
The models were trained using the [Song Familiarity Dataset](https://openneuro.org/datasets/ds005876/versions/1.0.1) gathered by Dr. Cameron Hassal of the Psychology Department at Grant MacEwan University.
The EEG autoencoder arcitecture was inspired by tweaking and repurposing [EEGnet](https://arxiv.org/abs/1611.08024).
