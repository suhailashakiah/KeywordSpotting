# Keyword Spotting for Speech Recognition Systems
Keyword spotting for trigger words in speech recognition systems. 

Used the Google Speech Commands Dataset. The task is to classify the words into 12 classes: yes, no, up, down, left, right, on, off, stop, go, silence, unknown

Accuracy achieved: 85.6% (Placed in top 30% - Rank: 383/1315)

The kaggle competition winning model achieved an accuracy of 91%.

### Code Hierarchi 

1. Collecting files and organizing data, making noise samples.ipynb
2. Creating noised data.ipynb
3. Data augmentation - Time shifting noised and unnoised data.ipynb	
4. Augmenting classes 0 to 9.ipynb
5. MFCC EXTRACTION.ipynb
6. Neural network.ipynb
7. Kaggle testing set performance.ipynb

### Methodology: 

1. MFCC parameters: 
Number of MFCC features: 128, 
Hop length: 320, 
FFT window: 2048

2. Convolutional neural network: 

Note: The data was augmented by time shifting and adding noise as described in the data augmentation jupyter notebooks. 

