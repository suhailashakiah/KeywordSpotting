# Keyword Spotting for Speech Recognition Systems
Keyword spotting for trigger words in speech recognition systems. 

Used the Google Speech Commands Dataset. The task is to classify the words into 12 classes: yes, no, up, down, left, right, on, off, stop, go, silence, unknown

Accuracy achieved: 85.6% (Placed in top 30% - Kaggle Rank: 383/1315)

<img width="576" alt="loss and confusion matrix" src="https://user-images.githubusercontent.com/18056877/35067373-acda92aa-fba1-11e7-9452-a1fec7f2291d.png">

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

![model](https://user-images.githubusercontent.com/18056877/35067415-ce308202-fba1-11e7-9372-110f84143bbc.png)

Note: The data was augmented by random time shifting between 1 and 200 ms, and adding noise as described in the data augmentation jupyter notebooks. 

