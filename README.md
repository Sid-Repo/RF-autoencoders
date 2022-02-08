# RF-autoencoder

The project was developed to detect anomalous transmissions of RF signals in a spectrum band.

Implemented using Deep standard autoencoder, Deep VAE autoencoder, and Deep LSTM autoencoder to evaluate different models.

--- dataset source: RF signal data obtained using Software-defined radio (SDR) and MATLAB

Results:

1) 'ELU' activation function performed the best.
2) Deep standard autoencoder works well with signal I/Q data. Deep VAE does not work well for this task.
3) Achieved 99.98% precision, 87.76% recall and 0.93 F1-score. 


# Library versions

tensorflow: 2.6.0

tensorflow-gpu: 2.6.0

keras: 2.6.0

numpy: 1.19.5

pandas: 1.3.4

cudnn: 8.2.1

cudatoolkit: 11.3.1
